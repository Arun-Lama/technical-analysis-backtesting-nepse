# This program can be used to backtest any historical data based on RSI, MA, and MACD. 
The program takes OHLC historical price as input. Separate OHLC file has been used for each symbols. You can use different approach for reading price. 

Rule of the strategy: 
Buy: When price is above 20 MA, RSI is above 50, and MACD line is above signal line. 
Sell: When price is below 20 MA, RSI is below 50, and MACD line is below signal line. 
