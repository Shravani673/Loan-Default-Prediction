 Loan-Default-Prediction
# Loan Default Prediction 🏦

## 📌 Project Overview
This project predicts the probability of loan default using borrower financial and demographic data.

## 🎯 Objective
To build a classification model that helps financial institutions identify high-risk borrowers and reduce credit risk.

## 📂 Dataset
Loan dataset with features such as:
- Income
- Credit score
- Debt-to-income ratio
- Employment status
- Loan amount

 Approach
1. Exploratory Data Analysis (EDA)
2. Feature engineering (Loan-to-Income ratio)
3. Handling class imbalance using SMOTE
4. Model training (Logistic Regression, Random Forest, XGBoost)
5. Evaluation using Precision, Recall, F1-score, ROC-AUC

 Results
Logistic Regression was selected due to high recall and interpretability.

Key Insights
- Low credit score and high DTI increase default risk
- Employment stability significantly affects repayment behavior

 Tech Stack
Python, Pandas, Scikit-learn, Imbalanced-learn, Streamlit

How to Run
1. Install dependencies
2. Run notebook or Streamlit app

Impact
Supports risk-based lending and early detection of high-risk customers.
