# Revenue Forecasting Model

## Overview
Predictive analytics project using Linear and Polynomial Regression to forecast future revenue trends based on 24 months of historical data.

## Dataset
- 24 months of historical revenue data
- Revenue Range: $52,484 - $142,876
- Train/Test Split: 19/5 (80/20)

## Model Performance

### Linear Regression
- **R² Score: 0.9920** ✓ BEST MODEL
- **RMSE: $1,691.90**
- Excellent fit for revenue forecasting

### Polynomial Regression (Degree 2)
- R² Score: 0.5921
- RMSE: $12,063.69
- Less suitable for this dataset

## 6-Month Revenue Forecast
Linear Regression Predictions:
- Month 25: $149,081
- Month 26: $150,577
- Month 27: $151,996
- Month 28: $153,416
- Month 29: $161,881
- Month 30: $171,830

## Visualizations
- Historical Revenue Trend
- Linear Regression Actual vs Predicted
- Polynomial Regression Actual vs Predicted
- Combined Forecast with 6-month projection

## Output Files
- `revenue_forecast.png` - Forecast visualization
- `forecast.csv` - Forecasted values

## Technologies
- Python 3
- Scikit-learn (Linear & Polynomial Regression)
- Pandas, NumPy
- Matplotlib

## Recommendation
Use Linear Regression model for revenue forecasting due to superior R² score.
