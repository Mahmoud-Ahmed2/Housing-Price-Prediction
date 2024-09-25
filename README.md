# Housing-Price-Prediction

This project aims to predict housing prices using multiple linear regression techniques, including regularized methods like Ridge and Lasso regression. The dataset contains various features such as square footage, the number of bedrooms, bathrooms, neighborhood, and the age of the building.

## Project Structure
Housing_Price_Prediction_Notebook.ipynb: The main Jupyter notebook containing the code, explanations, and visualizations for the project.
Project Overview
### 1. Data Preprocessing:
Handling missing values and encoding categorical features.
Transforming YearBuilt into BuildingAge by calculating the difference between the current year and the year built.
### 2. Feature Engineering:
Creating dummy variables for categorical features like Neighborhood.
Normalizing features to ensure uniform scaling.
### 3. Modeling:
Implementing basic Linear Regression as a baseline.
Utilizing Ridge and Lasso Regression to regularize and prevent overfitting.
Using a pipeline for normalization and regression to streamline the process.
### 4. Evaluation:
Calculating Root Mean Squared Error (RMSE) and R² Score for each model.
Visualizing the effect of alpha in Ridge and Lasso regression on RMSE and R² Score.
