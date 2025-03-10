# Stock Market Analysis with PCA and Portfolio Optimization

## Overview
This project performs a comprehensive analysis of stock prices, log returns, and portfolio optimization using Principal Component Analysis (PCA). The workflow includes data retrieval, statistical analysis, visualization, and portfolio performance evaluation.

## Features
- **Stock Data Retrieval**: Load and preprocess stock price data.
- **Log Returns Calculation**: Compute log returns for time-series analysis.
- **PCA Analysis**: Reduce dimensionality and extract key market trends.
- **Portfolio Optimization**: Construct and compare different portfolios.
- **Data Visualization**: Generate histograms, time-series plots, and cumulative return comparisons.
- **CSV Export**: Save key results for further analysis.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scipy sklearn
```

## File Structure
```
📂 Project Folder
├── data/                 # Raw stock price data
├── output/               # Results and visualizations
├── analysis.py           # Main analysis script
├── requirements.txt      # List of dependencies
└── README.md             # Project documentation
```

## Results
- Principal Component Loadings and Explained Variance
- Portfolio Performance Compared to Market Index
- Visualization of Market Trends and Risk Factors

# Financial Data Analysis

This repository contains various analyses and visualizations related to financial data.

## Visualizations

### Cumulative Returns
![Cumulative Returns](images/Cumulative%20returns%20cac40.png)

### Log Returns
![Log Returns](images/Log%20returns.png)

### Principal Component Analysis (PCA) Returns
![PC1 Returns](images/PC1%20returns.png)

### Portfolio vs Index Performance
![Portfolio vs Index](images/portfolio_vs_index_cumulative_returns.png)

### Residual Analysis
![Residuals vs Fitted Values](images/Residuals%20vs%20Fitted%20values.png)

### Autocorrelation of Residuals
![Autocorrelation of Residuals](images/Autocorrection%20of%20residuals.png)

---
