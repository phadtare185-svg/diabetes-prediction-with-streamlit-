# Diabetes Prediction Web App

A Machine Learning web application built with **Streamlit** that predicts the likelihood of diabetes in a patient based on diagnostic health metrics.

## 📌 Project Overview

This project uses a classification model trained on health parameter metrics to predict whether a person is diabetic or non-diabetic. The trained Machine Learning model and feature scaler are deployed via an interactive Streamlit interface.

## 📁 Repository Structure

```text
├── diabetes.csv          # Dataset used for training and evaluation
├── diabetes_model.pkl    # Serialized trained Machine Learning model
├── diabetes_scaler.pkl   # Serialized StandardScaler object for input normalization
├── diabetiescode.ipynb   # Jupyter Notebook containing EDA, preprocessing, and model training
└── README.md             # Project documentation
