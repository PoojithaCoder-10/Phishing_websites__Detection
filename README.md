# 🛡️ Phishing Website Detection using Machine Learning

A Django-based web application that detects phishing websites using machine learning models such as Random Forest, Decision Tree, and Naive Bayes. This project was developed as part of our B.Tech final year submission.

## 📌 Project Overview

Phishing is a type of cyber-attack that aims to steal sensitive user data by mimicking legitimate websites. This project applies advanced machine learning techniques to detect phishing attempts in real time, improving detection accuracy and reducing false positives.

## ⚙️ Features

- 🔐 User & Admin Authentication
- 📁 Dataset upload and preprocessing
- 📊 Machine Learning model training and evaluation
- 📈 Real-time prediction and classification results
- 📉 Visualization of metrics such as Accuracy, Precision, Recall
- 📦 Random Forest achieved 97.8% accuracy on real-world data

## 🧠 Machine Learning Models Used

- Random Forest Classifier 🌲
- Decision Tree 🌳
- Naive Bayes 🧮

## 🖼️ UI Screenshots

| Home Page | User Dashboard | Admin Panel |
|-----------|----------------|-------------|
| ![Home](screenshots/home.png) | ![User](screenshots/user_home.png) | ![Admin](screenshots/admin_panel.png) |

## 🔄 Modules

- **User**: Register/login, upload dataset, train model, get predictions.
- **Admin**: Activate users, view overall metrics and results.
- **Data Preprocessing**: Handles missing values, noise, and feature selection.
- **ML Training**: Model fitting and accuracy evaluation.

## 🧪 Testing Summary

| Test Case | Expected Result | Status |
|-----------|------------------|--------|
| User Registration | Registers successfully or fails if duplicate | ✅ |
| Login (User/Admin) | Valid credentials redirect to dashboard | ✅ |
| Model Execution | Generates metrics and predictions | ✅ |
| View Dataset | Dataset renders on UI | ✅ |

## 🚀 Technologies Used

- Python 🐍
- Django 🌐
- HTML5/CSS3
- Bootstrap 🧩
- Pandas / Scikit-learn 📊

## 📂 Dataset

- Source: UCI Machine Learning Repository
- Type: CSV containing phishing & legitimate URLs with labels

## 📌 Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/phishing-detection-ml.git
