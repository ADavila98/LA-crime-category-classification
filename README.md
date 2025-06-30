# Crime Category Classification

This project focuses on analyzing and predicting crime categories in Los Angeles using machine learning. The dataset includes reported crime incidents from 2020 to the present.

## Dataset

- **Source**: [Kaggle - Los Angeles Crime Data (2020–Present)](https://www.kaggle.com/datasets/benmann2448/los-angeles-crime-data-from-2020-to-present?resource=download)

## Project Goals

- Clean and preprocess crime report data.
- Engineer meaningful features (e.g., time of occurrence, modus operandi).
- Train and evaluate multiple machine learning models.
- Predict generalized crime categories (e.g., Property, Violent, Fraud, etc.).

## Final Output

The final submission file contains:
- `ID`: A unique identifier.
- `Crime Category`: Predicted category label for each record.

## Models Used

- Random Forest
- XGBoost (with tuning)
- Gradient Boosting
- CatBoost
- MLPClassifier (Deep Learning)

## Results

Best performance achieved using **XGBoost** after hyperparameter tuning with final accuracy of 0.9618.
