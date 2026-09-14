# Stock Price Analysis — Moving Average Crossover Strategy

## What it does
Pulls real historical stock price data for Apple (AAPL) using the 
yfinance API, calculates 20-day and 50-day moving averages, generates 
buy and sell signals based on crossover points, and backtests the 
strategy against a simple buy and hold approach.

## Key finding
The MA crossover strategy returned 10.6% vs 54.8% for buy and hold 
over 2023. This underperformance is expected in a strong bull market 
— the lagging nature of moving averages means the strategy misses 
early gains. It would likely outperform in a volatile or bearish market 
where cutting losses early has more value.

## Technologies used
- Python
- pandas — data manipulation
- yfinance — pulling real market data
- matplotlib — visualisation

## How to run it
1. Clone the repository
2. Install dependencies: pip install pandas yfinance matplotlib
3. Open stock_analysis.ipynb in Jupyter notebook and run all cells
