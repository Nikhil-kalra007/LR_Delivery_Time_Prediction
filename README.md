# LR\_Delivery\_Time\_Prediction

## Overview

This repository contains the solution for the delivery time prediction assignment using Multiple Linear Regression. The project involves analyzing Porter order data to predict delivery times based on multiple features like order details, delivery partner availability, and distance etc.

## Contents
- **LR_Delivery_Time_Prediction_Nikhil_Kalra.zip**  
  └── Contains:  
  &nbsp;&nbsp;&nbsp;&nbsp;• `LR_Delivery_Time_Estimation_Starter_Nikhil_Kalra.py` – Python script with the full model pipeline  
  &nbsp;&nbsp;&nbsp;&nbsp;• `LR_Delivery_Time_Prediction_Nikhil_Kalra.pdf` – Report documenting methodology, visualizations, insights, and results

- **Dataset File** – Provided separately outside the ZIP (ensure it's placed in the correct directory as specified in the code)

## Approach

* Data cleaning and handling outliers
* Exploratory Data Analysis for insights on data distribution and feature relationships
* Feature scaling and transformation (sin/cos encoding of hour feature)
* Linear Regression model training and evaluation
* Residual analysis and multicollinearity checks
* Recursive Feature Elimination (RFE) for feature selection
* Interpretation of coefficients (scaled and unscaled)

## How to Run

1. Clone the repository
2. Open and run the Jupyter Notebook to reproduce analysis and results
3. Review the PDF report for detailed explanations and visual insights

## Key Insights

* Delivery time is strongly influenced by features such as subtotal, distance, and the number of outstanding orders.
* Some multicollinearity exists among dasher-related variables, but model accuracy remains strong.
* Residual plots indicate some heteroscedasticity, suggesting potential improvements with more advanced models.
