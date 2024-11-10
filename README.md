# Loan Status Prediction

## Project Overview

This project aims to predict the loan approval status for applicants based on features such as credit history, income, loan amount, and other financial data. Using various machine learning models, the project analyzes applicant information to determine the likelihood of loan approval, providing a tool to aid lenders in the decision-making process.

## Problem Statement

The objective of this project is to **predict loan status** (approved or not approved) based on applicant details, including:

- **Credit History**
- **Applicant and Coapplicant Income**
- **Loan Amount**
- **Loan Amount Term**
- **Property Area**
- **Marital Status**

By accurately predicting loan approval, financial institutions can streamline the loan application process and better assess risk.

## Business Implications

Loan status prediction is critical for banks and financial institutions to ensure they are making informed lending decisions. Predicting the likelihood of loan approval or rejection can reduce defaults and improve customer service by offering timely feedback to applicants.

## Data Analysis Techniques Used

### Univariate and Bivariate Analysis

- Univariate Analysis: Explores individual variables to understand their distribution and key characteristics.
- Bivariate Analysis: Examines relationships between pairs of variables to find correlations or patterns affecting loan approval.

### Data Preprocessing

- **Handling Missing Values**: Addressing any incomplete data to ensure model accuracy.
- **Encoding Categorical Variables**: Converting categorical data into numerical form for compatibility with machine learning models.

## Machine Learning Models Used

### Logistic Regression

- A classification algorithm that models the relationship between a binary dependent variable and independent variables.

### Decision Tree

- A tree-structured model that splits data based on feature values to classify loan status.

### Random Forest

- An ensemble model that uses multiple decision trees to improve prediction accuracy.

### Support Vector Machine (SVM)

- A classifier that finds the optimal boundary to separate classes based on input features.

## Model Evaluation Metrics

- **Accuracy**: Measures the proportion of correctly predicted loan statuses.
- **Precision and Recall**: Evaluate the model’s ability to identify approved and rejected loans accurately.
- **F1 Score**: Provides a balance between precision and recall, useful for imbalanced datasets.

## Cross Validation

- Used to ensure that the model generalizes well on unseen data by splitting the data into multiple folds for training and testing.

## Major Takeaways

- **Data Preprocessing and Handling**: Learned methods to clean and transform data.
- **Categorical Encoding**: Understood how to process non-numeric data for machine learning.
- **Model Selection and Evaluation**: Experienced with various models and metrics to find the best-performing approach.
- **Cross Validation**: Gained insight into improving model robustness by testing on different data subsets.
