# Stock Market Portfolio Clustering

This repository contains a Jupyter notebook for clustering analysis and momentum prediction of stock market portfolios. The analysis involves hierarchical clustering, community detection, and identification of market momentum and types (bear/bull markets).

## Features

- **Download Historical Stock Data:** Retrieves data for selected stocks and S&P 500 ETF (SPY) using Yahoo Finance.
- **Calculate Daily Returns and Normalization:** Computes daily returns and normalizes them for analysis.
- **Hierarchical Clustering:** Performs clustering using various linkage methods and evaluates the clusters.
- **Portfolio Backtesting:** Compares cluster-based portfolio performance against the S&P 500 ETF.
- **Momentum Calculation:** Computes 12-month momentum for each stock.
- **Market Type Identification:** Identifies current market status (bear, bull, or neutral).

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Stock-Market-Portfolio-Clustering.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd Stock-Market-Portfolio-Clustering
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook Stock_Market_Portfolio_Clustering.ipynb
    ```
2. Run the notebook cells sequentially to perform the analysis.

## Dependencies

- yfinance
- pandas
- numpy
- scipy
- scikit-learn
- matplotlib

You can install these packages using:
```bash
pip install yfinance pandas numpy scipy scikit-learn matplotlib
