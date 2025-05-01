# TASK 3: STOCK PREDICTION
## Overview
The objective of this task is to predict sales based on advertising expenditure across three platforms—TV, Radio, and Newspaper. The aim is to uncover insights on which medium has the strongest impact on sales and build a predictive model for future sales.

## Project Details
* Data Components:
  - Advertising spends on TV, Radio, and Newspaper.
  - Sales data as the dependent variable.
* Approach:
  - Performed Exploratory Data Analysis (EDA) to study relationships between advertising channels and sales.
  - Focused on TV spending as the strongest predictor, identified via correlation analysis.
  - Built and trained a Linear Regression model using the Scikit-Learn library.
* Model Training:
  - Data split into 70% training and 30% testing subsets.
  - Linear regression model fitted to predict sales based on advertising data.
    
## Key Features
* Correlation Analysis:
  - TV ad spend showed the strongest positive correlation with sales.
  - Heatmap visualization highlighted relationships among variables.

* Linear Regression Model:
  - Equation: Sales = 7.14 + 0.0547 × TV Spend.
  - Coefficients indicate that for every additional unit spent on TV advertising, sales increase by approximately 0.0547 units.

* Model Performance:
  - Predictions were visualized with a regression line superimposed on scatter plots of actual sales data.
  - Regression analysis confirmed the reliability of TV ad spending as a sales predictor.

* Visualization:
  - Scatter plots of TV, Radio, and Newspaper spends vs. sales.
  - Regression line showing the relationship between TV spending and sales.

### This task successfully demonstrates the application of linear regression for sales prediction, providing actionable insights for effective advertising budget allocation.

  
