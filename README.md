# DSheartfailure
The task is to classify the survival of patients with heart failure disease.

1. Project Overview
Title: Predicting Heart Failure with Machine Learning
Objective: Develop a machine learning model to predict heart failure based on patient data, helping identify at-risk individuals and improving early intervention.

2. Problem Statement
Predicting heart failure can improve patient outcomes by identifying risk factors and providing timely medical interventions. Using a dataset of 299 patients with 12 features, the project aims to build predictive models for classifying whether a patient will experience heart failure.

3. Dataset
Dataset Name: Heart Failure Dataset (299 rows, 12 features)
Features:

Numerical: age, creatinine_phosphokinase, ejection_fraction, platelets, serum_creatinine, serum_sodium, time
Binary: anaemia, diabetes, high_blood_pressure, sex, smoking
Target: DEATH_EVENT (indicates if a patient experienced heart failure)

4. Technologies Used
Languages: Python
Libraries: Scikit-Learn, Pandas, Matplotlib, Seaborn, NumPy
Algorithms: k-Nearest Neighbors (k-NN), Decision Trees, Naïve Bayes, K-Fold Cross-Validation
Tools: Jupyter Notebook for development, GitHub for version control

5. Solution Approach
Data Preprocessing: Handled missing values, normalized continuous features, and performed one-hot encoding for categorical variables.
Modeling: Implemented k-Nearest Neighbors, Decision Trees, and Naïve Bayes classifiers. Applied K-Fold Cross-Validation to evaluate model performance.
Performance Metrics: Used accuracy, precision, recall, and F1-score to evaluate models.

6. Results
The k-NN model achieved an accuracy of 82%, while Decision Trees performed slightly better with 84%.
The Naïve Bayes classifier, though less accurate at 78%, provided valuable insights into conditional probabilities of risk factors.
Visualizations: Include confusion matrices, ROC curves, and feature importance charts to support findings.
