# 🏠 House Price Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Linear%20Regression-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Project Overview

This project focuses on predicting house prices using a supervised machine learning approach.  
A Linear Regression model was implemented to estimate housing prices based on multiple numerical features.

The project demonstrates the complete ML workflow including data preprocessing, visualization, model training, and evaluation.

---

## 🛠️ Tech Stack

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📊 Dataset Description

The dataset contains structured housing data including features such as:

- Area
- Number of Bedrooms
- Number of Bathrooms
- Location-related attributes
- Other numerical housing parameters

---

## ⚙️ Machine Learning Workflow

1. Data Collection & Loading  
2. Data Cleaning & Handling Missing Values  
3. Exploratory Data Analysis (EDA)  
4. Feature Selection  
5. Train-Test Split  
6. Model Training using Linear Regression  
7. Model Evaluation  

---

## 📈 Model Performance

The Linear Regression model achieved the following performance metrics:

- **Mean Absolute Error (MAE):** 16,907.50  
- **Mean Squared Error (MSE):** 457,447,410.06  
- **R² Score:** 0.9636  

### 🔎 Interpretation

- The **R² Score of 96.36%** indicates that the model explains most of the variance in housing prices.
- The relatively low **MAE** suggests that predictions are close to actual values on average.
- The model demonstrates strong predictive capability using basic Linear Regression.


## 📊 Data Visualization

- Correlation Heatmap
- Distribution Plots
- Regression Line Visualization

(Matplotlib & Seaborn used for visualization)

---

## ▶️ How to Run

```bash
git clone <your-repo-link>
cd house-price-prediction
pip install -r requirements.txt