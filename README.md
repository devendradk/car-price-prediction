# Used Car Price Prediction Analysis
## Project Overview
In this project, we dive into a used car dataset originally sourced from Kaggle that includes data on approximately 3 million vehicles. For practicality and processing efficiency, our analysis focuses on a subset of 426K entries from the dataset. The main objective is to uncover the factors that influence the price of used cars, providing actionable insights to a used car dealership client. This understanding will assist the dealership in stock selection and pricing strategy, aligning with what consumers value most in used cars.

## Business Problem to Data Problem Conversion
From a business perspective, the task is to pinpoint the primary determinants of used car pricing. In the CRISP-DM framework, this translates into developing a predictive model.

## Reframing Business Problem into Data Problem
To address the business question through data science, we concoct a regression model that predicts used car prices based on various attributes. The "price" serves as the dependent variable while independent variables include features such as "region", "year", "manufacturer", "model", "condition", "cylinders", "fuel", "odometer", "title_status", "transmission", "VIN", "drive", "size", "type", "paint_color", and "state". Initial data preprocessing steps such as handling missing values, implementing encoding for categorical data, and normalizing/scaling numeric input are fundamental to refine model accuracy.

## Model Selection and Evaluation
We select appropriate machine learning algorithms for a regression problem, considering options like Linear Regression, Decision Trees, Random Forest, or Gradient Boosting Machines. After picking a model, it's trained on a portion of the data and validated on another set to evaluate its accuracy and generalizability.
