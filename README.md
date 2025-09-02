# Delhi Air Quality Index (AQI) Time Series Analysis

## Project Description & Objectives
This project conducts an in-depth analysis and forecasting of Delhi's Air Quality Index (AQI) using historical daily AQI data. The aim is to understand air pollution trends, predict future values, and extract actionable insights to support public health and policy decisions.

## Data Source
- **Source:** Daily AQI dataset for Delhi, available in `delhi_aqi_recent_stats.csv`
- **Attributes:** Date, city, no. of stations, air quality category, AQI value, and prominent pollutant

## Methodology
1. **Data Acquisition & Cleaning**: Imported and inspected the AQI csv dataset. Handled missing and inconsistent values for robust analysis.
2. **Exploratory Data Analysis**: Used Seaborn and Plotly for visualizations (line plots, distribution charts). Examined trends, seasonality, extremes, and pollutant breakdown. Time series decomposition for trend and seasonality.
3. **Time Series Modeling**: Applied ARIMA, SARIMA, and Holt-Winters Exponential Smoothing models. Model selection based on AIC/BIC and diagnostics.
4. **Forecasting & Evaluation**: Generated AQI forecasts for future periods. Evaluated predictions using MAE and RMSE metrics.

## Key Results / Highlights
- Identified periods of critical and severe air pollution in Delhi.
- Visualized cyclical trends and periodicity in AQI values.
- Reliable predictive accuracy with time series models.
- Highlighted impact of prominent pollutants (NO2, PM2.5, O3) on AQI.
- Delivered actionable dashboards and forecast visualizations.

## How to Run / Usage
1. Install dependencies:
```bash
pip install -r requirements.txt
```
2. Run the analysis notebook:
   - Open `Delhi AQI/Delhi Air Quality Index (AQI) Time series analysis.ipynb` in JupyterLab or Notebook
   - Run all cells for full analysis and forecast reproduction
3. Ensure `delhi_aqi_recent_stats.csv` is in the project directory

## Tech Stack & Dependencies
- Python
- pandas, numpy, matplotlib, seaborn, plotly, statsmodels, scikit-learn, Jupyter Notebook

## Project Structure
```
Delhi_AQI/
│
├── Delhi AQI/
│   └── Delhi Air Quality Index (AQI) Time series analysis.ipynb
├── delhi_aqi_recent_stats.csv
├── README.md
├── requirements.txt
```

## Credits / Contact
- **Author:** Jaideep193
- For questions or contributions, open an issue or reach out via GitHub profile.
