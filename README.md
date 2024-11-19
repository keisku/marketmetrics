# Market Metrics

Market Metrics is a Python application for technical stock market analysis. It allows users to analyze stock data using various technical indicators and visualize the results.

## Features

- Fetch stock data using the Yahoo Finance API
- Calculate and plot technical indicators such as:
  - Moving Averages (MA)
  - Relative Strength Index (RSI)
  - Moving Average Convergence Divergence (MACD)
  - Bollinger Bands
  - Fibonacci Retracement Levels
  - Mark Golden Crosses and Death Crosses

## Usage

1. Install [rye](https://rye.astral.sh/guide/installation/)
2. `rye sync`
3. `rye run marketmetrics`
4. Dialog will prompt you to enter a stock symbol.

## Contributing

- `rye test` for run pytest.
- `rye run ruff format` for format code.
