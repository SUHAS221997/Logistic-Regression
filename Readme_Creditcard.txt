This repository demonstrates how to apply Logistic Regression to predict credit card fraud using a publicly available dataset. The dataset contains anonymized features related to credit card transactions, and the task is to classify each transaction as either fraudulent (1) or non-fraudulent (0).

The Link to Dataset: https://drive.google.com/file/d/1n3VjU48WaQBR7Is4692Ul75wX6B8SXSj/view?usp=sharing

Overview
Credit card fraud detection is a critical application of machine learning. In this project, we use Logistic Regression, a powerful yet simple binary classification algorithm, to predict whether a given transaction is fraudulent based on various transaction features.

Dataset
The dataset used for this project is the Credit Card Fraud Detection Dataset, available on Kaggle. It contains 284,807 transactions, of which 492 are fraudulent, making this an imbalanced dataset.

Features:
•	Time: Time elapsed between the transaction and the first transaction in the dataset.
•	V1, V2, ..., V28: 28 anonymized features representing the transaction details.
•	Amount: The amount of the transaction.
•	Class: The target variable (1 for fraud, 0 for non-fraud).

Requirements:
To run the code, you'll need Python 3.x and the following packages:
•	numpy
•	pandas
•	scikit-learn
•	matplotlib
•	seaborn

