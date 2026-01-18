# 📈 Financial Data Pipeline & Interactive Stock Dashboard

## 🎯 Project Overview
This project serves as a comprehensive **data pipeline** designed for a startup investment firm. The primary goal is to automate the **ETL (Extract, Transform, Load)** process for essential financial datasets, including historical share prices and quarterly revenue reports for **Tesla, Amazon, AMD, and GameStop**. By correlating equity performance with fundamental revenue trends, this tool enables investors to perform high-level **quantitative analysis** for data-driven decision-making.

## 🛠️ Tech Stack & Engineering Skills
* **Python**: Core engine for the entire automated pipeline.
* **`yfinance` (API Extraction)**: Leveraged to fetch high-fidelity historical market data (Open, Close, High, Low, Volume).
* **`BeautifulSoup4` & `Requests` (Web Scraping)**: Engineered a custom scraper to parse **HTML tables** for quarterly revenue where public APIs were unavailable.
* **`Pandas` (Data Wrangling)**: Performed intensive cleaning operations, including **regex-based** character removal ($, ,), handling missing values (`.dropna()`), and type-casting strings to `float64` for numerical processing.
* **`Plotly` / `Matplotlib` (Data Visualization)**: Built a synchronized **dual-axis dashboard** to visualize the relationship between stock price volatility and revenue growth.

## 🚀 Key Technical Features
* **Hybrid Data Sourcing**: Seamlessly integrates data from both **RESTful-like APIs** and raw **DOM parsing**.
* **Automated Wrangling Pipeline**: Robust cleaning scripts to standardize currency formats and temporal data.
* **Modular Analytics**: Implemented a reusable `make_graph` function for scalable visualization of multiple stock tickers.

## 📊 Dashboard Preview
> **Note**: Below is a visualization of the correlation between Stock Price and Revenue.
> 
![Stock Dashboard Preview](https://via.placeholder.com/800x400?text=Insert+Your+Tesla/GameStop+Graph+Screenshot+Here) 
*(Tip: Replace this placeholder with your own screenshot saved in an `/images` folder)*.

## ⚙️ Installation & Deployment
1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/AndresGonzalezAlvarez/Stock-Analysis-Dashboard.git](https://github.com/AndresGonzalezAlvarez/Stock-Analysis-Dashboard.git)
    ```
2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Execute the Pipeline**:
    Run the Jupyter Notebook `Revenue Data and Building a Dashboard-v1.ipynb` to regenerate the analysis.
