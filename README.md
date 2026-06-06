# 🩺 Disease Prediction from Medical Data

## 📌 Project Overview

This project is developed as part of the CodeAlpha Machine Learning Internship.

The goal of this project is to predict whether a person is likely to have diabetes based on various medical attributes such as glucose level, blood pressure, BMI, insulin level, age, and other health indicators.

Machine Learning techniques are used to analyze patient data and make accurate predictions that can assist in early disease detection.

---

## 🎯 Objectives

- Analyze medical data
- Perform data preprocessing and visualization
- Train a Machine Learning model
- Predict disease occurrence
- Evaluate model performance using various metrics

---

## 📊 Dataset Information

Dataset: Pima Indians Diabetes Dataset

Features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

Target Variable:

- Outcome
  - 0 = Non-Diabetic
  - 1 = Diabetic

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

- Loaded dataset using Pandas
- Checked missing values
- Explored dataset statistics
- Correlation analysis using heatmap
- Feature scaling using StandardScaler
- Train-Test Split

---

## 🤖 Model Used

Logistic Regression

The model was trained to classify whether a patient is diabetic or non-diabetic based on medical attributes.

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📊 Visualizations

- Correlation Heatmap
- Confusion Matrix
- Feature Importance Analysis

---

## 🚀 Results

The model achieved a satisfactory accuracy score and successfully predicted diabetes outcomes based on patient medical data.

Example Prediction:

- Diabetic
- Non-Diabetic

---

## 📂 Project Structure

CodeAlpha_Disease_Prediction/

├── disease_prediction.ipynb

├── diabetes.csv

├── diabetes_model.pkl

├── requirements.txt

└── README.md

---

## 🔮 Future Improvements

- Deploy using Streamlit
- Improve accuracy using Random Forest and XGBoost
- Add multiple disease prediction capabilities
- Build a web application for real-time predictions

---

## 👨‍💻 Author

Manjunadh Prakash

Machine Learning Intern @ CodeAlpha
