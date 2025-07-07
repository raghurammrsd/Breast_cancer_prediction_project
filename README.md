# Breast_cancer_prediction_project
# 🧠 Breast Cancer Prediction using Machine Learning

This project predicts whether a breast tumor is **malignant (cancerous)** or **benign (non-cancerous)** using machine learning techniques on the Breast Cancer Wisconsin dataset.

---

## 📌 Project Overview

- 🏥 Uses real medical diagnostic data from the **Breast Cancer Wisconsin (Diagnostic)** dataset
- 🔬 Predicts the likelihood of **breast cancer** based on 30 numerical features (e.g., radius, texture, smoothness)
- 📈 Models trained: **Logistic Regression**, **Random Forest Classifier**
- ✅ Achieved up to **97% accuracy**
- 🚀 Allows prediction on new patient data (manual or CSV input)



## 📊 Dataset Used

- 📁 Dataset: Breast Cancer Wisconsin (Diagnostic)
- 📌 Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- 📦 Also available directly in `scikit-learn`:
```python
from sklearn.datasets import load_breast_cancer
