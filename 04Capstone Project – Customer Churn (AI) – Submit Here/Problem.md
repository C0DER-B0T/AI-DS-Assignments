# Project: Binary Classification on 'Customer_Churn' using Keras

## Problem Statement
You are the Data Scientist at a telecom company "Leo" whose customers are churning to competitors. You need to analyze the company's data to find insights and develop a model to predict and prevent customer churn.

## Dataset Information
*   **Dataset:** `customer_churn`
*   **Domain:** Telecom
*   **Environment:** Jupyter Notebook

---

## Tasks to be Performed

### A) Data Manipulation
Perform the following extractions and calculations:
1.  Find the total number of male customers.
2.  Find the total number of customers whose Internet Service is 'DSL'.
3.  Extract all female senior citizens whose payment method is 'Mailed check' and store the result in `new_customer`.
4.  Extract customers whose tenure is less than 10 months OR their total charges are less than $500, and store the result in `new_customer`.

### B) Data Visualization
1.  Build a pie chart showing the distribution of customers who are churning.
2.  Build a bar plot showing the distribution of 'Internet Service'.

### C) Model Building

#### Model 1: Single Feature
*   **Feature:** `tenure`
*   **Target:** `Churn`
*   **Architecture:**
    *   **Input Layer:** 12 nodes, ReLU activation.
    *   **Hidden Layer:** 1 hidden layer, 8 nodes, ReLU activation.
    *   **Optimizer:** Adam.
    *   **Training:** 150 epochs.
*   **Evaluation:** Predict on test set, build confusion matrix, and plot 'Accuracy vs Epochs'.

#### Model 2: With Dropout
*   **Feature/Target:** Same as Model 1.
*   **Architecture:**
    *   Add a Dropout layer (0.3) after the input layer.
    *   Add a Dropout layer (0.2) after the hidden layer.
*   **Evaluation:** Predict on test set, build confusion matrix, and plot 'Accuracy vs Epochs'.

#### Model 3: Multi-Feature
*   **Features:** `Tenure`, `Monthly Charges`, `Total Charges`
*   **Target:** `Churn`
*   **Architecture:**
    *   **Input Layer:** 12 nodes, ReLU activation.
    *   **Hidden Layer:** 8 nodes, ReLU activation.
    *   **Optimizer:** Adam.
    *   **Training:** 150 epochs.
*   **Evaluation:** Predict on test set, build confusion matrix, and plot 'Accuracy vs Epochs'.
