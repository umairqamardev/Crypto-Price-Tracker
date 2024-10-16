# Crypto-Price-Tracker
Overview

The Crypto Price Tracker project automates the extraction of cryptocurrency pricing data from the CoinMarketCap API. This application retrieves the latest cryptocurrency listings, processes the data, and generates visualizations to analyze price trends over time. It serves as a practical tool for tracking cryptocurrency price changes and understanding market dynamics.
Technologies Used

  Programming Language: Python
    Libraries:
        Requests: For making HTTP requests to the CoinMarketCap API.
        Pandas: For data manipulation and analysis.
        Matplotlib: For data visualization.
        Seaborn: For enhanced visualizations and statistical graphics.
    APIs: CoinMarketCap API for fetching cryptocurrency data.

Features:

  Automated Data Retrieval: Regularly fetches cryptocurrency price data using the CoinMarketCap API.
    Data Cleaning and Transformation: Normalizes the data and handles any inconsistencies to ensure accuracy.
    Data Visualization: Creates visual representations of price trends over different time frames (1 hour, 24 hours, etc.) using Seaborn and Matplotlib.
    Flexible Data Analysis: Allows for dynamic querying of specific cryptocurrencies (e.g., Bitcoin) for focused analysis.

Key Learnings:

  Gained hands-on experience in working with RESTful APIs to fetch real-time data.
    Developed skills in data manipulation using Pandas, including data cleaning, transformation, and aggregation.
    Learned to implement error handling for HTTP requests to manage potential connection issues and timeouts.
    Enhanced knowledge of data visualization techniques to present complex data insights effectively.


The project consists of a Python script that performs the following functions:

  Fetches Data: Uses the Requests library to send GET requests to the CoinMarketCap API, retrieving the latest cryptocurrency prices.
    Processes Data: Parses the returned JSON data, normalizing it into a structured format using Pandas DataFrames.
    Visualizes Data: Creates visualizations to analyze price trends, including line plots for specific cryptocurrencies and categorical plots for price changes over various timeframes.
    Automates Execution: Incorporates a loop to continuously fetch data at regular intervals, ensuring up-to-date pricing information.

Conclusion:

This project serves as a practical application of data extraction, manipulation, and visualization techniques using Python, showcasing the ability to automate data workflows for cryptocurrency analysis. It lays the foundation for further exploration in data analytics and financial modeling.
