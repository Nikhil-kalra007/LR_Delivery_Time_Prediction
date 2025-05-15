# LR\_Delivery\_Time\_Prediction

## Overview

This repository contains the solution for the delivery time prediction assignment using Multiple Linear Regression. The project involves analyzing Porter order data to predict delivery times based on multiple features like order details, delivery partner availability, and distance etc.

## Contents
* **LR\_Delivery\_Time\_Prediction.ipynb** — Interactive Jupyter Notebook with code for data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.
* **LR\_Delivery\_Time\_Prediction\_Report.pdf** — Detailed report documenting visualizations, methodologies, insights, model results, and inferences.

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
