# demand-forecasting-and-inventory-optimization-engine

## Overview

This project develops a machine learning system for predicting future product demand and supporting inventory optimization decisions.

The goal is to help businesses reduce stockouts, minimize excess inventory, and improve supply chain efficiency through data-driven forecasting.

---

## Problem Statement

Accurate demand forecasting is a major challenge in retail environments due to:

- seasonal patterns
- promotions and discounts
- product differences
- store-level variations
- changing customer behavior

This project uses historical sales data to build predictive models for future demand.

---

## Dataset

The dataset contains retail transaction information including:

- sales history
- product catalog information
- store information
- pricing history
- discount history
- online sales data

Large raw datasets are not included in this repository due to size limitations.

---

## Project Workflow

### 1. Data Exploration

- Understanding sales trends
- Identifying missing values
- Analysing product and store behaviour

### 2. Data Preprocessing

- Data cleaning
- Handling missing values
- Date processing
- Feature preparation

### 3. Feature Engineering

Created features such as:

- lag features
- rolling averages
- time-based features
- promotional indicators

### 4. Machine Learning Models

Models explored:

- Baseline forecasting methods
- Tree-based regression models
- Machine learning forecasting approaches

### 5. Evaluation

Models are evaluated using forecasting metrics such as:

- MAE
- RMSE
- MAPE

---

## Technologies Used

Python

Libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

---

## Project Structure






---

## Future Improvements

- Deploy forecasting API
- Add automated retraining pipeline
- Implement inventory optimization algorithms
- Create interactive dashboard
