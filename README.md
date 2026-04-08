![ML](https://img.shields.io/badge/Machine%20Learning-5%20Models-blue)
![XAI](https://img.shields.io/badge/Explainable%20AI-SHAP%20%7C%20LIME-orange)

# XAI Framework for Crime Rate Prediction in India

## 📌 Overview

This project focuses on predicting crime patterns using machine learning models and improving interpretability using Explainable Artificial Intelligence (XAI) techniques. The aim is not only to achieve accurate predictions but also to understand **why** those predictions are made.

---

## 🎯 Objectives

* Predict crime outcomes using machine learning models
* Compare performance of multiple models
* Apply SHAP and LIME for model explainability
* Perform feature selection using XAI techniques
* Analyze how explainability affects model performance

---

## 📊 Datasets Used

1. **Dataset 1 – Crimes Against Women**

   * Structured dataset with features like rape, kidnapping, domestic violence, etc.

2. **Dataset 2 – Crime Dataset India**

   * Real-world dataset with case-level details (city, crime type, victim info, etc.)

---

## ⚙️ Machine Learning Models

### 🔹 Baseline Models

* K-Nearest Neighbors (KNN)
* Logistic Regression
* Random Forest

### 🔹 Main Models for Analysis

* Gaussian Naive Bayes (GNB)
* Multi-Layer Perceptron (MLP)

---

## 🧠 Explainability Techniques

* **SHAP (SHapley Additive Explanations)**

  * Provides global feature importance
  * Used for feature selection

* **LIME (Local Interpretable Model-Agnostic Explanations)**

  * Explains individual predictions
  * Used for local interpretability

---

## 🔄 Workflow

1. Data preprocessing and feature engineering
2. Train baseline models (KNN, Logistic Regression, Random Forest)
3. Train main models (GNB, MLP)
4. Evaluate performance (Accuracy, Precision, Recall, F1-score)
5. Apply SHAP and LIME
6. Select top features
7. Retrain models using selected features
8. Compare results before and after XAI

---

## 📈 Results Summary

* Dataset 1 achieved high accuracy due to structured data
* Dataset 2 showed lower accuracy due to complexity and noise
* MLP consistently performed better than simpler models
* SHAP improved performance, especially for MLP
* LIME provided local explanations but showed less stability

---

## 📊 Visualizations

* SHAP summary plots
* Feature importance bar plots
* Model comparison graphs
* SHAP force plots

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* SHAP
* LIME
* Pandas, NumPy, Matplotlib

---

## 📌 Key Insights

* Data quality has a major impact on model performance
* Complex models (MLP) benefit more from feature selection
* SHAP is more effective for global interpretability
* LIME is useful for explaining individual predictions

---

## 🚀 Future Scope

* Use advanced models like XGBoost and deep learning
* Build real-time crime prediction systems
* Apply geospatial analysis for crime hotspot detection
* Combine SHAP and LIME for hybrid explainability

---

## 👥 Authors

* Anoushka Deb
* Shalini Shree
* Triyanjana Paul
* Srija Adhya

---

## ⭐ Acknowledgment

This project was developed as part of an academic research initiative on Explainable AI and crime prediction.

---
