# Diabetes Prediction Machine Learning

A machine learning project aimed at detecting the likelihood of diabetes in patients based on health parameters, using Support Vector Machine (SVM) classifier.

## Project Overview

This project utilizes the PIMA Diabetes Dataset to develop a predictive model for diagnosing diabetes. The model takes health indicators such as glucose level, blood pressure, BMI, age, and more to classify whether a patient has diabetes.

## Dataset

The dataset contains **768 records** with the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (target: 0 – no diabetes, 1 – diabetic)

## Technologies Used

- Python 3
- NumPy
- Pandas
- Scikit-learn:
  - StandardScaler: Data standardization
  - train_test_split: Data splitting into training and testing sets
  - Support Vector Machine (svm): Classification model
  - accuracy_score: Model accuracy measurement

## Features

- Loading and inspecting the dataset
- Data standardization with StandardScaler
- Splitting data into train and test sets
- Building an SVM classifier
- Model prediction and evaluation
- Accuracy reporting

## Installation

