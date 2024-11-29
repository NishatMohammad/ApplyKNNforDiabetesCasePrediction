# Diabetes Prediction and Abalone Prediction

## Overview  
This repository contains two separate machine learning projects:

1. **Diabetes Prediction**  
   Implements a custom k-Nearest Neighbors (kNN) regression model and logistic regression for predicting the age and presence of diabetes in patients.

2. **Abalone Age Prediction**  
   Uses machine learning techniques to predict the age of abalones based on physical measurements using a regression model.

---

## Part 1: Diabetes Prediction Using kNN

### Highlights  
- **Data Preparation**: The dataset is cleaned and normalized for training the kNN model.  
- **Custom kNN Regression**: Implements a k-Nearest Neighbors (kNN) algorithm to predict the age of diabetes patients based on various features.
- **Model Evaluation**: The model is evaluated using Root Mean Squared Error (RMSE) to assess prediction accuracy.

### Key Functions  
- `knn.reg()`: A custom function to predict the target variable using the kNN algorithm with weighted averaging.  
- `wtd_av()`: Computes the weighted average of k nearest neighbors' values.
- `get_euc_dist()`: Calculates the Euclidean distance between data points for kNN.

---

## Part 2: Abalone Age Prediction Using kNN Regression

### Highlights  
- **Data Preprocessing**: The dataset is cleaned and preprocessed for machine learning, including handling categorical features and normalizing numeric features.  
- **kNN Regression Model**: Implements a k-Nearest Neighbors regression model to predict the age of abalones based on their physical features.
- **Model Evaluation**: The model is evaluated using Mean Absolute Error (MAE) to measure its prediction accuracy.

### Key Functions  
- `predict_age_knn()`: The function uses the kNN algorithm to predict the age of abalones based on features like diameter, height, and weight.
- `mae()`: Calculates the Mean Absolute Error to evaluate the model's accuracy.

---

## Requirements  
- R programming environment  
- Required libraries: `ggplot2`, `dplyr`, `caret`, `e1071`

---

## Author 
Dr. Nishat Fatima Mohammad
