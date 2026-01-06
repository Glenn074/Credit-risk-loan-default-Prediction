# Credit Risk & Loan Default Prediction

## 📌 Project Overview
This project focuses on predicting loan default risk using machine learning techniques.  
The goal is to assist financial institutions in identifying high-risk applicants and minimizing financial losses.

---

## 🧠 Problem Statement
Loan default prediction is a critical task in the finance and fintech industry.  
Incorrectly approving high-risk applicants can lead to significant losses, making risk-aware evaluation essential.

---

## 📊 Dataset
- Source: Public credit risk dataset
- Target Variable: `loan_status`
  - `0` → No Default
  - `1` → Default

---

## ⚙️ Approach
- Data Cleaning and Preprocessing
- Handling Class Imbalance
- Train-Test Split with Stratification
- Model Training:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Risk-Focused Evaluation using Recall and ROC-AUC
- Threshold-Based Decision Making

---

## 📈 Results
- **XGBoost ROC-AUC:** ~0.95  
- **Recall (Defaulters):** ~0.80  

These results demonstrate strong model performance in identifying high-risk borrowers.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib

---

## 🚀 Future Improvements
- Advanced encoding techniques (WoE, target encoding)
- Cost-sensitive learning
- Model explainability using SHAP

---

## 👤 Author
**Glenn Joseph**  
BTech – Information Technology & Data Science  
