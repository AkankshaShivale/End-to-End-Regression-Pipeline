# End-to-End Regression Pipeline

A comprehensive and customizable machine learning pipeline for regression tasks. This project includes data preprocessing, feature selection, model training, and hyperparameter tuning to streamline the process of building and optimizing regression models.

## Features

### *Data Preprocessing*
- Handles missing values with customizable imputation strategies.
- Encodes both numerical and categorical features.
- Supports train-test splitting with user-defined ratios and random states.

### *Feature Reduction*
- Multiple feature reduction options:
  - No Reduction
  - Correlation-Based Selection
  - Tree-Based Feature Selection
  - Principal Component Analysis (PCA)
- Easily configurable to optimize feature sets and improve model performance.

### *Supported Regression Algorithms*
This pipeline supports various regression algorithms, including:
- RandomForestRegressor
- GradientBoostingRegressor
- XGBoost
- LinearRegression, Ridge, Lasso, and ElasticNet
- DecisionTreeRegressor
- SVR (Support Vector Regression)
- SGDRegressor (Stochastic Gradient Descent)
- KNeighborsRegressor (K-Nearest Neighbors)
- ExtraTreesRegressor
- MLPRegressor (Neural Network)

### *Hyperparameter Tuning*
- Performs Grid Search with Cross-Validation to find the best hyperparameters.
- Offers a highly configurable parameter grid for each algorithm.

### *Performance Metrics*
Evaluates models using:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Installation

Follow these steps to set up the project:
### Clone the Repository and Install the required dependencies:
```bash
git clone https://github.com/AkankshaShivale/End-to-End-Regression-Pipeline.git
cd End-to-End-Regression-Pipeline

pip install -r requirements.txt
