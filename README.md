
# Digit Classification with Logistic Regression

## Overview

This repository features a machine learning model built for classifying handwritten digits using logistic regression. The model leverages the classic MNIST-like digit dataset to recognize and predict digits from 0 to 9 based on pixel data.

## Dataset

The dataset used for training and evaluation is the `Digits` dataset, which includes:

- **Features:** Each digit image is represented by a flattened 8x8 grid of pixel values, resulting in a feature vector of 64 values.
- **Target:** Labels corresponding to the digit (0-9) shown in the images.

### Dataset Details

- **Number of Images:** 1,797
- **Image Dimensions:** 8x8 pixels
- **Features per Image:** 64
- **Classes:** 10 (digits 0 through 9)

## Data Visualization

The dataset images are visualized using matplotlib to provide a clearer understanding of what the digits look like. Each image is displayed in grayscale, and the corresponding label is shown.

## Model Training

### Model Type

- **Classifier:** Logistic Regression

### Training

The model is trained using:
- **Training Set:** 80% of the data
- **Test Set:** 20% of the data

### Performance

The model's accuracy is evaluated using the test set, with a final accuracy score of approximately 96.67%. This indicates a strong performance in classifying the digits correctly.

### Confusion Matrix

A confusion matrix is used to visualize the performance of the classifier, showing how many predictions were correct or incorrect for each digit class. The matrix is displayed using seaborn for better interpretability.

## Results

- **Sample Predictions:**
  - Actual: 2, Predicted: 2
  - Actual: 7, Predicted: 7
  - Actual: 8, Predicted: 8

- **Accuracy Score:** 0.9667
