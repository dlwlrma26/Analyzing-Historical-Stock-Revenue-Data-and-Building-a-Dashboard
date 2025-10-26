# Extracting and Visualizing Stock Data

# Project Description
This project demonstrates how to extract historical stock data and revenue data for specific companies (Tesla and GameStop) and visualize this information using Python libraries. The primary goal is to compare historical share prices with historical revenue to identify potential correlations or trends.

Data is sourced using the yfinance library for stock information and web scraping techniques (requests and BeautifulSoup) for revenue data from specific web pages. The extracted data is cleaned using pandas and then visualized using plotly to create interactive graphs comparing share price and revenue over time.

# Key Features

Stock Data Extraction: Uses yfinance to fetch historical stock data (Open, High, Low, Close, Volume) for Tesla (TSLA) and GameStop (GME).

Revenue Data Web Scraping: Uses requests and BeautifulSoup to scrape quarterly revenue data for Tesla and GameStop from specific HTML pages.

Data Cleaning: Employs pandas to clean the revenue data by removing currency symbols, commas, and handling missing values.

Data Visualization: Utilizes plotly to generate interactive dashboard-style graphs showing historical share price and revenue trends side-by-side for each company up to mid-2021.

# Technologies Used

Python 3

Jupyter Notebook

Libraries:

yfinance

pandas

requests

beautifulsoup4 (bs4)

plotly

warnings

nbformat (mentioned in pip installs, likely for notebook handling)

Data Sources

Stock Data: Yahoo Finance (accessed via yfinance library)

Tesla Revenue Data: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm (scraped)

GameStop Revenue Data: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html (scraped)


Run the cells sequentially to execute the data extraction, cleaning, and visualization steps.

The final cells will display the interactive Plotly graphs for Tesla and GameStop.

Authors
