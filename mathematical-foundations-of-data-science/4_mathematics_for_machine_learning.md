# [Mathematics for Machine Learning](https://mml-book.github.io/book/mml-book.pdf)

## Descriptive Statistics
### Chapter 6
#### Section 4
- Means and Covariances
    - Mean and (co)variance are often useful to describe properties of probability distributions (expected values and spread). We will see in Section 6.6 that there is a useful family of distributions (called the exponential family), where the statistics of the random variable capture all possible information.
- Expected Value: "The expected value serves as a fundamental concept to evaluate models, frame problems, and guide decision-making within a business context by using the Expected Value Framework to quantify potential costs and benefits of a model's probabilistic predictions."
- Median
    - For distributions, which are asymmetric or have long tails, the median provides an estimate of a typical value that is closer to human intuition than the mean value
    - More robust to outliers than mean
- Mean
- Mode
- Covariance
- Variance
- Standard Deviation
- Correlation
- Population vs Sample

## What do Models Do?
### Chapter 8: When Models Meet Data
#### Section 1: Data, Models and Learning
- Data as Vectors
    - Discusses how data should be tabular usually, where each row represents a vector of features or attributes
    - Definitions for vectors of features (xn) and targets (y)
    - *feature maps* can represent xn in a higher dimensional representation 
    - *kernal* -> feature map leads to kernal (CH 12)
- Models as Functions
    - Once data is in vector representation, we can construct a predictor
    - Predictor as a function vs a probabalisitic model (p 261)
    - "A predictor is a function that, when given a particular input example (in our case, a vector of features), produces an output. For now, consider the output to be a single number, i.e., a real-valued scalar output. This can be written as f : R^D → R, where the input vector x is D-dimensional (has D features), and the function f then applied to it (written as f(x)) returns a real number
    - We use the linear function case: f(x) = (θ^⊤)x + θ0 for unknown θ and θ0
- Models as Probability Distributions
    - "how to use concepts from probability (Chapter 6) to define machine learning models in Section 8.4, and introduce a graphical language for describing probabilistic models in a compact way in Section 8.5."
- Learning is Finding Parameters
    - "The goal of learning is to find a model and its corresponding parameters such that the resulting predictor will perform well on unseen data. There are conceptually three distinct algorithmic phases when discussing machine learning algorithms:"
        - 1. Prediction or inference
        - 2. Training or parameter estimation
        - 3. Hyperparameter tuning or model selection
    - "The prediction phase is when we use a trained predictor on previously unseen test data"
    - "When we have a probabilistic model (discussed further in Section 8.4) the prediction phase is called inference"
    - "Remark. Unfortunately, there is no agreed upon naming for the different algorithmic phases. The word “inference” is sometimes also used to mean parameter estimation of a probabilistic model, and less often may be also used to mean prediction for non-probabilistic models."
    - The training or parameter estimation phase is when we adjust our predictive model based on training data
        - Stategies are finding the best predictor based on some measure of quality (sometimes called finding a point estimate), or using Bayesian inference
    - For the non-probabilistic model, we follow the principle of empirical risk empirical risk minimization
        - Maximum likelihood
    - *cross validation* - how to  simulate the behavior of our predictor on future unseen data
    - *abduction* - trade off between fitting well on training data and finding “simple” explanations of the phenomenon
    - *hyperparameter*
    - *model selection* 
    - *nested cross validation* - For non-probabilistic models, model selection is often done using this method

### Chapter 9: Linear Regression
- This chapter motivates linear regression from the problem of modeling noisy data, presenting the same linear regression formula as a maximum likelihood solution.
#### Section 0
TODO

#### Section 1
TODO
#### Section 2 (until 9.2.2)
TODO