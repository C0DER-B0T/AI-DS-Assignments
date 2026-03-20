# Module 9: Introduction to NLP - Assignment

## Problem Statement

You are a Data Scientist in a big firm. You have to develop a deep learning model to perform sentiment analysis on a dataset of tweets related to various candidates.

## Tasks to be Performed

### 1. Data Loading and Preprocessing
*   Load the tweet data from a CSV file.
*   Filter for relevant columns: `candidate`, `sentiment`, and `text`.
*   Preprocess the text: remove stop words, remove punctuation, convert to lowercase, and perform other cleaning steps.

### 2. Text Vectorization
*   Convert preprocessed text into numerical format using tokenization and padding for use in a deep learning model.

### 3. Model Development
Develop a deep learning model using TensorFlow and Keras including:
*   An **Embedding layer**.
*   A **SpatialDropout1D layer** to prevent overfitting.
*   An **LSTM layer** for sequence data processing.
*   A **Dense layer** for output (classifying sentiment into three categories).

### 4. Model Training and Evaluation
*   Train the model using categorical cross-entropy as the loss function and accuracy as the evaluation metric.
*   Use a validation split to evaluate performance and prevent overfitting.
