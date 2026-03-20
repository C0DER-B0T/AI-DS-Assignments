# Module 4: Introduction to Fully Connected NN - Assignment

## Problem Statement
Fashion MNIST is a dataset comprising 60,000 training images and 10,000 testing images, each depicting various fashion items in a 28x28 grayscale format. The dataset encompasses ten distinct categories of apparel. The primary aim of this assignment is to develop a fully connected neural network (FCNN) that can accurately classify these images into the correct fashion categories.

## Objectives

### 1. Data Visualization and Preprocessing
*   **Visualize:** Show the distribution of different fashion items in the dataset.
*   **Normalize:** Normalize image pixel values for effective training.
*   **One-Hot Encoding:** Convert categorical labels into a one-hot encoded format.

### 2. Model Architecture and Development
*   Design an FCNN with appropriate input, hidden, and output layers.
*   Ensure the model is complex enough to capture patterns without overfitting.

### 3. Model Training
*   **Loss Function:** Categorical Cross-Entropy.
*   **Optimizer:** Stochastic Gradient Descent (SGD).
*   **Metric:** Accuracy.
*   **Validation:** Use a validation split to monitor performance on unseen data.

### 4. Performance Evaluation
*   Assess model performance using both training and validation datasets.
*   Visualize training and validation loss/accuracy to identify overfitting or underfitting.
