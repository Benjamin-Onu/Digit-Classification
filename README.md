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

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax 
