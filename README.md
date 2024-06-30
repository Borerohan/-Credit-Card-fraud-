# -Credit-Card-fraud-

Credit Card Fraud Detection
Project Overview
Credit card fraud detection is essential for financial institutions to prevent unauthorized transactions and reduce financial losses. This project aims to build a classification model to predict fraudulent transactions using a dataset of credit card transactions made by European cardholders in September 2013.

Dataset
The dataset contains 284,807 transactions made by credit cards in September 2013 by European cardholders. It includes 492 frauds, making the dataset highly imbalanced, with frauds accounting for only 0.172% of all transactions.

Project Workflow
Exploratory Data Analysis (EDA)
Analyzed and understood the data using descriptive statistics and visualizations.
Data Cleaning
Standardized the 'Amount' feature and converted the 'Time' feature to a more readable format.
Dealing with Imbalanced Data
Applied SMOTE to balance the dataset by generating synthetic samples for the minority class (fraud).
Feature Engineering and Feature Selection
Created new features and selected the most relevant ones using correlation analysis and feature importance metrics.
Train/Test Split
Applied stratified sampling to ensure the train and test sets have a similar distribution of fraud and non-fraud transactions.
Model Selection and Training
Trained several models including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
Model Validation
Evaluated model performance using accuracy, precision, recall, F1-Score, and ROC-AUC.
Hyperparameter Tuning
Used Grid Search and Random Search to find the optimal hyperparameters for the best-performing model.
Model Deployment
Prepared the model for deployment using a REST API framework.
Conclusion
The selected model performed well with an accuracy exceeding 75%, demonstrating robustness against imbalanced data. Future improvements could include integrating more diverse datasets, enhancing feature engineering, and employing advanced techniques like ensemble learning.
