# Estimating Healthcare Insurance Expenses through Machine Learning.

# Project Overview:

This project aims to predict individual healthcare costs using demographics and health risk factors, to help understand drivers of expenses and provide personalized estimates.

A Random Forest Regression model is developed using a dataset of 1338 patients with features like age, BMI, smoking status, and geographic region. The model achieves an R-squared of 0.88 and RMSE of 4647 on test data.

# Key technical skills demonstrated:
Data cleaning

Exploratory data analysis

Feature engineering

Model building, evaluation and optimization

Regression techniques

Python (Pandas, Matplotlib, Scikit-learn)

# Data
The dataset contains 1338 rows and 7 features:

Age: integer age of patient

Sex: gender of patient

BMI: body mass index

Children: number of children

Smoker: whether patient smokes or not

Region: residential region in US

Charges: individual medical costs billed

# Methods
The project follows a typical machine learning workflow:

Data Cleaning: Fill missing values, remove duplicates

EDA: Distributions, correlations, segmentation

Preprocessing: Label encoding, one-hot encoding

Modeling: 80/20 train/test split, Random Forest Regression

Evaluation: RMSE, R-squared, feature importance

Optimization: Tuning hyperparameters, feature selection

# Key techniques used:

Visualizations with Matplotlib and Seaborn

Feature encoding

Random Forest Regression

Hyperparameter tuning with grid search

Model evaluation metrics
# Results
The Random Forest model obtains:

R-squared: 0.88

RMSE: 4647
# Key findings:

BMI and age are the top predictors of health expenses

Smokers incur significantly higher costs

Location correlates with costs due to variability in care pricing
