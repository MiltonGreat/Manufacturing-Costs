# Manufacturing Cost Prediction Based on Production Volume

## Overview

This project explores the relationship between production volume and manufacturing costs, utilizing both linear regression and polynomial regression models to predict costs based on the number of units produced. The goal is to identify patterns in how scaling production affects costs and provide insights that help manufacturers optimize their operations and identify economies of scale.

## Problem Statement

Accurate predictions of manufacturing costs are essential for manufacturers aiming to scale production efficiently. By understanding how production volume impacts costs, businesses can make data-driven decisions to optimize operational efficiency and minimize costs. This project focuses on developing a model that helps predict manufacturing costs as production volume changes, providing valuable insights for cost optimization strategies.

## Dataset

- **Source**: The dataset contains two columns:
  - `Number_of_Units`: Production volume.
  - `Manufacturing_Cost`: Corresponding manufacturing cost.

- **Statistics**
  - Number of Instances: 1,000.
  - Average Number of Units: ~4.47.
  - Average Manufacturing Cost: ~40.05.

### Methods

- Regression Models: Applied Linear Regression and Polynomial Regression to predict manufacturing costs based on production volume.
- Polynomial Regression: A more flexible model used to capture non-linear relationships in cost prediction, helping identify economies of scale where cost reductions become more pronounced as production scales up.

### Results

- Linear Regression Model Evaluation: MAE: 4.51, MSE: 35.20, R²: 0.57 (57% of variance explained by the model)
- Polynomial Regression Model Evaluation: MAE: 4.37, MSE: 33.23, R²: 0.59 (59% of variance explained by the model)
- 
### Key Insights

- Non-linear Relationship: Polynomial regression models captured the non-linear decrease in cost with increased production volume, a hallmark of economies of scale.
- Model Performance: The polynomial regression model outperformed linear regression, improving predictive accuracy and reducing errors.
- Extrapolation Issues: While the polynomial model fits the data well within the range of observed production volumes, it can produce unrealistic predictions outside this range, such as negative costs for very high production volumes.

### Key Findings

1. **Economies of Scale**
   - The polynomial model indicates a non-linear decrease in cost with increased production volume, a hallmark of economies of scale.

2. **Model Performance**
   - The polynomial regression model's higher R² value suggests it explains more variance in manufacturing costs compared to the linear regression model, making it a more accurate predictive tool.

### Source

https://www.kaggle.com/datasets/vinicius150987/manufacturing-cost
