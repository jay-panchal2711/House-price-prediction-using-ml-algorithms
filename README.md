# House Price Prediction Using Multiple Regression Techniques

## Overview
This project predicts house prices using various machine learning regression techniques. 
It leverages multiple features such as area, number of bedrooms, location score, and others 
to estimate the housing price accurately.

## Dataset
The dataset contains **500 rows and 12 columns**, including:
- ID
- SquareFeet
- NumBedrooms
- NumBathrooms
- NumFloors
- YearBuilt
- HasGarden
- HasPool
- GarageSize
- LocationScore
- DistancetoCenter
- Price

## Data Preprocessing
- Removed unnecessary columns (like ID)
- Handled missing values if any
- Created new feature **Age = CurrentYear - YearBuilt**
- Split data into **80% training** and **20% testing**
- Applied **StandardScaler** for normalization

## Algorithms Used
- Multiple Linear Regression
- Lasso Regression
- Ridge Regression
- ElasticNet Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors (KNN) Regressor

## Model Evaluation
| Model | R² Score |
|--------|-----------|
| Multiple Linear Regression | 0.9797 |
| Ridge Regression | 0.9796 |
| Lasso Regression | 0.9797 |
| ElasticNet Regression | 0.9796 |
| Decision Tree Regressor | 0.9761 |
| Random Forest Regressor | 0.8565 |
| KNN Regressor | 0.8565 |

## Insights
Linear regression-based models (Lasso, Ridge, ElasticNet) provided the best accuracy 
with R² ≈ 0.98. This indicates strong linear relationships between the input features 
and the target variable (Price).

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Project Workflow
1. Data Collection and Cleaning  
2. Feature Engineering  
3. Data Normalization  
4. Model Training  
5. Evaluation and Comparison  
6. Result Visualization  

## Results
Linear models significantly outperformed non-linear models for this dataset, 
demonstrating that features such as square footage and location have predictable, 
proportional effects on pricing.

## Author
Developed by Jay Panchal

Email - panchaljay2711@gmail.com

LinkedIn - https://www.linkedin.com/in/jay-panchal-396443176

Github - https://github.com/jay-panchal2711
'''
