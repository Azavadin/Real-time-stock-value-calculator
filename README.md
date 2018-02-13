# Real-time-stock-value-calculator

We'll write a program that displays the net asset value for shares held by a user. The program will read a file which has a list of stock ticker symbols and the number of shares for each ticker. It will then go out to Yahoo! and request for the current stock price for one ticker at a time. The program will then find the value for a stock held by the user, based on the current stock price and the number of shares held by the user.

The program will display the following:

A table with each line displaying a ticker symbol, number of shares for that ticker, stock price for that ticker, and the total value for that stock ticker. In the last row, display the net asset value which is a total of the values for all the stocks held.

To requests for the current stock price from Yahoo!, use the URL
http://ichart.finance.yahoo.com/table.csv?s=TICKER

where TICKER is a symbol like GOOG or AAPL.
