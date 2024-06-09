## Overview of the Analysis

In this analysis, the goal was to predict credit risk using a machine learning model trained on a dataset containing various financial features. The dataset comprised information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable was binary, with class 0 indicating healthy credit and class 1 indicating high risk.

The machine learning process began with data preprocessing, including splitting the dataset into training and testing sets using stratification to ensure balanced classes. A logistic regression model was then selected and trained on the training data. Model evaluation was performed using a confusion matrix and a classification report.

## Results

Logistic Regression Model:

-Precision for class 0: 100%

-Recall for class 0: 100%

-F1-score for class 0: 100%

-Precision for class 1: 87%

-Recall for class 1: 89%

-F1-score for class 1: 88%

-Accuracy: 99%

## Summary

The logistic regression model demonstrates excellent performance in predicting credit risk. For class 0 (healthy credit), the model achieves perfect precision, recall, and F1-score, indicating accurate classification of instances in this category. For class 1 (high risk), although precision and recall are slightly lower, the model still achieves a high F1-score of 88%, indicating effective identification of high-risk cases.

Overall, the model exhibits high accuracy and balanced performance across both classes, making it a suitable choice for predicting credit risk. However, further analysis and model comparison with alternative algorithms could provide additional insights and validation.
