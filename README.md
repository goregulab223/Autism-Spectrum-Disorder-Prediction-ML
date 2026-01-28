# 🧠 Autism Spectrum Disorder Prediction – Machine Learning

## 📌 Project Overview
This project builds a machine learning model to predict **Autism Spectrum Disorder (ASD)** using screening and demographic data.  
It includes EDA, preprocessing, class imbalance handling, model selection, hyperparameter tuning, and deployment-ready prediction logic.

---

## 🎯 Objectives
- Analyze ASD screening data
- Handle missing values and outliers
- Address class imbalance using SMOTE
- Train and compare ML models
- Build a reusable prediction system

---

## 🗂 Dataset
- **Source:** Public ASD screening dataset
- **Target Variable:** `Class/ASD`
- **Features:** Demographics, screening scores, medical indicators

---

## 🔍 Key Techniques Used
- Exploratory Data Analysis (EDA)
- Label Encoding with saved encoders
- Outlier treatment (IQR + Median)
- SMOTE for class imbalance
- Cross-validation
- RandomizedSearchCV
- Model persistence using Pickle

---

## 🤖 Models Trained
- Decision Tree
- Random Forest
- XGBoost (Best Performing)

---

## 📊 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score

---
Future Scope

- Experiment with advanced models such as Random Forest or XGBoost to improve accuracy.
- Apply hyperparameter tuning techniques like Grid Search
- Address class imbalance using resampling techniques.
- Add more behavioral and clinical features for better prediction.
- Deploy the model using Flask or Streamlit for real-time user interaction.
- Implement explainable AI methods to improve model transparency.

--- 
## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Matplotlib, Seaborn

---

## 👤 Author
**Gulab Gore**  


