# Cryptocurrency Data Analysis Tool

This tool is designed to facilitate the retrieval and analysis of cryptocurrency data using the CoinGecko API. It provides a simple interface to extract data for specific cryptocurrencies within a given time range and generate line plots for visual analysis.

#### Features
1. Retrieve cryptocurrency data: use the get_crypto_data function to retrieve data for specific cryptocurrencies, including prices, market cap, and total volume within a specified time range.

2. Generate line plots for single currency: utilize the generate_line_plot_single_currency function to generate separate line plots for price, market cap, and total volume against a timeframe for a single currency.

3. Generate line plots for multiple currencies: use the generate_line_plots_multiple_currencies function to generate line plots for multiple currencies, either combined into a single graph or displayed as separate line plots.

#### Prerequisites
Python 3.8 or above  
Required Python packages: pycoingecko, pandas, matplotlib

#### Installation
Install the required packages:

$ pip install pycoingecko pandas matplotlib

#### Usage

1. Import the necessary modules in your Python code:


```python
from pycoingecko import CoinGeckoAPI
import pandas as pd
import matplotlib.pyplot as plt
```

2. Use the provided functions (get_crypto_data, generate_line_plot_single_currency, generate_line_plots_multiple_currencies) to retrieve cryptocurrency data and generate line plots based on your analysis requirements. Refer to the function documentation for detailed usage examples.

3. Modify the parameters within the functions to specify the cryptocurrency identifiers, time range, and other relevant settings based on your analysis needs.

4. Run your Python code and view the generated line plots to gain insights into the cryptocurrency data.

#### Examples
For example usage of the tool, refer to the provided Jupyter Notebook (cgTool.ipynb). The notebook demonstrates how to retrieve cryptocurrency data, generate line plots, and customize the visualization based on user preferences.



