
![Galpha Project Logo Official](https://github.com/user-attachments/assets/f35b1c34-8986-4dca-8c1f-d5e66fd1ec6f)


# Galpha - Stock Analysis and Portfolio Optimisation 
Python-based stock analysis and portfolio optimisation project — overview of objectives, structure, and techniques used.


# About this project
The decision to start this project came from my interest in financial markets and the world of investing. In the 8th grade, I read my first book about investments in stocks and bonds and was amazed by this system. In high school, I took Economics as a Higher Level subject on the International Baccalaureate (IB) programme and explored fundamental areas, such as microeconomics, macroeconomics, and global trade. At that time, I already knew that I would study finance at the university. Currently, I am a Year 4 Business and Finance student with equity research experience and cleared CFA Level 1. As I am approaching graduation, I am planning to start investing a portion of my income into stocks. Given my previous experience in stock analysis and actively growing knowledge of Python, I decided to utilise both of them and create the project Galpha. Letter “G” comes from my first name, while “alpha” comes from alpha-strategy, which represents the value an active fund manager or an investment strategy adds by using skill, information, and unique insights.

# Problem: 
Analysing stocks is time-consuming and difficult, especially when it comes to generating a complete equity research report and building a DCF valuation model for a single company. Moreover, there are thousands of different stocks, so it may be difficult to select which industries to explore and what stocks to choose to build a profit-maximising and risk-minimising portfolio over the long term. Lastly, many websites provide financial data and calculate key ratios, but they have one issue: doing peer analysis is inconvenient and building an efficient portfolio is extremely difficult. 

# Solution: 
The Galpha project aims to streamline the process of analysing and selecting the optimal stocks for creating a portfolio with maximised returns and minimised risks. By incorporating many techniques into stock analysis, such as fundamental, technical, and AI-assisted sentiment analysis, and presenting them in one space, I aim to facilitate the process of exploring the stock, increase the user-friendliness of the results to users, and reduce the need for costly licenses, portfolio management software, and data providers. All financial data for this project is taken from Yahoo Finance. Since the project is currently in the development phase, it was decided to select only US large-cap stocks because of the substantial data availability and news coverage. 




# Source code available upon request.
The request can be done via email or LinkedIn. 



# Structure with main folders and description of folders

# 1. Data integration 
# Status: Currently Finished (Open to Updates)
Content: This module uses yfinance (Python library for Yahoo Finance data) to download price and volume data of the US large-cap stocks for the last 5 years, as well as their financial statements for the last 5 years, clean this data, standardise name formatting, check for missing values, convert data into csv files, and conduct statistical analysis of returns and price changes.

# 2. Initial screening 
# Status: Currently Finished (Open to Updates)
Content: This module performs sector fetching, liquidity screening, market capitalisation filtering, volatility analysis, validation, etc.

# 3. Fundamental analysis 
# Status: In Progress
Content: Fundamental analysis is a crucial section of the project which starts with preprocessing the data by creating a dictionary and ensuring all components of financial statements are properly saved in the system for further analysis and usage. This process is followed by computation and analysis of key ratios, exploration of deep value or contrarian ratios, investigation of earnings quality, performance of peer analysis, creation of stocks ranking, and completion of the quality check. If this idea is found feasible, simple DCF modelling can be implemented. 

# 4. Portfolio optimisation 
# Status: Coming Soon
Content: This section is designed to run Monte Carlo simulations, model efficient frontier, calculate risk-adjusted performance metrics, conduct correlation analysis using a heatmap, etc. 

# 5. Technical analysis 
# Status: Coming Soon
Content: This section will utilise the most prominent technical analysis indicators and techniques to identify momentum, trends, and patterns of stocks. 

# 6. AI-assisted sentiment analysis 
# Status: Coming Soon 
Content: This module may contain a code that will use Twitter (now X) APIs to analyse news and posts about stocks to come up with a "good", "neutral", or "bad" sentiment with respect to them.

# 7. Backtesting 
# Status: Coming Soon
Content: This module performs a backtest of the investment strategy against historical data. It is designed to evaluate the strategy's performance and risk profile before live deployment.

# Actual Proof of Work
Please see the photo below, demonstrating the contributions made to the project. 
<img width="1224" height="391" alt="Github Galpha Proof of Work photo" src="https://github.com/user-attachments/assets/d02d3db3-c91c-4cf1-9116-58e22ccd3513" />


# Disclaimer
This project and the abovementioned structure do not constitute financial advice. The author, Georgii Khvedelidze, and all affiliates do not provide recommendations through this project. Georgii Khvedelidze is not responsible for investment actions taken by viewers, and his project should not be used as a basis for investment trades. 






