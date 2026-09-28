# Automated Equity Analysis

A Python-based equity research tool that automates financial statement analysis, valuation, risk analysis and technical analysis for publicly traded companies.

## Overview

This project uses a user-provided stock ticker to retrieve financial and market data and generate a structured equity research analysis.

The project is split into two Jupyter notebooks:

### 01 — Equity Financial Analysis

Analyses the company's:

* Income statement
* Revenue and earnings growth
* EPS growth
* Gross, operating and net profit margins
* Return on Equity (ROE)
* Return on Assets (ROA)
* Debt-to-equity ratio
* Current, quick and cash ratios
* Operating cash flow
* Capital expenditure
* Free cash flow
* Free cash flow margin and growth

### 02 — Valuation, Risk & Technical Analysis

Analyses:

* Enterprise Value / Revenue
* Enterprise Value / EBITDA
* Peer valuation comparisons
* Historical share-price returns
* Annualised volatility
* 50-day and 200-day moving averages
* Relative Strength Index (RSI)
* Moving Average Convergence Divergence (MACD)
* Automated equity research summary

## Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* yfinance

## How It Works

The user provides a stock ticker, after which the notebooks retrieve the relevant financial and market data and perform the analysis automatically.

The output combines quantitative financial analysis with valuation, risk and technical indicators into a structured equity research report.

The notebooks are designed to work across different publicly traded companies rather than being hard-coded to a single company.

## Project Structure

```text
automated_equity_analysis/
│
├── 01_Equity_Financial_Analysis.ipynb
├── 02_Valuation_Risk_Technical_Analysis.ipynb
└── README.md
```

## Example Output

The analysis produces financial metrics, charts and automated assessments covering company fundamentals, valuation and market risk.

## Disclaimer

This project is for educational and analytical purposes only and does not constitute financial advice or a recommendation to buy or sell any security.

