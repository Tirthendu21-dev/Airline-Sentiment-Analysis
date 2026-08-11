# ✈️ Airline Passenger Sentiment Analysis

A machine learning project that analyzes airline passenger reviews and classifies them into **Positive, Neutral, or Negative** sentiment.

## 📌 Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning techniques to analyze airline passenger reviews.

The text data is cleaned and converted into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)**. Two machine learning classification algorithms are then trained and evaluated:

- Logistic Regression
- Linear Support Vector Machine (SVM)

A Streamlit web application is also included, allowing users to enter a passenger review and receive a sentiment prediction.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Streamlit

## 🔄 Project Workflow

```text
Airline Passenger Reviews
          ↓
Data Cleaning
          ↓
Text Preprocessing
          ↓
TF-IDF Feature Extraction
          ↓
Train/Test Split
          ↓
┌─────────────────────┐
│                     │
▼                     ▼
Logistic Regression   Linear SVM
│                     │
└──────────┬──────────┘
           ↓
     Model Evaluation
           ↓
  Sentiment Prediction
           ↓
Positive / Neutral / Negative