# Project Overview
This project focuses on leveraging financial data and quantitative techniques to construct and analyze optimal investment portfolios. The core objective is to apply principles of modern portfolio theory (MPT) and its derivatives to help hypothetical investors make informed decisions by balancing risk and return. More specifically, the goal was to maximize profits while managing risk, specifically targeting the Sortino(and Sharpe) ratio for optimization.
# Project File Links
[PowerPoint Presentation](https://github.com/angusleebusiness/simple-portfolio-risk-optimizer-sharpe-and-sortino-ratio/blob/main/Risk-Optimized%20Portfolio%20Project%20-%20Angus%20Lee.pptx)

[Spreadsheet ods format](https://pages.github.com/](https://github.com/angusleebusiness/simple-portfolio-risk-optimizer-sharpe-and-sortino-ratio/blob/main/Portfolio%20Optimization%20Personal%20Project%20Finalized%20Spreadsheet%20(Fully%20Optimized).ods))

[Canva Link w/ 🔥 animations](https://www.canva.com/design/DAGrzJZ8qoA/fbJS8rNiaKAiLDugO4W2Eg/view)

# Highlights
 - Leveraged Alpaca API and Python to gather historical data for selected financial instruments. The data was then processed using Pandas DataFrames and exported to a CSV for analysis.
 - Hand-selected a group of stocks spanning various financial instruments: USA equities, international equities, commodities, and fixed-income. Further categorized instruments into areas like big-tech, small market-cap companies, and risky stocks.
 - Utilized an evolutionary algorithm (Differential Evolution) to optimize the financial risk-adjusted return, with range constraints set for each identified category.
 - Calculated the covariance matrix of daily negative returns using Excel's Data Analysis ToolPak. Employed spreadsheet functions to determine total portfolio standard deviation, expected returns, Sortino ratio, and instrument category weights.
 - Achieved a Sortino ratio of 1.96 and an annualized expected return of 20.6%.

# Technologies Used
  - Python: the primary programming language for data mining.
  - Pandas: for data manipulation using DataFrames.
  - Alpaca API & Requests Library: for data source for historical bars.
  - LIbreOffice Calc: the primary software for data analysis and algorithm implementation.
     - DEPS Evolutionary Algorithm: the primary algorithm used in optimizing risk-return ratios.
