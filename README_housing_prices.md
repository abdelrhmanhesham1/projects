# Housing Price Prediction

## Overview
This project builds a machine learning model to predict housing prices using various regression techniques. The dataset is preprocessed, analyzed, and used to train multiple models, including a custom-built Linear Regression, Scikit-Learn's Linear Regression, and Polynomial Regression.

## Features
- **Data Preprocessing**: Handling missing values, duplicate removal, feature engineering, and outlier detection.
- **Exploratory Data Analysis (EDA)**: Correlation analysis, heatmaps, and boxplots.
- **Feature Engineering**: Creating new features to improve model accuracy.
- **Regression Models**:
  - Custom-built Linear Regression
  - Scikit-Learn Linear Regression
  - Polynomial Regression (Degree 3, Ridge Regularization)
- **Model Evaluation**: Mean Absolute Error (MAE) and R-squared score.
- **Visualizations**: Scatter plots, residual plots, and model comparisons.

## Dataset
The dataset (`Housing.csv`) contains various housing attributes, including:
- `price`: The target variable.
- `area`, `bedrooms`, `bathrooms`, `stories`, `parking`: Numerical features.
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`: Categorical features.

## Installation
Ensure you have the following libraries installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn plotly
```

## Data Preprocessing
1. **Load and Explore Data**: Read the dataset, check for missing values, duplicates, and summary statistics.
2. **One-Hot Encoding**: Convert categorical variables into numerical format.
3. **Feature Engineering**: Create new features such as `log_price`, `log_area`, `area_bedrooms`, `bath_stories`, etc.
4. **Outlier Removal**: Using the Interquartile Range (IQR) method to remove extreme values.
5. **Feature Scaling**: Standardization using `StandardScaler`.

## Model Training
### 1. Custom Linear Regression
A linear regression model implemented from scratch using the Normal Equation.

### 2. Scikit-Learn Linear Regression
Using `LinearRegression` from `sklearn.linear_model`.

### 3. Polynomial Regression
- Polynomial transformation of features (degree = 3)
- Regularization using `Ridge` regression.

## Model Evaluation
Models are evaluated using:
- **Mean Absolute Error (MAE)**: Measures prediction error in the original price scale.
- **R-squared Score (R²)**: Indicates the proportion of variance explained by the model.

## Visualization
1. **Feature Correlation Heatmap**: Shows relationships between variables.
2. **Actual vs. Predicted Prices**: Scatter plots comparing different models.
3. **Residual Analysis**: Checks model performance by plotting residuals.



