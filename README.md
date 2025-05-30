# Logistic Regression Classifier - Breast Cancer Detection

This project implements a binary classifier using Logistic Regression to predict whether a tumor is benign or malignant using the Breast Cancer Wisconsin Dataset.

## Overview

- Algorithm: Logistic Regression
- Dataset: Breast Cancer Wisconsin (built into scikit-learn)
- Objective: Classify tumors as malignant (0) or benign (1)

## Dataset

The dataset is accessed using:


from sklearn.datasets import load_breast_cancer
It contains 569 samples with 30 numerical features describing tumor characteristics.

Steps Performed
Load and explore the dataset

Split into training and test sets

Standardize features

Use cross-validation to tune the regularization parameter (C)

Train logistic regression model using best C

Evaluate model with:

Confusion matrix

Precision and recall

ROC-AUC score

ROC curve

Visualize validation curve to check overfitting


How to Run
Install dependencies:


pip install numpy pandas matplotlib scikit-learn
Run the Python script or Jupyter notebook.

Key Concepts
Binary classification

Logistic regression and sigmoid function

Cross-validation

Regularization to prevent overfitting

ROC and validation curves
