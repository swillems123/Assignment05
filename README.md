# Breast Cancer Classification

## Overview
This project implements machine learning classification models to aid in breast cancer detection using the Scikit-learn breast cancer dataset. Three different models (Logistic Regression, Random Forest, and SVM) are trained, optimized, and compared to determine the most effective approach for distinguishing between malignant and benign tumors.

## Purpose
Using machine learning for early detection has contributed to reduced breast cancer mortality rates (down 44% over 30 years). This project explores how different classification algorithms perform with medical imaging data.

## Features
- Data exploration and visualization of the Wisconsin Breast Cancer dataset
- Implementation of three classification models:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine
- Hyperparameter optimization using GridSearchCV
- Comprehensive performance evaluation (accuracy, precision, recall, F1, ROC AUC)
- Feature importance analysis
- Model comparison and recommendation

## Class Structure
The `BreastCancerClassifier` class encapsulates the entire workflow:
- Data loading and preprocessing
- Model training and optimization
- Performance evaluation
- Visualization generation
- Report creation

## Results
Support Vector Machine achieved the best performance:
- Accuracy: 98.25%
- Precision: 98.61%
- Recall: 98.61%
- F1 Score: 98.61%
- ROC AUC: 99.37%

## Installation & Usage
