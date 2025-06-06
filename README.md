# Telecom Customer Churn Prediction 📉📞

This is a **Supervised Learning** classification problem where the target variable is whether a customer churns (`Yes` or `No`). The model learns patterns from labeled historical data to predict churn for new customers.

## 🔍 Project Overview
- Dataset: Telco Customer Churn (telecom_dataset.csv)
- Model: Random Forest (with SMOTE to balance classes)
- Features: Contract type, internet service, monthly charges, etc.
- Output: Churn prediction (Yes/No)

## 🛠 Features
- Label encoding of categorical variables
- SMOTE oversampling
- Train-test split
- Hyperparameter tuning using GridSearchCV
- Model evaluation: Accuracy, Confusion Matrix, Precision, Recall, F1-score
- Model and encoder saved as `.pkl` files
- Custom input prediction using saved model

## 🧪 Tools Used
- Python, Pandas, Scikit-learn and more in requirements.txt
- Jupyter Notebook
- Pickle

## ▶️ How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook

