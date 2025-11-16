# Credit Card Fraud Detection — Automated Hyperparameter Tuning with Optuna & XGBoost

This repository contains my end-to-end machine learning project for detecting credit card fraud using:
- XGBoost
- Optuna for automated hyperparameter tuning
- AUPRC optimization
- Threshold tuning
- Proper evaluation for highly imbalanced data

You can modify any part of this README to match updates to your project.

## Project Structure

credit-card-fraud-detection/
│── notebooks/
│ └── Credit_CardFraud.ipynb
│── data/
│ └── .gitkeep
│── models/
│ └── .gitkeep
│── LICENSE
│── README.md
│── .gitignore

Feel free to rename folders or reorganize as needed.

---

## 📊 Project Overview

This project aims to build a robust machine learning model to identify fraudulent transactions in a highly imbalanced dataset.  

Key points:
- Fraud accounts for **less than 0.2%** of total transactions.
- Standard accuracy is misleading for this dataset.
- Better evaluation metrics include: **AUPRC, Recall, Precision, ROC-AUC**.

You can expand this section later with more details.

---

## Dataset

Dataset used: **Credit Card Fraud Detection (Kaggle)**  
Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Note: The dataset is not included in this repo due to size and licensing.

---

## Methods Used

You can modify or update this list anytime.

- Data preprocessing and scaling
- XGBoost model training
- Optuna hyperparameter tuning (AUPRC objective)
- Stratified cross-validation
- Threshold tuning to balance recall and precision
- Final evaluation on test set

---

## Final Model Performance (Test Set)

Replace these numbers with your own if you rerun the model:

- **Threshold:** 0.5  
- **Recall:** 0.8649  
- **Precision:** 0.0936  
- **F1-score:** 0.1689  
- **ROC-AUC:** 0.9619  

Confusion Matrix:

[[42028 620]
[ 10 64]]


---

## How to Run the Project

### 1. Clone the repository
git clone https://github.com/<your-username>/credit-card-fraud-detection.git
cd credit-card-fraud-detection


### 2. Install dependencies
pip install -r requirements.txt


### 3. Add the dataset
Download `creditcard.csv` from Kaggle and place it into:
data/creditcard.csv

## 💬 Contact

Add your own details here:

- **Author:** Farhan Ali Khan  
- **GitHub:** https://github.com/Farhan0604 
- **Email:** iamkhan0604@gmail.com  
