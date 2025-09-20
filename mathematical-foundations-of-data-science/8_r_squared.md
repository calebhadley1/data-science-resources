# [R-Squared or Coefficient of Determination | Regression | Probability and Statistics | Khan Academy (12:40)](https://www.youtube.com/watch?v=lng4ZgConCM)
- This video walks through the process of motivating and calculating R2.
- Explains how to find the "squared error of the regression line"
- How much of the variation in y *is* described by the variation in x (as in the reg line)
    - Finding total variation in y  or the "squared error of mean(y)
- How much of the variation in y *is not* described by the variation in x (as in the reg line)
    - Squared error of the reg line / squared error of mean(y)
- Now you can answer the first question by taking 100% - the answer of the second question.
- This is called R squared or the coefficient of determiniation
- 1 <= R squared <= -inf
- Good fit = R squared close to 1

# [Measuring the fit of a Regression Model: R-Squared](https://mcrovella.github.io/DS701-Tools-for-Data-Science/17-Regression-I-Linear.html#measuring-the-fit-of-a-regression-model-r-2)
- These lecture notes define R2, talk about the intuition behind their use, and warn of traps from similar notation from correlation. The example of linear regression farther down on the page also includes evaluation and discussion of the resulting R2 values.
- Provides a good explanatin of the R^2 = 1 - RSS/TSS formula
- Breaks down RSS, TSS, and Y Variance

# [Statistical Forecasting: Notes on Regression and Time Series Analysis, What’s a Good Value for R-Squared?](https://people.duke.edu/~rnau/rsquared.htm)
- These lecture notes talk about the limitations of R2 in assessing the quality of a model.
- "Adjusted R squared"
- Discusses how high R squared can be misleading. Models can still be poor with a high R squared
- Summary of what a good value for R^2 is (it depends on the type of model)
- Explanations of common pitfalls