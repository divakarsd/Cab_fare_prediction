# Cab_fare_prediction
Prediction of cab fare using machine learning

## Problem Statement -
You are a cab rental start-up company. You have successfully run the pilot project and
now want to launch your cab service across the country. You have collected the
historical data from your pilot project and now have a requirement to apply analytics for
fare prediction. You need to design a system that predicts the fare amount for a cab ride
in the city.

```
Given attributes:
pickup_datetime - timestamp value indicating when the cab ride started.
pickup_longitude - float for longitude coordinate of where the cab ride started.
pickup_latitude - float for latitude coordinate of where the cab ride started.
dropoff_longitude - float for longitude coordinate of where the cab ride ended.
dropoff_latitude - float for latitude coordinate of where the cab ride ended.
passenger_count - an integer indicating the number of passengers in the cab ride.
````
## Findings
It is a regression Problem.

## Steps implemented in this project
1. Data Pre-processing.
2. Data Visualization.
3. Outlier Analysis.
4. Missing value Analysis.
5. Feature Selection.
- Correlation analysis.
- Chi-Square test.
- Analysis of Variance(Anova) Test
- Multicollinearity Test.
6. Feature Scaling.
- Normalization.
7. Splitting into Train and Validation Dataset.
8. Model Development 
- I. Linear Regression 
- II. Ridge Regression
- III. Lasso Regression
- IV. Decision Tree
- V. Random Forest
9. Finalize Model
- Save model for later use
