# Bike-rental-prediction

## Overview
This repository contains a machine learning model built with XGBoost for predicting bike rental counts 'cnt' on an hourly basis. The model utilizes historical data on various factors such as weather conditions, time of day, and day of the week etc to forecast the number of bike rentals for each hour.

## Dataset
The dataset includes features such as:
- dteday
- Weather conditions (temperature, humidity, windspeed)
- Season 
- Holiday status
- Day of the week, etc

## Model Development
The model development process involves the following steps:
1. **Data Preprocessing**: Cleaning and preprocessing the dataset, including handling missing values, doing feature correlation, encoding categorical variables, and feature scaling.
2. **Feature Engineering**: Creating new features or transforming existing features to improve model performance, eg Lag function.
3. **Model Training**: Splitting the dataset into training and testing sets, and training an XGBoost regression model on the training data, alongside gridseach based hyper-parameter tunning.
4. **Model Evaluation**: Evaluating the trained model's performance on the testing data using evaluation metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R^2).

## Acknowledgements
The dataset used in this project is sourced from [UC Irvine Machine learning repository](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset).

## Author
[*Harsh Shah*]
