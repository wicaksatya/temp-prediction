# Temperature Prediction Project

## Overview
This project is focused on creating a machine learning model to predict average temperatures. The model is trained using a Random Forest regressor and evaluated against a baseline model to ensure accuracy and prevent overfitting.

## Contents
- `temp-pred.ipynb`: A Jupyter notebook containing the Python code for the temperature prediction model.

## Model Evaluation
The model's performance is evaluated using the following metrics:
- **Mean Absolute Error (MAE)**: Represents the average absolute difference between the predicted values and the actual values. A lower MAE indicates better model performance.
- **Mean Squared Error (MSE)**: Measures the average squared difference between the predicted values and the actual values. Like MAE, a lower MSE is better.
- **R2-score**: Reflects the proportion of the variance in the dependent variable that is predictable from the independent variables. An R2-score of 1.00 indicates perfect prediction.

## Latest Updates
- The Random Forest model achieved an MAE of 0.33, significantly outperforming the baseline model's MAE of 15.30.
- The model does not appear to be overfitting, as it generalizes well to unseen data.

## Customization
You are encouraged to adjust and improve the code. Feel free to experiment with different models, hyperparameters, and feature sets to enhance the model's performance.

## Note
For more specific details about the project, please refer to the actual content of the `temp-pred.ipynb` notebook or other files within the repository.
