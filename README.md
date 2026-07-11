# Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview

This project demonstrates how to build a **Machine Learning Classification Model** to detect **fraudulent credit card transactions**. Fraud detection is one of the most important real-world applications of machine learning in the financial industry, where the goal is to identify suspicious transactions while minimizing false alarms.

Using the **`credit-fraud-dataset.csv`** dataset, this notebook covers the complete machine learning workflow, including data exploration, preprocessing, handling class imbalance, model training, evaluation, and fraud prediction for new transactions.

---

## 🎯 Objectives

* Understand the credit card fraud detection problem
* Perform data preprocessing and feature scaling
* Handle imbalanced datasets effectively
* Train a binary classification model
* Evaluate model performance using multiple classification metrics
* Predict whether a transaction is Legit or Fraudulent

---

## 📂 Dataset

**Dataset Used:** `credit-fraud-dataset.csv`

The dataset contains transaction-related features collected from credit card operations. Since fraudulent transactions are very rare compared to legitimate ones, the dataset is **highly imbalanced**, making it an excellent dataset for learning fraud detection techniques.

The target variable indicates:

* **0 → Legit Transaction**
* **1 → Fraudulent Transaction**

---

## 📖 Concepts Covered

* Binary Classification
* Fraud Detection
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Feature Scaling
* Handling Imbalanced Data
* Train-Test Split
* Logistic Regression
* Model Evaluation
* Confusion Matrix
* Precision
* Recall
* F1-Score
* ROC Curve
* AUC Score
* Prediction System

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

---

## ⚙️ Implementation Steps

### Data Preparation

* Load the fraud detection dataset
* Explore dataset structure
* Check missing values
* Analyze class distribution

### Data Preprocessing

* Prepare the dataset for machine learning
* Scale numerical features using StandardScaler
* Handle class imbalance
* Split the dataset into training and testing sets

### Model Training

* Train a binary classification model
* Learn transaction patterns to distinguish legitimate and fraudulent activities

### Model Evaluation

* Calculate Accuracy Score
* Generate Confusion Matrix
* Compute Precision, Recall, and F1-Score
* Plot ROC Curve
* Calculate AUC Score

### Prediction System

* Predict whether a transaction is Legit or Fraudulent
* Test the model using new transaction data
* Display prediction results

---

## 🔍 Key Observations

* Fraud detection datasets are highly imbalanced.
* Accuracy alone is not enough to evaluate model performance.
* Precision, Recall, F1-Score, and ROC-AUC provide a better understanding of model quality.
* Proper preprocessing and handling class imbalance improve fraud detection performance.

---

## ✅ Advantages

* Demonstrates a complete end-to-end machine learning workflow
* Uses a real-world financial fraud detection dataset
* Covers handling of imbalanced classification problems
* Includes prediction for new transaction data
* Builds practical experience in financial machine learning applications

---

## 🏁 Conclusion

This project demonstrates how machine learning can help detect fraudulent credit card transactions using historical transaction data. From data preprocessing and imbalance handling to model evaluation and prediction, it provides a complete understanding of building an effective fraud detection system for real-world financial applications.

---

## 💻 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
