# Implementation of LSTM for PyTorch



This repository is an implementation of the LSTM cells descibed in **Lstm: A search space odyssey** paper without using the PyTorch LSTMCell.  

Paper link: https://arxiv.org/pdf/1503.04069

This code is the modification of this repository: https://github.com/emadRad/lstm-gru-pytorch

## Summery
It is tested on the MNIST dataset for classification. 

The 28x28 MNIST images are treated as sequences of 28x1 vector.

The RNN consist of 

- A linear layer that maps 28-dimensional input to and 128-dimensional hidden layer
- One intermediate recurrent neural network (LSTM)
- A fully connected layer which maps the 128 dimensional input to 10-dimensional vector of class labels.



## Requirements 

Python>=3.5

PyTorch== 1.0.0



