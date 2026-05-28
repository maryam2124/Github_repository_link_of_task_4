# Handwritten Digit Classification using ANN (MNIST)

## Overview
This project implements an **Artificial Neural Network (ANN)** to classify handwritten digits using the MNIST dataset. The model is built using TensorFlow/Keras and trained to recognize digits from 0 to 9.

---

## Dataset
The dataset used is the MNIST dataset:
- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- Grayscale handwritten digits (0–9)

---

## Objective
To build a deep learning model that:
- Classifies handwritten digits
- Learns patterns from image data
- Predicts digit labels accurately

---

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

---

## Model Architecture
The ANN model consists of:

- Flatten Layer (28×28 → 784 input features)
- Dense Layer (128 neurons, ReLU activation)
- Dense Layer (32 neurons, ReLU activation)
- Output Layer (10 neurons, Softmax activation)

---

## Data Preprocessing
- Normalization of pixel values (0–255 → 0–1)
- Reshaping images into 28×28 format
- One-hot style classification using sparse labels

---

## Training Process
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 25
- Validation Split: 20%

---

## Model Performance

- **Test Accuracy: 0.9775 (97.75%)**
- Strong generalization with minimal overfitting

---

## Predictions

Example prediction:
```text id="mnist_pred"
Input Image → Model Output: 2
