# Kidney-Disease-Detection-using-ML-with-XAI
# 🩺 Kidney Disease Detection using Machine Learning and Explainable AI (XAI)

## 📘 Project Overview

Chronic Kidney Disease (CKD) is a serious public health issue affecting millions worldwide. Early and accurate prediction of CKD can improve patient outcomes and reduce healthcare costs. This project focuses on building robust machine learning models to classify CKD cases using clinical data, with a strong emphasis on model interpretability through Explainable AI (XAI) techniques such as SHAP and LIME.

---

## 🎯 Objectives

- ✅ Predict CKD using various supervised ML algorithms.
- ✅ Compare model performance based on key evaluation metrics.
- ✅ Apply XAI methods to make model predictions interpretable.
- ✅ Provide insights to aid healthcare professionals in decision-making.

---

## 🗃️ Dataset

- **Source**: [UCI Machine Learning Repository - CKD Dataset](https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease)
- **Records**: 1200 patients
- **Features**: 26 clinical attributes
- **Target Variable**: CKD status (`ckd` or `notckd`)

---

## 🧠 Models Implemented

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Ensemble Methods (Voting Classifier)

---

## 📊 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 🧪 Explainable AI (XAI) Techniques

| Technique | Purpose |
|----------|---------|
| **SHAP** | Explains individual predictions using Shapley values, offering global and local model insights. |
| **LIME** | Builds local surrogate models to explain individual predictions in a human-interpretable way. |

---

## 📌 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
