# Module 8: Recurrent Neural Networks - Assignment

## Problem Statement
Build a sentiment analysis model using Recurrent Neural Networks (RNNs) to classify movie reviews from the IMDB dataset into positive or negative sentiments.

## Dataset
The dataset comprises 25,000 movie reviews from IMDB, labeled by sentiment (positive/negative). Reviews are preprocessed and encoded as sequences of word indices (integers).

## Tasks to be Performed

### 1. Data Preprocessing
*   Load the IMDB dataset, keeping only the **top 10,000** most frequently occurring words.
*   **Pad the sequences** so that they all have the same length.

### 2. Model Building
*   Create a **Sequential RNN model** using TensorFlow and Keras.
*   The model should consist of:
    *   An **Embedding layer**.
    *   A **SimpleRNN layer**.
    *   A **Dense output layer**.
*   Compile the model with the appropriate optimizer, loss function, and metrics.

### 3. Training
*   Train the model on the preprocessed movie reviews.
*   **Batch Size:** 128.
*   **Validation:** Use 20% of the training data for validation.
*   **Epochs:** Run for 10 epochs.

### 4. Evaluation
*   Evaluate the model on the test set and report the accuracy.

## Expected Outcome
A trained RNN model that can classify movie reviews into positive or negative sentiments, with an accuracy metric provided at the end of the training process.
