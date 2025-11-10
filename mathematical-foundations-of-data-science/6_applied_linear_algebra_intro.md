# [Introduction to Applied Linear Algebra](https://web.stanford.edu/~boyd/vmls/vmls.pdf)


## Chapter 1: Vectors
- These chapters talk about vectors more formally, and interleave many examples of applications.
### Section 1: Vectors
- Definitions on vectors, including what a vector is, what its elements are, vector equality, and real vs complex scalars
- Blocked or stacked vectors are essentially concatted vectors (p. 4)
- Subvectors are slices within a vector which you can access using indices i.e. arr[0:10]. The `0:10` is called the *index range*
- Zero vectors (e.g. [0,0,0])
- Unit vectors (e.g. [1,0,0]. Only 1 element can be a 1)
- Ones vector (e.g. [1,1,1])
- A vector is sparse if many elements are zeroes
- Pages 6-11 covers examples where vectors can be used. For example representing color, time series, etc.

### Section 2: Vector Addition
- Vector Addition is the element wise addition of two vectors. e.g. [1,2,3] + [4,5,6] = [5,7,9]
- Vector Subtraction is the logical opposite of vector addition. e.g. [5,7,9] - [1,2,3] = [4,5,6]
- Vector addition properies:
    - Commutative: a + b = b + a.
    - Associative: (a + b) + c = a + (b + c)
    - Adding zero vector to a vector has no effect
    - Subtracting a vector from itself yields the zero vector
- Pages 12-14 covers examples where vector addition may be useful

### Section 3: Scalar-vector Multiplication
- Scalar-vector Multiplication is also just known as scalar multiplication
- Performed by multiplying each element in the vector by a scalar. e.g. (-3) * [1,2,3] = [-3,-6,-9]
- Properties:
    - Commutative: a * c = c * a.
    - Associative: (a * b) * c = a * (b * c)
- Page 16 includes some examples for scalar-vector multiplication
- Linear combinations (p. 17)
- Linear combinations of unit vectors (p. 17)
- Special linear combinations (p. 17)
    - Sum of the vectors
    - Average of the vectors
    - Affine combination
    - Convex combination, a mixture, or a weighted average
- Page 18 provides some more examples

## Chapter 2: Linear Functions
- This chapter introduces vectors and their broader context for linear algebra.
### Section 1: Linear Functions
- Function Notation
    - Explains how to write the notation like "f is a function that maps n real vectors to real numbers"
- The inner product function 
    - Essentially a weighted sum of the elements in a vector
- Superposition and linearity
    - A function that satisfies superposition is linear
    - Homogeneity
    - Additivity
- Inner product representation of a linear function
- Affine functions

## Chapter 3: Norm and Distance
### Section 1: Norm
- This reading defines the Euclidean norm, and general requirements for other norms
- The Euclidean norm of an n-vector x (named after the Greek mathematician Euclid), denoted ∥x∥, is the squareroot of the sum of the squares of its elements. It can also be described as the squareroot of the inner product of the vector with itself
- Sometimes it is written with subscript 2 like ||x||<sub>2</sub>. The 2 represents that the elements are raised to 2nd power
- It can also be called the *magnitude* or *length* of a vector
- Properties of norm (p. 46):
    - Nonnegative homogeneity: Multiplying a vector by a scalar multiplies the norm by the absolute value of the scalar
    - Triangle inequality: The Euclidean norm of a sum of two vectors is no more than the sum of their norms, also called *subadditivity*
    - Nonnegativity: ||x|| >= 0
    - Definiteness: ||x|| = 0 only if x=0
    - The last two properties together is called *positive definiteness*
- General norms: Any norm that satisfies the properties above
- Root-mean square value (RMS) formula is provided on p. 46. It tells us what a typical value in the vector is
- Norm of a sum formula is provided on p. 46 (norm of a sum of 2 vectors)
- Norm of block vectors: The norm-squared of a stacked vector is the sum of the
norm-squared values of its subvectors
- Chebyshev inequality (p. 47)

### Section 2: Distance
- This reading defines the Euclidean distance between two vectors, and general requirements for distance functions.
- Euclidian distance: We can use the norm to define the Euclidean distance between two vectors a and b as the norm of their difference: dist(a,b) = ||a-b||
- We describe the distance between two vectors using the terms "close" and "far". e.g. vector 1 is closer to vector 2 than vector 3
- The origin of the name "triangle inequality" is described on page 49 by building upon the definition of euclidian distance
- Pages 50-51 include examples
- Units for heterogeneous vector entries: Basically be careful when using euclidian distance on a vector which describes multiple features because the distances between elements might not describe the same units. (difference of 1 may be huge for one feature and small for another)

### Section 3: Standard Deviation
- The standard deviation of a vector x tells us the typical amount by which its entries deviate from their average value
- Covers standardization of the standard deviation with zscores
- For a vector x, the demeaned vector is dervied by: x - avg(x)*1
- Standard Deviation is defined as the RMS value of the demeaned vector. The formula can be found on page 52
- It tells us the typical amount that a value differs from the mean
- rms(x<sup>2</sup>) = avg(x<sup>2</sup>) + std(x<sup>2</sup>)
- Chebyshev inequality for standard deviation
- Properies of standard deviation:
    - Adding a constant: Adding a constant to every entry of a vector does not change its standard deviation
    - Multiplying by a scalar: Multiplying a vector by a scalar multiplies the standard deviation by the absolute value of the scalar
- Standardized version of vector x has mean 0 and std 1

## Chapter 4: TODO
### Section 2: Eigenvectors and Eigenvalues
- TODO fill me in

## Chapter 5: Linear Independence
### Section 1: Linear Dependence
- This reading defines linear dependence and independence.
- Linear dependence of a list of vectors does not depend on the ordering of the vectors in the list (p. 89)
- Linear independence holds if Linear dependence is not true

## Chapter 6: Matrices
- TODO fill me in. make sure to do sec 2, 4 

## Chapter 7: Matrix Examples
- TODO try a few of these in spare time (optional)

## Chapter 10: Matrix Multiplication
- TODO fill me in

## Chapter 11: Matrix Inverses
- TODO do section 0-2