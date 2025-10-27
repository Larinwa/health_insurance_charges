# Health Insurance Charges Prediction using Linear Regression

## Overview
This project applies Linear Regression to predict health insurance charges  based on individual demographic and lifestyle attributes.  
It demonstrates data preprocessing, encoding categorical variables, model training, and performance evaluation.

## Objectives
- Explore the relationships between features like age, BMI, and smoking habits and insurance charges  
- Train a regression model to predict charges  
- Evaluate model performance using MSE and R²  

## Software requirements, Tools & Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly, Google colab.

## Data Description
The dataset (`insurance.csv`) contains 1338 rows and 7 features:
* age – Age of primary beneficiary  
* sex  – Gender
* bmi** – Body mass index  
* children  – Number of dependents  
* smoker  – Whether the person is a smoker  
* region  – Residential area  
* charges  – Medical cost billed by health insurance  

## Key Steps
1. Data Cleaning – Checked for missing values and data types  
2. Encoding – Applied One-Hot Encoding to nominal categorical variables  
3. Model Training – Linear Regression model using 80/20 train-test split  
4. Evaluation – Calculated MSE and R² to measure performance  

## Results
- Mean Squared Error (MSE): 6233.40  
- R² Score: 0.7513  
- The model explains ~75% of the variance in insurance charges.


## Insights
- Smoking status and BMI strongly influence insurance charges.  
- Age also contributes significantly to cost variation.  
- Further model improvements can include polynomial regression or regularization.


## 📁 Repository Structure
