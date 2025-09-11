   
-
 NO2 consistent year-round from vehicular emissions
###
 Public Health Implications
-
 
**
83.2%
**
 of days exceed "Good" air quality standards
-
 
**
50.1%
**
 of days fall in unhealthy ranges (Poor to Severe)
-
 Critical need for air quality management interventions

## 📊 Sample Visualization

![Delhi AQI Time Series Analysis](https://via.placeholder.com/800x400/2E86AB/FFFFFF?text=Delhi+AQI+Monthly+Trends+%7C+Jan+2024+-+Apr+2025)

*Figure: Monthly AQI trends in Delhi showing seasonal patterns and air quality deterioration during winter months (Oct-Feb)*

### Key Insights from Visualization:
- **Seasonal Pattern**: Clear deterioration during winter months (AQI 300-450) due to crop burning and reduced wind speeds
- **Summer Relief**: Relatively better air quality during summer months (AQI 150-250) with monsoon cleaning effect
- **Trending Upward**: Overall AQI shows concerning upward trend over the analysis period
- **Critical Periods**: November-January consistently show "Severe" category (AQI > 400)

##
 Project Structure
```
Delhi_AQI/
|
├── Delhi AQI/
│   ├── Delhi Air Quality Index (AQI) Time series analysis.ipynb
│   └── delhi_aqi_recent_stats.csv
├── README.md
└── requirements.txt
```
##
 Usage Instructions
###
 Prerequisites
```
bash
pip install -r requirements.txt
```
###
 Required Libraries
-
 pandas, numpy
-
 matplotlib, seaborn, plotly
-
 statsmodels
-
 scikit-learn
-
 jupyter notebook
###
 Running the Analysis
1.
 
**
Launch Jupyter Environment
**
:
   
```
bash
   
jupyter notebook
   
```
2.
 
**
Open the Analysis Notebook
**
:
   
-
 Navigate to 
`
Delhi AQI/Delhi Air Quality Index (AQI) Time series analysis.ipynb
`
   
-
 Run all cells sequentially for complete analysis
3.
 
**
Data Requirements
**
:
   
-
 Ensure 
`
delhi_aqi_recent_stats.csv
`
 is in the same directory
   
-
 No additional data preprocessing required
###
 Notebook Sections
1.
 
**
Data Loading & Exploration
**
 (Cells 1-12)
2.
 
**
Visualization & EDA
**
 (Cells 13-18)
3.
 
**
Time Series Analysis
**
 (Cells 19-22)
4.
 
**
Model Development
**
 (Cells 23-28)
5.
 
**
Forecasting & Evaluation
**
 (Cells 29-33)
##
 Technical Specifications
###
 Model Parameters
-
 
**
SARIMA
**
: (1,1,1)x(1,1,1,12)
-
 
**
Seasonal Period
**
: 12 (monthly patterns)
-
 
**
Forecast Horizon
**
: 30 days
-
 
**
Confidence Intervals
**
: Available for predictions
###
 Performance Metrics
-
 
**
Mean Absolute Error (MAE)
**
: 120.13
-
 
**
Root Mean Square Error (RMSE)
**
: 140.50
-
 
**
Model Selection
**
: AIC-based comparison
##
 Future Development
###
 Potential Enhancements
1.
 
**
Feature Engineering
**
:
   
-
 Weather data integration
   
-
 Holiday/festival indicators
   
-
 Emission source tracking
2.
 
**
Advanced Modeling
**
:
   
-
 Machine learning ensemble methods
   
-
 Deep learning approaches (LSTM, GRU)
   
-
 Multi-variate time series analysis
3.
 
**
Real-time Integration
**
:
*Last Updated: September 2025 | Data Coverage: January 2024 - April 2025*
