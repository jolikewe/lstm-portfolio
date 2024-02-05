## Develop a daily-rebalanced portfolio of weights to beat S&P

1) Extract data from yfinance
2) Conduct feature engineering to generate additional features
3) Observe feature correlation and feature importance using xgboost
4) Concatenate 500 stocks of n features each
5) Create train and test data to predict the true weights
   - true weights refer to the normalised relative returns of each stock
7) Initiate LSTM model
8) Observe MSE and general trend via matplotlib
9) Conduct backtesting and obtain statistical measures such as Sharpe ratio
