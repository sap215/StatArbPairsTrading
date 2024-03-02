# StatArbPairsTrading
#### This repository includes an introduction to statistical arbitrage pairs trading. My jupyter notebook, StatArbBlog.ipynb, is divided into two central categories: research and backtesting.

## Research
#### In the research aspect of my jupyter notebook, I discuss a few different statistical approaches to analyze cointegration and mean-revresion. Additionally, I discuss a rather simple way to finding a pair with cointegration tendencies, i.e., selected the most liquid competing companies within a specific sector. In my example, I used the car manufacturing industry as my sector of choice.

## Backtesting
#### In the backtesting aspect of my jupyter notebook, I discuss how to formally create a backtest as well as calculate realized pnl and sharpe ratio. By no means do I consider this way to be the best way of creating a backtest, I've just had great success with this method and it has allowed me to calculate performance metrics rather easily. Additionally, I did not discuss calculating unrealized pnl, drawdowns, or rolling sharpe ratio. Again, this notebook is to get the reader accustomed to developing simple statistical arbitrage pairs trading strategies.

## Notice
#### I'd also like to mention that there are MANY things I that have excluded from my baktest. Some of which include: calculating market impact, analyzing daily volume for both stocks in my pair to find an ideal and accessible number of shares to trade with, using minute market data instead of daily data, taking corporate actions into account (e.g. dividends), etc.


