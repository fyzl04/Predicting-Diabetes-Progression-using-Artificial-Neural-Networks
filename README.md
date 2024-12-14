# Predicting Diabetes Progression using Artificial Neural Networks

## Overview

This project demonstrates how to predict diabetes progression using an Artificial Neural Network (ANN). The dataset used is the Diabetes dataset available in the `sklearn` library, which contains various health-related metrics of diabetes patients. The goal is to predict the progression of diabetes in patients based on their medical data, providing valuable insights for healthcare professionals.

## Objectives

- Load and preprocess the Diabetes dataset.
- Perform exploratory data analysis (EDA) to visualize feature distributions and correlations.
- Build and train a simple Artificial Neural Network (ANN) to predict diabetes progression.
- Evaluate the model's performance using common metrics (e.g., Mean Squared Error, Mean Absolute Error).
- Improve the model by experimenting with different architectures and hyperparameters.

## Dataset

The Diabetes dataset is included in the `sklearn.datasets` module. It contains 10 features, such as age, sex, body mass index (BMI), blood pressure, etc., and the target variable represents a measure of diabetes progression one year after baseline.

### Features:
- `age`: Age of the patient
- `sex`: Sex of the patient (0 = female, 1 = male)
- `bmi`: Body mass index
- `bp`: Blood pressure
- `s1`: Total serum cholesterol
- `s2`: Low-density lipoproteins
- `s3`: High-density lipoproteins
- `s4`: Triceps skinfold thickness
- `s5`: 2-Hour serum insulin
- `s6`: Body mass index
- `target`: Diabetes progression (target variable)

## Project Structure

```plaintext
.
├── data/
│   └── diabetes_data.csv  # Dataset file (optional, if you wish to include the raw data)
├── notebooks/
│   └── Predicting_Diabetes_Progression.ipynb  # Jupyter notebook with model implementation
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
