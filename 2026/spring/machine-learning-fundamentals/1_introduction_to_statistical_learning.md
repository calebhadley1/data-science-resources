# [An Introduction to Statistical Learning: With Applications in Python](https://www.statlearning.com/)
James, G., Witten, D., Hastie, T., Tibshirani, R., & Taylor, J. (2023)

## Preface
- The Elements of Statistical Learning book is mentioned as the first mainstream stats book. ISLR was born out of a need for a less mathematically leaning explanations of statistical methods. The initial version was in R and later Python became popular, so this version was released.
## Chapter 1. Introduction
- Pages 1-2 briefly discuss the differences in supervised/unsupervised learning and classification/regression problems.
- The Wages dataset is introduced, including the features and some preliminary discussion about how age and education can affect wages. This dataset can be used for supervised learning
- The Gene Expression (NCI60) dataset is introduced as a dataset which only has input features. This dataset can be used for clustering
- A Brief History of Statistical Learning (p. 5)
    - This section describes the origins of regression, classification, neural nets, etc.
- Pages 8-10 discuss the books notation
- Page 12 includes a table of the datasets used throughout the book

## Chapter 2. Statistical Learning
### Section 1: What is Statistical Learning
- Page 15 introduces the notion of features (X) and the response or independent variable (Y)
- Page 17 discusses estimating a function (f) to predict the independent variable
#### Subsection 1: Why estimate *f*?
- Prediction
    - Reducible vs irreducible error
        - We can reduce the error for *f*, but no matter how much we reduce it, Y^ will never directly represent Y (page 17)
- Inference
    - Which predictors are associated with the response?
    - What is the relationship between the response and each predictor?
    - Can the relationship between Y and each predictor be summarized using linear equation? Or more complicated?
#### Subsection 4: Supervised vs Unsupervised Learning
- This section discusses the difference between supervised and unsupervised learning. Specifically the lack of response variables in unsupervised learning and what you can do instead
### Section 2: Assessing Model Accuracy
#### Subsection 1: Measuring the Quality of Fit
- Mean Squared Error (MSE)
- We need to evaluate the evaluation metric against the *test set*, not the training set exclusively. As the model is given more flexibility it will fit the training set better, but it may overfit.
- Cross validation can be used to ensure that the choice of training set does not majorly influence the resulting model

## Chapter 3: Linear Regression
### Section 1: Simple Linear Regression
- Formulas for describing a linear relationship betweeen X and Y are derived on pages 70-71
- Coefficient estimation (p. 71)
    - Residual sum of squares (RSS)
- Accuracy of coefficient estimation (p. 72)
    - Y = f(x) + error. When approximation f(x) we can use Y = B0 + B1X + E
        - The error term is a catch all
    - Population regression line vs least squares line
        - We can only optimize coefs based on available data. The full population data is not available so these lines are not equal. See fig 3.3 on page 74
    - Residual standard error (RSE) (p. 75)
        - Can be used to calculate *confidence intervals*
    - T Statistic (p. 76)
- Assessing the Accuracy of the Model (p. 77)
    - RSE + R^2 (p. 77 - 79)
### Section 2: Multiple Linear Regression
- By extending the Simple Linear Regression, we can use multiple predictors. It is not effective to train multiple models for each feature

## Chapter 5: Resampling Methods 
### Section 2: The Bootstrap
- Used to "quantify the uncertainty associated with a given estimator or statistical learning method" (p. 212)
- This method can estimate standard errors of the coefs from a lin reg fit. It can also be adapted to many other statistical learning methods

# TODO read pages 86-87 on feature selection