# Neural Network from Scratch using NumPy

This project provides a complete, professional implementation of a basic neural network built entirely with NumPy. It demonstrates a solid understanding of core machine learning principles by manually constructing each component without relying on high-level libraries such as TensorFlow or PyTorch.

## Overview

The project includes a Jupyter Notebook that walks through the full development of a neural network, covering:

- Manual dataset loading and splitting
- Forward propagation
- ReLU activation function and its derivative
- Backward propagation using gradients
- Weight and bias updates
- Custom evaluation and testing functions

Every part of the process was implemented from scratch using only NumPy.

## Project Structure


## Dataset

- The dataset used was sourced from Kaggle.
- It is stored locally in the `dataset/` folder.
- All data preprocessing, splitting, and usage are handled manually within the notebook.

## Key Components

- **Data Splitting**: The dataset is divided manually into training and testing sets.
- **ReLU Activation**: Both the ReLU function and its derivative are implemented explicitly.
- **Forward Propagation**: Computes outputs layer-by-layer using matrix operations.
- **Backward Propagation**: Gradients are calculated manually to update the model's parameters.
- **Model Evaluation**: Includes custom functions to test and evaluate performance on test data.

## Motivation

The primary goal of this project was to gain a clear and practical understanding of how neural networks function internally. By avoiding machine learning libraries and coding each function from scratch, I was able to deepen my understanding of:

- Neural network architecture
- The mathematics behind training models
- The flow of data during training and inference
- The role of activation functions and gradients in learning

This project reflects both technical knowledge and the discipline to build a complete learning system from first principles.

## How to Run

To execute this project locally:

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd <repo-name>
