
# 📊 Customer Churn Prediction System

A Machine Learning–powered web application that predicts whether a customer is likely to churn (leave the service) based on demographic details, service usage, and billing information.

---

## 🚀 Project Overview

Customer churn prediction helps businesses identify customers who are likely to discontinue their services. This project uses a trained Machine Learning model deployed with Flask to provide real-time churn predictions.

---

## 🧠 Machine Learning Workflow

- Data Cleaning & Preprocessing
- Label Encoding for categorical features
- Feature Scaling using StandardScaler
- Handling Imbalanced Data using SMOTE
- Model Training using Random Forest
- Hyperparameter Tuning with GridSearchCV
- Model Evaluation and Selection
- Model Deployment using Flask

---

## 🖥️ Tech Stack

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib & Seaborn
- Pickle

---

## 📁 Project Structure

Customer-Churn-Prediction/
│
├── app.py
├── best_model.pkl
├── encoder.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
├── .gitignore
│
└── templates/
    └── index.html

---

## ⚙️ How to Run the Project

1. Clone the repository  
2. Install dependencies  
   pip install -r requirements.txt  
3. Run the Flask app  
   python app.py  
4. Open browser and go to  
   http://127.0.0.1:5000/

---

## 🌐 Application Features

- User-friendly web interface
- Real-time churn prediction
- Displays churn probability
- Clean UI using Bootstrap

---

## 📌 Output

- Prediction: Churn / No Churn
- Probability Score

---

## 🔮 Future Improvements

- Cloud deployment (Render / Heroku)
- UI enhancements
- Model explainability
- User authentication

---

## 👩‍💻 Author

Kritika Gupta  
BCA Final Year Student  

---

⭐ If you like this project, give it a star on GitHub!
