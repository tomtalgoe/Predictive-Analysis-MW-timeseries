# Time Series Analysis of Power Load and Predictors

This project analyzes hourly **power load (load_MW)** together with several predictors such as **solar power**, **wind power**, **temperature**, **cloud cover**, and **electricity price**.  
The notebook includes exploratory data analysis, preprocessing, and forecasting using both multivariate and univariate models.

## Features
- Data inspection and summary statistics  
- Timestamp handling and missing-value imputation  
- Visualization of all variables and correlations  
- Stationarity checks and differencing  
- **VAR model** for multivariate forecasting  
- **SARIMA model** for univariate load forecasting  
- Evaluation of forecasts (MAPE, MAE, RMSE)

## Files
- `main.ipynb` – full analysis and forecasting workflow  
- `data.csv` (or project dataset) – input time series data  

## How to Run
1. Clone the repository  
2. Install required Python libraries (pandas, numpy, matplotlib, statsmodels, etc.)  
3. Open `main.ipynb` in Jupyter and run the cells sequentially  

## Purpose
A compact demonstration of time series modeling for power load forecasting using weather variables and market data.
