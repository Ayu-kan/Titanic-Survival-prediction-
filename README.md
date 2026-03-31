# Titanic Survival Prediction using Machine Learning

## Overview
This project focuses on **Titanic Survival Prediction** using **Machine Learning** techniques.  
The notebook performs:

- **Data Cleaning**
- **Missing Value Handling**
- **Categorical Encoding**
- **Feature Scaling**
- **Model Training**
- **Model Evaluation**
- **Prediction on Test Data**
- **Submission File Creation**

The goal is to build a model that can classify whether a passenger survived the Titanic disaster.

The target classes are:

- **0 → Did Not Survive**
- **1 → Survived**

---

## Features
This project includes:

- Titanic dataset preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling using **StandardScaler**
- Classification using **Logistic Regression**
- Accuracy and confusion matrix evaluation
- Prediction on unseen test data
- CSV result file generation

---

## Technologies Used

### Programming Language
- Python

### Libraries
- pandas
- numpy
- matplotlib
- scikit-learn

---

## Project Structure

```bash
titanic-survival-prediction/
│
├── titanic.ipynb              # Main Jupyter Notebook
├── train.csv                  # Training dataset
├── test.csv                   # Test dataset
├── gender_submission.csv      # Reference output file
├── result.csv                 # Predicted output file
└── README.md                  # Project Documentation
