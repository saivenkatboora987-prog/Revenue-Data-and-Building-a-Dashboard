# Revenue-Data-and-Building-a-Dashboard
A Python-based data science project analyzing Tesla and GameStop financial performance. Uses yfinance and BeautifulSoup to scrape/extract stock and revenue data, visualized through a custom Matplotlib dashboard.
Project Summary: Historical Stock & Revenue Analysis Dashboard
This project focuses on the extraction, cleaning, and visualization of historical financial data for Tesla (TSLA) and GameStop (GME). By combining automated data retrieval with web scraping, this project provides a comparative look at share price movements versus corporate revenue growth.

Key Features
Automated Data Extraction: Utilized the yfinance API to retrieve historical stock prices (Open, High, Low, Close, Volume).

Web Scraping: Implemented BeautifulSoup and requests to scrape quarterly revenue data from HTML-based financial reports.

Data Wrangling: Performed data cleaning using pandas to handle missing values and format currency strings into numerical data.

Visual Analytics: Developed a custom Matplotlib dashboard (make_graph) to plot historical share prices and revenue trends on a dual-axis timeline for better correlation analysis.

Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Matplotlib, BeautifulSoup4, Yfinance, Requests

Tools: Jupyter Notebook
