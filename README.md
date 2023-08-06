# Credit Card Fraud Detection Project

This project is focused on building a credit card fraud detection system using a dataset from Kaggle. The goal is to develop a machine learning model that can accurately detect fraudulent credit card transactions and minimize false positives.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)

## Introduction

Credit card fraud is a significant concern for financial institutions and consumers alike. Traditional rule-based systems for fraud detection may not be sufficient to handle sophisticated fraudulent activities. Machine learning models can help identify fraudulent transactions by learning from historical data patterns.

This project aims to apply machine learning techniques to a real-world dataset obtained from Kaggle, enabling the creation of a fraud detection model that can be used to identify suspicious transactions in real-time.

## Dataset

The dataset used in this project can be found on Kaggle at the following link: [Kaggle Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains a large number of credit card transactions, some of which are fraudulent, along with various features that describe each transaction. The dataset is labeled, meaning each transaction is marked as either fraudulent or non-fraudulent.

**Dataset Features:**
- Feature 1
- Feature 2
- ...
- Feature N
- Class (0: Non-fraudulent, 1: Fraudulent)

Please download the dataset and save it in the `data/` directory before proceeding.

## Usage

To use the fraud detection model on new data, you can follow the steps below:

1. Load the model and required preprocessing functions.
2. Preprocess the new data using the same preprocessing steps as in the training process.
3. Use the loaded model to predict the class labels (fraudulent or non-fraudulent) for the new data.

Make sure to have the trained model saved in the appropriate directory.


Contributions to this project are welcome! If you find any issues or have ideas to improve the fraud detection model, please submit a pull request or open an issue.

Machine Learning model that uses Random Forest Classifier to classify credit card transaction as fraud or valid. The Model has an accuracy of **98%** !



