# Module 7: Learning from Pre-Built Models - Assignment

## Problem Statement
The goal is to develop a model capable of accurately distinguishing between cat and dog images using **transfer learning**. Instead of building a CNN from scratch, we leverage the **VGG16** model (pre-trained on ImageNet). We will use the convolutional layers of VGG16 for feature extraction and add custom fully connected layers for the classification task.

## Objectives

### 1. Utilize VGG16 for Feature Extraction
*   Employ the VGG16 model, excluding its top layers.
*   Ensure input images are resized to **150x150** and preprocessed to match VGG16 requirements.

### 2. Data Preprocessing and Augmentation
*   Implement image data generators for real-time data augmentation to ensure a robust and varied dataset.

### 3. Build and Train the Classification Model
*   Add custom fully connected layers on top of the VGG16 base.
*   **Freeze** the convolutional layers of VGG16 to retain pre-trained features.
*   Only train the added classification layers.

### 4. Model Compilation and Training
*   **Optimizer:** Stochastic Gradient Descent (SGD).
*   **Loss Function:** Categorical Cross-Entropy.
*   **Metric:** Accuracy.
*   Train using training data and validate performance with a validation set.

### 5. Evaluate and Test the Model
*   Assess model performance based on accuracy in classifying cats vs. dogs.
*   Implement a **prediction function** to classify new images, providing the predicted category and confidence level.
