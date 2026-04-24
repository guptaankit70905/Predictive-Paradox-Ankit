# Predictive-Paradox-Ankit
Machine learning pipeline to forecast next-hour electricity demand using historical data, feature engineering, and Random Forest.

# Predictive Paradox - Power Demand Forecasting

## Objective
To predict next hour electricity demand using machine learning.

## Approach

### Data Cleaning
- Converted datetime column
- Removed duplicates
- Handled missing values using forward fill

### Outlier Handling
- Used IQR method to remove extreme values

### Feature Engineering
- Time features: hour, day, month
- Lag features: previous demand values
- Rolling mean for trend capture

### Model
- Random Forest Regressor

### Evaluation
- Metric: Mean Absolute Percentage Error (MAPE)
- Achieved MAPE ≈ 2.13%

### Insights
- Previous demand (lag features) is the most important factor
- Time patterns strongly influence electricity usage
