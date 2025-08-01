# Appliance-Energy-Consumption-Prediction

A machine learning-based regression project designed to predict total energy usage based on sensor and environmental data. This solution helps understand power consumption patterns and supports smart energy management decisions.

## 📌 Introduction

This project uses statistical and machine learning techniques to estimate total energy consumption from a variety of features including temperature, humidity, and other environmental and operational parameters. The approach includes data cleaning, feature engineering, model selection, and performance evaluation.


## 🚀 Key Features

- ✅ Load and process sensor data from CSV
- ✅ Identify and remove irrelevant features
- ✅ Convert date columns to datetime format
- ✅ Handle missing values
- ✅ Engineer time-based features (e.g., hour, day)
- ✅ Encode categorical variables
- ✅ Train and evaluate multiple regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Gradient Boosting Regressor
- ✅ Evaluate with:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score


## 🛠 Technologies Used

| Technology         | Purpose                                      |
|-------------------|-----------------------------------------------|
| Python            | Core programming language                     |
| Pandas, NumPy     | Data manipulation and preprocessing            |
| Matplotlib, Seaborn | Data visualization                          |
| Scikit-learn      | Regression models and metrics                  |
| Jupyter Notebook / Python Script | Interactive development & automation |


## ⚙ Workflow Overview

1. **Data Loading**  
   Load energy data from CSV file

2. **Data Cleaning**
   - Drop irrelevant columns  
   - Convert datetime strings to actual `datetime` type  
   - Handle missing values  

3. **Feature Engineering**
   - Extract date parts (hour, day, month)  
   - Encode categorical features  
   - Create correlation heatmaps  

4. **Modeling**
   - Split into train/test sets  
   - Train models (Linear, Tree, Gradient Boosting)  
   - Evaluate performance using multiple metrics

5. **Model Comparison**
   - Compare all models' scores to select the best performer


## 📈 Model Evaluation (Example Output)

| Model                    | MAE   | RMSE  | R² Score |
|--------------------------|-------|-------|----------|
| Linear Regression        | 0.68  | 0.89  | 0.78     |
| Decision Tree Regressor  | 0.42  | 0.61  | 0.91     |
| Gradient Boosting        | 0.38  | 0.56  | 0.93     |

## Contributor

**V.Venkata Sravani**

## Feel free to reach out for any questions or collaboration opportunities!
