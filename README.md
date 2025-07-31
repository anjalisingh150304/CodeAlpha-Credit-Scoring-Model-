# CodeAlpha-Credit-Scoring-Model-
# Credit Risk Prediction using Machine Learning

This project focuses on predicting credit risk (likelihood of loan default) using supervised machine learning models such as Logistic Regression, Decision Tree, and Random Forest. Additionally, it integrates model explainability using **LIME** (Local Interpretable Model-agnostic Explanations) to provide insights into individual predictions.

---

## 📌 Project Description

Credit risk assessment is crucial for financial institutions in determining the probability of a borrower defaulting on a loan. This repository presents a machine learning-based solution trained on the publicly available **Credit Risk Dataset**. The key components include:

- Data cleaning and preprocessing
- Feature encoding and scaling
- Training and evaluating ML models
- Model performance comparison (precision, recall, F1-score, ROC-AUC)
- Model interpretability using **LIME**

---

## 📁 Dataset

The dataset used is sourced from Kaggle:

**[Credit Risk Dataset (CSV)](https://www.kaggle.com/datasets/aniketmuthal/credit-risk-dataset-csv)**

- Features include: age, income, home ownership, employment length, loan amount, loan intent, credit history, etc.
- Target variable: `loan_status` (0 = no default, 1 = default)

---

## 🚀 Models Used

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**

Performance is evaluated using classification reports and ROC-AUC scores. Random Forest performed best in this scenario.

---

## 🔍 Explainability with LIME

To understand **why** a model made a specific prediction, LIME was used to generate local explanations for individual test instances. This helps improve transparency in model decisions—especially important in financial applications.

---

## 🧪 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
