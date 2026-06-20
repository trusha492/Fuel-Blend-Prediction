# Fuel Blend Properties Prediction

## Overview

Fuel Blend Properties Prediction is a machine learning project that predicts multiple fuel blend properties from chemical composition data. The project explores and compares different machine learning and deep learning models to identify the most effective approach for accurate prediction.

## Objective

The objective of this project is to develop predictive models capable of estimating fuel blend properties using historical training data. Multiple algorithms were evaluated and compared to improve prediction accuracy.

## Dataset

The dataset contains fuel blend composition data and corresponding target properties.

Files:

* train.csv – Training dataset
* test.csv – Test dataset
* sample_solution.csv – Sample submission format

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* LightGBM
* TensorFlow
* Optuna
* Matplotlib

## Models Implemented

### XGBoost

* Gradient boosting-based regression model
* Feature importance analysis
* Hyperparameter tuning

### LightGBM

* Efficient gradient boosting framework
* Fast training and prediction

### Random Forest

* Ensemble learning using multiple decision trees
* Robust performance on tabular data

### Neural Network

* Deep learning model developed using TensorFlow
* Multi-target regression prediction

## Methodology

1. Data Preprocessing

   * Missing value handling
   * Feature scaling
   * Data cleaning

2. Feature Engineering

   * Feature selection
   * Data transformation

3. Model Training

   * XGBoost
   * LightGBM
   * Random Forest
   * Neural Network

4. Model Evaluation

   * Mean Absolute Error (MAE)
   * Cross Validation
   * Performance Comparison

5. Ensemble Learning

   * Combined predictions from multiple models
   * Improved prediction stability and accuracy

## Project Structure

Fuel-Blend-Prediction/

├── notebooks/
│   ├── Fuel_Blend.ipynb
│   ├── XGBoost.ipynb
│   ├── RG_&_NN.ipynb
│   └── compare.ipynb
│
├── dataset/
│   ├── train.csv
│   ├── test.csv
│   └── sample_solution.csv
│
├── outputs/
│   ├── submission_xgb.csv
│   ├── submission_rf.csv
│   ├── submission_nn.csv
│   └── ensemble.csv
│
├── requirements.txt
└── README.md

## Key Features

* Multi-model machine learning pipeline
* Hyperparameter optimization
* Ensemble learning
* Model comparison and evaluation
* Fuel property prediction

## Future Improvements

* Advanced feature engineering
* Additional ensemble techniques
* Automated model selection
* Deployment using FastAPI

## Author

Trusha Tembhurne
AI & ML Engineer
