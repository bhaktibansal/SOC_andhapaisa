# SOC_andhapaisa
## Assignment 1

https://docs.google.com/document/d/1gWOuZ651Y9yJX48ILIwFxN12Y4KDyk_-4OHDFVdpCfY/edit?usp=sharing

Stock Market Basics:

A stock is a security of having ownership of some fraction of the shares of a company. Companies sell shares to raise capital in order to invest in their future projects. It is traded on a stock exchange wherein the company is listed, eg. NYSE, Nasdaq, NSE or on trading applications for common users online.

A market order is when you want the order to be executed as soon as possible at the current market price, whereas a Limit order is one where you can set an upper/lower limit to the stock prices at which you are willing to buy/sell your order respectively.

BID-ASK SPREAD: Amount by which the ask price exceeds the bid price for an asset in the market.
It is a measure of market liquidity and signifies how quickly and easily a stock can be bought or sold in the market. It is basically the transaction cost.

The price of stock actually signifies nothing but the current amount at which it is being bought and sold. It does not represent, in any way, the intrinsic value of a share. A share that costs less may in fact be of much more value than one that’s pricey. The price is determined by the company’s credentials, its financial statements and news regarding its ups and downs, therefore the company working does influence the share price, but it is the supply and demand of its shares that will ultimately decide the price. (which also depends on the work done)

Symbols are a combination of letters and numbers used to represent the shares traded in any market.
Dividends are a distribution of some percentage of the company’s earnings to the shareholders. They are paid out voluntarily by the company to gain the faith of the shareholders and maintain a high reputation of the company.

Technical Analysis:

Moving Average:
It is a technical trend indicator.
In statistics, moving average (aka rolling average/rolling mean/running average) is a type of Finite Impulse Response* filter that is used to analyze a set of data points.
It involves creating a series of averages of different subsets of the complete data set.
The plot line connecting all these data points is the Moving Average. (ie. it is a set of numbers)
A moving average may use unequal weights for each value in the subset in order to highlight certain values in that subset.
Eg. EXPONENTIAL MOVING AVERAGE:
This is an INFINITE IMPULSE RESPONSE filter since the weight never actually reaches 0.
It applies weights that decrease exponentially for older data points.
*Finite Impulse Response Filter: a non recursive filter that stops taking input after a finite amount of time and computes output based on the current and previous INPUTS only.

 Relative Strength Index:
It is a momentum indicator.
It is used to chart the current and previous strengths and weaknesses of a stock based on its closing prices.
It measures the velocity and magnitude of price movements.
Momentum = Rate of (rise/fall) of the closing price.
(QUALITATIVELY)
momentum = (higher closes/lower closes)*100
It is typically used on a 14 day timeframe and is measured on a scale of 0 to 100.
Low: <= 30
High: >= 70
Calculation:
i) RELATIVE STRENGTH:
		
		RS = EMA(U, n)/EMA(D, n)

*if EMA(D, n) = 0; RS = 100
ii) RELATIVE STRENGTH INDEX:

		RSI = 100 - 100/(RS + 1)

MACD (Moving Average Convergence/Divergence):
It is a technical analysis indicator used to spot changes in strength, direction, momentum and duration of a trend in a stock’s price.
Mathematically, it’s the difference between 2 EMAs (of different periods) of closing prices. The difference is charted over time alongside the moving average of the difference.
Since moving averages are based on past and current prices, it is a “lagging indicator”.

Bollinger Bands:
Technical Analysis tool
It evolved from trading bands
Used to measure highness/lowness relative to previous trades.
Consist of:
A middle band = An N-Period simple moving Average
An upper band at k times the N period standard deviation above middle band (SMA + k*SD)
A lower band at k times the N period standard deviation below the middle band (SMA - k*SD)
Typically, N = 20, k = 2, and EMA may be used instead of SMA according to the application.
It is used to define when the prices are relatively high or low, high being >= the upper band and low being <= the lower band.
INDICATORS FROM BOLLINGER BANDS:
%b: 
it tells where you are in relation to the bands.
%b = (last price - lowerBB) / (upperBB - lowerBB)
It is used in system building and pattern recognition.


![plot1](https://github.com/bhaktibansal/SOC_andhapaisa/assets/63958296/66be3ec5-d995-473f-95cb-a6cbaf7a2d71)
