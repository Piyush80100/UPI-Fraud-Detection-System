# 💳 UPI Fraud Detection System

## 📌 Project Overview

The **UPI Fraud Detection System** is a Machine Learning-based application developed using **Python**, **Flask**, and **Scikit-learn** to identify fraudulent UPI transactions.

The system is trained using a historical UPI transaction dataset and predicts whether a transaction is **Genuine** or **Fraudulent** using a **Random Forest Classifier**. This project demonstrates practical implementation of machine learning techniques for fraud detection in digital payment systems.

---

## 🎯 Features

- Detects fraudulent UPI transactions using Machine Learning
- Random Forest Classification algorithm
- Data preprocessing and feature selection
- Model training and prediction
- Trained model saved using Joblib
- Lightweight Python-based application

---

## 🧠 Machine Learning Model

- **Algorithm:** Random Forest Classifier
- **Machine Learning Library:** Scikit-learn
- **Dataset:** Historical UPI Transaction Dataset
- **Model File:** `model.pkl`
- **Feature Columns:** `model_columns.pkl`

---

## 🛠️ Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```text
UPI-Fraud-Detection-System/
│
├── app.py
├── train_model.py
├── fraud_dataset.csv
├── model.pkl
├── model_columns.pkl
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Piyush80100/UPI-Fraud-Detection-System.git
```

### 2. Navigate to the Project Folder

```bash
cd UPI-Fraud-Detection-System
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

---

## 📊 Project Workflow

1. Load the transaction dataset
2. Preprocess and clean the data
3. Select important features
4. Train the Random Forest model
5. Save the trained model using Joblib
6. Predict whether a transaction is Genuine or Fraudulent

---

## 📈 Future Improvements

- Improve prediction accuracy using advanced ML algorithms
- Hyperparameter tuning for better performance
- Deploy the application on cloud platforms
- Add REST API support
- Build a real-time fraud detection dashboard

---

## 🎓 Academic Purpose

This project was developed as part of academic learning to understand the application of **Machine Learning** in fraud detection and digital payment security.

---

## 👨‍💻 Author

**Piyush Jadhav**

B.Tech Computer Engineering

SVKM's NMIMS MPSTME, Shirpur

GitHub: https://github.com/Piyush80100
