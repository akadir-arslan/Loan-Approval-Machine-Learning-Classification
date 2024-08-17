# Loan-Approval-Machine-Learning-Classification

## Project Overview

This project focuses on classifying users on a platform (LendingClub.com) that enables users to lend or borrow money, with the goal of identifying potential high-risk borrowers who may default on loans. The analysis includes data preprocessing, exploratory data analysis (EDA), and evaluation of various machine learning models to determine their effectiveness in predicting loan defaults.

## Key Components

1. **Data Preparation**: 
   - Data is sourced from LendingClub and involves cleaning and preprocessing to make it suitable for analysis.
   
2. **Model Evaluation**:
   - **Baseline Model**: Dummy Classifier to establish a performance baseline.
   - **Machine Learning Models**: Random Forest and XGBoost Classifiers to assess and compare their performance in user classification.

3. **Hyperparameter Tuning**:
   - Utilization of GridSearchCV and nested cross-validation to find the optimal hyperparameters for each model.

4. **Model Comparison**:
   - Comparative analysis of model performance to identify the best-performing classifier.

5. **Feature Importance**:
   - Analysis of which features contribute most to the model's predictions.

## Data Source

The dataset for this project can be obtained from [www.kaggle.com](https://www.kaggle.com/datasets/saramah/loan-data/code). Please download and prepare the data as outlined in the notebook.

## Project Structure

- Data Analysis: Cleaning and preprocessing of the dataset.
- Model Evaluation: Implementation and comparison of different classifiers.
- Hyperparameter Tuning: Optimization of model parameters.
- Feature Importance: Identification of key features influencing the model.

## Goals

- To develop a robust classification model for predicting high-risk borrowers.
- To provide insights into feature importance and model performance.

## How to Run

1. Download the dataset from the provided source.
2. Install the required libraries
3. Run the Jupyter Notebook to execute the analysis and model evaluation steps.