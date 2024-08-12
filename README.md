# About this project
This repository contains a custom neural network framework implemented from scratch using the numpy library. The framework includes essential components like linear layers, activation functions like ReLU and Softmax, CrossEntropyLoss function, and SGD optimizer. The framework is used to train a model on the MNIST dataset.


## MODEL WEIGHTS:


For the First Linear Layer: Linear(784, 128) 

For the Second Linear Layer: Linear(128, 10) 


## Description
### 1. Linear Layer
The layer performs the operation:
output = input × weights + biases

### 2. ReLU
ReLU performs the operation:
ReLU(x)=max(0,x)

### 3. Softmax function
Softmax performs the operation:
Softmax(x i) = exp(x i) / ∑ exp(x j)

