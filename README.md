# 🧠 Stroke Risk Prediction and Prevention in Hypertensive Patients

This project uses **machine learning** to predict stroke risk among hypertensive patients aged 50–85, aiming to provide clinicians and patients with a robust, data-driven decision support tool for improved prevention and personalized care.

---

## 🩺 Problem Statement

Stroke is a leading cause of morbidity worldwide, especially in individuals with hypertension—a key modifiable risk factor.

**This project seeks to:**
- Build predictive models to assess stroke risk in hypertensive individuals.
- Identify the main clinical and behavioral features contributing to increased stroke risk.
- Deliver interpretable predictions to inform both patients and healthcare providers.

---

## 🧠 Models Implemented

- **Random Forest:** Ensemble method offering strong classification performance and interpretability.
- **XGBoost:** Gradient boosting for optimal accuracy and handling class imbalance.
- **MLP, KNN, Logistic Regression, AdaBoost, SVM, GaussianNB:** Baseline and comparative models.
- **Feature Selection:** SelectKBest (ANOVA) to highlight the most relevant predictors.
- **Class Imbalance Handling:** Synthetic Minority Over-sampling Technique (SMOTE) for balanced learning.

---

## 🗄️ Datasets

- **Primary Dataset:** [Kaggle Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
    - 5,110 patient records, 11 features (age, hypertension, heart disease, BMI, glucose, smoking, etc.)
    - Focused analysis on hypertensive group (stroke prevalence: 13.2%)

---

## 🔁 Workflow Overview

1. Data cleaning and preprocessing (encoding, imputation, scaling)
2. Addressing class imbalance using SMOTE
3. Feature selection to improve model focus and interpretability
4. Training and testing multiple machine learning models
5. Evaluating models on accuracy, F1-score, precision, recall, and AUC
6. Interpreting top risk factors and generating actionable insights

---

## 📊 Results Summary

- **Top Predictors:** Age, hypertension, heart disease, glucose level, BMI, and smoking status.
- **Best Model:** Random Forest — Accuracy: 0.88, F1-score: 0.89
- **Interpretability:** XGBoost and Random Forest models allow insight into individual patient risk factors.
- **Clinical insight:** Effective for prioritizing intervention among high-risk hypertensive patients.

---

## 🛠️ Tools Used

- **Python:** Data analysis and modeling
- **Pandas, NumPy:** Data manipulation
- **Scikit-learn:** Model building and evaluation
- **Imbalanced-learn:** Class balancing (SMOTE)
- **XGBoost:** Advanced boosting
- **Matplotlib, Seaborn:** Visualization

---

## 🚀 Future Enhancements

- Integrate explainable AI methods for clearer risk interpretation.
- Apply models to more granular, longitudinal patient data.
- Clinical testing and integration with EMR systems.

---

## 🙌 Contributors

- Rashmitha Eri
- Oscar Odera

