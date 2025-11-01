# 🩺 Health Insurance Premium Prediction

This project predicts an individual's annual health insurance premium based on demographic, lifestyle, and financial data.
The goal is to help insurance providers estimate fair premiums and identify key factors influencing costs.

## 🔍 Overview

Using a dataset of customer records, the model learns how personal attributes and behaviors correlate with premium amounts. It combines categorical and numerical features to predict the annual_premium_amount with strong accuracy and interpretability.

## 🧩 Features

### Categorical:
gender, region, marital_status, bmi_category, smoking_status,
employment_status, income_level, medical_history, insurance_plan

### Numerical:
age, number_of_dependants, income_lakhs
Target: annual_premium_amount

## 🌐 Live Demo
Check out the deployed Streamlit app here: [Health Insurance Premium Predictor](https://bukky-ml-project-health-insurance-prediction.streamlit.app/)

## ⚙️ Tech Stack

Python (pandas, numpy, scikit-learn, seaborn, matplotlib)

Models: Linear Regression, Random Forest, XGBoost

Streamlit for web interface

Evaluation: MAE, RMSE, R² Score

## 💻 Web App Features

Simple input fields for all model features

Clean, responsive design

Prediction on One Click!

##🚀 How to Run Locally
### Clone the repo
git clone https://github.com/bukky300/ml-project-health-insurance-prediction


### Install dependencies
pip install -r requirements.txt

### Run the app
streamlit run main.py


Then open the local URL Streamlit provides (usually http://localhost:8501).
