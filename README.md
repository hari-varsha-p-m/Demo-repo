# Neural Network Binary Classification

This repository contains a Python implementation of a simple neural network for binary classification using the sigmoid activation function. The neural network is trained on a sample dataset to predict the output based on the input features.

## Introduction

The neural network architecture consists of an input layer, a hidden layer, and an output layer. The input layer has two neurons, the hidden layer has three neurons, and the output layer has one neuron. The sigmoid activation function is used to introduce non-linearity into the network.

## Dataset

The sample dataset used for training the neural network is provided in the code as follows:

```python
X = np.array(([2, 9], [1, 5], [3, 6]), dtype=float)
y = np.array(([92], [86], [89]), dtype=float)
