# 🩺 Liver Disease Prediction using Machine Learning

## 📘 Overview

This project uses machine learning to predict whether a patient has liver disease based on various medical attributes. It leverages a dataset of Indian liver patients and provides a user-friendly web interface built with Flask for real-time predictions.

## 🧪 Features

- Trained machine learning model for binary classification (Liver Disease / No Liver Disease)
- Flask-based web application with a form-based UI
- Real-time predictions with input validation
- Preprocessed dataset with feature scaling
- Saved models (`model.pkl`, `sc.pkl`) for efficient deployment

## 📂 Project Structure

├── app.py # Flask app for web interface
├── Liver_Disease_Prediction.ipynb # Model training and evaluation
├── indian_liver_patient.csv # Dataset used for training
├── model.pkl # Trained ML model
├── sc.pkl # Scaler for input features
├── templates/
│ ├── index.html # Home page form
│ └── result.html # Prediction result page

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Liver-Disease-Prediction.git
   cd Liver-Disease-Prediction
pip install -r requirements.txt

python app.py
![image](https://github.com/user-attachments/assets/b1c09fcd-1c40-454b-9185-313f9a479e7d)
![image](https://github.com/user-attachments/assets/f8fe41e5-05d8-4198-97f1-3ebb62797330)
![image](https://github.com/user-attachments/assets/17e37121-0c2e-420f-9cb8-4566cc3dfb68)
![image](https://github.com/user-attachments/assets/30cfc778-4d4c-452d-9bba-d8a64405f3c8)




📊 Dataset
Source: UCI Machine Learning Repository

Attributes: Age, Gender, Total Bilirubin, Alkaline Phosphotase, Albumin, etc.

Target: 1 = Liver Disease, 0 = No Liver Disease

📈 Model
Algorithm: Random Forest Classifier (or other based on the notebook)

Scaler: StandardScaler

Evaluation metrics: Accuracy, Confusion Matrix, etc.

🚀 Deployment
This app can be deployed using:

Local server (Flask)

Cloud platforms like Heroku, Render, or AWS
