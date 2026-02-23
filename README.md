🛒 E-Commerce Fraud Detection Web App

A machine learning–powered web application that predicts whether an e-commerce transaction is fraudulent or legitimate using a stacked ensemble model. The system provides a simple web interface built with Flask for real-time prediction.

🚀 Features

Real-time fraud prediction via web interface

Ensemble ML model (stacking approach)

Upload transaction data for prediction

Accuracy evaluation included

Lightweight Flask backend

🧠 Machine Learning Approach

The system uses an ensemble learning strategy combining multiple classifiers:

Decision Tree

Random Forest

Logistic Regression

XGBoost

Stacking Classifier (final predictor)

The trained models are stored and loaded for prediction at runtime.

🖥️ How the Web App Works

User inputs transaction details or uploads data

Flask backend processes the features

Trained ML model predicts fraud probability

Result displayed on webpage

📁 Project Structure
E-COMMERCE FRAUD/
│
├── model/                 # Additional model-related files (if any)
├── static/                # CSS, JS, images
├── templates/             # HTML pages for web interface
├── test_data/             # Sample test datasets
│
├── app.py                 # Main Flask application
├── fraud_stack.pkl        # Stacking model file
├── fraud_xg.pkl           # XGBoost model file
├── upload.csv             # Sample input dataset
├── Accuracy.txt           # Model accuracy results
├── requirements.txt       # Python dependencies
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
2️⃣ Install required libraries
pip install -r requirements.txt
3️⃣ Run the application
python app.py
4️⃣ Open in browser
http://127.0.0.1:5000
📊 Model Performance

Model evaluation results are stored in:

Accuracy.txt

This file contains performance metrics from training and testing.

📦 Requirements

Python 3.x

Flask

scikit-learn

xgboost

numpy

pandas

Install automatically using:

pip install -r requirements.txt
🎯 Project Purpose

This project demonstrates:

Application of machine learning in fraud detection

Integration of ML model with web application

Real-time prediction system

End-to-end ML deployment workflow

Designed as an academic major project and prototype system.

⚠️ Disclaimer

This project is for educational purposes only and not intended for real financial production environments.

👨‍💻 Author

Developed as an E-Commerce Fraud Detection major project.
