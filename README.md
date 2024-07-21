# Forest Fire Prediction
This project aims to predict forest fire occurrences using the forest_fire.csv dataset. Various regression and classification models were applied to the data to evaluate their performance in predicting fire risks.

## Dataset
Dataset Name: forest_fire.csv
Description: Contains data related to forest fires, including various meteorological factors.
Source: UCI Machine Learning Repository - Forest Fires Dataset
## Features
Features Used in Models:

temp (Temperature)
RH (Relative Humidity)
wind (Wind Speed)
rain (Rainfall)
Target Column:

area (Area burned by fire)
## Visualizations
Several visualizations were created to explore the dataset:

Heatmap: Shows the correlation between different features.
Bar Plot: Represents the distribution of forest fires by various categories.
Scatter Plot: Displays the relationship between key features.
## Data Preprocessing
Missing Values: The dataset was checked for missing values, and none were found.
## Models and Performance
Various models were applied to predict the likelihood of forest fires, with the following results:

Linear Regression:

RMSE = 1.5220
MAD = 1.1365
Ridge Regression:

RMSE = 1.5315
MAD = 1.1456
Lasso Regression:

RMSE = 1.5356
MAD = 1.1492
Random Forest:

RMSE = 1.4961
MAD = 1.1251
SVM:

RMSE = 1.6137
MAD = 1.0809
Bayesian Ridge Regression:

RMSE = 1.5352
MAD = 1.1488
Additional Analysis
The models were also re-evaluated using Knime, and the results are included in the project.

## Results and Discussion
Best Performing Model: Random Forest with the lowest RMSE and MAD values.
Model Insights: The Random Forest model provided the best performance in predicting forest fire occurrences. Other models, while useful, showed higher RMSE and MAD values.
