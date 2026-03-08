# 🛒 E-Commerce Fraud Detection System

A machine learning–powered web application that detects fraudulent e-commerce transactions in real time using an ensemble stacking model. The system integrates machine learning with a Flask web interface to provide fast and accurate fraud predictions.

---

## 📌 Project Description

Online financial transactions are increasingly vulnerable to fraud.  
This project applies machine learning techniques to analyze transaction features and classify them as:

✔ Legitimate Transaction  
✘ Fraudulent Transaction  

The trained model is deployed in a web application that allows users to input or upload transaction data and receive instant predictions.

## 🖼️ Application UI Preview

<p align="center">
  <img src="images/Screenshot 2026-03-08 124212.png" width="800">
</p>

<p align="center">
  <img src="images/Screenshot 2026-03-08 124608.png" width="800">
</p>

<p align="center">
  <img src="images/Screenshot 2026-03-08 124743.png" width="800">
</p>

---

## ✨ Features

- Real-time fraud prediction
- Machine learning stacking ensemble model
- Web interface using Flask
- CSV upload support for batch prediction
- Model accuracy evaluation included
- Simple and lightweight architecture

---

## 🧠 Machine Learning Model

The system uses an ensemble learning approach combining multiple classifiers:

- Decision Tree Classifier  
- Random Forest Classifier  
- Logistic Regression  
- XGBoost  
- Stacking Classifier (Final Prediction Layer)

Pre-trained models are stored and loaded during runtime.

---

## 🖥️ Application Workflow

User Input / CSV Upload  
⬇  
Feature Processing  
⬇  
Machine Learning Model  
⬇  
Fraud Prediction Result  

---

## 📁 Project Structure

```
E-COMMERCE FRAUD/
│
├── model/                 # Model-related supporting files
├── static/                # CSS, JavaScript, images
├── templates/             # HTML templates for UI
├── test_data/             # Sample datasets for testing
│
├── app.py                 # Main Flask application
├── fraud_stack.pkl        # Stacking ML model
├── fraud_xg.pkl           # XGBoost model
├── upload.csv             # Sample input dataset
├── Accuracy.txt           # Model accuracy results
├── requirements.txt       # Python dependencies
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
cd YOUR-REPOSITORY-NAME
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the application
```bash
python app.py
```

### 4️⃣ Open in browser
```
http://127.0.0.1:5000
```

---

## 📊 Model Performance

Model evaluation metrics are available in:

```
Accuracy.txt
```

This file contains training and testing accuracy results.

---

## 📦 Requirements

- Python 3.x
- Flask
- scikit-learn
- xgboost
- numpy
- pandas

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🎯 Use Cases

- Academic machine learning project
- Fraud detection prototype system
- ML + Web application integration
- Financial transaction risk prediction

---

## ⚠️ Disclaimer

This project is developed for educational and demonstration purposes only.  
It is not intended for real-world financial deployment.

---

## 👨‍💻 Author

Developed as an E-Commerce Fraud Detection Major Project.

---

## ⭐ Support

If you found this project useful, consider giving it a star ⭐
