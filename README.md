# Predicting Flight Ticket With Machine Learning Model
This project we have using three models to prediction the flight ticket price since the pricing of the flight ticket is often influenced by factors such as flight duration, seat availability, airline, travel dates, and booking conditions.

## Data Source
https://www.kaggle.com/datasets/justinmitchel/flightprices-min?resource=download

## Models using during this project
1. Linear Regression
2. K-Nearest Neighbours
3. Random Forest

## Accuracy of each model
Linear Regression
- R2 Score            : 63.07%
- MAE                 : 63.84
- MSE                 : 7899.51
- RMSE                : 88.88
- Best Hyperparameters: N/A

KNN Regression
- R2 Score            : 83.41%
- MAE                 : 20.11
- MSE                 : 3548.68
- RMSE                : 59.57
- Best Hyperparameters: Weight = "Uniform", p = "1", n_neighbours = "1"

Random Forest Regression
- R2 Score            : 87.22%
- MAE                 : 29.15
- MSE                 : 2735.10
- RMSE                : 52.30
- Best Hyperparameters: n = "100", min_split = "10", min_leaf ="1", max_ features = "sqrt", max_depth ="40"

## Team Member
1. See Chwan Kai
2. Kho Wei Cong
3. Teo Jing An
4. Tee Kian Hao
