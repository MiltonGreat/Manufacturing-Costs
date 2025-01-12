# Manufacturing Cost Prediction

## Overview

This project explores the relationship between production volume and manufacturing costs, leveraging regression models to predict costs based on production volume. By analyzing how scaling production influences costs, this project aims to help manufacturers optimize production and identify economies of scale.

## Problem Statement

Understanding the relationship between production volume and manufacturing costs is crucial for optimizing production and identifying when economies of scale begin to apply. Accurate cost prediction models can assist manufacturers in making data-driven decisions about scaling production and improving operational efficiency.

## Dataset

- **Source**: The dataset contains two columns:
  - `Number_of_Units`: Production volume.
  - `Manufacturing_Cost`: Corresponding manufacturing cost.

- **Statistics**:
  - Number of Instances: 1,000.
  - Average Number of Units: ~4.47.
  - Average Manufacturing Cost: ~40.05.

### Methods

- Regression Models: Applied Linear Regression and Polynomial Regression to predict manufacturing costs based on production volume.
- Sensitivity Analysis: Conducted to identify cost inflection points where economies of scale begin to take effect.
- Visualization: Utilized Tableau to visualize cost trends and production scaling impacts.

### Results

- R² of 0.88: Developed a cost prediction model with a high explanatory power.
- Economies of Scale: Identified production thresholds where economies of scale lead to a 20% cost reduction.
- Recommendations: Informed production scaling decisions based on cost predictions.

### Key Findings:

- Non-linear Relationship: Polynomial regression models captured the non-linear decrease in cost with increased production volume, a hallmark of economies of scale.
- Model Performance: The polynomial regression model outperformed linear regression, improving predictive accuracy and reducing errors.

### Model Evaluation:

 Linear Regression:
  - MAE: 4.51
  - MSE: 35.20
  - R²: 0.57
  
 Polynomial Regression:
  - MAE: 4.37
  - MSE: 33.23
  - R²: 0.59

Residual Analysis:
- Residuals showed no significant patterns, confirming the model assumptions.
- The polynomial regression model better captured the non-linear trend in cost reductions with production scaling.

### Key Insights

1. **Economies of Scale**:
   - The polynomial model indicates a non-linear decrease in cost with increased production volume, a hallmark of economies of scale.

2. **Model Selection**:
   - Polynomial regression improved predictive accuracy, making it a better choice for modeling this dataset.

### Future Directions

- Incorporate external factors like raw material price fluctuations and market demand into the model for more accurate cost predictions.
- Extend the model to predict costs in real-time for dynamic production planning.
- Explore more advanced regression techniques and machine learning models for further optimization.

### Source

https://www.kaggle.com/datasets/vinicius150987/manufacturing-cost
