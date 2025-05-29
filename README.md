# Linear Regression - California Housing Dataset

## Overview

This project demonstrates how to implement and evaluate a Linear Regression model using the California Housing dataset. The goal was to predict median house values based on features like median income, average rooms, and geographic location.

## Objectives

- Load and explore a real-world regression dataset
- Train a Linear Regression model using scikit-learn
- Evaluate model performance using MAE, MSE, and R²
- Interpret coefficients and plot actual vs. predicted values
- Reflect on model accuracy and limitations

## Files Included

- `Day3_LinearRegression.ipynb`: Jupyter Notebook with all steps
- `README.md`: Project overview and summary

## Dataset

The dataset used in this project is the **California Housing Dataset**, originally derived from the 1990 U.S. Census. It is available directly through `sklearn.datasets` and is commonly used for regression tasks in machine learning.

### Source
The dataset is built into `scikit-learn` and can be loaded using:
```python
from sklearn.datasets import fetch_california_housing
```

## Key Insights

- `MedInc` (median income) had the strongest positive effect on housing value
- Geographic features (`Latitude`, `Longitude`) captured important location trends
- The model performed well overall but showed greater prediction error at higher price ranges

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score (Coefficient of Determination)

## Conclusion

Linear Regression was effective for capturing main trends in the data. While predictions were accurate for typical homes, high-value predictions had more error. Future tasks may explore more advanced models to improve performance.
