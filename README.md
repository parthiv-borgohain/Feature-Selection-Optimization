# Feature Selection Optimization
Project as a part of coursework for Optimization-I in UT Austin's MS Business Analytics Program.

Selecting best features/variables for least squares regression using optimization techniques by minimizing the error. Comparing the results of this method with Lasso regression method of selecting features

## Introduction:

This project aims to compare and contrast the two approaches of variable selection in Machine Learning algorithms, Mixed Integer Quadratic Programming (MIQP) and Lasso Regression. Both methods have their pros and cons, and the purpose of this project is to determine which method is more suitable for a given scenario.

## Section 1: Mixed Integer Quadratic Programming (MIQP)

MIQP is a direct variable selection approach that uses optimization based on the Ordinary Least Squares (OLS) linear regression. The solution obtained from this method is guaranteed to be optimal and results in the best variables that can be selected through the process. The number of variables to be included in the model can be pre-specified.

## Section 2: Lasso Regression

Lasso Regression is an indirect variable selection method that regularizes the coefficients. This method is faster in computation compared to MIQP and helps in introducing bias to the model to find the optimal bias-variance trade-off to get the minimal Total Error. However, it cannot pre-specify the number of variables to be included in the model.

## Comparison:

The results of the comparison between MIQP and Lasso Regression showed that MIQP is more accurate but takes a considerable amount of time to run, while Lasso is quicker but not as accurate. The β values in both models are similar, and the additional variables included in Lasso do not have significant magnitudes.

## Conclusion:

The choice between MIQP and Lasso Regression depends on the resources available, the data points in the dataset, and the number of variables to be included in the model. MIQP is recommended for accuracy if the company has the resources and enough data points to avoid overfitting. Lasso is recommended for large datasets with many dimensions.
