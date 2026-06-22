# 🧬 Cancer Classifier using GDA

This project implements **Gaussian Discriminant Analysis (GDA)** to classify breast cancer tumors as **Malignant (M)** or **Benign (B)**.  
It uses **Pandas** for data handling, **NumPy** for numerical computation, and **Matplotlib** for visualization.  
The dataset is sourced from **Kaggle: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)**

---

## 📌 Project Overview
- **Goal:** Predict whether a tumor is malignant or benign.
- **Dataset:** Breast Cancer dataset (`data.csv`) from UCI repository.
- **Approach:** 
  - Compute class means and covariance matrix.
  - Derive discriminant function parameters.
  - Classify new samples using GDA.
- **Output:** Prediction results and feature mean comparison plots.

---

## ⚙️ Requirements
- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - matplotlib
