# Stock-Data-API-Integration-Project
A Python project to fetch daily stock prices from the Alpha Vantage API and store them in a SQLite database, demonstrating skills in API integration and backend data management for financial trading applications.

## Features
- Consumes financial data using Python's `requests` library.
- Stores stock prices in a SQLite database with `sqlite3`.
- Includes error handling for API and database operations.
- Applicable to trading tool integration.

## Setup
1. Install dependencies: `pip install requests`
2. Get a free API key from [Alpha Vantage](https://www.alphavantage.co/).
3. Replace `YOUR_API_KEY` in `stock_data_api_integration.py` with your key.
4. Run: `python stock_data_api_integration.py`

## Usage
- Fetches daily closing prices for a specified stock (e.g., IBM).
- Stores data in `stock_prices.db`.
- Prints sample data to verify storage.
