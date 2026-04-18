# Fraud Detection using Machine Learning

## 📊 Overview
This project aims to detect fraudulent financial transactions using machine learning techniques.

The dataset contains transaction details such as type, amount, and account balances. The goal is to classify transactions as Fraud or Not Fraud.

---

## 📁 Dataset
- Size: 21,000 records  
- Source: Kaggle dataset  

---

## 🛠 Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## ⚙️ Data Preprocessing
- Handled missing values using:
  - Most frequent values for categorical data
  - Mean values for numerical columns
- Removed duplicate records
- Renamed columns for better readability
- Dropped unnecessary columns
- Encoded transaction types into numerical values

---

## 📊 Data Analysis & Visualization
- Analyzed transaction types for fraud vs valid cases
- Visualized:
  - Transaction distribution using pie charts
  - Fraud vs valid amounts using boxplots
- Key findings:
  - Fraud occurs mainly in **TRANSFER** and **CASH_OUT**
  - Fraud transactions tend to have higher amounts

---

## 🤖 Model
- Algorithm: Decision Tree Classifier
- Features used:
  - Transaction type
  - Amount
  - Sender old balance
  - Sender new balance

---

## 🚀 Results
- Accuracy: **99.4%**
- Model successfully classifies fraudulent transactions

---

## 🔍 Example Prediction
Input:[TRANSFER, 9839.64, 9839.64, 0.0]
Output:Fraud

---

## 📌 Note
This project is based on a Kaggle dataset.  
I implemented the preprocessing steps, built the model, and evaluated its performance.

---

## 📬 Contact
Faten Safi  
Email: fatensafi555@gmail.com
