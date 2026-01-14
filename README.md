# Stock-Data-Scraping-Analysis
A Python project using BeautifulSoup and yfinance to analyze historical stock and revenue trends for Tesla and GameStop.

## Project Overview
This project focuses on extracting essential financial data for **Tesla (TSLA)** and **GameStop (GME)** to visualize the relationship between historical stock prices and quarterly revenue.

## Key Technical Skills
* **API Integration:** Extracted max period stock data using the `yfinance` library.
* **Web Scraping:** Utilized `BeautifulSoup` and `Requests` to parse HTML tables for quarterly revenue data.
* **Data Engineering:** Cleaned currency data using `Pandas` by removing special characters ($, ,) and handling null values.
* **Data Visualization:** Built a custom graphing function with `Matplotlib` to display dual-axis charts of Share Price vs. Revenue.

## Project Structure
The analysis is organized into the following questions:
1. Extracting Tesla stock data via yfinance.
2. Scraping Tesla revenue data from a web source.
3. Extracting GameStop stock data.
4. Scraping GameStop revenue data.
5. Visualizing Tesla stock and revenue trends.
6. Visualizing GameStop stock and revenue trends.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install yfinance pandas requests bs4 matplotlib`.
3. Open the `.ipynb` file in Jupyter Notebook or Google Colab.
