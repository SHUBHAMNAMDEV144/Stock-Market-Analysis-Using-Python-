# Stock-Market-Analysis-Using-Python-
Business Scenario
Data Science extracts meaningful insight from chunks of raw data, which is useful to different business segments for planning their future course of action. Finance is probably one of the first to catch on to this trend with a rise in the penetration of analytics into many aspects of our lives. Here, we will analyze data from the stock market for some technology stocks such as Apple, Google, Amazon, and Microsoft.

Objective
The objective of this project is to utilize Python libraries such as Pandas, Seaborn, and Matplotlib to extract and analyze information, visualize it, and explore different ways to analyze the risk of a stock based on its performance history.

About the Data
The stocks chosen are from various industries and market caps, namely:

Apple
Google
Microsoft
Amazon
Data is retrieved from Yahoo Finance website directly.

Tasks Performed
Data Retrieval and Cleaning:

Data is fetched directly from Yahoo Finance website using the yfinance library.
Missing values are handled accordingly to ensure data integrity.
Visualization and Analysis:

Stock price change over time is visualized using line plots.
Volume of stocks traded over time is visualized using line plots.
Moving average of stock prices is calculated and plotted.
Daily return average of each stock is calculated.
A new column 'Trend' is added based on daily returns, and trend frequency is visualized using a pie chart.
Correlation between daily returns of different stocks is calculated.
Requirements
Python 3.x
Required libraries: Pandas, Matplotlib, Seaborn, yfinance
Usage
Install the required libraries using pip:
Copy code
pip install pandas matplotlib seaborn yfinance
