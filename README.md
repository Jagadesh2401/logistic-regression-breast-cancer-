# Logistic Regression - Breast Cancer Classification

This project implements a binary classification model using **Logistic Regression** on the **Breast Cancer Wisconsin Dataset**.

## 📌 Objective

Build a binary classifier to predict whether a tumor is malignant or benign using logistic regression, and evaluate its performance using various metrics.

---

## 📁 Dataset

- **Source:** [Breast Cancer Wisconsin Dataset (UCI/Kaggle)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Features:** Radius, texture, perimeter, area, smoothness, etc.
- **Label:** `diagnosis` (`M` for malignant, `B` for benign)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

---

## 🔍 Key Steps

1. Load and preprocess the dataset
2. Train/test split and feature scaling
3. Train logistic regression model
4. Predict and evaluate using:
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC Curve
5. Threshold tuning for classification
6. Visualize Sigmoid function

---

## 📊 Outputs

- Confusion Matrix Heatmap
- ROC Curve Plot
- Sigmoid Function Plot
- Classification Report

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/logistic-regression-breast-cancer.git
   cd logistic-regression-breast-cancer
