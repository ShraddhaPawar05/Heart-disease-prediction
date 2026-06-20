# ❤️ Heart Disease Prediction using Machine Learning

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)]()
[![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red.svg)]()
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KNN-green.svg)]()

A Machine Learning-powered web application that predicts the likelihood of heart disease based on various health parameters. This project follows a complete Machine Learning workflow including Exploratory Data Analysis (EDA), Data Preprocessing, Feature Engineering, Model Comparison, Model Selection, and Deployment using Streamlit.

---

## 🌐 Live Demo

🔗 https://heart-disease-prediction-t8jxbzmuez2k2cejqh8ros.streamlit.app/

Try the deployed Streamlit application to predict heart disease risk using real-time health parameters.

---

## 🎯 Project Objective

Heart disease is one of the leading causes of death worldwide. Early identification of high-risk patients can help in timely diagnosis and treatment.

This project aims to build a machine learning model capable of predicting heart disease risk using patient health information such as age, blood pressure, cholesterol level, chest pain type, ECG results, and other medical indicators.

---

## 📊 Dataset Overview

The dataset contains patient medical records with features including:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate
* Exercise Induced Angina
* Oldpeak
* ST Slope

### Target Variable

**HeartDisease**

* 0 → Low Risk
* 1 → High Risk

---

## 🔍 Exploratory Data Analysis (EDA)

Performed detailed EDA to understand:

* Feature distributions
* Correlation between variables
* Target class distribution
* Missing values analysis
* Outlier detection
* Important health indicators affecting heart disease

---

## 🧹 Data Preprocessing

The following preprocessing techniques were applied:

* Handling missing values
* Removing duplicate records
* One-Hot Encoding for categorical features
* Feature Engineering
* Train-Test Split
* Feature Scaling using StandardScaler

---

## ⚙️ Feature Engineering

Additional analysis and transformations were performed to improve model performance and data representation.

Examples:

* Age Group categorization
* Risk-based feature creation
* Medical parameter analysis

---

## 🤖 Machine Learning Models Evaluated

Multiple classification algorithms were trained and compared:

| Model               | Accuracy | F1 Score |
| ------------------- | -------: | -------: |
| Logistic Regression |   85.87% |   87.38% |
| KNN                 |   86.41% |   88.04% |
| Naive Bayes         |   84.78% |   86.14% |
| Decision Tree       |   79.35% |   81.37% |
| SVM                 |   84.24% |   86.26% |

---

## 🏆 Final Model Selection

After evaluating multiple classification algorithms, **K-Nearest Neighbors (KNN)** achieved the highest overall performance.

### Selected Model

* Algorithm: K-Nearest Neighbors (KNN)
* Accuracy: 86.41%
* F1 Score: 88.04%

The trained KNN model was serialized using Joblib and integrated into a Streamlit web application for real-time heart disease risk prediction.

---

## 🖥️ Application Screenshots

### Home Page

![Home Page](screenshots/Home%20Page.png)

### Low Risk Prediction

![Low Risk](screenshots/Low%20Risk%20Prediction.png)

### High Risk Prediction

![High Risk](screenshots/High%20Risk%20Prediction.png)

---

## 📚 Key Learnings

Through this project, I gained hands-on experience with:

* Exploratory Data Analysis (EDA)
* Data Cleaning and Preprocessing
* Feature Engineering
* One-Hot Encoding
* Feature Scaling using StandardScaler
* Model Evaluation using Accuracy and F1 Score
* Comparing Multiple Machine Learning Algorithms
* Model Serialization using Joblib
* Streamlit Web Application Development
* GitHub Project Management and Deployment

---

## 🛠️ Tech Stack

### Machine Learning

* Python
* Pandas
* NumPy
* Scikit-Learn
* Joblib

### Deployment

* Streamlit

### Development Environment

* Google Colab
* VS Code

---

## 📁 Project Structure

```text
Heart-disease-prediction/
│
├── app.py
├── heart_model.pkl
├── scaler.pkl
├── columns.pkl
├── heart.csv
├── heart_disease_prediction.ipynb
├── requirements.txt
├── README.md
└── screenshots/
```

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## 👩‍💻 Author

**Shraddha Pawar**

GitHub:
https://github.com/ShraddhaPawar05

Project Repository:
https://github.com/ShraddhaPawar05/Heart-disease-prediction

Live Application:
https://heart-disease-prediction-t8jxbzmuez2k2cejqh8ros.streamlit.app/
