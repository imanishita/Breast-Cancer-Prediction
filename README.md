# Breast Cancer Classification using Logistic Regression

This project uses the **Breast Cancer Wisconsin** dataset to build a classification model that predicts whether a tumor is **malignant** or **benign** using **Logistic Regression**.

---

## Project Structure

├── breastcancer.py # Main Python script
├── README.md # Project documentation

---
## Overview
Breast cancer is one of the most common cancers in women worldwide. Early diagnosis is critical. This machine learning project uses supervised learning to classify tumors based on features like radius, texture, perimeter, area, etc.
---
## Dataset Information

- **Source**: Built-in from `sklearn.datasets.load_breast_cancer()`
- **Samples**: 569
- **Features**: 30 numerical features  
  *(e.g., radius, texture, perimeter, area, etc.)*
- **Target Classes**:
  - `0`: Malignant
  - `1`: Benign

---

## Features of this Project

- Loads breast cancer data from `sklearn`
- Cleans and prepares the data
- Performs exploratory analysis using:
  - `.info()`
  - `.describe()`
  - `.value_counts()`
- Splits the dataset into training and test sets
- Trains a **Logistic Regression** model
- Evaluates model performance with accuracy score
- Builds a simple predictive system to classify new input data

---

## Model Performance

- **Training Accuracy**: ~93.2%
- **Test Accuracy**: ~92.98%

---


##  Getting Started

To run the project locally:

```bash
pip install numpy pandas scikit-learn
