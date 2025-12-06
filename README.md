Indian Diabetes Prediction using Machine Learning and Optuna Hyperparameter Optimization

This repository contains a complete machine learning workflow for predicting diabetes using the Indian Diabetes Dataset.
The project includes data preprocessing, exploratory data analysis (EDA), model building, and hyperparameter tuning using Optuna, inspired by techniques taught in CampusX tutorials.

🚀 Project Overview

The goal of this project is to build an accurate predictive model that can classify whether a person has diabetes based on medical features such as glucose level, BMI, pregnancies, etc.

To achieve high performance, Optuna, a powerful automated hyperparameter optimization framework, is used to search for the best model parameters efficiently.

📂 Dataset

The dataset used is commonly known as the Pima Indian Diabetes Dataset, widely used for classification tasks.
It contains 768 rows × 8 features, including:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Target variable:

Outcome (1 = diabetic, 0 = non-diabetic)

🧹 Workflow / Pipeline
✔ 1. Data Cleaning

Handling missing or zero values (especially insulin, skin thickness, BP)

Treating outliers

Scaling features using StandardScaler

✔ 2. Exploratory Data Analysis (EDA)

Distribution plots

Correlation heatmap

Feature relationships

Class imbalance check

✔ 3. Model Building

Models experimented with:

Logistic Regression

Random Forest

XGBoost / LightGBM (optional)

SVC

✔ 4. Hyperparameter Tuning with Optuna

Defined an objective function for each model

Optuna used TPE sampler for efficient parameter search

Evaluated based on accuracy / F1-score

Visualization of Optuna optimization history

✔ 5. Model Evaluation

Metrics used:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

