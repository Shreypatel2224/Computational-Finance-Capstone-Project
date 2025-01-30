# Quantitative Investment Fund Creation - Capstone Project

This repository contains a Jupyter Notebook implementing various tasks related to constructing, evaluating, improving, and combining trading strategies for an investment management fund.

## Project Structure:

Part 1: Constructing Trading Strategies
- Implemented three trading strategies: Time Series Momentum, Cross-sectional Echo, and Low Volatility.
- Evaluated the performance of each strategy and compared their cumulative returns from 1980 to 2023.

Part 2: Improving the Strategies
- Investigated ways to improve strategies by incorporating macroeconomic conditions, particularly the US Economic Uncertainty Index.
- Analyzed the impact of economic uncertainty on strategy performance and risk attributes.

Part 3: Combining the Strategies
- Combined the three strategies to create an integrated fund, following specific rules for buying and shorting stocks.
- Evaluated the performance of the integrated strategy and compared it to AQR's "Alternative Risk Premia Fund" (MUTF: QRPIX).

Part 4: Diversification Benefit Comparison
- Demonstrated the diversification benefit of the fund by comparing its correlation with the S&P500 index ETF and determining the optimal weight for portfolio allocation.

### Data files
- Monthly_Stock_Returns.csv: includes monthly returns for a large number of stocks in the U.S. The variables include the firm identifier (permno), date, unadjusted end of month price (prc), monthly return (ret), and market capitalization (mcap)
- Daily_Stock_Returns.csv: includes daily return for the stocks in our sample. The variables include the firm identifier (permno), date, and the monthly return (ret)
- US_Policy_Uncertainty_Data.csv: includes the U.S. economic policy uncertainty index, which is based on the information from news papers.
