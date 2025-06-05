Logistic Regression - Breast Cancer Classification

* Overview

This project is part of an AI & ML internship and involves building a binary classification model using Logistic Regression to predict whether a tumor is benign or malignant using the Breast Cancer Wisconsin Diagnostic Dataset.

* Tools & Libraries

Python 3

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

* Dataset

The dataset used is the Breast Cancer Wisconsin Diagnostic Data Set, publicly available from the UCI Machine Learning Repository.

* Project Workflow

1. Data Preprocessing

Removed unnecessary columns (id, unnamed columns)

Converted categorical diagnosis values ('M' and 'B') to binary (1 and 0)

2. Train-Test Split

80% training data, 20% test data

3. Feature Scaling

Standardized feature values using StandardScaler

4. Model Training

Trained Logistic Regression model using Scikit-learn

5. Evaluation Metrics

Accuracy

Precision

Recall

F1 Score

ROC-AUC Score

6. Visualizations

Confusion Matrix

ROC Curve

Sigmoid Function
