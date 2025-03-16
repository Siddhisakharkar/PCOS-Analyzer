# Overview

This project aims to predict the likelihood of Polycystic Ovary Syndrome (PCOS) in patients using machine learning techniques. The dataset consists of medical and demographic features such as Age, BMI, Testosterone levels, and Antral Follicle Count. A Logistic Regression model is trained to classify patients as having PCOS (1) or not (0).

# Features

Data Cleaning & Preprocessing: Handling missing values and standardizing numerical features.

Exploratory Data Analysis (EDA): Visualizing distributions, correlations, and feature importance.

Machine Learning Model: Logistic Regression for classification.

Performance Evaluation: Accuracy, confusion matrix, and classification report.

# Dataset

The dataset includes the following features:

Age

BMI

Menstrual_Irregularity

Testosterone_Level

Antral_Follicle_Count

PCOS_Diagnosis (Target Variable)

# Requirements

Ensure you have the following libraries installed before running the Jupyter Notebook:

pip install pandas numpy matplotlib seaborn scikit-learn

Steps to Run

Load the dataset into a Pandas DataFrame.

Perform data cleaning and handle missing values.

Split data into training and testing sets.

Standardize numerical features.

Train a Logistic Regression model.

Evaluate model performance using accuracy and confusion matrix.

Visualize insights using Matplotlib and Seaborn.

Model Training & Evaluation

Train-Test Split: 80% training, 20% testing.

Standardization: Applied to numerical features.

Metrics Used: Accuracy, classification report, confusion matrix.

# Results

The model's performance is evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

# Visualization

Histogram of Age Distribution

Boxplot of BMI by PCOS Diagnosis

Correlation Heatmap

# Future Improvements

Experimenting with other ML models (Random Forest, SVM, etc.)

Hyperparameter tuning for better accuracy

Collecting more diverse data to improve generalization
