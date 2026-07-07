# ❤️ Heart Disease Prediction System

A Machine Learning-based web application that predicts the likelihood of heart disease based on a patient's medical information. This project demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, and deployment through an interactive web interface.

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals make timely decisions and improve patient outcomes.

This project uses a supervised machine learning classification model trained on patient health records to predict whether a person is at risk of heart disease.

> **Disclaimer:** This project is intended for educational purposes only and should not be used as a substitute for professional medical advice or diagnosis.

---

## 🚀 Features

* Predicts the risk of heart disease using patient health parameters
* User-friendly web interface
* Data preprocessing and feature engineering
* Trained Machine Learning classification model
* Real-time predictions
* Clean and responsive design

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** NumPy, Pandas, Scikit-learn
* **Data Visualization:** Matplotlib, Seaborn
* **Web Framework:** Streamlit, FastAPI

---

## 📂 Project Structure

```text
Heart-disease-prediction-system/
│
├── dataset/                 # Dataset file
├── model_dir/               # Trained model
├── frontend/app.py          # fontend application
├── backend/                 # backend applications
├── notebook_files           # Model training notebook
├── requirements.txt         # Dependencies (if available)
├── README.md

```

---

## 📊 Dataset

The project is trained on a publicly available Heart Disease dataset containing various patient health attributes such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression (Oldpeak)
* Slope of ST Segment
* Number of Major Vessels
* Thalassemia

**Target Variable**

* **0** → No Heart Disease
* **1** → Heart Disease Detected

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Abhishek98negi/Heart-disease-prediction-system.git
```

### Navigate to the project folder

```bash
cd Heart-disease-prediction-system
```

### Create a virtual environment (Optional)

```bash
python -m venv .venv
```

Activate the environment:

**Windows**

```bash
.venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

To run a FastAPI application with Uvicorn:

```bash
uvicorn backend.main:app --reload
```

For Streamlit:

```bash
streamlit run frontend/app.py
```


---

## 📈 Machine Learning Workflow

* Data Collection
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Selection
* Data Preprocessing
* Model Training
* Model Evaluation
* Model Serialization
* Deployment

---

## 🎯 Future Improvements

* Add multiple machine learning algorithms for comparison
* Deploy on Streamlit Cloud, Render, or Heroku
* Add user authentication
* Store prediction history in a database

---

## Screenshots
<img width="1920" height="832" alt="image-1" src="https://github.com/user-attachments/assets/19f3edc4-8904-4cd1-a6d5-3374b22203d6" />

<img width="1908" height="805" alt="image-2" src="https://github.com/user-attachments/assets/0fd81240-e0e5-4ffe-b3cc-d65b0ef4ed0b" />

