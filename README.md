# Credit-Card-Fraud-Detection
## Overview
This project is a machine learning pipeline designed to detect fraudulent credit card transactions. Because real-world fraud data is highly unbalanced, this project emphasizes handling class imbalance by building a sample dataset with an equal distribution of legitimate and fraudulent transactions to ensure accurate model training.
## Features
1. Data Preprocessing: Identifies and separates legitimate and fraudulent transactions for targeted analysis.
2. Under-Sampling: Mitigates extreme dataset imbalance by taking a random sample of the majority class to match the exact count of the minority class.
3. Feature Scaling: Standardizes the dataset features using Scikit-Learn's StandardScaler to optimize model performance.
4. Automated Evaluation: Utilizes a loop to efficiently train and evaluate multiple machine learning models consecutively.
## Technologies Used
Programming Language: Python
Data Manipulation & Analysis: Pandas, NumPy
Machine Learning Libraries: Scikit-Learn, XGBoost
## Exploratory Data Analysis(EDA)
1. Extracts foundational dataset information and checks for any missing (null) values across all columns.
2. Evaluates the distribution of class labels to confirm the highly unbalanced nature of the raw data.
3. Generates statistical measures (mean, standard deviation, percentiles) for the transaction amounts.
4. Groups the data by transaction class to compare the mean values of features between legitimate and fraudulent transactions.
## Machine Learning Models Used
1. Logistic Regression
2. Random Forest Classifier
3. XGBoost Classifier
## Evaluation Metrics
1. Accuracy Score
2. Precision Score
3. Recall Score
4. F1-Score
5. ROC-AUC Score 
