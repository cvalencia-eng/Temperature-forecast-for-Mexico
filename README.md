# Temperature Forecast for Mexico

This project focuses on performing exploratory data analysis and forecasting historical temperatures in Mexico using machine learning regression techniques, specifically `SGDRegressor`.

## Project Overview

- **Exploratory Data Analysis (EDA):**
  - Data cleaning and transformation.
  - Visualization of temperature trends.
  - Focus on temperature data for Mexico.
- **Predictive Modeling:**
  - Feature standardization.
  - Model training using linear regression.
  - Performance evaluation using MAE, RMSE, and R² metrics.

## Technologies and Libraries

- `pandas`, `numpy`: Data manipulation and numerical computations.
- `matplotlib`, `seaborn`, `plotly`: Data visualization and exploratory insights.
- `scikit-learn`: Regression modeling and performance metrics.
- `datetime`: Date parsing and temporal operations.

## Code Structure

1. **Data Loading:**
   - The dataset `GlobalLandTemperaturesByCountry.csv` is loaded and parsed.
2. **Date Parsing:**
   - A robust function handles multiple date formats and invalid entries.
3. **Data Filtering:**
   - Extracts records specific to Mexico for analysis and modeling.
4. **EDA:**
   - Analyzes long-term and seasonal temperature trends.
   - Utilizes static and interactive plots for visual insights.
5. **Modeling Pipeline:**
   - Features are scaled using `StandardScaler`.
   - `SGDRegressor` is trained on the time series data.
   - Model predictions are evaluated with MAE, RMSE, and R².

## Dataset

- Source: [Kaggle - Global Land Temperatures](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
- Required file: `GlobalLandTemperaturesByCountry.csv`

## How to Run

1. Ensure Python 3.8+ and Jupyter Notebook are installed.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
   ```
3. Launch the notebook:
   ```bash
   jupyter notebook Temperature_forecast_for_Mexico.ipynb
   ```

## Notes

- Includes robust handling of malformed date entries.
- Provides both static and interactive visualizations.
- While the model used is basic, it can be extended to advanced forecasting methods (e.g., ARIMA, LSTM).

## Author

Developed by **Cristhian Valencia Arreguin**  
Email: cristhian.valenciaa02@outlook.com
