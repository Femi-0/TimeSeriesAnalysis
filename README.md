# Time Series Analysis (TSA)

Two ipynb files present the analysis of time series data. In this case, the futures trading price of Canadian Dollar (CDN) to Japanese Yen (JPY):

<hr>

# 1. Returns Forcasting:

- This portion of the analysis attempts to determine whether or not any predictable patterns may be discerned from the historical price data.

- Following the ascertion that predictable patterns where present, ARMA and ARIMA models were used to predict price movements.

- Finally, a GARCH model was used to determine the volatility inherent to the pattern

<details>
 <summary>Returns Forcasting</summary>
 <img src="https://github.com/Femi-0/TimeSeriesAnalysis/blob/main/Images/Forcasting/Screen%20Shot%202022-05-02%20at%204.37.15%20PM.png" name="Price vs. Trend">
 <img src="https://github.com/Femi-0/TimeSeriesAnalysis/blob/main/Images/Forcasting/Screen%20Shot%202022-05-02%20at%204.37.49%20PM.png" name="Noise">
 <img src="https://github.com/Femi-0/TimeSeriesAnalysis/blob/main/Images/Forcasting/Screen%20Shot%202022-05-02%20at%204.38.32%20PM.png" name="image-name">
 <img src="https://github.com/Femi-0/TimeSeriesAnalysis/blob/main/Images/Forcasting/Screen%20Shot%202022-05-02%20at%204.38.46%20PM.png" name="image-name">
</details>

<hr>

# 2. Regession Analysis:

- This workbook is setup to determine the presence of seasonal patterns by implementing a linear regression on the data provided.

- The suitability of the linear regression is also confirmed by using the "root mean squared error" method to compare the performance of the regression on training and sample data 
  
<details>
  <summary>Regression Analysis</summary>
  <img src="https://github.com/Femi-0/TimeSeriesAnalysis/blob/main/Images/LR/Screen%20Shot%202022-05-02%20at%204.40.16%20PM.png" name="image-name">
</details>
