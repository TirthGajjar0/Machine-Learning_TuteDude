# Assignment 5 - Clustering and Neural Networks

## Overview

This assignment explores both unsupervised learning and deep learning techniques using a food delivery dataset.

The project focuses on identifying delivery behavior patterns through clustering and predicting delivery status using an Artificial Neural Network (ANN).

## What I Did

### Data Preparation

- Cleaned and prepared the dataset
- Encoded categorical features
- Standardized numerical variables
- Calculated geographical distance using the Haversine Formula
- Created rush-hour indicators
- Generated delivery status categories (Fast / Delayed)

### Clustering Analysis

Implemented and compared:

- K-Means Clustering
- Hierarchical Clustering (Agglomerative Clustering)

#### Clustering Evaluation

- Elbow Method
- Silhouette Analysis
- Dendrogram Visualization
- Cluster Interpretation

### Neural Network Development

Built an Artificial Neural Network (ANN) using:

- Input Layer
- Hidden Layers with ReLU Activation
- Sigmoid Output Layer

### Model Improvement

Experimented with:

- Number of Hidden Layers
- Number of Neurons
- Learning Rate
- Activation Functions
- Training Epochs

### Model Evaluation

Evaluated the neural network using:

- Accuracy
- Precision
- Recall
- F1 Score

## Results

### Clustering Results

#### K-Means Clustering

- Optimal Clusters: 5
- Silhouette Score: 0.0633

#### Hierarchical Clustering

- Optimal Clusters: 5
- Silhouette Score: 0.0520

The clustering analysis revealed meaningful delivery behavior groups and highlighted the influence of traffic conditions, rush-hour periods, and delivery personnel experience on delivery performance.

### Neural Network Results

#### Baseline Model

- Accuracy: 50%
- Precision: 0.49
- Recall: 0.50
- F1 Score: 0.49

#### Tuned Model

- Accuracy: 70%
- Precision: 0.72
- Recall: 0.70
- F1 Score: 0.70

The tuned neural network significantly outperformed the baseline model after hyperparameter optimization.

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- TensorFlow
- Keras

## Key Learning Outcomes

- Understanding Unsupervised Learning
- K-Means Clustering
- Hierarchical Clustering
- Cluster Evaluation Techniques
- Artificial Neural Networks (ANN)
- Hyperparameter Tuning
- Deep Learning Fundamentals
- Model Evaluation and Comparison

## Educational Purpose

This project was completed as part of my Machine Learning learning journey and was designed to provide hands-on experience with clustering techniques and neural networks.

The dataset used was intended for educational purposes. The primary objective was to understand pattern discovery through clustering and develop practical experience in building, tuning, and evaluating neural network models.

## Practical Experience Gained

- K-Means Clustering
- Hierarchical Clustering
- Silhouette Analysis
- Elbow Method
- Dendrogram Analysis
- Artificial Neural Networks
- Hyperparameter Tuning
- Deep Learning Workflows

## Project Status

Completed as part of my Machine Learning learning journey.
