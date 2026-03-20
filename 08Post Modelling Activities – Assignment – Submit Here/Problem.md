# Module 6: Post Modelling Activities - Assignment

## Problem Statement
Fashion MNIST is a dataset of Zalando's article images, consisting of 60,000 training examples and 10,000 test examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. The task is to classify these images into an apparel category amongst 10 categories on which the dataset is benchmarked.

## Objectives

### 1. Data Preparation and Visualization
*   Load the Fashion MNIST dataset.
*   Visualize different samples from the dataset.
*   Normalize pixel values to be between 0 and 1.
*   Convert output labels to categorical format.

### 2. Model Building and Training
Construct a Neural Network using TensorFlow and Keras:
*   Use multiple **dense layers** with a significant number of neurons.
*   Use **ReLU activation** for hidden layers and **Softmax activation** for the output layer.
*   Train the model on the prepared dataset.
*   Implement callbacks, particularly **TensorBoard**, to visualize the training process.

### 3. Model Evaluation and Analysis
*   Evaluate performance using a validation set.
*   Analyze the training process with TensorBoard.
*   **Save the trained model**, including its architecture and learned weights.

### 4. Model Loading and Verification
*   Load the saved model and verify its architecture.
*   Check the consistency in the number of model parameters and weights.
