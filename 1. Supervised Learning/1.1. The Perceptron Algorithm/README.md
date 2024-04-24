# Perceptron Algorithm

## History:

The Perceptron algorithm was invented by Frank Rosenblatt in 1957. It was one of the earliest algorithms used for training artificial neural networks. The algorithm become popular because of its simplicity in performing binary classification. 

## How it works:

1. Initialize the weights and bias of the perceptron to some starting value. Oftentimes, random values or zeros are selected first.
2. For each training epoch, calculate the weighted sum of the input features and the corresponding weights.
3. Apply an activation function to the weighted sum to obtain the output of the perceptron.
4. Compare the predicted output with the actual output and adjust the weights and bias based on the error.
5. Repeat steps 2-4 until the perceptron converges or a maximum number of iterations is reached.

## Activation function:

We use a super simple activation function for the perceptron algorithm. If we get a weighted sum that is positive we return 1 and we get -1 otherwise. 

## Limitations:

The Perceptron algorithm has some limitations:
- It works great for binary classification when the data can be split linearly. 
- It might not converge if the data is not linearly separable.

## Example

See an example implementation of the perceptron algorithm in the jupyter notebook in this folder. Enjoy!
