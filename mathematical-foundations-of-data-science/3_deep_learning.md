[Deep Learning](https://www.deeplearningbook.org)

@book{Goodfellow-et-al-2016,
    title={Deep Learning},
    author={Ian Goodfellow and Yoshua Bengio and Aaron Courville},
    publisher={MIT Press},
    note={\url{http://www.deeplearningbook.org}},
    year={2016}
}

[Chapter 3 - Probability and Information Theory](https://www.deeplearningbook.org/contents/prob.html)

Section 1 - Why Probability?
- Discusses non-determinism (**stochasticity**) and uncertainty in Machine Learning
- 3 types of uncertainty:
    - Inherent stochastically - the system being modeled in non-deterministic
    - Incomplete observability - the subject thinks the system is non deterministic
    - Incomplete modeling - **When we use a model that must discard some of the information we have observed, the discarded information results in uncertainty in the model’s predictions.**
- In many cases a simple but uncertain rule can be more useful than a complex and certain one
- "Degree of belief"
- Frequentist prob
- Bayesian prob

[Chapter 4: Gradient Based Optimization](https://www.deeplearningbook.org/contents/numerical.html)

Section 3:
- Briefly touches on the definition for objective function, gradient descent, and how derivatives are used for gradient descent.
- Critical/stationary points where the slope/derivative is 0. These could be local or global min or maximums, or even a saddle point
- These points make it difficult to find the global min/max. Therefore we often settle for something minimized enough albeit not perfect
- For functions with multiple inputs we use the partial derivative
- Directional derivative
    - To minimize *f*, we would like to ﬁnd the direction in whichfdecreases thefastest. We can do this using the directional derivative
    - This gives us the *method of steepest descent, or gradient descent*
- Line search strategy for finding the learning rate
- *Hill climbing* for ascending an objective function
- Jacobian matrix
    - Matrix containing all partial derivatives of a fn whose inputs and outputs are both vectors
- Second derivative
    - Tells us how the ﬁrst derivative will change as we vary the input. This is importantbecause it tells us whether a gradient step will cause as much of an improvementas we would expect based on the gradient alone
    - Measures *curvature*
- Hessian matrix
    - When our function has multiple input dimensions, there are many second derivatives. These derivatives can be collected together into a this matrix
    - Equivalently, the Hessian is the Jacobian of the gradient.
- "The second derivative test"
    - Used to see whether a critical point is a local maximum, a local minimum, or a saddle point
    - In multiple dimensions, we need to examine all the second derivatives of thefunction. Using the eigendecomposition of the Hessian matrix, we can generalizethe second derivative test to multiple dimensions
- Optimization algorithms
    - First and second order optimization algorithms
        - Lipschitz continuous
        - Lipschitz constant
        - Convex optimization