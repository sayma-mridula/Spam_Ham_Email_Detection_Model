# Spam/Ham Email Detection Using Naive Bayes and Bag of Words

This project implements a spam/ham email classification model using the **Naive Bayes** algorithm and **Bag of Words** technique for feature extraction. The model classifies emails as either spam or ham based on the content of the email.

## Project Overview

Spam email classification is a common task in natural language processing (NLP) and machine learning. This project focuses on building a model that can accurately classify emails into spam or ham categories. The steps followed are:

1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Feature Extraction**: Using the **Bag of Words** technique to transform email text into numerical features.
3. **Model Building**: Training a **Naive Bayes classifier** on the dataset to predict spam or ham.
4. **Model Evaluation**: Evaluating the performance of the model using metrics like accuracy, precision, recall, and F1-score.

## Dataset

The dataset used in this project is provided in the `spam.csv` file and contains the following columns:

- `v1`: The target variable (spam or ham).
- `v2`: The email content (text).

## Files

- `spam.csv`: The dataset for email classification.
- `spam_ham_detection.ipynb`: Jupyter notebook implementing data preprocessing, feature extraction, and Naive Bayes classification.

## Requirements

The following Python libraries are required to run this project:

- pandas
- numpy
- scikit-learn
- nltk
- matplotlib

You can install the necessary libraries using pip:

```bash
pip install pandas numpy scikit-learn nltk matplotlib
