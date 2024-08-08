# Momentum Strategy for Stock Analysis
## Overview

This project implements a momentum trading strategy for a single stock using Python. It utilizes the yfinance library to fetch historical stock data, pandas for data manipulation, and Plotly for interactive visualizations. The momentum strategy evaluates the stock's price movement to identify potential buy or sell signals based on past performance.
## Features
* Fetch historical stock data using yfinance
* Calculate momentum indicators
* Analyze stock price trends and momentum indicators with pandas
* Visualize stock price, momentum indicators, and buy/sell signals using interactive Plotly charts

## Prerequisites

* Python 3.7 or higher
* pip (Python package installer)

## Installation

1. Clone the repository:

         git clone https://github.com/yourusername/Algo_trading-analysis.git

2. Navigate to the project directory:

        cd Algo_trading-analysis

3. Create a virtual environment (optional but recommended):
   
        python -m venv venv

4. Activate the virtual environment:

        Windows: venv\Scripts\activate

        MacOS/Linux: source venv/bin/activate

5. Install the required packages:

        pip install -r requirements.txt

## Data

* Stock Data: The project fetches historical stock data using yfinance. You need to specify the stock ticker symbol in the scripts to get the data.

## Results

* Momentum Indicators: The MACD and RSI indicators are calculated to assess the stock's momentum.
* Visualizations: Interactive charts display stock price, providing insights into potential buy or sell signals based on the momentum strategy.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
## Acknowledgments

* yfinance for fetching historical stock data.
* Pandas for data manipulation and analysis.
* Plotly for interactive data visualization.
