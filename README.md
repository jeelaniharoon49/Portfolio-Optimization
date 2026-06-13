# A Python project that finds the best stock portfolio allocation using Modern Portfolio Theory and Monte Carlo simulation.

# What it does

Pulls 5 years of price data (2020–2025) for AAPL, MSFT, GOOGL, AMZN, TSLA using yfinance. 
Calculates daily returns, risk, and the covariance between stocks. 
Simulates 5,000 random portfolios with different weight combinations. 
For each portfolio, calculates return, risk, and Sharpe ratio. 
Plots all portfolios to show the efficient frontier. 
Highlights the portfolio with the highest Sharpe ratio (best risk-adjusted return)
<img width="982" height="707" alt="image" src="https://github.com/user-attachments/assets/c4d1e5f4-6a96-4281-a5b3-32b03aede391" />
The red star marks the best portfolio out of the 5,000 simulated — the one with the highest return per unit of risk.

#Tech Stack

- Python · pandas · numpy · yfinance · matplotlib

#Key Concepts

1) Modern Portfolio Theory — diversification and risk-return tradeoff
2) Sharpe ratio — comparing portfolios on a risk-adjusted basis
3) Monte Carlo simulation — exploring many possible portfolios to find a near-optimal one
