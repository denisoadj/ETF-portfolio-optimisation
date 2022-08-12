# ETF-portfolio-optimisation
In this repository you will find a mini-project which consists on optimise a portfolio of ETFs that aim to track some major stock indices. The potential investments are as follows:

- The SPDR S&P 500 Trust ETF (SPY)
- Vanguard FTSE 100 UCITS ETF GBP (VUKE.L)
- Invesco QQQ ETF that tracks the Nasdaq-100 Index (QQQ.O)

Here are the steps I used to tackle this project: 

- Decided the time range of historical data.
- Downloaded the data from Eikon API
- Optimised the portfolio based on maximising Sharpe ratio.
- Provided comment on whether the most optimised porfolio is sub-optimal/good/very good/excellent. 
  knowing that any Sharpe ratio greater than 1.0 is considered acceptable to good by investors. A ratio higher than 2.0 is rated as very good. A ratio of 3.0 or higher is considered excellent. A ratio under 1.0 is considered sub-optimal.
- Finally, I displayed the efficient frontier graph.
