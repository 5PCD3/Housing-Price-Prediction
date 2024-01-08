# Housing Price Prediction Model

## Overview

This project implements a machine learning model to predict housing prices based on various features. The model is trained on a dataset containing information about different houses.

## Dataset

The dataset (`data/Housing.csv`) includes the following columns:

- `price`: The target variable representing the price of the house.
- `area`: Area of the house.
- `bedrooms`: Number of bedrooms.
- `bathrooms`: Number of bathrooms.
- `stories`: Number of stories.
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `parking`, `prefarea`: Binary categorical variables indicating the presence or absence of certain features.
- `furnishingstatus`: Categorical variable indicating the furnishing status of the house.

## Data Preprocessing

The dataset undergoes preprocessing to handle missing values, scale numerical features, and encode categorical variables. The preprocessing steps are implemented using scikit-learn pipelines.

## Model Training

The project trains multiple regression models, including Linear Regression, Lasso, Ridge, and ElasticNet. Model evaluation metrics such as RMSE, MAE, and R-squared score are used to assess the performance of each model.

## Usage

1. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
