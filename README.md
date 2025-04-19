# Neural Network from Scratch Using Numpy

This repository contains the implementation of a neural network from scratch using Python's Numpy library. It covers the basic operations of a neural network, including forward and backward propagation, the ReLU activation function, and the derivatives of these functions. The dataset used is sourced from Kaggle.

## Table of Contents

1. [Overview](#overview)
2. [Project Structure](#project-structure)
3. [Dependencies](#dependencies)
4. [Data](#data)
5. [Implementation Details](#implementation-details)
   - [Data Splitting](#data-splitting)
   - [ReLU Activation Function](#relu-activation-function)
   - [Forward and Backpropagation](#forward-and-backpropagation)
   - [Testing Functions](#testing-functions)
6. [How to Run](#how-to-run)
7. [Results](#results)
8. [Acknowledgments](#acknowledgments)

## Overview

This project demonstrates the implementation of a neural network from scratch using the Numpy library. The goal is to create a fully functional neural network that can be used for classification tasks. The model includes data preprocessing, activation functions, backpropagation, and evaluation metrics.

## Project Structure

- `neural_network.py`: Main implementation of the neural network with the forward and backward propagation functions.
- `data_processing.py`: Scripts for splitting and preprocessing the dataset.
- `utils.py`: Helper functions, including activation functions like ReLU.
- `test.py`: Script for evaluating the performance of the model.
- `README.md`: Project documentation.

## Dependencies

The following libraries are required to run this project:

- Python 3.x
- Numpy
- Pandas (for data handling)
- Matplotlib (for plotting results)

You can install the dependencies using:

```bash
pip install -r requirements.txt
