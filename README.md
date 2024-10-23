# Diabetes Progression Model

## Table of Contents

1.  introduction
2.  dataset
3.  loading-and-preprocessing
4.  exploratory-data-analysis-eda
5.  building-the-ann-model
6.  training-the-ann-model
7.  evaluating-the-model
8.  improving-the-model

## Introduction

This project develops a neural network regression model to predict diabetes progression.

## Dataset

- Diabetes dataset from sklearn library

### Loading and Preprocessing

- Loaded Diabetes dataset from sklearn
- Handled missing valuesand duplicates (none present)

### Exploratory Data Analysis (EDA)

- Visualized feature distributions
- Visualized relationships between features and target variable by heatmap
- checked and handled skewness & kurtosis (Square root transformation)

### Building the ANN Model

- Designed simple ANN architecture with 2 hidden layers (64, 32 units)
- Used ReLU activation function

### Training the ANN Model

- Trained model on training data
- Used Mean Squared Error loss function and Adam optimizer

### Evaluating the Model

- Evaluated model on testing data
- Reported performance metrics (Mean Squared Error, R² Score)

### Improving the Model

- Experimented with different architectures, activation functions, and hyperparameters
- Reported changes made and corresponding improvement in performance
