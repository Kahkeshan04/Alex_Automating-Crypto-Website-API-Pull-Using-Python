# Crypto Data Analysis with CoinMarketCap API

## Overview

This project explores cryptocurrency data using the CoinMarketCap API and Python libraries such as Pandas, Matplotlib, and Seaborn. The goal is to gain insights into cryptocurrency market trends and perform data analysis and visualization.

## Key Insights and Learnings

### 1. Data Retrieval

- Utilized the CoinMarketCap API to fetch the latest cryptocurrency listings.
- Explored various parameters such as `start`, `limit`, and `convert` to customize API requests.
- Handled potential errors like connection errors, timeouts, and too many redirects.

### 2. Data Processing and Analysis

- Processed the retrieved data using Pandas to transform it into a structured format.
- Normalized data using `pd.json_normalize()` to handle nested JSON structures.
- Calculated descriptive statistics like mean, median, and standard deviation.

### 3. Data Visualization

- Created informative visualizations using Matplotlib and Seaborn.
- Visualized cryptocurrency prices over time using line plots.
- Analyzed percentage change in prices using point plots.
- Explored trends in price changes over different time intervals (1 hour, 24 hours, 7 days, etc.).

### 4. Automation

- Developed a script (`api_runner.py`) to automate data retrieval from the CoinMarketCap API.
- Scheduled the script to run periodically using cron jobs or task scheduler.
- Explored optimizations for data retrieval and processing workflows.
