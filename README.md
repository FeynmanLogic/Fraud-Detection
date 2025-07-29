# Fraud Detection Project 🕵️‍♀️💳

This project focuses on detecting fraudulent transactions using supervised machine learning techniques. The goal is to identify anomalous transactions within a dataset and reduce false negatives in fraud prediction systems.

---

## 📂 Project Structure

- `Fraud_detection_project.ipynb` — Main notebook containing:
  - Data preprocessing  
  - Exploratory Data Analysis (EDA)  
  - Model training & evaluation  
  - Performance metrics and visualization  

---

## 🔍 Problem Statement

Financial institutions lose billions annually due to fraudulent activities. This project aims to build a reliable fraud detection model that accurately identifies malicious transactions from a given dataset while maintaining a balance between precision and recall.

---

## 🛠️ Technologies Used

- **Python** 🐍  
- **NumPy & Pandas** — Data manipulation  
- **Matplotlib & Seaborn** — Visualization  
- **Scikit-learn** — Machine Learning  
- **Imbalanced-learn** — Handling class imbalance (e.g., SMOTE)  

---

## 📊 Dataset

The dataset contains anonymized credit card transactions including both fraudulent and non-fraudulent transactions.

**Features include:**
- Numerical features: `V1`, `V2`, ..., `V28`  
- `Time`, `Amount`  
- `Class`:  
  - `0` = Non-fraud  
  - `1` = Fraud  

---

## ✅ Steps Covered

### 📌 Data Cleaning
- Checked for missing values  
- Handled outliers  
- Checked multi-collinearity (e.g., VIF)  

### 📌 Exploratory Data Analysis (EDA)
- Distribution of transaction types  
- Correlation heatmaps  
- Visual comparison between fraudulent and non-fraudulent transactions  

### 📌 Model Building
- Logistic Regression  
- Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - AUC  
