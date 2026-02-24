ARTI308-Lab2
Heart Disease Dataset Analysis
Dataset

This dataset contains medical information of 302 patients with 14 features, including demographics (age, sex), clinical measurements (thalach, trestbps, chol, oldpeak), and symptom-related features (cp, etc.). The target variable is target (presence of heart disease), indicating whether a patient has heart disease or not.

After checking for duplicate rows, 723 duplicate records were removed to ensure accurate analysis, leaving a final cleaned dataset with 302 unique patient records. There are no missing values in any column, making the dataset complete and suitable for further analysis.

Machine Learning Problem

The task is a classification problem because the target variable is categorical (presence/absence of heart disease). The model aims to predict whether a patient has heart disease based on the features, which can assist in early diagnosis and risk assessment.

Key Points:

Type: Supervised Learning → Classification

Target Variable: target (presence of heart disease)

Features: 14 predictor variables including demographic, clinical, and symptom-based metrics

Key Observations:

thalach (maximum heart rate achieved) shows a strong correlation with the target variable

Features such as cp (chest pain type) and oldpeak also show noticeable relationships with heart disease

Data Distribution:

Most patients are in the 40–60 years age range

Cholesterol (chol) and resting blood pressure (trestbps) values are concentrated around moderate levels

Expected Output: Predictive model classifying patients as likely to have heart disease or not
