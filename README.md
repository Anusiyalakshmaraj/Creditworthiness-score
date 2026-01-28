# 🏦 Banking Customer Creditworthiness Score Prediction

## Project Overview

Banks must decide whether to approve or reject loan applications based on a customer’s ability to repay.  
Wrong decisions can lead to financial loss or missed business opportunities.

This project aims to predict the **creditworthiness of banking customers** using their financial and personal information, helping banks make faster and more accurate loan approval decisions.

The system analyzes customer behavior patterns and classifies whether a customer is likely to be a **good or risky borrower**.

---

## Objective

- Analyze customer financial and demographic data  
- Identify patterns linked to loan repayment behavior  
- Predict whether a customer is creditworthy  
- Support banks in reducing loan default risk  

---

## Tools and Technologies Used

### Programming Language
- **Python** – Used for data preprocessing, feature engineering, modeling, and evaluation.

### Data Handling and Processing
- **Pandas** – Loading datasets, cleaning missing values, feature creation, and data transformations.
- **NumPy** – Numerical computations, ratio calculations, and threshold-based evaluations.

### Data Preprocessing & Feature Engineering
- **Scikit-learn (sklearn)**  
  - `LabelEncoder` – Encoding categorical variables  
  - `StandardScaler` – Feature scaling  
  - `train_test_split` – Stratified train-test split  
  - `CalibratedClassifierCV` – Probability calibration  
  - Feature correlation analysis and imbalance handling  

### Machine Learning Models
- **Logistic Regression** – Baseline credit risk classification model.
- **Calibrated Logistic Regression** – Improved probability reliability for credit scoring.
- **LightGBM (Light Gradient Boosting Machine)** – High-performance gradient boosting model for credit default prediction.

### Model Evaluation & Metrics
- **Scikit-learn Metrics**
  - ROC-AUC
  - Precision, Recall, F1-score
  - Confusion Matrix
  - Precision-Recall Curve
- **Threshold Optimization** – Performance analysis across multiple probability cutoffs.

### Model Explainability
- **SHAP (SHapley Additive Explanations)**  
  - Global feature importance
  - Feature contribution analysis
  - Model interpretability for credit risk decisions

### Visualization
- **Matplotlib** – ROC curves, Precision-Recall curves, feature importance plots.

### Model Persistence & Deployment Support
- **Joblib** – Saving trained models, scalers, and calibrated classifiers.
- **OS** – Directory and file management for deliverables.

---

## Dataset Information

The dataset is stored separately on **Google Drive** due to file size and access convenience.

### 🔗 Dataset Location:
👉 https://drive.google.com/drive/folders/1sD7IgFihj10C-4nqUroCTrCUr12wxTrm?usp=sharing

### Dataset Contains:

- Customer demographic details  
- Employment and income information  
- Loan history and credit behavior  
- Financial indicators affecting repayment ability  

Each row represents one banking customer with multiple attributes used for risk assessment.

---

## Project Workflow

### 1. Data Loading
- Load dataset from Google Drive  
- Verify file structure and columns  

### 2. Data Cleaning
- Handle missing and invalid values  
- Convert categorical features to numerical form  
- Remove unnecessary columns  

### 3. Exploratory Data Analysis
- Analyze distribution of income, age, and loan amounts  
- Study relationships between features and credit risk  
- Identify important risk-related indicators  

### 4. Data Preprocessing
- Feature scaling  
- Encoding categorical variables  
- Splitting data into training and testing sets  

### 5. Model Building
- Apply machine learning classification models  
- Train models to predict creditworthiness  
- Compare model performance  

### 6. Model Evaluation
- Measure accuracy and prediction reliability  
- Analyze classification performance  

---

## Key Concepts Used

- Credit risk analysis  
- Supervised machine learning classification  
- Feature preprocessing and encoding  
- Model evaluation techniques  

---

## Outcome

The trained model can:

- Predict whether a customer is eligible for credit  
- Reduce chances of loan default  
- Support faster and more consistent loan decisions  

This improves operational efficiency and financial safety for banking institutions.

---

## Future Improvements

- Add more customer behavioral data  
- Apply advanced models like XGBoost or Neural Networks  
- Implement explainable AI to justify decisions  
- Deploy as a web-based loan approval system  

---
