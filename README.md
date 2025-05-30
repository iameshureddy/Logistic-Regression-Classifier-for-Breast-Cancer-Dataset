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

Steps Performed:

1.Load and explore the dataset

2.Split into training and test sets

3.Standardize features

4.Use cross-validation to tune the regularization parameter (C)

5.Train logistic regression model using best C

6.Evaluate model with:

Confusion matrix

Precision and recall

ROC-AUC score

ROC curve

7.Visualize validation curve to check overfitting


How to Run
Install dependencies:


pip install numpy pandas matplotlib scikit-learn
Run the Python script or Jupyter notebook.
