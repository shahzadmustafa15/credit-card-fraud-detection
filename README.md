# 💳 Credit Card Fraud Detection (Stratified K-Fold + Random Forest)

This project detects fraudulent credit card transactions using a Random Forest classifier with **Stratified K-Fold Cross-Validation**. It uses the popular [Kaggle credit card fraud dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which is highly imbalanced.

## 🚀 Features

- Random Forest with `class_weight='balanced'`
- Stratified 5-Fold Cross-Validation
- F1-score as the primary metric
- Classification report and confusion matrix
- F1-score visualization across folds

## 📈 Results

**Average F1-score across 5 folds**: ~0.85  
The model performs well despite the severe class imbalance.

## 🧠 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- 284,807 transactions
- 492 fraudulent (Class = 1), 284,315 legitimate (Class = 0)

> ⚠️ Place the `creditcard.csv` file in the root of this project.

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
