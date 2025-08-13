📊 Stock Price & Revenue Analysis – Tesla & GameStop
📝 Project Overview

This project demonstrates data collection, cleaning, and visualization for two popular companies – Tesla (TSLA) and GameStop (GME) – using Python.
We analyze both historical stock prices and quarterly revenue data to visualize trends and compare market performance over time.

The project covers:

Extracting stock market data using yfinance

Web scraping financial data (quarterly revenue) from Macrotrends.net

Cleaning & processing datasets with Pandas

Plotting dual-axis graphs for stock price vs revenue using Matplotlib

📂 Dataset Sources

Stock Price Data – Fetched using the yfinance API.

Revenue Data – Scraped from Macrotrends.net (publicly available tables).

⚙️ Tech Stack

Python 3.x

Libraries Used:

yfinance → Fetch stock market data

pandas → Data cleaning & manipulation

requests & io.StringIO → Web scraping HTML tables

matplotlib → Data visualization

dash & plotly (optional future integration) → Interactive dashboards

📈 Workflow Steps
1. Data Collection

Fetch historical stock prices for TSLA and GME from Yahoo Finance via yfinance.

Scrape quarterly revenue data from Macrotrends using requests and pandas.read_html().

2. Data Cleaning

Reset index for stock data.

Filter revenue tables to retain only the relevant Date and Revenue columns.

Remove $ and commas from revenue figures, convert to numeric format.

3. Data Visualization

Plot stock closing price on one axis and quarterly revenue on another (dual y-axis plot).

Separate visualizations for Tesla and GameStop.

📊 Example Output
Tesla Stock Price vs Revenue

📉 Stock price movement over time compared to the company’s revenue growth.

GameStop Stock Price vs Revenue

📉 GameStop’s performance trends alongside quarterly revenue changes.

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/yourusername/stock-analysis.git
cd stock-analysis

2️⃣ Install Dependencies
pip install -r requirements.txt


requirements.txt:

yfinance
pandas
requests
matplotlib
dash
plotly

3️⃣ Run the Script
python stock_analysis.py

📌 Key Learnings

Using yfinance for financial data retrieval.

Extracting tabular data from HTML pages.

Cleaning financial datasets for analysis.

Creating dual-axis charts to compare two related metrics.

📬 Contact

Author – Pritam Ganguly
📧 Email: pritamganguly168@gmail.com
🔗 LinkedIn
💻 GitHub
