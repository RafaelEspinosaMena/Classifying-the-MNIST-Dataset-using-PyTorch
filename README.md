# MNIST Classification with PyTorch

## Project Overview

This project involves building and training a convolutional neural network model using PyTorch to classify handwritten digits from the MNIST dataset.It achieved an overall result of 99.9% accuracy for classification in every class.

## Key Features

#### Data Augmentation: 
Implemented using PyTorch's transforms to include random affine transformations (stretching and compressing), enhancing the model's robustness and generalization.
#### Model Architecture: 
A combination of convolutional and fully connected layers, optimized for image classification tasks.
#### Training and Validation: 
The dataset is split into 60% training, 20% validation, and 20% test sets to ensure a comprehensive evaluation. Early stopping is implemented to prevent overfitting.
#### Performance Visualization: 
Training and validation losses and accuracies are plotted per epoch to monitor the model's learning process.

## Evaluation

The model's performance is evaluated based on accuracy, and a detailed analysis is provided through a confusion matrix and ROC curves for each class. The ROC curves and corresponding AUC scores offer a deeper understanding of the model's classification capabilities for each digit in the MNIST dataset.
