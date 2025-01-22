# Deep Neural Network from Scratch

This repository contains an implementation of a Deep Neural Network (DNN) from scratch using Python. The goal is to understand and build the core components of a neural network without relying on high-level libraries like TensorFlow or PyTorch.

## Features

- Implementation of forward and backward propagation.
- Support for multiple layers and activation functions.
- Gradient descent optimization.
- Easy-to-understand modular code structure.
- Example datasets for training and testing.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Results](#results)
- [License](#license)

## Introduction

Deep Neural Networks (DNNs) are the foundation of many modern machine learning applications. This project provides an educational implementation of a fully functional DNN to help users understand its inner workings, including:
- Initialization of weights and biases
- Matrix operations for forward propagation
- Computing gradients for backpropagation
- Updating parameters using optimization algorithms

## Requirements

To run this project, ensure you have the following installed:
- Python 3.8 or later
- NumPy
- Matplotlib (optional, for visualizations)

Install the dependencies using:
```bash
pip install numpy matplotlib
Usage
1. Clone the Repository
   git clone https://github.com/yourusername/deep-neural-network-from-scratch.git
   cd deep-neural-network-from-scratch
2. Run the Code
Run the script with a sample dataset:
python b22ee057_b22ee094.py
```
# Customize
Modify the network parameters such as the number of layers, neurons per layer, or learning rate in the code to experiment with different configurations.
Code Structure
b22ee057_b22ee094.py: Main script containing the neural network implementation.
utils.py: Helper functions for data preprocessing and evaluation (if applicable).
datasets/: Sample datasets for training and testing (optional).
Results
Training Accuracy: 100X%

Test Accuracy: 98%

### Confusion Matrix
Below is the confusion matrix generated after testing the model:

![Confusion Matrix](LINK_TO_CONFUSION_MATRIX_IMAGE)

### Loss and Accuracy vs. Epoch
The following graph shows how the loss and accuracy change over epochs:

![Loss and Accuracy vs. Epoch](LINK_TO_LOSS_ACCURACY_IMAGE)



