# Pakistan House Price Prediction

## Overview

A machine learning project that explores and predicts house listing prices in Pakistan using Python and Scikit-learn.

The project follows an end-to-end regression workflow, from data cleaning and exploratory data analysis to feature engineering, preprocessing, model comparison, hyperparameter tuning, and error analysis.

## Objectives

- Understand the real-estate dataset and its quality.
- Explore relationships between property features and listing prices.
- Engineer useful numerical and date-based features.
- Build and compare regression models.
- Evaluate model performance using MAE, RMSE, and R².
- Investigate prediction errors across price ranges and cities.

## Technologies

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Project Workflow

1. Data loading and understanding
2. Data cleaning
3. Target selection and dataset preparation
4. Exploratory data analysis
5. Train-test split
6. Feature engineering
7. Data preprocessing
8. Model development and comparison
9. Model evaluation and error analysis
10. Conclusion and limitations

## Models

The experiments include a median baseline, linear regression, gradient boosting, and ExtraTrees regression. A log transformation of the target price was also evaluated.

## Evaluation Metrics

- **MAE:** Average absolute prediction error in PKR.
- **RMSE:** Prediction error metric that penalizes larger errors more heavily.
- **R²:** Measures how much variation in the target is explained by the model.

## Limitations

The dataset contains historical listing prices, which may differ from final transaction prices. Important variables such as property condition, construction age, amenities, and detailed neighbourhood characteristics are unavailable. Prediction errors also vary by city and price range, particularly for expensive properties.

The model requires reproducible evaluation and testing on genuinely new data before it can be relied upon for real-world property valuation.

## How to Run

1. Clone or download this repository.
2. Install the required Python packages.
3. Open `house_price_prediction.ipynb` in Jupyter Notebook.
4. Place the dataset in the documented data location, if redistribution is permitted.
5. Run the notebook cells in order.

## Disclaimer

This is an educational machine learning project. Its predictions are estimates, not professional property valuations or guaranteed sale prices.
