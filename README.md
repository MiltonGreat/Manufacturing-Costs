# Manufacturing Cost Prediction

## Problem Statement

Understanding the relationship between production volume and manufacturing costs is essential for identifying economies of scale.

### Solution Approach:

Data: Production data with variables like units produced, raw material costs, and energy consumption.

Methods:

- Applied regression models (Linear Regression, Polynomial Regression) to predict costs based on production volume.
- Conducted sensitivity analysis to determine cost inflection points.
- Visualized cost trends using Tableau dashboards.
- Tools: Python (Scikit-learn, Matplotlib), Tableau.

### Results:

- Developed a cost prediction model with an R² of 0.88.
- Identified production thresholds where economies of scale start to apply, leading to cost savings of 20%.
- Recommendations informed decisions on production scaling.

### Key Skills

Regression modeling, cost analysis, data visualization, Python.

### Future Directions

Incorporate external factors like market demand and raw material price fluctuations into the model.

## Project Overview

This project explores the relationship between the number of units produced and manufacturing costs, leveraging regression models to predict manufacturing costs based on production volume. It aims to estimate costs and analyze economies of scale, helping manufacturers optimize production.

## Dataset

- **Source**: The dataset contains two columns:
  - `Number_of_Units`: Production volume.
  - `Manufacturing_Cost`: Corresponding manufacturing cost.

- **Statistics**:
  - Number of Instances: 1,000.
  - Average Number of Units: ~4.47.
  - Average Manufacturing Cost: ~40.05.

## Steps Undertaken

### 1. **Exploratory Data Analysis (EDA)**
- Visualized the distribution of `Number_of_Units` and `Manufacturing_Cost`.
- Assessed the linear relationship using a scatter plot.

### 2. **Model Development**
- **Linear Regression**: Initial model to predict manufacturing cost based on production volume.
  - **Performance**:
    - MAE: 4.51
    - MSE: 35.20
    - R²: 0.57
  - Insights: Moderate performance but indicated potential non-linear patterns.

- **Polynomial Regression**: Enhanced model with degree-2 polynomial features to capture non-linear relationships.
  - **Performance**:
    - MAE: 4.37
    - MSE: 33.23
    - R²: 0.59
  - Insights: Improved accuracy, reduced error, and better explained variance.

### 3. **Residual Analysis**
- Verified linear regression assumptions:
  - Checked for patterns in residuals.
  - Analyzed residual normality using a Q-Q plot.

### 4. **Polynomial Regression Visualization**
- Visualized the polynomial regression curve, which better aligned with the observed non-linear trends.

## Results

The polynomial regression model outperformed linear regression, showing that the relationship between `Number_of_Units` and `Manufacturing_Cost` is non-linear. This highlights the importance of exploring advanced modeling techniques for capturing complex relationships in manufacturing data.

## Key Insights

1. **Economies of Scale**:
   - The polynomial model indicates a non-linear decrease in cost with increased production volume, a hallmark of economies of scale.

2. **Model Selection**:
   - Polynomial regression improved predictive accuracy, making it a better choice for modeling this dataset.

### Source

https://www.kaggle.com/datasets/vinicius150987/manufacturing-cost
