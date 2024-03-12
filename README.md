# Yelp Data Mining Case Study

## Overview
This repository contains a case study on data mining using Yelp data. The goal of this project is to explore Yelp datasets, identify important insights, and solve a data science problem using machine learning techniques. The project involves data collection, preprocessing, exploration, and modeling to address the selected problem.

## Problem Statement
The problem addressed in this case study is to predict a business's profitability and popularity based on various characteristics extracted from Yelp data. By analyzing business attributes such as category, location, and check-in trends, the aim is to develop a machine learning model that can forecast the number of check-ins a business might receive, which is indicative of its popularity and potential profitability.

## Importance and Interest
Understanding the factors that contribute to a business's success and popularity on Yelp is crucial for both business owners and consumers. Business owners can use these insights to make informed decisions about marketing strategies, resource allocation, and overall business performance. Consumers, on the other hand, can benefit from accurate predictions of a business's popularity when making choices about where to dine, shop, or socialize. Additionally, policymakers and urban planners can leverage this information to make informed decisions about zoning laws, infrastructure development, and community engagement programs.

## Data Collection and Processing
- Two datasets are used: Business data and Checkin data.
- The data is loaded from JSON files and converted to CSV format for easier handling.
- Basic preprocessing steps are performed, including merging datasets, dropping unnecessary columns, and handling missing values.

## Data Exploration
1. **Most Popular Business Categories**: The top 10 most popular business categories are identified by counting the number of businesses in each category.
2. **Most Popular Business Objects**: The top 10 most popular business objects/IDs are determined based on the total number of check-ins for each business.
3. **Other Explorations**: Additional exploratory analyses include visualizations of rating distributions, review counts vs. ratings scatter plot, and the most popular categories by city.

## Solution Approach
The solution to the problem involves a data science approach consisting of several steps:
1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Model Selection
5. Model Training and Evaluation
6. Prediction

## Implementation in Python
Python code is provided to implement the solution approach. This includes:
- Loading and preprocessing data
- Model selection (Linear Regression, Decision Tree Regressor, Random Forest Regressor)
- Model training, evaluation, and prediction
- Results summary and visualization (MSE calculation, histogram plots, feature importance plots)

## Results and Visualization
The results of model evaluation, including Mean Squared Error (MSE) for each model, are presented. Histogram plots visualize the distribution of actual and predicted ratings, while feature importance plots demonstrate the significance of input features in predicting business success.

## Conclusion
This case study demonstrates the application of data mining techniques to extract insights from Yelp data and solve a real-world problem related to business popularity prediction. By leveraging machine learning models and exploratory data analysis, valuable insights can be obtained to inform business decisions and enhance consumer experiences.

## Contributors
- Shraddha Uday Teredesai
