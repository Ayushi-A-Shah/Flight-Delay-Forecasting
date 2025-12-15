# Flight Delay Forecasting
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Libraries](https://img.shields.io/badge/Libraries-pandas%2C%20statsmodels%2C%20seaborn-brightgreen)
![Status](https://img.shields.io/badge/Status-Complete-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A time series forecasting project analyzing U.S. flight delays using BTS aviation data. The project includes exploratory data analysis, regional trend comparisons, forecasting pipelines, and model evaluation. It highlights how delays vary by geography and time, and builds predictive models to forecast monthly delay totals.

## Project Motivation
Flight delays cost airlines millions and impact millions of passengers. This project explores:
- How delay patterns differ across U.S. regions
- Which months consistently experience higher delays
- What types of delays dominate the dataset
- How well we can forecast future delays using classical forecasting models

## Project Report
The full Exploratory Data Analysis (EDA) and forecasting report is available here:
[Flight Delay Forecasting Report](reports/Flight_Delay_Forecasting_Report.pdf)

## Project Notebook
The full Jupyter Notebook containing EDA and forecasting code is available here:  
[Flight Delay Forecasting Notebook](notebooks/Flight_Delay_Forecasting_Code.ipynb)

## How to Run This Project Locally

## 1. Clone the repository
```bash
git clone https://github.com/Ayushi-A-Shah/Flight-Delay-Forecasting.git
cd Flight-Delay-Forecasting


### 2. Install dependencies
pip install -r requirements.txt


### 3. Launch Jupyter Notebook
jupyter notebook
Then open the notebook located at: notebooks/Flight_Delay_Forecasting_Code.ipynb
```

## Key Findings
- Seasonality: Delay spikes in summer months across all regions.
- Regional Variation: Western and Southern regions show stronger seasonal effects compared to Midwest and Northeast.
- Delay Types: Late Aircraft and NAS delays dominate total delay minutes.
- Forecast Accuracy: SARIMA models consistently outperform naive baseline and exponential smoothing.

## Methods & Techniques

Exploratory Data Analysis
- Trend analysis
- Seasonality decomposition
- Heatmaps and correlation analysis
- Delay category breakdown
  
Forecasting Models
- Naive Forecast
- Exponential Smoothing
- SARIMA
- Rolling forecast evaluation
  
Model Evaluation Metrics
- RMSE
- MAPE
- Residual diagnostics

Future Improvements
- Incorporate machine learning models (Random Forest Regressor, XGBoost)
- Build a dashboard using Streamlit
- Integrate airport-level features for better granularity
- Explore LSTM or NeuralProphet for longer-term forecasts

Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels
- Scikit-learn
- Jupyter Notebook

License
- MIT License
