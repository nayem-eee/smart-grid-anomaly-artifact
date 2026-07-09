# Smart Grid Cyber-Physical Anomaly Classification

## Distinguishing Cyber-Induced Anomalies and Physical Disturbances in Smart Grids Using Interpretable Machine Learning

## Introduction

This repository accompanies an anonymous manuscript submitted for peer review. The proposed study presents an explainable machine learning framework for distinguishing cyber-induced anomalies from physical grid disturbances using operational smart-grid measurements. Accurate differentiation between cyber events and physical disturbances is essential for enhancing situational awareness, operational reliability, and decision support in modern cyber-physical power systems.

Unlike conventional anomaly detection methods that primarily focus on identifying abnormal events, the proposed framework explicitly distinguishes three operational states: **Normal**, **Cyber**, and **Grid Disturbance**. The framework integrates supervised machine learning, statistical validation, and explainable artificial intelligence (XAI) to provide accurate and interpretable cyber-physical event classification.

---

## 🔍 Key Contributions

- **Three-Class Cyber-Physical Classification:** A unified framework for distinguishing **Normal**, **Cyber**, and **Grid Disturbance** events using operational electrical measurements.

- **Comprehensive Machine Learning Evaluation:** Comparative assessment of Logistic Regression, KNN, SVM-RBF, Decision Tree, Random Forest, and XGBoost using stratified 5-fold cross-validation.

- **Statistical Performance Validation:** Friedman statistical test is employed to verify whether the observed performance differences among classifiers are statistically significant.

- **Explainable Artificial Intelligence:** SHAP-based feature attribution and interpretable decision rules are utilized to provide transparent explanations for model predictions.

- **High Classification Performance:** The proposed framework demonstrates strong predictive performance while maintaining model interpretability for smart-grid monitoring applications.

---

## Proposed Workflow

*(Methodology Figure will be inserted here.)*

---

## Experimental Results

*(Representative performance table will be inserted here.)*

---

## SHAP Explainability

*(SHAP Beeswarm and/or Dependence Plot will be inserted here.)*

---

## Code Availability

To preserve the integrity of the double-blind review process, the complete implementation is not publicly released at the time of submission.

Upon acceptance, this repository will be updated with:

- Complete source code
- Data preprocessing scripts
- Model training and evaluation pipeline
- SHAP analysis
- Reproducibility instructions
- Documentation
