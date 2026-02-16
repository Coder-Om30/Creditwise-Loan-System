# 🏦 CreditWise Loan Approval Prediction

> A Machine Learning project that predicts whether a loan application will be **Approved or Rejected** based on applicant financial and demographic details.

---

## 🚀 Project Overview

Financial institutions receive thousands of loan applications daily. Manually evaluating them is slow, inconsistent, and prone to bias.

**CreditWise** is a data‑driven solution that automates loan approval decisions using Machine Learning models trained on applicant data such as income, credit score, employment status, savings, and debt ratio.

This project demonstrates a complete ML pipeline — from raw dataset → preprocessing → feature engineering → model training → evaluation.

---

## 🧠 Problem Statement

Predict:

> Will the bank approve the loan? (Yes / No)

This is a **Binary Classification Problem**.

---

## 📊 Dataset Features

Key attributes used in prediction:

* Applicant Income
* Co‑Applicant Income
* Credit Score
* Debt‑to‑Income Ratio (DTI)
* Savings
* Employment Status
* Marital Status
* Property Area
* Loan Purpose
* Education Level
* Employer Category
* Gender

Target Variable:

* **Loan_Approved (0 = No, 1 = Yes)**

---

## ⚙️ Machine Learning Pipeline

### 1️⃣ Data Preprocessing

* Missing value handling (Mean & Most Frequent Imputation)
* Removing unnecessary columns (Applicant_ID)
* Encoding categorical variables

  * Label Encoding
  * One‑Hot Encoding
* Feature scaling using **StandardScaler**

### 2️⃣ Exploratory Data Analysis (EDA)

* Class distribution visualization
* Income & Credit Score distribution
* Outlier detection using Boxplots
* Correlation Heatmap

### 3️⃣ Feature Engineering

* Added polynomial features:

  * DTI_Ratio²
  * Credit_Score²
* Improved model learning ability

### 4️⃣ Model Training

Models implemented:

* Logistic Regression
* K‑Nearest Neighbors (KNN)
* Gaussian Naive Bayes ⭐ (Best Precision)

### 5️⃣ Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 🏆 Best Performing Model

**Gaussian Naive Bayes** achieved the best precision after feature engineering, making it the most reliable for minimizing false approvals (important in banking risk assessment).

---

## 📁 Project Structure

```
CreditWise/
│── creditwise_loan_system.ipynb
│── loan_approval_data.csv
│── README.md
```

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit‑learn
* Jupyter Notebook

---

## 💡 Real‑World Applications

* Banking loan approval automation
* Credit risk assessment
* FinTech underwriting systems
* Microfinance decision systems

---

## 👨‍💻 Author

**Om Sahu**
Computer Science Engineering Student
Aspiring ML Engineer

---

## ⭐ If you like this project

Give it a star on GitHub and feel free to fork & improve!
