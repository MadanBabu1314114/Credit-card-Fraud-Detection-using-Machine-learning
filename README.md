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

Due to the class imbalance ratio, it is recommended to measure accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

## Data Simulator

A simulator for transaction data has been released as part of the practical handbook on Machine Learning for Credit Card Fraud Detection. You can find it [here](https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html).

## Acknowledgements

The dataset was collected and analyzed through a research collaboration between Worldline and the Machine Learning Group of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. Please cite the following works:

- [Dal Pozzolo et al., 2015](link)
- [Dal Pozzolo et al., 2014](link)
- [Dal Pozzolo et al., 2018](link)
- [Dal Pozzolo, 2017](link)
- [Carcillo et al., 2018](link)
- [Carcillo et al., 2018](link)
- [Lebichot et al., 2019](link)
- [Carcillo et al., 2019](link)
- [Le Borgne and Bontempi, Handbook](link)
- [Lebichot et al., Incremental Learning](link)

## Contributors

- Your Name
- Additional contributors (if any)

## License

This project is licensed under the [MIT License](LICENSE).
