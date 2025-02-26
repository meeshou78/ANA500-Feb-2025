# Song Popularity Prediction

## Overview

This repository contains a **machine learning project** focused on predicting the **popularity of songs** based on various audio and metadata features. The project involves data preprocessing, feature engineering, and applying different machine learning models to classify song popularity.

## Project Structure

```
📦 song-popularity-prediction
├── 📜 song_popularity_analysis.py   # Combined Python script for full analysis
├── 📜 data/                         # Raw and cleaned datasets (if applicable)
├── 📜 models/                       # Trained machine learning models
├── 📜 requirements.txt              # Dependencies for the project
├── 📜 README.md                     # Project Documentation
```

## 🔗 Dataset
The dataset used for this project is publicly available on Kaggle:
[Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset/data)
The downloaded dataset has also been added to this repository

## Machine Learning Models

This project applies multiple machine learning models to classify song popularity:

- **Logistic Regression**
- **Decision Trees**
- **Random Forest**
- **Gradient Boosting**
- **Neural Networks (MLPClassifier)**
- **LSTM (Long Short-Term Memory)**

## Key Findings

- **Random Forest achieved the highest accuracy and lowest Mean Squared Error (MSE), making it the best model.**
- **LSTM performed well for sequential dependencies but struggled with binary classification.**
- **Feature selection and normalization significantly improved model performance.**

## Visualizations

- **ROC Curves** to compare model performance.
- **Actual vs. Predicted Scatterplots** for evaluating regression-based models.

**Song Popularity Prediction** - Predicting music trends with machine learning!

