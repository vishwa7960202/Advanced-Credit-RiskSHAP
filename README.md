# Interpretable Machine Learning: SHAP Analysis of Credit Risk Prediction

This project builds, evaluates, and interprets a credit default prediction model using advanced machine learning techniques and SHAP (SHapley Additive exPlanations). The primary objective is to demonstrate how interpretable ML can be applied in highly regulated domains such as financial risk modeling.

---

## 📊 Project Overview

This project simulates a real-world credit scoring pipeline, including:

- Synthetic dataset generation (20,000 credit applications)
- Data preprocessing with imputation and one-hot encoding
- Handling class imbalance using SMOTE
- Training a LightGBM classifier
- Model evaluation using ROC AUC
- Global interpretability using SHAP:
  - Beeswarm summary plot
  - SHAP bar plot
  - Interaction effects for top 3 features
- Local interpretability using SHAP force plots for 5 sample loans

The key focus is **model explainability**, a requirement in regulated industries such as lending and credit underwriting.

---

## 📁 Repository Contents

