# 🫀 Heart Disease Prediction App

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=MLflow&logoColor=white)
![Accuracy](https://img.shields.io/badge/Accuracy-90%25-success.svg)

An interactive, data-driven web application built with **Python** and **Streamlit** that utilizes Machine Learning to predict the likelihood of a patient developing heart disease based on their clinical and vital metrics.

---

## 📌 Overview & Problem Statement
Early diagnosis of cardiovascular diseases (CVDs) plays a critical role in saving lives. Traditional diagnostic methods can be time-consuming and resource-intensive. This project aims to provide a fast, reliable, and accessible preliminary screening tool for individuals and healthcare professionals to assess heart disease risk using routine clinical data (e.g., blood pressure, cholesterol levels, max heart rate).

## ✨ Key Features
* **Interactive UI:** A clean, user-friendly interface for seamless clinical data entry.
* **Real-time Prediction:** Instantaneous processing and risk assessment.
* **Advanced Feature Engineering:** Incorporates medical domain knowledge by utilizing engineered features like Heart Rate Reserve (HRR) and a Composite Risk Score to enhance predictive accuracy.
* **Probability Confidence:** The model doesn't just output a binary "Healthy/Disease" classification; it provides a probabilistic percentage indicating the severity of the risk.

---

## 🧠 Model Performance
Multiple classification algorithms (including Random Forest and Gradient Boosting) were evaluated and tuned using `GridSearchCV`. The experiments were rigorously tracked using `MLflow`. 

The final production model is a fine-tuned **Logistic Regression**, which proved to be highly robust and resistant to overfitting on this clinical dataset, achieving the following metrics on the unseen test set:
* **Accuracy:** 90.0%
* **ROC-AUC Score:** 94.0%

---

## 🛠️ Tech Stack
* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Experiment Tracking:** MLflow
* **Web Framework:** Streamlit
* **Data Visualization:** Plotly, Matplotlib, Seaborn

---

## 🚀 How to Run Locally

To run this application on your local machine, follow these steps:

**1. Clone the repository:**
```bash
git clone [https://github.com/ahmedhamdy-DS/Heart-Disease-Prediction.git](https://github.com/ahmedhamdy-DS/Heart-Disease-Prediction.git)
cd Heart-Disease-Prediction:

```bash
git clone https://github.com/ahmedhub2005/heart-disease-predictor.git
cd heart-disease-predictor

