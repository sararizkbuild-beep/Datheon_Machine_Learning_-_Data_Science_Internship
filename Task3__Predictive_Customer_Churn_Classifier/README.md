# Task 3: Customer Churn Prediction

## Project Overview

This project focuses on predicting customer churn using machine learning techniques. The objective is to identify customers who are likely to leave a telecommunications company.

## Dataset

- **Dataset:** IBM Telco Customer Churn
- **Number of customers:** 7,043 (before cleaning)
- **Target variable:** Churn
- **Problem type:** Binary Classification

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Jupyter Notebook

## Project Workflow

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Analysis of class imbalance
5. Feature encoding
6. Training and testing data split
7. Class balancing using SMOTE
8. Random Forest model training
9. XGBoost model training
10. Model evaluation and comparison
11. Feature importance analysis

## Machine Learning Models

Two classification algorithms were implemented:

- Random Forest Classifier
- XGBoost Classifier

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Results

The notebook contains the model comparison results and visualizations. These results help identify which algorithm performs better at predicting customer churn.

## Conclusion

This project demonstrates how machine learning can help telecommunications companies identify customers at risk of leaving. By analyzing customer information and predicting churn, businesses can develop targeted retention strategies and improve customer loyalty.

## How to Run

1. Install the required libraries.
2. Open `customer_churn.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook cells in order.
