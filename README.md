# MSFT-Stock-Analysis
Python-based analysis of Microsoft (MSFT) stock using intraday market data and technical indicators to identify short-term price trends and momentum.

📌 Project Overview

This project presents an analytical study of Microsoft Corporation (MSFT) stock price movements using historical market data. The analysis focuses on short-term intraday trends through the application of technical indicators, particularly moving averages (5 minutes and 15 minutes), to understand price behavior and momentum.

The project is intended for educational and analytical purposes, demonstrating practical financial data analysis using Python.

🎯 Objectives

To analyze MSFT stock price movements using intraday data

To identify short-term trends using moving averages

To visualize price action and trend behavior clearly

To derive actionable insights from technical indicators

📊 Data Description

Stock: Microsoft Corporation (MSFT)

Data Frequency:

5-minute intervals

15-minute intervals

Features Used:

Open

High

Low

Close

Volume

Data Source: Yahoo Finance

🔧 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook

🧹 Data Preprocessing

The following preprocessing steps were applied:

Converted timestamps to datetime format

Removed missing and duplicate values

Sorted data in chronological order

Selected relevant price and volume fields

📈 Exploratory Data Analysis

Initial exploration focused on:

Price movement over time

Trading volume patterns

Identification of volatility periods

Line charts were used to visualize closing price trends across different time intervals.

📉 Technical Indicators Used

The analysis applies moving averages to smooth price fluctuations and identify trend direction:

Short-term Moving Average (SMA) – captures immediate price momentum

Medium-term Moving Average (SMA) – confirms broader intraday trends

These indicators help highlight trend continuation and potential reversals.

🔍 Key Insights

Periods where the price remained above the moving average indicated bullish momentum

Frequent price crossovers suggested short-term market indecision

Volume spikes aligned with strong price movements, confirming trend strength

The 15-minute interval provided more stable trend signals compared to the 5-minute interval

