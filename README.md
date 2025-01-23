# MultiModel-HousePricePredictor
# Housing Price Prediction with Machine Learning Models

This project implements and evaluates multiple regression models to predict housing prices using the **USA Housing Dataset**. The objective is to determine the most effective model for accurate price predictions.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models Implemented](#models-implemented)
- [Evaluation Metrics](#evaluation-metrics)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction
Predicting housing prices is a critical task in the real estate industry. This project explores various machine learning models to predict house prices based on multiple features, such as the number of rooms, area population, and others. The results of these models are compared to identify the best approach.

## Dataset
The dataset used is `USA_Housing.csv`, which contains:
- **Features:** Average Income, Number of Rooms, Area Population, etc.
- **Target Variable:** Price
- **Ignored Column:** Address (non-numerical)

## Models Implemented
The following regression models are trained and evaluated:
1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. ElasticNet
5. Polynomial Regression
6. SGD Regressor
7. Artificial Neural Networks (MLP)
8. Random Forest Regressor
9. Support Vector Machines (SVM)
10. LightGBM Regressor
11. XGBoost Regressor
12. K-Nearest Neighbors (KNN)
13. Huber Regressor

## Evaluation Metrics
The models are evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-squared (R²)**

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/housing-price-prediction.git
    cd housing-price-prediction
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Ensure the dataset (`USA_Housing.csv`) is in the root directory.

## Usage
Run the script to train models and save results:
```bash
python model.py
