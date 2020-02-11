# Real Estate Price Prediction

## Introduction
Prediction of housing prices based on features such as nearby amenities, floor area, schools, etc. 

## Description
This compilation of notebooks details a machine learning workflow from start to finish:

### 1. Data Exploration
1. Exploring numerical features using histograms
2. Exploring distributions of categorical features
3. Exploring relationships between categorical and numerical features
4. Exploring correlations between numerical features using correlation matrices and heatmaps

### 2. Data Cleaning
1. Drop duplicated observations
2. Fixing of structural errors (misspelt class labels, replacing NaNs with values, and 'suspicious' outliers). Finding outliers will be easier by observing violin plots
3. Filling up missing categorical data
4. Filling up missing numerical data using the **flag-and-fill** method

### 3. Feature Engineering
1. Create new categories by combining features
2. Grouping sparse classes
3. Create numerical features out of categorical features via **one-hot-encoding**
4. Finalize the dataset to be used for model training (**Analytical Base Table**) and save it as a CSV file

### 4. Exploration of Regression Models
1. Explored the `Lasso`, `Ridge` and `ElasticNet` regressors from ScikitLearn's `linear_model` library

### 5. Model Training and Evaluation
1. Further exploration of the `RandomForestRegressor` and `GradientBoostingRegressor` of ScikitLearn's `ensemble` library
2. Performed standardization (`StandardScaler()`) and 10-fold cross-validation for hyperparameter tuning
3. Compare **R2** and **Mean Absolute Error (MAE)** scores
4. Select the best model and hyperparameter combination and save it

## Credits
Credit goes to the team at [EliteDataScience](https://elitedatascience.com/machine-learning-masterclass) for providing the supplementary code.
