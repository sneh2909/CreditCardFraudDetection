# Credit Card Fraud Detection Project

This project is focused on building a credit card fraud detection system using a dataset from Kaggle. The goal is to develop a machine learning model that can accurately detect fraudulent credit card transactions and minimize false positives.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Result](#Result)

## Introduction

Credit card fraud is a significant concern for financial institutions and consumers alike. Traditional rule-based systems for fraud detection may not be sufficient to handle sophisticated fraudulent activities. Machine learning models can help identify fraudulent transactions by learning from historical data patterns.

This project aims to apply machine learning techniques to a real-world dataset obtained from Kaggle, enabling the creation of a fraud detection model that can be used to identify suspicious transactions in real-time.

## Dataset

The dataset used in this project can be found on Kaggle at the following link: [Kaggle Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains a large number of credit card transactions, some of which are fraudulent, along with various features that describe each transaction. The dataset is labeled, meaning each transaction is marked as either fraudulent or non-fraudulent.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

**Dataset Features:**
- Feature 1
- Feature 2
- ...
- Feature N
- Class (0: Non-fraudulent, 1: Fraudulent)

## Result

Machine Learning model that uses Random Forest Classifier to classify credit card transaction as fraud or valid. The Model has an accuracy of **98%** !



