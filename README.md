# Momentum, Volatility, and Hybrid Portfolio Strategies

This project compares three portfolio construction strategies—momentum, inverse volatility, and a hybrid of the two—using monthly return data from 49 U.S. industry portfolios.

## Project Overview
The objective of this analysis is to evaluate which strategy delivers the best risk-adjusted performance while maintaining portfolio stability across market cycles.

## Data
- Monthly returns for 49 U.S. industries
- Historical data spanning multiple decades

## Strategies Tested
- **Momentum Strategy:** Selects industries with the highest trailing 12-month returns and allocates equally across them
- **Inverse Volatility Strategy:** Allocates more capital to industries with lower historical volatility
- **Hybrid Strategy:** Combines momentum ranking with inverse volatility weighting

## Methodology
- Cross-sectional ranking of industries
- Portfolio rebalancing at regular intervals
- Performance evaluation across strategies

## Performance Metrics
- Cumulative returns
- Annualized volatility
- Sharpe ratio
- Maximum drawdown

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib

## Key Takeaway
The hybrid strategy demonstrates how combining return-based signals with risk-based allocation can improve portfolio stability and risk-adjusted performance.
