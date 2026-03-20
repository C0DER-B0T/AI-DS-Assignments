# Module 2: Introduction to Neural Networks - Assignment

## Introduction

Neural networks, primarily known for their applications in classification tasks, can also be employed for regression problems. In this exercise, we aim to demonstrate the usage of a simple neural network in predicting a linear relationship between input features and the output.

## Objective

The primary objective is to predict the output value `y` based on two input features `x1` and `x2` using a basic neural network model with the equation `y = 3x1 + 4x2`. The neural network will be trained using a feed-forward and back-propagation mechanism to minimize the error between the predicted and actual values.

## Methodology

### 1. Activation Functions
*   **Sigmoid:** A popular activation function used in neural networks.
*   **Tanh:** Returns values between -1 and 1.
*   **ReLU (Rectified Linear Unit):** Returns positive values as they are and zeroes out negative values.

### 2. Sample Data
Use the following sample data for training:
*   `x1 = 3`
*   `x2 = 2`
*   `y_actual = 17`

### 3. Feed Forward
*   Initialize random weights `w1` and `w2` between 1 and 10.
*   Predict the output `y_pred` using the equation: `y_pred = x1 * w1 + x2 * w2`

### 4. Error Calculation
*   Compute the squared error: `error = (y_actual - y_pred)^2`

### 5. Back Propagation
*   Compute the gradients of the error with respect to the weights.
*   Update the weights using the computed gradients and a learning rate.

### 6. Training
*   Perform the above steps (Feed Forward to Back Propagation) iteratively (e.g., 20 times) to refine the weights and minimize the error.

### 7. Visualization
*   Plot the progression of the error across epochs.
*   Plot the progression of `y_pred` across epochs.

## Expected Outcome

After sufficient training, the predicted `y_pred` should be close to the actual value `y_actual = 17`. The error graph should show a declining trend, indicating that the model is learning and improving its predictions over time.
