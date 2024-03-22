# BigMart Sales Predictor
This project aims to predict the sales of various products in supermarkets using machine learning techniques. The dataset used in this project contains information about different attributes such as branch, customer type, gender, product line, unit price, quantity, tax, and total sales. We'll explore the data, perform data cleaning, visualization, feature engineering, and finally build a machine learning model to predict the sales.

## Dataset
The dataset used in this project contains 1000 entries and 17 columns:

Invoice ID
Branch
City
Customer type
Gender
Product line
Unit price
Quantity
Tax 5%
Total
Date
Time
Payment
cogs
gross margin percentage
gross income
Rating

## Exploratory Data Analysis (EDA)
We perform exploratory data analysis to understand the dataset better. We visualize the data using various plots and charts to identify patterns, trends, and relationships between different attributes.

## Data Cleaning
We check for missing values and drop unnecessary columns. We also handle categorical variables by encoding them appropriately for model training.

## Data Visualization
We visualize the data using seaborn and matplotlib libraries to gain insights into the distribution of various attributes, relationships between variables, and other patterns in the data.

## Feature Engineering
We engineer new features and standardize numerical variables to prepare the data for model training.

## Model Building
We split the data into training and testing sets. We then build a machine learning model using Linear Regression to predict the sales of products based on various attributes.

## Model Evaluation
We evaluate the model using metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE) to assess its performance in predicting sales accurately.

## Conclusion
This project demonstrates the application of machine learning techniques in predicting sales based on various attributes. By leveraging the insights gained from exploratory data analysis and feature engineering, we were able to build a predictive model that can assist in forecasting sales for better inventory management and decision-making in supermarkets.
