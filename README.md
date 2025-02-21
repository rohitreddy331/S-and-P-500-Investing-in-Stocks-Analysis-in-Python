# 📈 Investing in Stocks: Buy-and-Hold vs. Momentum Trading Using Modern Portfolio Theory (MPT)


# 🛠 Python Libraries & Packages Used


To analyze investment strategies, we used various Python libraries for data processing, financial modeling, and visualization. These helped in retrieving stock data, optimizing portfolio allocation, and comparing strategies effectively.

Pandas & NumPy → Data processing and analysis


Matplotlib & Seaborn → Visualizing trends, returns, and portfolio performance


Pyomo → Portfolio optimization using Modern Portfolio Theory (MPT)

SciPy → Mathematical computation and risk-return calculations


Yahoo Finance API → Retrieving real-time and historical stock data


Requests-HTML → Web scraping stock-related data


IDAES-PSE → Simulation and optimization


Yahoo_fin → Market data analysis


# 🏆 Project Overview


This project aims to analyze and compare three investment strategies—Buy-and-Hold, Momentum Trading, and Modern Portfolio Theory (MPT)—to identify the best risk-return trade-off. We used historical stock data from 2017 to 2023 and tested different investment strategies to measure profitability and stability.

Compared three investment strategies: Buy-and-Hold, Momentum Trading, and MPT.


Used historical stock data from 2017 to 2023.


Goal: Maximize returns while minimizing risk.


# 🔍 Data Collection & Preprocessing


We retrieved historical stock data from Yahoo Finance and compiled a list of S&P 500 companies from Wikipedia. We focused on three key sectors—Industrials, Technology, and Real Estate—to create a well-diversified portfolio.

Selected three sectors: Industrials, Technology, Real Estate.


Filtered 10 stocks per sector to create a diversified portfolio.


Computed daily returns using adjusted closing prices.


# 📊 Investment Strategies Implemented


# 🏦 Buy-and-Hold Strategy


Buy-and-Hold is a passive investment strategy where stocks are purchased and held for a long period without trading. We invested $100,000 equally among three stocks (MSFT, ETN, PSA) at the start of 2023 and tracked their performance. The final portfolio value showed steady growth with minimal risk.

Invested $100,000 in three selected stocks (MSFT, ETN, PSA).


Held investments throughout the year without trading.


Final portfolio value: $147,546


# ⚡ Momentum Trading Strategy


Momentum trading is a trend-following strategy where stocks are bought if their short-term moving average crosses above the long-term moving average. We applied an 8-day vs. 21-day Moving Average Crossover strategy to identify buy and sell signals dynamically and tested it on MSFT, ETN, and PSA.

MSFT: $99,941 profit


ETN: $25,454 profit


PSA: -$12,043 loss


Final portfolio value: $137,093


Higher volatility compared to Buy-and-Hold


# 📈 Modern Portfolio Theory (MPT)


Modern Portfolio Theory (MPT) optimizes investment allocation to maximize returns while minimizing risk. Using Pyomo, we built an Efficient Frontier and determined the best-performing portfolio at a risk level of 0.000216. The optimized portfolio allocated 67% to MSFT, 22% to ETN, and 11% to PSA.

MPT allocates investments to minimize risk and maximize returns.


67% MSFT, 22% ETN, 11% PSA for optimal portfolio balance.


Final portfolio value: $154,698 (highest return among all strategies).


# 📉 Risk vs. Return Analysis


To measure the effectiveness of each strategy, we analyzed risk-adjusted returns. MPT provided the highest return with stability, while Momentum Trading had high volatility, making it less predictable. Buy-and-Hold delivered steady growth with lower risk.

MPT Portfolio: Highest return with stability.


Momentum Trading: High risk and volatile performance.


Buy-and-Hold: Steady growth with low risk.

# MPT Portfolio 🏆 → Initial Investment: $100,000, Final Value: $154,698, Profit/Loss: +$54,698 ✅


# Buy-and-Hold 🏦 → Initial Investment: $100,000, Final Value: $147,546, Profit/Loss: +$47,546 ✅


# Momentum Trading ⚡ → Initial Investment: $100,000, Final Value: $137,093, Profit/Loss: +$37,093 ⚠️




# 📊 Comparison with S&P 500 Index

To compare the strategies against the market performance, we applied Buy-and-Hold and Momentum Trading strategies to the S&P 500 index. The Buy-and-Hold approach resulted in portfolio growth from $100,000 to $120,148, while Momentum Trading on the index produced fewer profitable signals.

Buy-and-Hold on S&P 500: $120,148 final value.


Momentum Trading on S&P 500: Lower success rate than MPT.


MPT consistently outperformed the S&P 500 Buy-and-Hold strategy.


# 🔮 Conclusion & Investment Takeaways


MPT provides the best balance between risk and return, making it the most effective investment strategy. While Momentum Trading offers high returns, it comes with significant risk and volatility. Buy-and-Hold remains a solid long-term strategy with consistent growth.

MPT provided the highest risk-adjusted return.


Momentum Trading had high potential but was riskier.


Buy-and-Hold showed stable returns with minimal risk.


# 📌 Future Enhancements


Expand analysis to include NASDAQ and Dow Jones stocks.


Explore additional strategies like Mean Reversion and Trend Following.


Implement Machine Learning models for automated investment optimization.


# 📢 Want to Explore More?


📬 Feel free to connect on LinkedIn (https://www.linkedin.com/in/rohit-reddy-marreddy-229472222/) or explore the repository for detailed code and insights!



# 🚀 Happy Investing! 📈💰



