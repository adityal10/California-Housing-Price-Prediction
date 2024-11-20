# California Housing Price Prediction

This project focuses on predicting housing prices in California using machine learning techniques. By leveraging historical data, the model aims to predict median house prices based on features such as location, number of rooms, population, and more. 

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Features](#features)
4. [Modeling](#modeling)
5. [Installation and Usage](#installation-and-usage)
6. [Results](#results)
7. [Future Improvements](#future-improvements)
8. [Contributing](#contributing)
9. [License](#license)

---

## Project Overview

The California housing price prediction project is designed to analyze and predict housing prices based on publicly available data. The main objectives include:

- Understanding the dataset through exploratory data analysis (EDA).
- Preparing data with appropriate feature engineering techniques.
- Building machine learning models for accurate predictions.
- Evaluating model performance using standard metrics.

---

## Dataset

The dataset used in this project is the **California Housing Dataset** from [Scikit-learn](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset). 

### Key Details:

- **Source:** California Census data.
- **Features:** Numeric features including median income, house age, population, and more.
- **Target:** Median house value (in 100,000s).

---

## Features

Below are the key features used in the project:

- `longitude` and `latitude`: Geographical coordinates of the area.
- `housing_median_age`: Median age of houses in the area.
- `total_rooms` and `total_bedrooms`: Total rooms and bedrooms in the area.
- `population`: Total population in the area.
- `households`: Total households in the area.
- `median_income`: Median income of the residents.
- `ocean_proximity`: Proximity of houses to the ocean (categorical).

---

## Modeling

The project involves the following steps for building and evaluating predictive models:

1. **Data Preprocessing:**
   - Handling missing values.
   - Feature scaling and transformation.
   - Encoding categorical variables.

2. **Exploratory Data Analysis (EDA):**
   - Visualization of feature distributions.
   - Correlation analysis.

3. **Model Training:**
   - Implementing multiple regression models, including:
     - Linear Regression
     - Random Forest
     - Gradient Boosting Machines
   - Hyperparameter tuning using GridSearchCV.

4. **Evaluation:**
   - Metrics used:
     - Mean Absolute Error (MAE)
     - Root Mean Square Error (RMSE)
     - R² Score

---

## Installation and Usage

### Prerequisites:
Ensure the following are installed:
- Python 3.8 or higher
- Required libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, and `seaborn`
