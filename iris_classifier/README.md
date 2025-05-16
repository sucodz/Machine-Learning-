# Iris Flower Classifier

A simple supervised machine learning project that classifies iris flower species using Random Forest.

## Dataset
[UCI Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)

## Features
- Sepal length
- Sepal width
- Petal length
- Petal width

## Goal
Predict the species of iris from given features.

## Results
- Accuracy: 96.7%
- Model: RandomForestClassifier with GridSearchCV
- Balanced precision and recall across classes
- No sign of overfitting or underfitting

## Files
- `iris_classifier.ipynb`: Full notebook
- `requirements.txt`: Dependencies
- `confusion_matrix.png`: Evaluation result

## Model Summary
- Model: RandomForestClassifier with GridSearchCV

- Best Parameters: n_estimators=50, max_depth=3, min_samples_split=2

- Accuracy: 96.7%

- No overfitting/underfitting, confirmed by:

 Balanced classification report

 Clean confusion matrix
