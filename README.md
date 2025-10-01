CUSTOMER INSIGHTS AND FRAUD PREDICTION

## Overview

This project uses **machine learning** to detect fraudulent transactions and generate insights from customer transaction data. By analyzing transaction patterns, we aim to identify high-risk transactions and understand the features driving fraud.  

The core model used is **XGBoost**, and the project includes data preprocessing, model training, evaluation, and feature importance analysis.  

---

## Features

- **Fraud Detection**: Train a model to classify transactions as fraudulent or non-fraudulent.  
- **Feature Importance Visualization**: Identify which features have the most impact on predictions.  
- **Data Insights**: Explore transaction distributions and correlations.  
- **High-Risk Transaction Flagging**: Automatically highlight transactions with a high probability of fraud.  

---

## Data

The project uses a **credit card transactions dataset** with the following structure:

- Features: `Time, V1–V28, Amount`  
- Target: `Class` (0 = Non-Fraud, 1 = Fraud)  

No missing values exist in the dataset, and all features are numeric.  

---

## Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/JoelJoyston0705/Customer-Insights-Fraud-Prediction.git
cd Customer-Insights-Fraud-Prediction
pip install -r requirements.txt
