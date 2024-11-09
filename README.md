# timeseries-forecasting-for-portfolio-management
## Overview
* In the fast-paced financial markets, predictive insights and robust portfolio management are essential for investment firms seeking to maximize returns while effectively managing risk. Guide Me in Finance (GMF) Investments, a data-driven financial advisory firm, is committed to providing clients with tailored investment strategies that leverage advanced analytics and real-time financial data. 
* By harnessing sophisticated time series forecasting models, It is possible to predict market trends and optimize asset allocation, thus enhancing portfolio performance and helping clients meet their financial goals.
* This Project outlines the approach and findings of a financial time series forecasting project, which seeks to improve portfolio management through data-driven predictions and strategic adjustments.

## Objective
The objective of this report is to apply time series forecasting methods to historical financial data to inform and optimize portfolio management strategies. 
Specifically, the goals are to:
1.	Extract and Prepare Financial Data: Utilize YFinance to retrieve historical data, including stock prices and market indices, to establish a foundation for analysis.
2.	Identify Trends and Patterns: Preprocess and analyze the data to uncover patterns, trends, and seasonalities, providing a basis for more accurate forecasting.
3.	Develop and Assess Forecasting Models: Implement and evaluate time series forecasting models to predict future market movements, with an emphasis on model performance and reliability.
4.	Provide Investment Recommendations: Use forecasted trends to offer actionable recommendations that optimize portfolio returns while managing associated risks, supporting GMF's commitment to achieving client financial objectives.
This report aims to bridge data analysis with strategic investment recommendations, ensuring GMF’s portfolios are well-positioned to capitalize on opportunities while minimizing potential risks.

## Dataset
Historical financial data for three key assets: Tesla (TSLA) Historical stock prices (Open, High, Low, Close), volume, and volatility. Vanguard Total Bond Market ETF (BND), and S&P 500 ETF (SPY). The data is sourced from YFinance and cover the period from January 1, 2015, to December 31, 2024.
- TSLA: High-growth, high-risk stock in the consumer discretionary sector (Automobile Manufacturing).
- BND: A bond ETF tracking U.S. investment-grade bonds, providing stability and income.
- SPY: An ETF tracking the S&P 500 Index, offering broad U.S. market exposure.

* The dataset includes
  - Date: Trading day timestamp.
  - Open, High, Low, Close: Daily price metrics, with Adj Close representing the adjusted close price to account for dividends and splits
  - Volume: The total number of shares/units traded each day.                
  - Volatility: calculated from rolling means and standard deviations to show how much the price varies over time.

## Prerequisites
* Python 3.x: Ensure Python is installed on your system.
* Virtual Environment: Recommended for managing project dependencies.
* Required Libraries:
  - pandas: Data manipulation and analysis.
  - numpy: Numerical operations.
  - matplotlib: Data visualization.
  - seaborn: Statistical visualizations.
  - yfinance: Financial data source
  
## Installation

1. **Create a virtual environment:**

   On macOS/Linux:

   ```
   python -m venv venv 
   source venv/bin/activate
   ```
   on windows:

   ```
   python -m venv venv
   venv\Scripts\activate
   ```

2. **Install dependencies:**   

   ``` pip install -r requirements.txt```


## Contributing

Contributions are welcome!

**License**

This project is licensed under the Apache License. See the LICENSE file for more details.