
# 🏦 Loan Eligibility Predictor

## 📌 Project Overview

The **Loan Eligibility Predictor** is a machine learning-based classification tool designed to help banks and fintech platforms determine whether a loan applicant is likely to be approved or rejected based on various personal and financial details.

---

## 🎯 Objective

Build a user-friendly, accurate classifier using logistic regression and random forest to predict loan approval based on features such as:

- Age
- Income
- Education
- Credit Score
- Marital Status

---

## 🛠️ Features

- ✅ Uses both **Logistic Regression** and **Random Forest** classifiers
- 📊 Evaluates models using:
  - Confusion Matrix
  - Classification Report
  - ROC Curve with AUC score
- 📦 Preprocessing:
  - Label encoding for categorical features
  - Handling missing values with imputation
  - Feature scaling with `StandardScaler`
- 🧪 Train/test split with reproducible random state

---

## 📂 Dataset

- The project uses a **synthetic dataset** for demonstration (can be replaced with real loan data).
- Replace with your own dataset using `pd.read_csv("your_file.csv")`.

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**.
2. Run all cells in order.
3. The models will be trained and evaluated.
4. The ROC Curve will be plotted to compare classifier performance.

---

## 💡 Sample Output

- Confusion matrix and classification report for each model.
- ROC Curve comparing performance with AUC scores.

---

## 📜 License

This project is licensed under the MIT License.

---
