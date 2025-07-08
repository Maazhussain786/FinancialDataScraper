Tesla & GameStop Stock and Revenue Analysis

This project performs web scraping and data analysis on Tesla and GameStop stock prices and quarterly revenues. It extracts financial data from online sources, processes it, and visualizes key trends over time.
Project Overview

    Data Sources:

        Tesla and GameStop quarterly revenue data scraped from specified financial tables.

        Historical stock price data (downloaded or sourced separately).

    Tools and Libraries:

        Python

        Requests

        BeautifulSoup

        Pandas

        Plotly (for interactive visualizations)

    Key Features:

        Web scraping with BeautifulSoup to extract quarterly revenue data.

        Data cleaning and transformation to handle financial formatting.

        Visualization of stock prices and revenue trends with interactive plots.

Getting Started
Prerequisites

Make sure you have the following installed:

    Python 3.x

    pip (Python package manager)

Installation

Install the required Python packages:

pip install requests beautifulsoup4 pandas plotly

Running the Project

    Clone this repository:

git clone https://github.com/your-username/StockRevenueAnalysis.git
cd StockRevenueAnalysis

Run the Python scripts to scrape, process, and visualize data. For example:

    python main.py

Usage

    The make_graph function creates interactive graphs showing stock price and revenue trends.

    Modify or extend the scraping scripts to add more companies or data sources.

Project Structure

/StockRevenueAnalysis
│
├── data/                   # Raw and processed data files (optional)
├── scripts/                # Python scripts for scraping and analysis
├── README.md               # This file
└── main.py                 # Entry point script

Acknowledgments

    Data provided by IBM Developer Skills Network course materials.

    Financial data sources are publicly available online.
