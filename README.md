# 🧠 Student Mental Health Risk Prediction

A machine learning project designed to analyze student-related risk factors and classify mental health risk into **Low, Medium, and High Risk** categories.

The project demonstrates an end-to-end machine learning workflow including data preprocessing, feature transformation, classification, model evaluation, and risk prediction.

> ⚠️ This project is for educational and research purposes only. It is not a medical diagnostic or clinical decision-making system.

---

## 🎯 Project Objective

The objective of this project is to build a machine learning-based system that can analyze student-related data and predict an associated mental health risk level.

The project focuses on:

- Data preprocessing
- Missing-value handling
- Numerical feature scaling
- Categorical feature encoding
- Risk-level classification
- Model evaluation
- Probability-based predictions
- Model comparison

---

## 🧠 Risk Classification

The system classifies observations into three risk categories:

| Class | Risk Level |
|---|---|
| 0 | Low Risk |
| 1 | Medium Risk |
| 2 | High Risk |

The risk labels are generated from the target variable using quantile-based thresholds.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Joblib
- Google Colab

---

## 🔄 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Missing Value Handling
     ↓
Feature Selection
     ↓
Risk-Level Generation
     ↓
Train-Test Split
     ↓
Numerical Scaling
     +
Categorical Encoding
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
     ↓
Risk Classification
