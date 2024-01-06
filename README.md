# Income Evaluation with Machine Learning

## Overview

The provided Python code focuses on income evaluation using various machine learning classifiers, including Gradient Boosting, Logistic Regression, K-Nearest Neighbors (KNN), Naive Bayes, Support Vector Machines (SVM) with both linear and radial basis function (RBF) kernels, Decision Tree, and Random Forest.

## Data Loading and Exploration

- Loading the 'income_evaluation.csv' dataset.
- Exploring the dataset using descriptive statistics, null checks, pair plots, and correlation heatmap.

## Data Preprocessing

- Dropping duplicates from the dataset.
- Encoding the 'income' column using LabelEncoder.
- Converting categorical columns to object type and performing one-hot encoding.
- Splitting the dataset into features (X) and target variable (y).

## Feature Selection

- Using Recursive Feature Elimination with Cross-Validation (RFECV) to select important features for the Logistic Regression model.

## Model Training

### Gradient Boosting

- Training a Gradient Boosting model with hyperparameter tuning.
- Evaluating the performance using accuracy, confusion matrix, and ROC curve.

### Logistic Regression

- Training a Logistic Regression model.
- Evaluating the performance using confusion matrix, accuracy, and ROC curve.

### K-Nearest Neighbors (KNN)

- Training a KNN model with 7 neighbors.
- Evaluating the performance using confusion matrix and accuracy.
- Visualizing the ROC curve.

### Naive Bayes

- Training a Gaussian Naive Bayes model.
- Evaluating the performance using confusion matrix and accuracy.

### Support Vector Machines (SVM)

#### Linear Kernel

- Training an SVM model with a linear kernel.
- Evaluating the performance using confusion matrix, f1-score, recall, and ROC curve.

#### RBF Kernel

- Training an SVM model with an RBF kernel.
- Evaluating the performance using confusion matrix, f1-score, and recall.
- Visualizing the ROC curve.

### Decision Tree

- Training a Decision Tree model.
- Evaluating the performance using confusion matrix, accuracy, and ROC curve.

### Random Forest

- Training a Random Forest model with 10 estimators.
- Evaluating the performance using confusion matrix, accuracy, and ROC curve.

## Conclusion

The code provides a comprehensive analysis of different machine learning classifiers for income evaluation. It covers data loading, preprocessing, feature selection, model training, and evaluation. Adjustments may be required based on the characteristics of the actual dataset.

## Note

This analysis assumes that the dataset 'income_evaluation.csv' contains relevant information for predicting income. Customization may be needed depending on the dataset's specifics.
