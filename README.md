# Perceptron Implementation for Logic Gates
## Overview
This project implements a single-layer perceptron neural network capable of learning basic logic gates (AND, OR) while demonstrating its fundamental limitation with the XOR gate. The implementation includes:

- A complete Perceptron class with training and prediction capabilities

- Visualization of decision boundaries

- Training history tracking

- Examples for AND, OR, and XOR gates

## Key Concepts Demonstrated
- Linear Separability: Shows how perceptrons can learn AND/OR (linearly separable) but fail at XOR

- Neural Network Fundamentals: Weight updates, activation functions, and learning process

- Decision Boundaries: Visual representation of the perceptron's classification capability

## Implementation Details
- Perceptron Class Features
- Initialization: Configurable learning rate and number of epochs

- Training: Implements the perceptron learning rule

- Prediction: Binary classification using step activation

- Visualization: Plots decision boundaries for 2D inputs

- History Tracking: Records weights, bias, and errors during training

## Expected Results
#### AND/OR Gates:

- Training will converge with 0 errors

- Decision boundary will perfectly separate classes

- 100% prediction accuracy

#### XOR Gate:

- Training will not converge

- Decision boundary will fail to separate classes

- Prediction accuracy will be ≤ 75%

## Educational Value
#### This implementation serves as an excellent demonstration of:

- The capabilities and limitations of single-layer perceptrons

- The importance of multi-layer networks for non-linear problems

- Fundamental machine learning concepts like weight updates and decision boundaries

- The clear visualization of decision boundaries makes it particularly valuable for understanding linear separability in neural networks.