# Used_Cars_Price_Prediction-using-random-Forest
This project involves building a machine learning model to predict house prices using a dataset containing various features of houses. The goal is to create an accurate regression model that can predict house prices based on the given features.

Here's a step-by-step summary of the project:

1. Importing Libraries: The necessary Python libraries like Pandas, NumPy, and Scikit-learn are imported.

2. Data Loading: The house price dataset is loaded into a Pandas DataFrame for further analysis.

3. Data Exploration: The dataset is explored to understand its structure, the available features, and the target variable (house prices). Descriptive statistics and visualization techniques are used to gain insights into the data.

4. Data Preprocessing: The data is prepared for modeling by handling missing values, converting categorical variables to numerical using one-hot encoding, and splitting it into features (X) and target (y).

5. Model Selection: Two regression models, namely Random Forest Regressor and Gradient Boosting Regressor, are chosen as potential candidates for predicting house prices.

6. Hyperparameter Tuning: Randomized Search Cross-Validation is performed to find the best hyperparameters for the selected models. The hyperparameters include the number of estimators, criterion, max depth, min samples split, min samples leaf, and max features.

7. Training and Evaluation: The models are trained using the best hyperparameters obtained from the tuning process. The performance is evaluated using mean absolute error (MAE) as the metric.

8. Final Model Selection: The model with the lowest MAE is selected as the final model for predicting house prices.

9. Making Predictions: Using the final model, predictions are made on new data (single observation) to estimate the house price.

10. Improving Output: To improve the output, the warning message "X does not have valid feature names" is suppressed using the `warnings` library.

Overall, the project is an end-to-end machine learning task that involves data preprocessing, model selection, hyperparameter tuning, and evaluation. The final result is a regression model capable of predicting house prices based on the given features with minimized error.
