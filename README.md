#Emerging Markets Sentiment Strategy
This strategy uses scraped News Articles and then applies a VADER Sentiment Analysis to score every article to get a compound sentiment.
Then using a series of parameters to capture momentum and change in sentiment we apply a trading logic to buy/sell fixed volumes of a given stock.
Using Backtrader we are able to view the historical outcome of such a strategy with ease. The model needs to be further optimised.

#Reasons for the choice of Companies
I chose Emerging Market equities assuming that such data is not being mined at high frequencies by machines compared to US equities. Choosing Securities with relatively 
high liquidity shows us that price changes are more likely. More work must be done on the stock choices to find stocks with higher Volatility, on the assumption that 
reasons for higher volatility will be captured by News Data.
