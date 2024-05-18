# PortfolioOptimizationGeneticAlgorithm

## Personal Project

### Year
2024

### Overview
This project provides a robust framework for optimizing and backtesting portfolio allocations using genetic algorithms. Users can download historical stock data from Yahoo Finance, optimize their portfolios based on historical performance, and evaluate the effectiveness of their investment strategies over selected periods. The system allows for detailed configuration, including the selection of optimization methods (minimizing standard deviation or maximizing Sharpe ratio), strategy start and end dates, as well as a historical lookback period for preliminary testing.

### Features
- **Stock Data Acquisition**: Enables downloading of historical stock data via Yahoo Finance.
- **Genetic Algorithm Optimization**: Utilizes a genetic algorithm to find the optimal portfolio allocation based on user-defined criteria.
- **Customizable Strategy Testing**: Offers flexibility in setting optimization methods, strategy start/end dates, and historical lookback periods for backtesting purposes.
- **Performance Metrics Calculation**: Calculates and presents key investment performance metrics for the chosen period.
- **Comparative Analysis**: Allows users to plot and compare the ROI% of the optimized portfolio against individual stocks over the same period.

### Functionality
The tool is designed to facilitate the empirical testing of portfolio optimization strategies by providing users with the ability to download historical stock data, optimize their portfolios using genetic algorithms, and execute backtests with customizable parameters. It aims to offer valuable insights into the potential profitability of different portfolio strategies through detailed performance metrics and comparative ROI analyses.

### How It Works
Users begin by downloading historical stock data for their chosen tickers via Yahoo Finance. They then proceed to set the parameters for the optimization method (either minimizing standard deviation or maximizing the Sharpe ratio) and define the testing period (including a historical lookback period for initial analysis). The system utilizes a genetic algorithm to optimize the portfolio allocation based on historical performance data. It calculates key performance metrics for the strategy over the selected period and enables users to compare the optimized portfolio's ROI% against the performance of individual stocks, providing a comprehensive view of the strategy's effectiveness.

![alt text](https://github.com/filipenovais/PortfolioOptimizationGA/blob/main/backtest_roi.png)
