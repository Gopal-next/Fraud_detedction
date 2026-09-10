# Fraud Detection Using XGBoost

Machine learning project for detecting fraudulent financial transactions using **XGBoost**.

## Overview

* Dataset: **6.36M+ transactions**
* Fraud transactions: **8,213**
* Problem: Highly imbalanced binary classification
* Model: **XGBoost Classifier**
* Train/Test Split: **80/20 with stratification**
* Imbalance handling: `scale_pos_weight`

## Features

Performed:

* Exploratory Data Analysis (EDA)
* Data quality checks
* Feature engineering
* Categorical encoding
* Class imbalance handling
* XGBoost model training

Engineered features include balance changes, amount ratio, high-risk transaction indicator, log amount, and high-amount indicator.

## Evaluation

Evaluated the model using:

* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC-AUC

**ROC-AUC: 0.99917**

## Technologies

Python • Pandas • NumPy • Scikit-learn • XGBoost • Matplotlib • Seaborn • Jupyter Notebook

## How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost jupyter
jupyter notebook
```

Open `Fraud_Detection.ipynb` and run the cells sequentially.

## Future Improvements

* Hyperparameter tuning
* SHAP-based model explainability
* Real-time fraud prediction API
* Model deployment and monitoring
