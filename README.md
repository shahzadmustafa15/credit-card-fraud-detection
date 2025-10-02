# 💳 Credit Card Fraud Detection

This project uses machine learning to detect fraudulent credit card transactions with a Random Forest classifier and Stratified K-Fold Cross-Validation.

---

## 🚀 Project Overview

- Implements a **Random Forest** model with `class_weight='balanced'` to handle class imbalance.
- Uses **Stratified 5-Fold Cross-Validation** to ensure fair evaluation across imbalanced classes.
- Evaluates model performance primarily with **F1-score**, suitable for imbalanced classification.
- Provides detailed **classification reports** and **confusion matrix** visualization.
- Plots F1-scores across folds to visualize model stability.

---

## 📊 Dataset

- Source: [Credit Card Fraud Detection dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains 284,807 transactions, of which only 492 are fraudulent (highly imbalanced).
- Dataset features are anonymized to protect privacy.

> ⚠️ **Important:** The dataset file `creditcard.csv` is **not included** here due to file size restrictions.  
> Please download it from Kaggle and place it in the root directory of this project.

---

## 📦 Requirements

Make sure you have Python installed. Then install the required libraries with:

```bash
pip install -r requirements.txt
