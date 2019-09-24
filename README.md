# NNprediction

In this code we use NN for the regression problem to predict the future output of a nonlinear function given in data samples (regression sine.mat).

This example has been modified from : https://medium.com/@benjamin.phillips22/simple-regression-with-neural-networks-in-pytorch-313f06910379

We modified the learning process into a single pass learning (no epoch) with moving horizon or sliding window (N).

This learning concept is suitable for:
  1. Data stream machine learning problem
  2. Nonlinear system prediction or modelling
  3. Intelligent control system
