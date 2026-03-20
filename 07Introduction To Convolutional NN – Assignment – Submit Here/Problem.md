# Module 5: Introduction to Convolutional NN - Assignment

## Problem Statement
The task involves classifying images of cats and dogs using a Convolutional Neural Network (CNN). Using a dataset of cat and dog images, the objective is to train a CNN model to accurately predict the class of each image.

## Objectives

### 1. Data Preparation
*   Download and extract the cats vs. dogs dataset.
*   Organize the dataset into a structured directory format suitable for TensorFlow’s `ImageDataGenerator`.
*   Split the dataset into training and testing sets.

### 2. Data Augmentation and Preprocessing
*   Implement data augmentation techniques to increase training diversity and aid generalization.
*   Normalize pixel values for optimal model performance.

### 3. Model Building
*   Construct a CNN using TensorFlow and Keras.
*   The model should contain:
    *   Multiple convolutional layers.
    *   Pooling layers.
    *   Fully connected layers.

### 4. Training
*   **Loss Function:** Categorical Cross-Entropy.
*   **Optimizer:** Stochastic Gradient Descent (SGD).
*   **Epochs:** Train for a sufficient number of epochs to achieve good performance.

### 5. Evaluation
*   Evaluate performance on the validation set during training to monitor for overfitting.
*   Assess final accuracy and make predictions on the test set.

### 6. Prediction
*   Implement a system to make predictions on new images (cat or dog).
*   The system should handle both single images and batches, including necessary preprocessing.
