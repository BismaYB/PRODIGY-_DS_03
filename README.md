# PRODIGY-_DS_03

Car price classification model

Car Price Classification Model

This project implements a machine learning model to classify car prices as either above median or below median based on various features of the car. The classification is achieved using a Decision Tree Classifier, and the model has been evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Features and Preprocessing

Dataset:
Source: Car details v3.csv

Target Variable: selling_price

Transformed into a binary classification task:1 for Above Median
0 for Below Median

## Preprocessing Steps:

Dropped Unnecessary Columns:
name, year, seats, and torque were excluded from the dataset.

Numeric Feature Extraction:

Extracted numeric values from mileage, engine, and max_power columns.

Converted these values to floats.

Categorical Encoding:

Used Label Encoding for categorical features: fuel, seller_type, transmission, and owner.

## Model Training

Algorithm:
Decision Tree Classifier

Libraries Used:
pandas for data manipulation,
scikit-learn for preprocessing, model building, and evaluation,
matplotlib for visualizing result

accuracy score 0.8849 

