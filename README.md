# Analysis and Visualization of Top Tech Stocks 

**Abstract**

Investigates the performance of the top 5 highest valued technology stocks—Microsoft (MSFT), Amazon (AMZN), Apple (AAPL), Alphabet (GOOG), and Meta (META)—during the first half of 2024. Utilizing Python libraries such as Pandas, Pandas-Datareader, Matplotlib, and PyPortfolioOpt, we analyze stock prices, daily simple rate of return, mean returns, variances, standard deviations, and correlations. This analysis provides insights into the similarities, differences, and potential investment opportunities within these tech giants.

**1. Introduction**

The technology sector plays a crucial role in the modern economy, and understanding the performance of leading tech companies is vital for investors and market analysts. This project focuses on five prominent tech stocks: MSFT, AMZN, AAPL, GOOG, and META. Our objective is to leverage data analysis and visualization techniques to gain insights into their price trends and risk-return profiles during the specified period.

**2. Data and Methodology**

**2.1 Data Acquisition:**

We retrieved historical stock data using the yfinance library in Python, covering the period from January 1st, 2024, to July 1st, 2024. This data includes daily adjusted closing prices for each of the five stocks.

**2.2 Methodology:**

Employed the following steps:

Data Loading and Cleaning: Imported necessary libraries (Pandas, NumPy, Matplotlib) and loaded stock data into a Pandas DataFrame.
Adjusted Closing Price Visualization: Plotted the adjusted closing prices over time using Matplotlib to observe overall price trends.
Daily Simple Rate of Return: Calculated and plotted the daily simple rate of return to understand daily price fluctuations.
Mean, Variance, and Standard Deviation: Calculated and visualized the mean, variance, and standard deviation of daily returns to assess risk and potential returns.
Correlation Analysis: Computed the correlation matrix to identify relationships between the stocks.
Portfolio Optimization (using PyPortfolioOpt): Calculated optimal portfolio weights using the Efficient Frontier for maximum Sharpe ratio, considering risk and return.

**3. Results and Discussion**

**3.1 Adjusted Closing Prices:**

Observation: The chart reveals that all five stocks experienced overall growth during the first half of 2024. META experienced the most significant price increase, while AAPL exhibited relatively stable growth. There was a notable dip in the price of META and GOOG around early May but they recovered by July 1st.

**3.2 Daily Simple Rate of Return:**

Observation: The subplots demonstrate the daily volatility of each stock. While all stocks experienced periods of fluctuation, META exhibited the largest swings in daily returns, indicating potentially higher risk. MSFT and AAPL showed relatively lower volatility compared to the other stocks.

**3.3 Mean, Variance, and Standard Deviation:**

Observation:

Mean: META had the highest mean daily return, indicating the greatest potential for gains. AAPL had the lowest mean return, suggesting more moderate growth over the period.
Variance and Standard Deviation: GOOG displayed the highest variance and standard deviation, signaling higher risk and price volatility. META followed with high variance, while AAPL had the lowest, indicating more stable returns.
3.4 Correlation Analysis:

Observation: All stocks exhibited positive correlations, implying they tend to move in the same direction, although the strength varied. MSFT and AMZN showed the highest correlation, suggesting similar market behavior. META and AAPL had the lowest correlation, potentially offering diversification benefits in a portfolio.

3.5 Portfolio Optimization:

The PyPortfolioOpt analysis suggests an optimal portfolio allocation for maximum Sharpe ratio as follows:

MSFT: 33.7%
AMZN: 33.2%
AAPL: 0.0%
GOOG: 33.1%
META: 0.0%
This portfolio achieved an expected annual return of approximately 18.5% with a volatility of around 19.5%, resulting in a Sharpe ratio of 0.95. The optimization process excluded AAPL and META from the portfolio, possibly due to their lower expected returns compared to the other stocks.

4. Conclusion

The analysis revealed that the top 5 tech stocks generally performed well during the first half of 2024. While all showed growth, META recorded the highest returns but with higher risk and volatility. AAPL exhibited more stable returns with lower risk. The correlation analysis highlighted potential for diversification by including stocks with lower correlations. Based on the portfolio optimization using PyPortfolioOpt, an allocation focusing on MSFT, AMZN, and GOOG could offer an attractive risk-return profile.

Limitations and Future Directions:

The analysis is limited to the specific period and relies on historical data, which may not accurately predict future performance. Further research could include analyzing different timeframes, incorporating external market factors, and evaluating different portfolio optimization strategies.
