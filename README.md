# MNIST Digit Classification (Digits 1, 2, 3)

A neural network implementation from scratch using NumPy to classify handwritten digits (1, 2, and 3) from the MNIST dataset.

## Table of Contents
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)
- [Implementation Details](#implementation-details)
- [Results](#results)
- [Visualizations](#visualizations)
- [Customization](#customization)
- [License](#license)
- [Future Improvements](#future-improvements)
- [Credits](#credits)
- [Contact](#contact)

## Project Overview

This project implements a simple neural network from scratch (using NumPy) to classify handwritten digits (1, 2, and 3) from the MNIST dataset. The implementation includes:

- Data loading and preprocessing
- One-hot encoding of labels
- Neural network with single layer
- Softmax activation and cross-entropy loss
- Training with gradient descent
- Performance evaluation

## Repository Structure
```
mnist-digit-classification/
├── mnist_neural_network.py # Main implementation script
├── README.md # This documentation file
├── requirements.txt # Python dependencies
├── images/ # Directory for output plots
│ ├── accuracy_vs_epochs.png
│ ├── accuracy_vs_lr.png
│ └── loss_vs_epochs.png
└── data/ # MNIST dataset (auto-downloaded)
```


## Dependencies

- Python 3.6+
- NumPy
- Matplotlib
- Keras (for dataset loading)

Install requirements:
```bash
pip install -r requirements.txt
```


### Implementation Details
Key components of the implementation:

1. Data Preparation
- Load MNIST dataset using Keras
- Filter for only digits 1, 2, and 3
- Flatten and normalize images (28x28 → 784-dim vectors)
- One-hot encode labels
2. Neural Network
- Single layer architecture (784 input → 3 output)
- ReLU activation function
- Softmax output layer
- Cross-entropy loss function
3. Training
- Batch gradient descent
- Learning rate comparison (0.1 to 0.5)
- 50 training epochs
4. Evaluation
- Test accuracy calculation
- Loss and accuracy tracking
- Prediction visualization

## Results
The model achieves the following performance:
# Metric  |  Value
Training Accuracy | ~98%
Test Accuracy | ~96%
Training Time | <1 minute

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax 
