# Housing Data Analysis and Regression Modeling

## Project Overview

This project analyzes a housing dataset (`housing.csv`) to understand key features influencing house prices and builds predictive regression models. The analysis covers data exploration, cleaning, visualization, and the application of linear and ridge regression techniques to model the price of houses.

## Features

- **Data Exploration:** Examine data types and statistical summaries to understand dataset structure.
- **Data Cleaning:** Handle missing values and remove unnecessary columns.
- **Visualization:** Use seaborn and matplotlib to create boxplots and regression plots for feature analysis.
- **Regression Models:**
  - Simple Linear Regression using `sqft_living`.
  - Multiple Linear Regression using various features.
  - Polynomial regression with pipeline for feature transformation.
  - Ridge Regression for regularized linear modeling.
- **Model Evaluation:** Evaluate models using the R² score to assess goodness of fit on training and test data.

## Dataset

The dataset used for this project is `housing.csv`, containing real estate data including house features such as bedrooms, bathrooms, floors, waterfront view, and price.

## Installation

To run this project, you need Python 3.x with the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
