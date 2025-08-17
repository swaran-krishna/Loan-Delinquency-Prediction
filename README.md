# Loan Delinquency Prediction

## 📌 Project Overview
This project predicts the likelihood of loan delinquency (default) using customer financial and demographic data.  
It applies machine learning models (Logistic Regression, Random Forest, XGBoost) to identify high-risk borrowers.

## 📊 Dataset
- Source: Delinquency_prediction_dataset.csv  
- Features:
  - Income  
  - Credit Score  
  - Age  
  - Debt-to-Income Ratio  
  - Loan Balance  
- Target: Delinquency (0 = No Default, 1 = Default)

## ⚙️ Workflow
1. Data Preprocessing (handling missing values, outliers, scaling)
2. Exploratory Data Analysis (EDA)
3. Model Building (Logistic Regression, Random Forest, XGBoost)
4. Model Evaluation (Accuracy, Precision, Recall, F1, ROC AUC)

## 🚀 Results
- Best Model: **XGBoost**
- Achieved high recall and ROC AUC for identifying high-risk applicants.

## 📈 Business Impact
This model helps financial institutions minimize lending risks by identifying potential defaulters early.

## 🔧 Tech Stack
- Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

## 📂 Repository Structure
