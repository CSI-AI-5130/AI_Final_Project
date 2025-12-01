# AI_Final_Project

This project focuses on building and improving machine learning models
to detect fraudulent credit card transactions using the publicly
available **Credit Card Fraud Detection Dataset** (Kaggle).

Because the dataset is **highly imbalanced** (fraud cases make up only
**0.17%** of all transactions), traditional accuracy metrics are
misleading.\
This project uses advanced preprocessing, sampling techniques, and model
tuning to significantly improve fraud-detection performance.

## 📌 Project Goals

The primary objective is to enhance the detection of fraudulent
transactions using:

### 1. Feature Engineering & Data Preprocessing

-   Cleaning and transforming data\
-   Scaling numerical features\
-   Handling missing or skewed values

### 2. Handling Class Imbalance

-   SMOTE (Synthetic Minority Oversampling Technique)\
-   Random Undersampling\
-   Hybrid sampling approaches

### 3. Training Multiple ML Algorithms

-   Random Forest\
-   Decision Tree\
-   Naive Bayes\
-   XGBoost

### 4. Hyperparameter Tuning

-   Grid Search / Random Search\
-   Cross-validation\
-   Threshold optimization

### 5. Evaluation Metrics

-   Classification Report\
-   Confusion Matrix\
-   ROC-AUC\
-   Precision-Recall Curve\
-   F1-Score\
-   Recall (Fraud Detection Performance)

## 📊 Dataset

Dataset used:\
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download

Place `creditcard.csv` in the project root directory.

## 📦 Setup

Install dependencies:

``` bash
pip install -r requirements.txt
```

## ▶️ Running the Project

1.  Ensure dataset is in the root directory\
2.  Open the notebook or script\
3.  Run preprocessing, sampling, model training, and evaluation steps

## 📈 Summary

This project demonstrates how preprocessing, sampling strategies, and
model tuning significantly improve fraud detection accuracy and recall
in highly imbalanced datasets.
