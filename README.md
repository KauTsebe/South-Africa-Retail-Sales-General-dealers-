# South-Africa-Retail-Sales-General-dealers-
# Retail Sales Forecasting

This project forecasts South African retail trade sales for **General Dealers** using time series analysis and XGBoost machine learning models.

It walks through:
- Data loading and exploration
- Feature engineering with decomposition (trend, seasonal, residual)
- Autocorrelation analysis
- Outlier detection
- XGBoost hyperparameter tuning
- Walk-forward validation forecasting
- Next month sales prediction

The dataset is sourced from Stats SA and includes monthly retail trade sales measured at constant prices.

## Project Structure

- **Data Cleaning**: Handling missing values and ensuring datetime formatting.
- **Exploratory Data Analysis (EDA)**: Univariate, bivariate, and trend analyses.
- **Feature Engineering**: Creating lags, rolling means, trend, seasonality, and date features.
- **Model Training**: XGBoost with hyperparameter tuning using RandomizedSearchCV.
- **Walk-Forward Prediction**: Rolling forecast updating model after every prediction.
- **Future Forecast**: Predicting the next month's sales using the latest data.

## How to Run

1. Ensure you have the dataset available at the specified path or adjust the `file_path` in the script.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
