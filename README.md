# Alzheimer Prediction Using ML Classification

This project aims to perform classification on a dataset to predict Alzheimer’s diagnosis based on various health and lifestyle factors. The dataset, sourced from Kaggle, includes features such as age, gender, education level, BMI, physical activity, smoking status, and others.

## Key Steps (Logistic Regression Classifier):
- Data Preprocessing: Categorical data was encoded for machine learning models.
- Modeling: Logistic Regression was used for classification.
- Evaluation: Model performance was assessed using accuracy, confusion matrix, and classification report. Achieved an accuracy of 0.7.

## Updates (Random Forest Classifier): 
- Added May, 2025
- Data Preprocessing: Ordinal features was labelled 0, 1, 2,.., binary features as 0, 1. Perform SVD, select smallest number of k components that retain more than 90% variance to select top 10 features. 
- Modeling: Random Forest.

## Tools & Technologies:
- Python Libraries: pandas, scikit-learn, matplotlib, seaborn.
- Model: Logistic Regression, Random Forest

