# 🚀 Customer Churn Prediction ML Pipeline

## 📌 Overview
This project is a machine learning pipeline designed to predict customer churn using the Telco Customer Churn dataset. It helps in identifying whether a customer will leave or continue using the service based on historical data patterns.

## 🎯 Objective
To build an end-to-end ML pipeline that:
- Processes and cleans raw data
- Performs feature engineering
- Trains a classification model
- Evaluates model performance
- Saves the trained model for real-world usage

## 🧠 Machine Learning Approach
- Type: Supervised Learning (Classification)
- Algorithm: Logistic Regression / Random Forest
- Framework: Scikit-learn
- Output: Binary Classification (Churn / No Churn)

## ⚙️ Workflow
- Data Loading  
- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Training  
- Model Evaluation  
- Model Saving using Joblib  

## 💾 Model Saving
```python
import joblib

joblib.dump(model, "churn_pipeline.pkl")
📁 Files in Repository
Telco-Customer-Churn.csv → Dataset
churn_pipeline.pkl → Trained ML Model
notebook.ipynb → Complete training + analysis
📊 Results

The model predicts:

Customers likely to churn (Yes)
Customers likely to stay (No)

Evaluation metrics include accuracy, precision, and recall.

🛠️ Tech Stack

Python | Pandas | NumPy | Scikit-learn | Joblib | Jupyter Notebook

👨‍💻 Author

Muhammad Abdullah
BSCS Student | AI & Machine Learning Enthusiast | Python & ML Developer

🔗 GitHub Profile: https://github.com/muhammadabdullah-devpk
