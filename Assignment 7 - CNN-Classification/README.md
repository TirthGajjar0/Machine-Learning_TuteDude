# Assignment 7 - CNN Classification

## Overview

This assignment focuses on developing and evaluating a Convolutional Neural Network (CNN) for delivery status classification.

The objective was to predict whether a food delivery would be completed quickly or delayed using delivery-related features such as distance, traffic conditions, weather, order priority, and delivery personnel experience.

The project covers the complete deep learning workflow, including preprocessing, feature engineering, model development, hyperparameter tuning, validation, and performance evaluation.

## What I Did

### Data Preparation

* Inspected and explored the dataset
* Checked for missing values and duplicates
* Created a binary target variable (Fast / Delayed)
* Applied feature scaling using StandardScaler

### Feature Engineering

* Calculated geographical distance using the Haversine Formula
* Created Rush Hour indicators
* Applied One-Hot Encoding to categorical variables
* Prepared features for CNN training

### CNN Development

Built a Convolutional Neural Network (CNN) consisting of:

* Conv1D Layer
* MaxPooling Layer
* Flatten Layer
* Dense Layers
* Dropout Layer
* Sigmoid Output Layer

### Hyperparameter Tuning

Experimented with:

* Number of Filters
* Dense Layer Size
* Dropout Rate
* Network Architecture

### Model Validation

Validated the model using:

* Confusion Matrix
* ROC Curve Analysis
* 5-Fold Cross Validation

## Results

### Baseline CNN

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 47.5%  |
| Precision | 46.67% |
| Recall    | 35.0%  |
| F1 Score  | 40.0%  |

### Tuned CNN

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 62.5%  |
| Precision | 64.71% |
| Recall    | 55.0%  |
| F1 Score  | 59.46% |

### Cross Validation

* Mean Accuracy: 50.0%
* Standard Deviation: 0.0447

The tuned CNN significantly improved performance compared to the baseline model. However, cross-validation results highlighted the challenges of training deep learning models on relatively small datasets.

## Model Comparison

A Logistic Regression model was used as a baseline for comparison.

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 50.0%    |
| Tuned CNN           | 62.5%    |

The CNN outperformed Logistic Regression across all major evaluation metrics, demonstrating its ability to capture more complex relationships within the dataset.

## Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* TensorFlow
* Keras

## Key Learning Outcomes

* Convolutional Neural Networks (CNN)
* Deep Learning Fundamentals
* Binary Classification
* Feature Engineering
* Hyperparameter Tuning
* Cross Validation
* ROC Curve Analysis
* Model Comparison

## Educational Purpose

This project was completed as part of my Machine Learning learning journey and was designed to provide hands-on experience with deep learning techniques.

The dataset used was relatively small and intended for educational purposes. The primary objective was to understand CNN architecture, model optimization, validation techniques, and performance evaluation rather than achieving production-level accuracy.

## Practical Experience Gained

* CNN Development
* Deep Learning Workflows
* Feature Engineering
* Hyperparameter Optimization
* Model Validation
* Cross Validation
* Performance Evaluation

## Project Status

Completed as part of my Machine Learning learning journey.

