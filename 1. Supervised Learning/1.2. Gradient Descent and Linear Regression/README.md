# The Gradient Descent Algorithm:

The Gradient Descent algorithm is an optimization algorithm commonly used in machine learning and deep learning. It is used to minimize the cost function of a model by iteratively adjusting the model's parameters.

## History:

The gradient descent algorithm is a product of early to mid 20th-century mathematics although it was first discovered in 1847 by Augustin-Louis Cauchy. The algorithm eventually evolved into a foundational optimization method used in machine learning algorithms later on. 


## How it works:

1. Initialize the model's parameters with some starting values.
2. Calculate the gradient of the cost function with respect to each parameter.
3. Update the parameters by taking a step in the opposite direction of the gradient, multiplied by a learning rate.
4. Repeat steps 2-3 until the cost function converges or a maximum number of iterations is reached.

## Learning Rate:

The learning rate, which is multiplied by the gradient, helps determine the size of the step at each iteration. A high learning rate may cause the algorithm to converge quickly, but it may also overshoot the optimal solution. On the other hand, a low learning rate may result in slow convergence.

## Types of Gradient Descent:

There are different variations of the gradient descent algorithm, including:

- Stochastic Gradient Descent: Updates the parameters using the gradients calculated from a single randomly selected training sample.
- Batch Gradient Descent: Updates the parameters using the gradients calculated from the entire training dataset.
- Mini-Batch Gradient Descent: Updates the parameters using the gradients calculated from a small randomly selected subset of the training dataset.

These algorithms are very important to machine learning. 

## Limitations:

The Gradient Descent algorithm has some limitations:
- We are only guaranteed to reach a local minimum, so we may never find the global optimal solution. 
- Gradient descent may result in different found solutions given different starting parameters and learning rate.
- It may require a large number of iterations to converge, especially for complex models or large datasets. You can experiment with better step sizes for better, quicker results. 

***


# Linear Regression:

Linear regression is a popular algorithm used in machine learning and statistics for predicting a continuous outcome variable based on one or more input variables. 

## History:

The concept of linear regression dates back to the early 19th century when mathematician Carl Friedrich Gauss introduced the method of least squares. Adding to Gauss' work, Francis Galton who popularized the use of linear regression in the late 19th century by applying it to the study of heredity. The algorithm has only grown since then.

## How it Works:

Linear regression aims to find the best-fitting line that represents the relationship between predictor variable(s) and a response variable. The line is defined by a slope and an intercept, and the goal is to minimize the difference between the predicted values and the actual values.

The algorithm works by calculating the optimal values for the slope and intercept using ordinary least squares. It minimizes the sum of the squared differences between the predicted values and the actual values for the given data. Once the line is determined, it can be used to make predictions on new data by plugging in the input variables.

## Types of Linear Regression:

There are different types of linear regression, depending on the number of input variables and the nature of the relationship between the variables. Some common types include:

- Simple linear regression: Involves a single input variable.
- Multiple linear regression: Involves multiple input variables.
- Polynomial regression: Allows for non-linear relationships by including polynomial terms of the input variables.

For simplicity, I will just use simple linear regression. 

## Limitations:

While linear regression is a powerful algorithm, it does have some limitations:

- Linearity assumption: Linear regression assumes a linear relationship between the input variables and the output variable. If the relationship is non-linear, linear regression may not be the best choice.
- Sensitivity to outliers: Linear regression is sensitive to outliers, which can significantly impact the model's performance.
- Reliant on the data: Recently, there have been issue with "p-value hacking" where people take huge amounts of data and manipulate it to get a model that seems statistically significant in ways that may not actually reflect the true spread of the data.

## Example:

See an example implementation of the linear regression and gradient descent algorithms in the jupyter notebook in this folder. Enjoy!