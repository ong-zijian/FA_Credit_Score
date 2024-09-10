# Credit Scoring Project

## Overview
This project focuses on building a credit scoring model to predict the likelihood of a customer defaulting on a loan. The project workflow includes Exploratory Data Analysis (EDA), Feature Engineering, and the implementation of a Logistic Regression model to evaluate credit risk.

## Project Structure
- EDA (Exploratory Data Analysis): Identifying key trends, patterns, and potential data issues by analyzing the distribution of features and their relationships.
- Feature Engineering: Creating new features from the raw data and transforming existing ones to improve model performance.
- Modeling: Logistic Regression was used to predict credit scores and assess credit risk.

## Dataset
The dataset contains customer information such as:
- Demographic details (age, gender, marital status)
- Bureau data (information collected from a bereau agency)

## Process
1. Exploratory Data Analysis (EDA)
In this step, I analyzed the dataset to identify key trends and patterns. Key analyses included:
- Checking for missing values and handling outliers.
- Visualizing distributions of numerical features like income, credit balance, etc.
- Understanding relationships between the target variable (default or not) and other features.

2. Feature Engineering
I enhanced the dataset by creating new features and transforming existing ones, such as:
- Creating ratios like Debt-to-Income and Credit Utilization Rate.
- Encoding categorical variables.

3. Modeling: Logistic Regression
I implemented a Logistic Regression model as it’s suitable for binary classification problems like credit scoring. Key steps included:
- Splitting the data into training and testing sets.
- Fitting the model to the training data.
- Evaluating performance using accuracy, precision, recall, and AUC-ROC curve.