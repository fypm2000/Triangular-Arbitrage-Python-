# Triangular Arbitrage-Python

## Objective

The objective of this project is to create a Python script that fetches real-time cryptocurrency prices (BTC, ETH, LTC) in USD from the CoinGecko API and detects triangular arbitrage opportunities in the cryptocurrency market, facilitating algorithmic trading strategies.

### Skills Learned

- Fetching data from an API using the requests library: learned how to interact with web APIs to retrieve data by sending HTTP requests using the requests library in Python. This skill is essential for accessing real-time or historical data from various online sources.
- Parsing JSON data: data obtained from APIs is often in JSON format. Learned how to parse this data in Python, extracting relevant information and converting it into a usable format. Understanding JSON parsing is crucial for working with web APIs effectively.
- Implementing algorithmic trading strategies: This project introduced you to the concept of algorithmic trading and provided practical experience in designing and implementing trading strategies, specifically triangular arbitrage, to exploit price discrepancies in the cryptocurrency market.

### Tools Used

- Python
- 'requests' library
- CoinGecko API

## Steps

- Import the requests library.
- Define a function fetch_prices() to fetch cryptocurrency prices from the CoinGecko API.
- Implement a function find_arbitrage_opportunity(prices) to calculate and detect triangular arbitrage opportunities.
- Create a main() function to orchestrate the process.
- In the main() function, fetch cryptocurrency prices using fetch_prices().
- Check for triangular arbitrage opportunities using find_arbitrage_opportunity(prices).
- Print the result indicating whether an arbitrage opportunity is detected or not.
- Handle error cases such as failed API requests or missing data.
