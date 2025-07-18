###  Sales Prediction using Linear Regression

##  Project Overview

This project focuses on predicting total sales using features like money spent on **TV, radio, and newspaper advertising**. Linear Regression is applied to model the relationship between marketing expenditure and resulting sales.

##  Problem Statement

> Predict total product sales based on the budget allocated to various advertisement channels: **TV**, **Radio**, and **Newspaper**.

##  Dataset Information

* **Source**: `Advertising.csv`
* **Features**:
  * `TV`: Advertising budget spent on TV (in thousands of dollars)
  * `Radio`: Advertising budget spent on Radio
  * `Newspaper`: Advertising budget spent on Newspaper
* **Target**:
  * `Sales`: Units sold (in thousands)

##  Steps Performed

1. **Data Loading & Exploration**

   * Loaded dataset and performed basic summary statistics.
   * Checked for null values and data types.

2. **Exploratory Data Analysis (EDA)**

   * Used pair plots and correlation heatmaps to understand relationships.
   * Visualized feature-target trends.

3. **Preprocessing**

   * Removed outliers using IQR method (if needed).
   * Normalized/standardized features (optional based on model).

4. **Model Building**

   * Trained a **Linear Regression** model using Scikit-learn.
   * Split dataset into training and testing subsets.

5. **Evaluation**

   * Evaluated model performance using:

     * R² Score
     * Mean Absolute Error (MAE)
     * Mean Squared Error (MSE)
     * Root Mean Squared Error (RMSE)

##  Results

* **Model shows strong correlation** between TV/Radio spends and sales.
* Achieved good predictive performance with low RMSE on test data.
* Newspaper advertising showed **less impact** on sales prediction.

##  Key Learnings

* Linear regression works well when predictors are linearly correlated with the target.
* Visual analysis helps identify impactful variables.
* Not all features equally contribute to predictive power.
