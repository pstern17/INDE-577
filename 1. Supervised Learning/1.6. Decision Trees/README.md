# Decision Trees:

## Introduction:

The Decision Trees algorithm is a popular machine learning technique used for both classification and regression tasks. It is a non-parametric supervised learning method that builds a model in the form of a tree structure to make predictions.

## History:

The concept of decision trees dates back to the 1960s, with the work of Arthur Samuel and others. However, it was not until the 1980s and 1990s that decision trees gained significant popularity, thanks to advancements in computing power and algorithmic improvements.

## How It Works:

The decision tree algorithm works by recursively partitioning the input data based on feature values. It selects the best feature at each step to split the data, aiming to maximize the information gain or minimize the impurity of the resulting subsets. This process continues until a stopping criterion is met, such as reaching a maximum depth or a minimum number of samples in a leaf node.

## Types of Decision Trees:

There are several variations of decision trees, including:

- Classification Trees: Used for categorical target variables, where each leaf node represents a class label.
- Regression Trees: Used for continuous target variables, where each leaf node represents a predicted value.
- Random Forests: Ensembles of decision trees that combine multiple trees to improve prediction accuracy. (See the next folder for a random forests implementation!)
- Gradient Boosted Trees: Ensembles of decision trees that are trained sequentially, with each tree correcting the mistakes of the previous ones.

## Limitations:

While decision trees have many advantages, they also have some limitations, including:

- Overfitting: Decision trees are prone to overfitting, especially when the tree becomes too deep or when the training data is noisy.
- Lack of Robustness: Decision trees are sensitive to small changes in the training data, which can lead to different tree structures and predictions.
- Bias towards Features with More Levels: Decision trees tend to favor features with more levels or categories, potentially neglecting other important features.
- Difficulty Handling Continuous Variables: Decision trees are not well-suited for handling continuous variables directly and often require discretization or other preprocessing techniques.

## Example:

See an example implementation of the decision trees in the jupyter notebook in this folder. Enjoy!