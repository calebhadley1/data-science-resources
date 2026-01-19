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

## Chapter 5: Linear Independence
### Section 1: Linear Dependence
- This reading defines linear dependence and independence.
- Linear dependence of a list of vectors does not depend on the ordering of the vectors in the list (p. 89)
- Linear independence holds if Linear dependence is not true
### Section 2: Bases
- Independence-dimension inequality states that any three 2-vectors must be linearly
dependent (p. 91)
- A collection of n linearly independent n-vectors (i.e., a collection of linearly
independent vectors of the maximum possible size) is called a basis (p. 92).
### Section 4: Gram Schmidt Algorithm
- This algorithm allows you to find if a list of n vectors is linearly independent
- If the vectors are linearly independent, this algo produces an orthonormal collection of vectors


## Chapter 6: Matrices
### Section 1: Matrices
- Defines matrices and some common attributes, such as its size or dimensions, elements, and indices.
- Square, tall and wide matrices
- Column (e.g. 3x1 vector) and row vectors (e.g. 1x3)
- Block matrices are matrices of matrices (blocks or submatrices)
### Section 2: Zero and Identity Matrices
- Zero matrix
- Identity matrix (diagonal of 1's)
- Sparse matrix (many entries are zeroes)
- Diagonal matrix (0 where i != j)
- Triangular matrix (upper if 0 for i > j. lower if 0 for i < j)
### Section 3: Transpose, Addition and Norm
- Matrix transpose (A<sub>ij</sub> = A<sub>ji</sub>)
- Row and column vectors
    - Transpose converts row vectors into column vectors, and vice versa
- Transpose of block matrices e.g. [A, B]<sup>T</sup> = [A<sup>T</sup>, B<sup>T</sup>]
- Document term matrix
- Data matrix (imagine DataFrame, matrix of features)
- Symmetric matrix (A == A<sup>T</sup> i.e. A<sub>ij</sub> == A<sub>ji</sub> for all i,j)
- Matrix addition
    - Associative
    - Commutative
    - Adding zero matrix has no effect
    - (A + B)<sup>T</sup> = A<sup>T</sup> + B<sup>T</sup>
- Scalar matrix multiplication
    - e.g. 2 * [[1,2]], you multiply the scalar by each element
- Matrix norm
    - Sqrt of the sum of the squares of its entries
    - Allows us to measure distance between matrices
### Section 4: Matrix-vector Multiplication
- Defines matrix-vector multiplication
- Provides examples, such as a matrix multiplied by the zero or identity matrix.
- Provides use cases, such as multiplying a feature matrix by its weights

## Chapter 8: Linear Equations
### Section 1: Linear and affine functions
- Vector-valued functions of vectors
    - Describes the notation for mapping a vector to another vector using functions (p. 147)
- The matrix-vector product function
    - Multiplying a matrix (A) by a vector (x) gives a new vector (b)
- Superposition and linearity
    - Superposition basically means "the response to multiple inputs is the sum of the responses to each individual input"
- Linear (like negation) and non linear functions (like absolute value)
- Affine function (the graph of an affine fn is always a straight line)
### Section 2: Linear function models
- "Many functions or relations between variables that arise in natural science, engineering, and social sciences can be approximated as linear or affine functions. In these cases we refer to the linear function relating the two sets of variables as a model or an approximation, to remind us that the relation is only an approximation, and not exact" (p. 149).
- Some examples of this are provided through the Regression model
### Section 3: Systems of linear equations
- Defines systems of linear equations
- Ex. x1 + x2 = 3, x2 + x3 = 2 can be modeled like [[1,1,0,3], [0,1,1,2]]
- Over and under-determined systems of linear equations (i.e. tall, wide, and squaree matrices)

## Chapter 11: Matrix Inverses
- "In this chapter we introduce the concept of matrix inverse. We show how matrix inverses can be used to solve linear equations, and how they can be computed using the QR factorization" (p. 199).
### Section 1: Left and Right Inverses
- Left inverse
    - A matrix X that satisifies XA = I is called the left inverse of A
    - If this matrix exists then A is left invertible
    - If A has dimensions m x n, then X will be n x m
    - Left invertible matrices that have one inverse actually have infinite
    - If A has a left inverse C then the columns of A are linearly independent
- Right inverse
    - Closely related to left inverse
    - A matrix X that satisifies AX = I is called the right inverse of A
- Transpose
    - If matrix A has a right inverse B, then B<sup>T</sup> is the left inverese of A<sup>T</sup> (p. 201)
    - A matrix is right-invertible if and only if its rows are linearly independent
    - A tall matrix cannot have a right inverse. Only square or wide matrices can be right-invertible
### Section 2: Inverse
- If a matrix is left- and right-invertible, then the left and right inverses are unique and equal. This is also known as an "invertible or nonsingular matrix" (proof on p. 202)
- Invertible matrices must be square, since tall matrices are not right-invertible, while wide matrices are not left-invertible
- Given Ax=b, if A is invertible, then x=A<sup>-1</sup>b is a solution of the equations (p. 203)
- "For square matrices, left-invertibility, right-invertibility, and invertibility are equivalent: If a matrix is square and left-invertible, then it is also right-invertible (and therefore invertible) and vice-versa" (p. 203). Additionally you can say that the matrix cols and rows are linearly independent
- Invertible matrices also have an invertible transpose
- Inverse of matrix product: (AB)<sup>-1</sup> = B<sup>-1</sup>A<sup>-1</sup>
- Dual basis (p. 205)
- Negative matrix powers (p. 206)
- Triangular matrices are invertible (p. 206)
- Inverse via QR factorization (p. 206)
### Section 3: Solving Linear Equations
- Back substitution (p. 207)
- QR factorization (p. 208)
- Factor solve methods (p. 208)
- Sparse matrices can be solved faster than the QR methodology. 
