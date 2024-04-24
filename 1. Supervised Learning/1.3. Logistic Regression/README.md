# Logistic Regression

Logistic regression is a popular statistical model used for binary classification problems. It is widely used in various fields, including machine learning, because of the way it can perform binary classification on datasets that are split non-linearly. 

## History

Logistic regression was first introduced by statistician David Cox in 1958. Logistic regression is a variation of linear regression, specifically for the purpose of binary classification. Over the years, logistic regression has evolved and gained popularity due to its simplicity and interpretability.

## How It Works

Logistic regression models the relationship between a set of independent variables and a binary dependent variable. It uses the logistic function (also known as the sigmoid function) to transform the linear regression output into a probability value between 0 and 1. This probability represents the likelihood of the input belonging to a particular class. Then, simply maximize the total probability that your predictions are correct. 

## Limitations:

The Logistic Regression algorithm has some limitations:

- Sensitive to outliers, especially when using the maximum likelihood estimation method.
- Prone to overfitting when the number of features is large compared to the number of observations.
- May suffer from multicollinearity when independent variables are highly correlated, affecting the stability of coefficient estimates.

## Example:

See an example implementation of the logistic regression algorithm in the jupyter notebook in this folder. Enjoy!

