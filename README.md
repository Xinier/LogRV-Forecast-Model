# LogRV Forecast Model
This project aims to develop a predictive model for the log RV of daily stock returns of the Commonwealth Bank of Australia (CBA) using the dataset provided.

<img src="https://images.squarespace-cdn.com/content/v1/5820f7b06b8f5b12160c7941/1507509923141-3LZQW12NQS1F0L2YGCWG/Volatility.jpg" width="400"/>

## General Information
Modelling and forecasting the volatility of financial asset returns is of great importance to financial institutions world wide. 
Volatility forecasts are used in risk management, derivative pricing, hedging and many other financial activities.
Recent research has shown that "realised variance (RV)" is an efficient measure of volatility for daily returns of a financial asset.
The RV of day is given by the sum of squared intra-daily returns:

$RV_t = \sum{r^2}$

The dataset contains the observed values of log RV and a set of potential features constructed using intra-daily returns 
(based on prices sampled at 5-minute intervals) of CBA from January 7, 2003 to August 20, 2021

### Dataset
Connect to the "cba_log_rv.sqlite" SQLite database using the Python sqlite3 module

### Methods Used
- Machine Learning
- Data Visualization
- Predictive Modeling

### Algorithme
- Linear Regression

## Credit 
Please note that this is an academic project conducted during my studies in The University of Sydney
