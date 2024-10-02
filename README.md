# DSheartfailure

1. Project Overview

- Title: Predicting Heart Failure with Machine Learning
- Objective: Develop a machine learning model to predict heart failure based on patient data, helping identify at-risk individuals and improving early intervention.

3. Problem Statement
   
- Predicting heart failure can improve patient outcomes by identifying risk factors and providing timely medical interventions. Using a dataset of 299 patients with 12 features, the project aims to build predictive models for classifying whether a patient will experience heart failure.

5. Dataset

- Dataset Name: Heart Failure Dataset (299 rows, 12 features)

Features:

- Numerical: age, creatinine_phosphokinase, ejection_fraction, platelets, serum_creatinine, serum_sodium, time
- Binary: anaemia, diabetes, high_blood_pressure, sex, smoking
- Target: DEATH_EVENT (indicates if a patient experienced heart failure)

4. Technologies Used

- Languages: Python
- Libraries: Scikit-Learn, Pandas, Matplotlib, Seaborn, NumPy
- Algorithms: Logistic Regression, k-Nearest Neighbors (k-NN) and Naïve Bayes
- Tools: Jupyter Notebook for development, GitHub for version control

5. Solution Approach

- Data Preprocessing: Handled missing values, normalized continuous features, and performed one-hot encoding for categorical variables.
- Modeling: Implemented Logistic Regression, k-Nearest Neighbors (k-NN) and Naïve Bayes. 
- Performance Metrics: Used accuracy, precision, recall, and F1-score to evaluate models.

6. Results

- Logistic Regression is the best model for our dataset with the ability to predict new, unseen data with 83.3% accuracy. However since the dataset has 67% more Class 0 (survived patients) over Class 1 (death patients), the model seems to be lacking in predicting Class 1 accurately, with all three models have precision, recall and f1-scores below 70%. Additional steps such as over-sampling and under-sampling could be done in the future to improve the performance of the imbalance data.
