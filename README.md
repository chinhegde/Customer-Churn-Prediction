# Customer-Churn-Prediction using Machine Learning
This repository contains code and documentation for predicting customer churn using machine learning. Two datasets were utilized in this project: the IBM Customer Churn Dataset, focusing on customer-centric features, and the Telecom Churn Dataset (Asia).

Read more about the project and the motivation: (Blog post)[https://chinmayih.wordpress.com/2023/12/30/unraveling-customer-churn-with-ml/]
### Execution Environment
The project was executed entirely in Google Colab.

## Data Preprocessing
The data preprocessing phase involved cleaning and transforming the datasets for analysis.

### Cleaning
- Removal of duplicates
- Dimensionality reduction by eliminating columns with more than 95% identical data
- Data imputation using KNN imputation and filling missing values with 0
- Transformation
- Normalization
- Label encoding
- One-hot encoding
- Introduction of new columns (average, total)

### Class Imbalance
- Handling class imbalance through undersampling and oversampling techniques

## Feature Selection
Various techniques were employed for feature selection, including:

1. Scikit Learn's SelectKBest with chi2 and ANOVA - f_classif
2. Scikit Learn's SelectFPR
3. Principal Component Analysis (PCA)

## Machine Learning Classification
The project implemented three classification algorithms:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Naive Bayes
- Evaluation
The evaluation of the models was conducted using standard machine learning metrics.
