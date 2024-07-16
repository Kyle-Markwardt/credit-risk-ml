# LendingClub Loan Risk Prediction

This repository contains scripts for predicting the credit risk of loans using data from LendingClub. The project involves preprocessing the data, training machine learning models, and evaluating their performance.

## Overview

The project uses the following data files:
- `2019loans.csv`: Data from the year 2019.
- `2020Q1loans.csv`: Data from the first quarter of 2020.

These files contain an equal number of high-risk and low-risk loans, undersampled from the original dataset to balance the classes.

## Key Steps

1. **Preprocessing**: Convert categorical data to numeric using `pd.get_dummies()` and ensure both training and testing sets have the same columns.
2. **Model Training**: Train and evaluate Logistic Regression and K-Nearest Neighbors (KNN) models on both unscaled and scaled data.
3. **Evaluation**: Compare the performance of the models and analyze the results.

## Files

- `loan_risk_prediction.py`: Main script for preprocessing, training, and evaluating models.
- `Resources/`: Directory containing the data files `2019loans.csv` and `2020Q1loans.csv`.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn

Install the required packages using:
```bash
pip install pandas numpy scikit-learn
```
