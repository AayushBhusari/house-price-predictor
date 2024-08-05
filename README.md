# House Prices Prediction

This project demonstrates the process of predicting house prices using a Random Forest Regressor. The goal is to predict the sale prices of houses based on various features such as lot area, year built, floor area, number of bathrooms, bedrooms, and total rooms above ground.

## Table of Contents

- [Introduction](#introduction)
- [Skills Learned](#skills-learned)
- [Tools Used](#tools-used)
- [Data Description](#data-description)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Usage](#usage)
- [Results](#results)

## Introduction

Predicting house prices is a common task in data science and machine learning. This project uses the Ames Housing dataset, which contains features related to residential homes in Ames, Iowa. By using these features, we aim to build a model that accurately predicts the sale price of a house.

## Skills Learned

- **Data Preprocessing**: Loading and preparing data for model training.
- **Feature Selection**: Identifying important features that influence house prices.
- **Model Training**: Training a Random Forest Regressor on the dataset.
- **Model Evaluation**: Evaluating the model's performance using Mean Absolute Error (MAE).
- **Prediction**: Making predictions on new data and exporting the results.

## Tools Used

- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning algorithms and model evaluation.
- **Random Forest Regressor**: For regression tasks.

## Data Description

The dataset used in this project is the Ames Housing dataset. The main features used for prediction include:

- **LotArea**: Lot size in square feet.
- **YearBuilt**: Original construction date.
- **1stFlrSF**: First floor square feet.
- **2ndFlrSF**: Second floor square feet.
- **FullBath**: Full bathrooms above grade.
- **BedroomAbvGr**: Number of bedrooms above grade.
- **TotRmsAbvGrd**: Total rooms above grade (excluding bathrooms).

## Model Training and Evaluation

### Import Libraries

```python
import pandas as pd
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_absolute_error
from sklearn.model_selection import train_test_split
```
