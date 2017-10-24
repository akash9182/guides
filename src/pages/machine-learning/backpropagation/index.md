---
title: Backpropagation
---
## Backpropagation
Backpropagation, short for "backward propagation of errors", is an algorithm used for supervised learning in Artificial Neural Networks(ANN). It teaches the network to correctly feed forward(update its weights) through ANN by learning from labeled training data. It calculates the gradient of error function with respect to the neural network's weights. Simply put, the Backprop algorithm is "**learning from mistakes**". 

The "backward" part of the name stems from the fact that its calculation of weight optimization(gradient) proceeds backward through the network. Initially, all the weights are randomly initialized. For each input in the training dataset, the ANN is activated and its output is observed and compared with the desired output we already know. The gradient of the error function is computed and used to correct the initial weights. This is calculated by applying the Chain rule to the error function. In fact, the better name for Backpropagation is "Applying Chain rule forever". The error is then propagated back to the previous layer. This process is repeated until the error is low, well enough that the network does its task accurately. 

- [Gradient Calcalation](https://brilliant.org/wiki/backpropagation/#formal-definition)

## What is its significance?
Almost all ANNs use gradient descent, and backprop is one of the cleanest and most efficient ways to find the gradient. So it is the backbone of ANN training.

## **Related videos**:

- [Neural Networks Demystified: BackPropagation ](https://youtu.be/GlcnxUlrtek)
- [BackProp in 5 minutes](https://youtu.be/q555kfIFUCM)

## **Sources**:
- [Explain back propagation algorithm to a beginner](https://www.quora.com/How-do-you-explain-back-propagation-algorithm-to-a-beginner-in-neural-network)
- [How the backpropagation algorithm works](http://neuralnetworksanddeeplearning.com/chap2.html)
