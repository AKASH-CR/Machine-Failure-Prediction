# 🛠️ Machine Failure Prediction Web App

A machine learning-based web application that predicts different types of machine failures using real-time sensor data. The model is trained on historical data and deployed with Streamlit to provide quick and accurate failure predictions.

---

## 📌 Project Overview

In manufacturing, unexpected machine failures can lead to production delays and high maintenance costs. This project aims to solve that by predicting failures **before** they happen using machine learning algorithms and sensor readings.

---

## 🚀 Web App Features

- Input fields for key sensor values
- Predicts multiple failure types:
  - No Failure
  - Random Failures
  - Power Failure
  - Overstrain Failure
  - Heat Dissipation Failure
  - Tool Wear Failure
- Built with an easy-to-use Streamlit interface
- Model trained with high accuracy (99%) using Random Forest

---

## 🧠 Machine Learning Model

- **Model**: Random Forest Classifier
- **Accuracy**: ~99% on test data
- **Dataset Source**: [Kaggle – Machine Failure Dataset](https://www.kaggle.com/datasets/paresh2047/machine-failure)
- **Features used**:
  - Type (L, M, H)
  - Air temperature [K]
  - Process temperature [K]
  - Rotational speed [rpm]
  - Torque [Nm]
  - Tool wear [min]

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python, scikit-learn
- **Libraries**: pandas, numpy, matplotlib, seaborn, joblib

---

## 💻 Setup Instructions

1. **Clone the repo**  
   ```bash
   git clone https://github.com/YOUR_USERNAME/machine-failure-prediction.git
   cd machine-failure-prediction
