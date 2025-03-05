# Building a Neural Network from Scratch with Automatic Differentiation

## Description
This project demonstrates how to build a simple neural network from scratch using a custom `Value` class that supports **automatic differentiation**. The goal is to understand the fundamentals of neural networks, backpropagation, and gradient-based optimization by implementing everything from the ground up.

## Key Features
- **Autograd Engine**: A custom `Value` class that supports basic operations (addition, multiplication, tanh, etc.) and automatically computes gradients using backpropagation.
- **Neural Network**: A simple feedforward neural network trained on a toy dataset.
- **Training and Evaluation**: Visualization of the training process and model predictions.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Pointbr8ker-123/neural_network_from_scratch.git


### Install the required dependencies:

pip install -r requirements.txt


## Usage
1. Open the Jupyter notebook: 
jupyter notebook neural_network_from_scratch.ipynb

2. Run the notebook cells to train the neural network and visualize the results.

## Results
- Training Progress: The loss decreases over epochs, indicating that the network is learning.

- Model Predictions: The network's predictions closely match the ground truth values.

### Repository Structure

neural_network_from_scratch/

├── neural_network_from_scratch.ipynb    # Main notebook

├── requirements.txt                     # List of dependencies        

└── README.md                            # This file

### Acknowledgments
Inspired by Andrej Karpathy's micrograd.

