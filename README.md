# Financial Market Trends Analysis
## Overview

This project dives deep into the financial market trends of the past decade. With the rapid integration of Artificial Intelligence into various sectors, we have observed significant revenue growth in numerous companies. This analysis aims to explore, analyze, and visualize the financial data of some of the leading US companies to provide insights into their performance and market trends.

## Companies Analyzed:

NVIDIA

META (Facebook)

Microsoft

Black Rock

Goldman Sachs

Google

.
├── financial_marketing.ipynb  # Main Jupyter notebook containing the analysis

├── machine_learning. ipynb    # machine learning models for fianancial markets

└── README.md                  # This file


## Key Features
`Data Collection`: Leveraging the `quantstats` library to fetch daily returns of the aforementioned companies.

`Data Preprocessing`: Ensuring data consistency by setting a specific date range and adjusting time zones.

`Data Visualization`: Comprehensive visualizations of daily returns for each company, providing insights into their performance over time.

### Libraries Used
* Data Handling and Statistical Analysis:
  * pandas
  * pandas_datareader
  * numpy
  * scipy.stats
* Data Visualization:
  * matplotlib.pyplot
  * seaborn
  * plotly
* Optimization and Allocation:
  * pypfopt
* Financial Data:
  * quantstats
  * ta
  * yfinance
* Modeling:
  * sklearn.linear_model
* Other Utilities:
  * plotly
  * datetime
  * warnings