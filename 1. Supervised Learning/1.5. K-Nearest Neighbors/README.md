# K-Nearest Neighbors Algorithm

## Introduction:

The k-nearest neighbors (KNN) algorithm is a popular supervised machine learning algorithm used for classification and regression tasks. It is a non-parametric algorithm that makes predictions based on the similarity of input data points to their k nearest neighbors in the training dataset.

## History:

The KNN algorithm was first introduced by Evelyn Fix and Joseph Hodges in 1951 as a non-parametric pattern recognition method. It gained popularity in the field of machine learning due to its simplicity and effectiveness in various domains.

## How It Works:

1. Choose the value of k, which represents the number of nearest neighbors to consider.
2. Calculate the distance between the input data point and all the data points in the training dataset.
3. Select the k nearest neighbors based on the calculated distances.
4. For classification tasks, assign the majority class label among the k nearest neighbors to the input data point.
5. For regression tasks, calculate the average or weighted average of the target values of the k nearest neighbors and assign it to the input data point.

## Types:

There are different variations of the KNN algorithm, including:
- Standard KNN: The basic version of the algorithm that assigns equal weights to all the nearest neighbors.
- Weighted KNN: Assigns weights to the nearest neighbors based on their distance from the input data point.
- Distance-Weighted KNN: Assigns weights to the nearest neighbors based on their distance, giving more importance to closer neighbors.

## Limitations:

The KNN algorithm has some limitations, including:
- Computational Complexity: As the size of the training dataset grows, the algorithm becomes computationally expensive.
- Sensitive to Noise and Outliers: KNN is sensitive to noisy and outlier data points, which can affect the accuracy of predictions.
- Choosing the Right Value of k: The choice of k can significantly impact the performance of the algorithm, and finding the optimal value requires experimentation and tuning.

## Example:

See an example implementation of the k-nearest neighbors algorithm in the jupyter notebook in this folder. Enjoy!
