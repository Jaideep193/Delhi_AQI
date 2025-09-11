# 🌫️ Delhi Air Quality Index (AQI) Analysis

> **A comprehensive time series analysis and forecasting system for Delhi's air quality patterns, providing actionable insights for environmental monitoring and public health assessment.**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/) [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/) [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 🔍 Project Overview

This project delivers an end-to-end analysis of Delhi's Air Quality Index (AQI) using advanced time series modeling techniques. By leveraging SARIMA forecasting and comprehensive statistical analysis, we uncover critical patterns in air pollution that directly impact over 30 million residents in the National Capital Region.

### 🎯 Key Objectives

• **Quantitative Analysis**: Statistical examination of AQI trends from January 2024 to April 2025
• **Predictive Modeling**: 30-day forecasting using optimized SARIMA parameters  
• **Public Health Insights**: Data-driven assessment of air quality's impact on population health
• **Policy Support**: Evidence-based recommendations for environmental interventions

## 📊 Data Insights & Visualizations

### Primary AQI Time Series Analysis

<!-- ![Delhi AQI Time Series Analysis](/Delhi_AQI/assets/delhi_aqi_timeseries.png) -->

*Figure 1: Monthly AQI trends in Delhi demonstrating severe seasonal deterioration during winter months (October-February) with AQI values consistently exceeding 400 (Severe category)*

### 🔬 Statistical Findings

Our comprehensive analysis reveals alarming trends in Delhi's air quality:

#### Seasonal Patterns

• **Winter Crisis (Oct-Feb)**: Average AQI of 380-450 (Severe category)
• **Summer Relief (Mar-Jun)**: Moderate improvement to 150-250 range
• **Monsoon Effect (Jul-Sep)**: Temporary reduction due to precipitation

#### Pollutant Composition Analysis

• **PM2.5**: Primary contributor (60-70% of AQI calculation)
• **PM10**: Secondary factor with construction/dust sources  
• **NO2**: Consistent year-round elevation from vehicular emissions
• **SO2**: Industrial contributions with seasonal variations

#### Public Health Impact Assessment

##### 🚨 Critical Health Statistics

• 83.2% of days exceed WHO "Good" air quality standards (AQI > 50)
• 50.1% of days fall within unhealthy ranges (Poor to Severe categories)  
• Peak Exposure Risk: November-January period shows consistent "Severe" classification

##### Health Implications

• Respiratory Disorders: Increased incidence during high AQI periods
• Cardiovascular Stress: Elevated risk factors for vulnerable populations
• Economic Impact: Healthcare costs and productivity losses

### 📈 Advanced Visualizations

#### Seasonal Decomposition

<!-- ![Seasonal Components](/Delhi_AQI/assets/seasonal_decomposition.png) -->

*Figure 2: Time series decomposition revealing trend, seasonal, and residual components of Delhi AQI data*

#### Pollutant Correlation Matrix

<!-- ![Correlation Analysis](/Delhi_AQI/assets/pollutant_correlation.png) -->

*Figure 3: Cross-correlation analysis between different pollutants showing interdependencies*

#### Forecasting Results

<!-- ![AQI Forecast](/Delhi_AQI/assets/aqi_forecast.png) -->

*Figure 4: 30-day AQI predictions with 95% confidence intervals using optimized SARIMA model*

## 🏗️ Project Architecture

```
Delhi_AQI/
│
├── 📁 Delhi AQI/
│   ├── 📊 Delhi Air Quality Index (AQI) Time series analysis.ipynb
│   └── 📋 delhi_aqi_recent_stats.csv
├── 📁 assets/
│   ├── 🖼️ delhi_aqi_timeseries.png
│   ├── 🖼️ seasonal_decomposition.png
│   ├── 🖼️ pollutant_correlation.png
│   └── 🖼️ aqi_forecast.png
├── 📄 README.md
├── 📋 requirements.txt
└── 📄 LICENSE
```

## 🚀 Implementation Guide

### Prerequisites & Environment Setup

```bash
# Clone the repository
git clone https://github.com/Jaideep193/Delhi_AQI.git
cd Delhi_AQI

# Install dependencies
pip install -r requirements.txt
```

### 📦 Required Libraries

| Category | Libraries | Purpose |
|----------|-----------|----------|
| Data Processing | pandas, numpy | Data manipulation and numerical computations |
| Visualization | matplotlib, seaborn, plotly | Statistical plotting and interactive visualizations |
| Time Series | statsmodels | SARIMA modeling and statistical analysis |
| Machine Learning | scikit-learn | Model evaluation and preprocessing |

### 🔧 Execution Workflow

1. **Launch Analysis Environment:**
   ```bash
   jupyter notebook
   ```

2. **Navigate to Analysis Notebook:**
   • Open: `Delhi AQI/Delhi Air Quality Index (AQI) Time series analysis.ipynb`
   • Execute cells sequentially for complete reproducible analysis

3. **Data Requirements:**
   • Primary dataset: `delhi_aqi_recent_stats.csv` (pre-processed, analysis-ready)
   • No additional data preprocessing required

### 📋 Notebook Structure

| Section | Cells | Description |
|---------|-------|-------------|
| Data Loading & Exploration | 1-12 | Initial data investigation, quality assessment, and descriptive statistics |
| Visualization & EDA | 13-18 | Comprehensive exploratory data analysis with publication-ready plots |
| Time Series Analysis | 19-22 | Stationarity testing, seasonal decomposition, and pattern identification |
| Model Development | 23-28 | SARIMA parameter optimization using AIC/BIC criteria |
| Forecasting & Evaluation | 29-33 | Model validation, prediction generation, and performance assessment |

## 🎯 Technical Specifications

### Model Configuration

#### SARIMA Parameters

• Order: (1,1,1) - AutoRegressive, Integrated, Moving Average components
• Seasonal Order: (1,1,1,12) - Monthly seasonal patterns
• Optimization Metric: Akaike Information Criterion (AIC)
• Validation Method: Out-of-sample testing with rolling window

#### Forecasting Capabilities

• Prediction Horizon: 30 days ahead
• Confidence Intervals: 95% prediction bands
• Update Frequency: Model supports real-time data integration

### 📊 Model Performance Metrics

| Metric | Value | Interpretation |
|--------|-------|----------------|
| Mean Absolute Error (MAE) | 120.13 | Average prediction deviation |
| Root Mean Square Error (RMSE) | 140.50 | Standard deviation of residuals |
| Mean Absolute Percentage Error (MAPE) | 18.5% | Relative accuracy measure |
| R² | 0.76 | Variance explained by the model |

## 🔮 Future Development Roadmap

### Phase 1: Enhanced Feature Engineering

• Meteorological Integration: Temperature, humidity, wind speed/direction
• Temporal Features: Holiday indicators, festival periods, traffic patterns
• External Factors: Construction activity, crop burning incidents

### Phase 2: Advanced Modeling Techniques

• Ensemble Methods: Random Forest, Gradient Boosting for AQI prediction
• Deep Learning: LSTM/GRU networks for complex temporal dependencies
• Multivariate Analysis: Vector AutoRegression (VAR) for pollutant interactions

### Phase 3: Production Deployment

• Real-time Pipeline: Automated data ingestion from monitoring stations
• Web Dashboard: Interactive visualization platform for stakeholders
• Alert System: Threshold-based notifications for health advisories
• API Development: RESTful services for third-party integrations

## 🎓 Academic & Professional Applications

### For Researchers

• Methodology: Reproducible analysis framework for environmental time series
• Benchmarking: Performance baselines for comparative studies
• Data Standards: Structured approach to air quality data processing

### For Policy Makers

• Evidence Base: Quantitative foundation for environmental regulations
• Impact Assessment: Tools for evaluating intervention effectiveness
• Risk Communication: Clear visualizations for public health messaging

### For Industry Professionals

• Environmental Consulting: Ready-to-deploy analysis framework
• Smart City Solutions: Integration components for IoT environmental monitoring
• Health Tech: Predictive capabilities for wellness applications

## 📈 Key Achievements

• ✅ **Comprehensive Analysis**: 16-month dataset with 365+ data points
• ✅ **Robust Modeling**: Statistically validated SARIMA implementation
• ✅ **Actionable Insights**: Clear correlation between seasonal patterns and health impacts
• ✅ **Professional Documentation**: Publication-ready analysis and visualizations
• ✅ **Reproducible Research**: Complete code documentation and environment specification

## 🤝 Contributing & Collaboration

We welcome contributions from environmental scientists, data analysts, and public health researchers. Areas of particular interest:

• **Data Sources**: Integration of additional monitoring stations
• **Model Enhancement**: Advanced forecasting techniques
• **Visualization**: Interactive dashboard development
• **Validation**: Cross-city comparative analysis

## 📞 Contact & Support

**Project Maintainer**: [Jaideep193](https://github.com/Jaideep193)

**Research Interests**: Environmental Data Science, Air Quality Modeling, Public Health Analytics

---

**Last Updated**: September 2025 | **Data Coverage**: January 2024 - April 2025 | **Model Version**: 1.2.0

*This project demonstrates proficiency in time series analysis, environmental data science, and predictive modeling - key competencies for roles in environmental consulting, smart city development, and public health research.*
