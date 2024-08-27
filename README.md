# Media Campaign Cost Prediction

This project focuses on predicting media campaign costs using various machine learning regression models. The goal is to analyze a tabular dataset containing information about store sales, demographics, and other factors to predict the cost of media campaigns.

## Dataset

The dataset used in this project contains the following features:

- store_sales(in millions)
- unit_sales(in millions)
- total_children
- num_children_at_home
- avg_cars_at home(approx).1
- gross_weight
- recyclable_package
- low_fat
- units_per_case
- store_sqft
- coffee_bar
- video_store
- salad_bar
- prepared_food
- florist

The target variable is 'cost'.

## Models Used

The following regression models were implemented and evaluated:

1. Random Forest Regressor
2. Gradient Boosting Regressor
3. Decision Tree Regressor
4. K-Nearest Neighbors Regressor
5. XGBoost Regressor
6. CatBoost Regressor
7. Voting Regressor (ensemble of the above models)

## Evaluation Metrics

The models were evaluated using the following metrics:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R2 Score

## Results

Based on the evaluation metrics, the XGBoost Regressor performed the best with the following results:

- Mean Squared Error: 795.9994
- Mean Absolute Error: 23.9265
- R2 Score: 0.1141

## Usage

1. Ensure you have the required libraries installed (numpy, pandas, scikit-learn, xgboost, catboost).
2. Load the training and test datasets.
3. Preprocess the data (scaling, etc.).
4. Train the models using the provided code.
5. Evaluate the models using the evaluation function.
6. Use the best performing model (XGBoost in this case) to make predictions on the test set.
7. Generate a submission file with the predictions.

## Future Improvements

- Feature engineering to create more informative features.
- Hyperparameter tuning for each model to optimize performance.
- Trying other advanced regression techniques or deep learning models.
- Analyzing feature importance to gain insights into the most influential factors.

## Dependencies

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- CatBoost

## Note

This project is part of a Kaggle competition (Playground Series - Season 3, Episode 11). Make sure to comply with the competition rules and guidelines when using this code or submitting predictions.
