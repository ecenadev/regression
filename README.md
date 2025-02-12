Linear and Logistic Regression

Overview

This repository contains implementations of three fundamental machine learning models:

Simple Linear Regression: Predicts continuous outcomes based on a single independent variable.

Multiple Linear Regression: Handles multiple predictor variables for improved predictive performance.

Logistic Regression: A classification algorithm used to predict binary outcomes.

Each model is implemented using Python and the scikit-learn library.

Dataset Requirements

The models require specific datasets for training and evaluation:

Simple Linear Regression: Salary_Data.csv (Salary vs. Years of Experience)

Multiple Linear Regression: 50_Startups.csv (Business profit prediction based on multiple factors)

Logistic Regression: Social_Network_Ads.csv (Predicting user purchase behavior)

Ensure that the datasets are present in the working directory before executing the scripts.

Installation

Prerequisites

Ensure that Python and the following libraries are installed:

pip install numpy pandas matplotlib scikit-learn

Usage

1. Simple Linear Regression

python simple_linear_regression.py

This script:

Loads Salary_Data.csv

Splits the dataset into training and testing sets

Trains a simple linear regression model

Visualizes predictions for both training and testing sets

2. Multiple Linear Regression

python multiple_linear_regression.py

This script:

Loads 50_Startups.csv

Encodes categorical variables

Splits data for training and testing

Trains a multiple linear regression model

Predicts test set results and compares them with actual values

3. Logistic Regression

python logistic_regression.py

This script:

Loads Social_Network_Ads.csv

Splits the dataset into training and testing sets

Applies feature scaling

Trains a logistic regression model

Evaluates performance using a confusion matrix and accuracy score

Visualizes results with decision boundary plots

Results & Visualization

Each script generates plots to illustrate:

Regression lines for Simple and Multiple Linear Regression

Decision boundaries for Logistic Regression
