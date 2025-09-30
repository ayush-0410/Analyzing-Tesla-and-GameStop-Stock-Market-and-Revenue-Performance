# Tesla & GameStop Stock and Revenue Analysis

This project provides an in-depth exploration of the financial performance of **Tesla (TSLA)** and **GameStop (GME)** by combining stock market data with company revenue records. It demonstrates how Python can be used to extract, clean, and visualize financial datasets to uncover insights into how company fundamentals and market sentiment interact.

## 📖 Project Overview

* **Objective**
  The goal of this project is to build a comparative analysis of Tesla and GameStop by visualizing their historical stock price movements alongside quarterly revenue trends. The analysis emphasizes not just raw data, but also the story behind how external market factors and company performance correlate.

* **Data Sources**

  * Stock price data is obtained from the **Yahoo Finance API** using the `yFinance` Python library.
  * Revenue data is collected from publicly available web tables using **BeautifulSoup** for web scraping.

* **Data Preparation**

  * Cleaned revenue data by removing formatting artifacts such as dollar signs and commas.
  * Ensured consistent column structures (`Date`, `Revenue`, `Close` price).
  * Converted date strings into proper datetime objects for filtering and time-series plotting.
  * Filtered datasets to highlight performance up to **June 2021**, matching the project’s focus.

* **Visualization & Analysis**

  * Created **dual interactive graphs** (stock prices vs. revenue trends) using **Plotly**.
  * Plots allow visual comparison between market valuation and underlying revenue growth.
  * Highlights the contrast between Tesla’s steady revenue growth and GameStop’s volatile stock price movement during the “meme stock” surge of early 2021.

## 🛠️ Tools & Technologies

* **Python** – core programming language
* **yFinance** – for stock market data collection
* **BeautifulSoup** – for web scraping revenue data
* **Pandas** – for data manipulation and cleaning
* **Plotly** – for interactive data visualization

## 🚀 Key Learning Outcomes

* Gained practical experience in **web scraping** and **API-based data extraction**.
* Strengthened understanding of **time-series analysis** in financial contexts.
* Developed skills in **data cleaning, transformation, and integration** from multiple sources.
* Built interactive, professional-grade visualizations suitable for reports and dashboards.

## 📈 Insights

* Tesla’s stock price aligns closely with its consistent revenue growth, reinforcing investor confidence.
* GameStop shows a stark divergence where stock price volatility far outpaced revenue performance, driven largely by social and speculative market dynamics.
* Combining fundamentals (revenue) with market data (stock price) provides a more complete picture of company performance.

---
