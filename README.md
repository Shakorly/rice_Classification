# rice_Classification Model

This repository contains a PyTorch-based machine learning model designed to classify rice samples into different classes (e.g., "Class 0" and "Class 1") based on input features. The model uses a neural network with multiple layers, trained and evaluated with a focus on achieving high accuracy and robust performance.

dataset link https://www.kaggle.com/datasets/mssmartypants/rice-type-classification

Overview
Purpose: The model classifies rice samples using a deep learning approach, achieving an accuracy of approximately 99% on the test set.
Framework: Built with PyTorch, a popular deep learning library.
Performance: The model demonstrates excellent precision, recall, and F1-score (all around 0.99) for both classes, as detailed in the classification report.
Features: Includes training, testing, plotting of loss and accuracy, and prediction capabilities.
Installation
Prerequisites
Python 3.11 or higher
PyTorch
NumPy
Matplotlib
Scikit-learn (for classification report)
Pandas (for data handling, if applicable)


Model Architecture
The model is a feedforward neural network with:

Input layer: Matches the number of features in X.shape[1].
Hidden layers: Configurable sizes (default: [64, 32, 16]) with ReLU activations.
Output layer: Single neuron with sigmoid activation for binary classification.
Regularization: Includes dropout (0.3) and weight decay (1e-5) to prevent overfitting.
Results
Training Accuracy: ~0.98
Test Accuracy: ~0.97–0.98
Classification
