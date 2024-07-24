# Linear Regression on Car Sales Data

## Project Overview

This project involves analyzing car sales data to predict car prices using linear regression. The dataset includes various features such as year, brand, price, body type, mileage, engine volume, engine type, registration year, and model name. The goal is to build a predictive model that can accurately estimate car prices based on these features.


## Dataset

The dataset contains the following features:

- **Year**: The year the car was manufactured.
- **Brand**: The make of the car.
- **Price**: The selling price of the car.
- **Body Type**: The body type of the car (e.g., sedan, SUV).
- **Mileage**: The mileage of the car.
- **Engine Volume**: The volume of the car's engine.
- **Engine Type**: The type of engine (e.g., petrol, diesel).
- **Registration Year**: The year the car was registered.
- **Model Name**: The model name of the car.

## Installation

To run this project, we will need to install the following dependencies:

- Python 3.7+
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


# Analysis and Methodology
## Data Preprocessing:

## Handle missing values.
- Convert categorical variables to numerical using one-hot encoding.
- Standardize/normalize numerical features.
- Exploratory Data Analysis (EDA):

## Analyze the distribution of features.
- Explore relationships between features and target variable (price).
- Visualize correlations using heatmaps and pair plots.

## Model Building:
- Split the data into training and testing sets.
- Train a linear regression model on the training data.
- Evaluate the model performance on the testing data using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

The linear regression model achieved an R-squared value of 0.85, indicating that the model explains 85% of the variance in car prices.

