 # Credit Card Fraud Detection using Machine Learning

## Overview

Credit card fraud detection is a crucial aspect for credit card companies to prevent unauthorized transactions and protect their customers from financial losses. This project focuses on utilizing machine learning techniques to identify fraudulent credit card transactions.

## Dataset

The dataset used in this project contains credit card transactions made by European cardholders in September 2013. The dataset is highly unbalanced, with only 0.172% of transactions labeled as fraud. It includes numerical input variables resulting from a PCA transformation. The 'Time' and 'Amount' features have not undergone PCA transformation.

### Dataset Details

- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Positive Class (Frauds) Ratio: 0.172%

### Features

- Principal components obtained with PCA: V1, V2, ..., V28
- Non-PCA transformed features: 'Time', 'Amount'
- Response Variable: 'Class' (1 for fraud, 0 otherwise)

## Evaluation Metric

![image](https://github.com/MadanBabu1314114/Credit-card-Fraud-Detection-using-Machine-learning/assets/123216438/e40f808f-1fab-44e1-a207-342829779e3f)


Due to the class imbalance ratio, it is recommended to measure accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

## Data Simulator

A simulator for transaction data has been released as part of the practical handbook on Machine Learning for Credit Card Fraud Detection. You can find it [here](https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html).

 

## Contributors

- Gaddiparthi Madan Babu
- Additional contributors (if any)

 
