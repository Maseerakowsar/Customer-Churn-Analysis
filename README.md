# 📊 Customer Churn Analysis using Machine Learning

## 🧠 Project Overview
This project predicts whether a customer will churn (leave the service) or stay using machine learning. It helps businesses understand customer behavior and reduce customer loss.

---

## 🎯 Objective
To build a machine learning model that can classify customers as:
- 1 → Churn (will leave)
- 0 → Not Churn (will stay)

based on customer details like tenure, contract type, monthly charges, etc.

---

## 📁 Dataset Information
- Dataset Name: Telco Customer Churn Dataset  
- Source: Kaggle  
- Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn  
- Target Column: Churn  
- Type: Classification Problem  

---

## ⚙️ Tools & Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧹 Data Preprocessing Steps
- Removed unnecessary columns (like customerID if present)
- Converted TotalCharges to numeric
- Handled missing values
- Converted categorical values into numerical format using encoding
- Standardized features using StandardScaler

---

## 🤖 Machine Learning Model Used
- Logistic Regression

---

## 🧪 Train-Test Split
- Training data: 80%  
- Testing data: 20%  

---

## 📊 Model Evaluation
The model is evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 📈 Results
- The model predicts customer churn with reasonable accuracy
- Helps identify customers who are likely to leave
- Useful for business decision-making

---

## 📂 Project Structure