# Energy Efficiency Dataset - Cooling Load Prediction

## Overview

This repository contains code for predicting cooling load using the Energy Efficiency Dataset (ENB2012_data.xlsx). Three regression models, Lasso regression, Ridge Regression, and Elastic Net regression, were implemented and evaluated based on the mean squared error (MSE).

## Dataset

The Energy Efficiency Dataset is a public dataset from UCI, available [here](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency). The dataset includes 768 samples with 8 features, and the goal is to predict the cooling load (Y2).

## Models

### 1. Lasso Regression
Lasso regression was applied to the dataset to predict the cooling load. The mean squared error (MSE) was used as the performance metric.

### 2. Ridge Regression
Ridge regression was implemented to predict the cooling load, and the model's performance was evaluated using MSE.

### 3. Elastic Net Regression
Elastic Net regression, a combination of L1 and L2 regularization, was employed for cooling load prediction. MSE was used to assess the model's performance.

## Code

The code for implementing and evaluating the models can be found in the Jupyter Notebook file `jmohanty_new_version.ipynb`.

## Performance Metrics

The models were evaluated based on the mean squared error (MSE) using 5-fold cross-validation. The results are as follows:

| Model               | Mean Squared Error |
|---------------------|--------------------|
| Lasso Regression    | \<13.627329\>       |
| Ridge Regression    | \<10.333851\>       |
| Elastic Net Regression | \<18.1189\>       |

## How to Run

1. Install the required packages listed in `requirements.txt`:

   ```bash
   pip install --no-cache-dir -r requirements.txt
   ```