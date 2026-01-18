Financial Data Pipeline & Interactive Stock Dashboard 📈
🎯 Project Overview
This project serves as a comprehensive data pipeline designed for a startup investment firm. The primary goal is to automate the collection, cleaning, and visualization of essential financial data, such as historical share prices and quarterly revenue reports, for companies like Tesla, Amazon, AMD, and GameStop. By correlating stock performance with revenue trends, this tool enables investors to make data-driven decisions.

🛠️ Tech Stack & Skills
Python: Core programming language used for the entire pipeline.

yfinance (API): Utilized to extract historical stock price data (Open, Close, High, Low).

BeautifulSoup & Requests (Web Scraping): Employed to scrape quarterly revenue data from financial websites where APIs were unavailable.

Pandas: Used for intensive data cleaning, handling null values, and formatting currency strings into floats for analysis.

Plotly / Matplotlib: Implemented to create a dual-axis dashboard displaying both stock prices and revenue trends simultaneously.

🚀 Key Features
Automated Data Extraction: Seamlessly pulls data from both financial APIs and HTML tables.

Data Wrangling Pipeline: Robust cleaning process to remove special characters ($, ,) and handle missing data points.

Interactive Analytics: A custom make_graph function that generates synchronized charts for stock price and revenue history.

📊 Dashboard Preview
(I recommend uploading a screenshot of your Tesla or GameStop graph here to showcase your work visually).

⚙️ Installation & Usage
Clone this repository.

Install the required dependencies: pip install -r requirements.txt.

Run the Jupyter Notebook Revenue Data and Building a Dashboard-v1.ipynb to generate the insights.
