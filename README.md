# Used Car Price Prediction

## Overview

This project focuses on predicting the selling price of used cars using Machine Learning.

The goal is to understand how different vehicle and market-related factors influence the resale value of a vehicle and to build a regression model capable of estimating the expected selling price.

The project uses a large real-world used-car dataset and considers factors such as vehicle model, manufacturing year, location, MMR (Manheim Market Report) value, and other relevant features available in the dataset.

## Objectives

- Perform data cleaning and preprocessing on real-world used-car data.
- Explore the dataset and identify important patterns and relationships.
- Analyze the factors that influence used-car selling prices.
- Prepare categorical and numerical features for Machine Learning.
- Build regression models for used-car price prediction.
- Evaluate model performance using appropriate regression metrics.
- Use the trained model to estimate the selling price of a used vehicle.

## Dataset

The project uses a large used-car dataset containing historical information about vehicles and their selling prices.

### Key Features

- Vehicle Model - Make and model information of the vehicle.
- Year - Manufacturing or model year of the vehicle.
- Location - Geographic location associated with the vehicle.
- MMR - Manheim Market Report value representing an estimated market value.
- Selling Price - Actual selling price of the vehicle and the prediction target.

The original dataset is not included in this repository due to its large size.

The notebook contains the data processing and Machine Learning workflow used for the project.

## Exploratory Data Analysis

The project explores:

- Distribution of vehicle selling prices.
- Relationship between vehicle age and selling price.
- Relationship between MMR and selling price.
- Price variation across different vehicle models.
- Price variation across locations.
- Analysis of numerical features.
- Identification and treatment of missing values.
- Detection and analysis of outliers.
- Visualization of important relationships within the dataset.

## Data Preprocessing

The dataset was prepared before applying Machine Learning techniques.

The preprocessing workflow includes:

- Handling missing values.
- Removing or handling irrelevant data.
- Data type conversion where required.
- Handling categorical variables.
- Feature selection.
- Preparing numerical and categorical features.
- Splitting the dataset into training and testing sets.

## Machine Learning

This project treats used-car price prediction as a supervised regression problem.

The model learns the relationship between vehicle characteristics and historical selling prices and uses those relationships to estimate prices for unseen vehicles.

### Prediction Features

The project considers features such as:

- Vehicle Model
- Vehicle Year
- Location
- MMR
- Other relevant vehicle and market features

### Target Variable

Selling Price

## Model Evaluation

The model performance can be evaluated using standard regression metrics such as:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

Model performance values will be added after the final model evaluation.

## Technologies and Libraries

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-learn

### Development Environment

- Jupyter Notebook

## Project Workflow

Raw Dataset  
↓  
Data Understanding  
↓  
Data Cleaning  
↓  
Exploratory Data Analysis  
↓  
Feature Engineering and Selection  
↓  
Data Preprocessing  
↓  
Train-Test Split  
↓  
Model Training  
↓  
Model Evaluation  
↓  
Used-Car Price Prediction

## Repository Structure

```text
Used-Car-Price-Prediction/
│
├── car_price_prediction.ipynb
├── README.md
└── requirements.txt
Used-Car Price Prediction
