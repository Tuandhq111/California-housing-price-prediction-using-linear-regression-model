# California Housing Price Prediction using Linear Regression Model

This project aims to predict housing prices in California using a linear regression model. The dataset used for this project is the California Housing Dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we use a linear regression model to predict housing prices based on various features such as median income, house age, and geographical location. The project includes data preprocessing, model training, and evaluation.

## Dataset

The dataset used in this project is the California Housing Dataset, which contains information about various houses in California. The dataset includes features such as median income, house age, average rooms, average bedrooms, population, households, latitude, and longitude.

longitude: Longitude coordinate of the housing unit.

latitude: Latitude coordinate of the housing unit.

housing_median_age: Median age of the housing units in the area.

total_rooms: Total number of rooms in the housing unit.

total_bedrooms: Total number of bedrooms in the housing unit.

population: Total population in the area.

households: Total number of households in the area.

median_income: Median income of households in the area (scaled).

median_house_value (Target): Median value of housing units in the area (in USD)
## Methodology
1. Data Preprocessing:

Handle missing values (e.g., imputation).

Normalize or scale numerical features.

Encode categorical variables (if applicable).
2. Exploratory Data Analysis (EDA):

Analyze feature distributions.

Identify correlations between features and the target variable.
Model Development:

3. Split the dataset into training and testing sets.

Train a Linear Regression model using the training set.

Evaluate model performance using metrics like Mean Squared Error (MSE) and R-squared.

4. Model Optimization:

Experiment with feature engineering.

Optimize hyperparameters for improved accuracy.
