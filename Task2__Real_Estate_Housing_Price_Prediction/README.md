
# Task 2: Real Estate Housing Price Prediction

## Internship
Datheon - Machine Learning & Data Science Internship

## Project Overview
This project develops a machine learning regression pipeline to predict median housing values using the California Housing dataset.

The objective is to estimate house values based on housing characteristics, household information and geographical location.

## Dataset
- Source: California Housing Dataset
- Format: CSV
- Samples: 20,640
- Original features: 9 input features
- Target: median_house_value

Dataset source:
https://raw.githubusercontent.com/ageron/handson-ml2/master/datasets/housing/housing.csv

## Feature Engineering
The following interaction and ratio features were created:
- Rooms per household
- Bedrooms per room
- Population per household
- Income multiplied by rooms per household

## Data Preprocessing
- Missing-value imputation using median and most frequent strategies.
- Numerical feature standardization.
- Categorical encoding using OneHotEncoder.
- Correlation analysis.
- Multicollinearity analysis using VIF.

## Machine Learning Models
1. Ordinary Least Squares (OLS)
2. Ridge Regression (L2)
3. Lasso Regression (L1)

## Hyperparameter Optimization
GridSearchCV with 5-fold cross-validation was used to optimize Ridge and Lasso regularization parameters.

## Evaluation Metrics
- RMSE: Root Mean Squared Error
- MAE: Mean Absolute Error
- R2: Coefficient of Determination

## Visualizations
- House value distribution
- Correlation heatmap
- VIF analysis
- Actual vs predicted values
- Residual distribution
- Residuals vs predicted values

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## How to Run

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

Make sure the dataset is located at:

data/housing.csv

Open housing_prediction.ipynb in Jupyter Notebook or Visual Studio Code.

Run all cells from beginning to end.

## Conclusion
This project demonstrates the application of regression algorithms to housing price prediction. It compares OLS, Ridge and Lasso while addressing missing values, feature engineering, multicollinearity and model optimization.
