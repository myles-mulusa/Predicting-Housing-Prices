# Phase 2 Project 


## House Sales Linear Regression Analysis

This repository contains the code and documentation for a project focused on utilizing multiple linear regression modeling to analyze house sales in a King county, Washington DC, where the housing market is undergoing substantial challenges. This project aims to predict house prices using linear regression based on various features such as the number of bedrooms, bathrooms, square footage, and location. The dataset used for this project contains information about houses sold, including their features and sale prices to provide insights and recommendations to stakeholders, particularly Real estate agents, Property owners, Homebuyers, Investors and Regulatory bodies, regarding how home renovations can potentially increase the estimated value of their properties and foster a more transparent, efficient, and competitive housing market in the county.


# Table of Contents

Overview
Dataset
Approach
Files Included
Dependencies
Usage
Contributing
License


## Overview

The primary stakeholder for this project is a real estate agency seeking to advise homeowners on renovations that could positively impact the value of their homes. The business problem revolves around the need to provide actionable recommendations based on quantitative analysis, specifically through regression modeling, to guide homeowners in making informed decisions about home improvements. 


## Dataset

While the dataset includes several columns, we will focus on a subset of features deemed relevant to predicting home values through regression analysis.
We start by preprocessing the dataset, which involves handling missing values, scaling numerical features, and encoding categorical variables. We then train a linear regression model using scikit-learn.


## Approach

Data Understanding: Explore the dataset to understand the features and their potential impact on home values. Identify any data quality issues or limitations that may need to be addressed.

Data Preparation: Clean the data by handling missing values or outliers and perform any necessary feature engineering to prepare the dataset for regression modeling.

Model Training: We train a linear regression model using the 'LinearRegression' class from scikit-learn. The training data is preprocessed by scaling numerical features and encoding categorical variables. After training the model, we make predictions on the test data and evaluate its performance using metrics such as mean absolute error.

Model Evaluation: We evaluate the trained model's performance using mean absolute error (MAE) and R-squared score. The MAE measures the average absolute difference between the predicted and actual house prices, while the R-squared score indicates the proportion of variance in the target variable explained by the model.

Dealing with Categorical Data: Categorical variables are one-hot encoded before training the model. This ensures that categorical features are represented as binary vectors, making them suitable for linear regression.

Regression Results: Interpret the coefficients of the regression models to understand the impact of each feature on home values. Translate the findings into actionable insights for stakeholders.


## Files Included
kc_house_data.csv: The dataset containing information about house sales in King County.
student.ipynb: Jupyter Notebook containing the analysis process, including data exploration, preparation, modeling, and interpretation of results.
README.md: This file providing an overview of the project, its objectives, and the approach taken.
requirements.txt: List of Python dependencies required to run the code.
Other supporting files and resources.


## Dependencies
Python 3.x
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Install the required dependencies using the following command:
pip install scikit-learn pandas numpy


## Usage

1. Clone this repository:
git clone https://github.com/FridaOyucho/Predicting-Housing-Prices.git

2. Navigate to the project directory:
cd dsc-phase-2-project-v2-3

3. Install the required dependencies:
pip install -r requirements.txt

Open and run the Jupyter student.ipynb to explore the analysis and results.


## Authors
[Frida Oyucho]
[Thomas Otiende]
[Yvonne Kirigo]
[Sonia Ojay]
[Charles Egambi]
[Myles Mulusa]


## Contributing
Contributions to this project are welcome. If you have suggestions for improvement or encounter any issues, please open an issue or submit a pull request.


## License

This project is licensed under the MIT License - see the [LICENSE] file for details.
