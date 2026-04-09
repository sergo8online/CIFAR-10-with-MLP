# CIFAR-10 Classification with MLP (PyTorch)

This repository contains a PyTorch implementation of a Multilayer Perceptron (MLP) for image classification on the CIFAR-10 dataset.

Unlike typical approaches based on convolutional neural networks, this model relies solely on fully connected layers. The architecture incorporates Batch Normalization and Dropout to improve training stability and reduce overfitting.

Data preprocessing includes normalization and data augmentation.

## Results
- Train Accuracy: 71%
- Test Accuracy: 63%

## Tech Stack
- PyTorch

## Motivation
This project investigates how far a simple MLP can go on a complex image dataset like CIFAR-10, providing a baseline for comparison with more advanced architectures.
