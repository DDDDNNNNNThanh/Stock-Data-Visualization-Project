# Stock-Data-Visualization-Project

---

This project focuses on extracting and analyzing stock data for Tesla (TSLA) and GameStop (GME) using various Python libraries and techniques.

## Table of Contents

- [Define a function to make graph](#define-a-function-to-make-graph)
- [Use yfinance to Extract Stock Data](#use-yfinance-to-extract-stock-data)
- [Use Webscraping to Extract Tesla Revenue Data](#use-webscraping-to-extract-tesla-revenue-data)
- [Use Webscraping to Extract GME Revenue Data](#use-webscraping-to-extract-gme-revenue-data)
- [Plot Tesla Stock Graph](#plot-tesla-stock-graph)
- [Plot GME Stock Graph](#plot-gme-stock-graph)

## Define a function to make graph

The `make_graph` function is responsible for creating a graph that displays the historical share price and revenue data for a given stock. It utilizes the `plotly` library to generate interactive plots.

```python
import yfinance as yf
import pandas as pd

def my_function():
print("Hello, world!")

x = 10
```

## Use yfinance to Extract Stock Data

The `yfinance` library is used to extract historical stock data for Tesla (TSLA) and GameStop (GME). The retrieved data is stored in Pandas DataFrames.

## Use Webscraping to Extract Tesla Revenue Data

Web scraping techniques are employed to extract revenue data for Tesla from a specific URL. The `requests` and `BeautifulSoup` libraries are used to retrieve and parse the HTML data, respectively.

## Use Webscraping to Extract GME Revenue Data

Similar to the previous step, web scraping is performed to extract revenue data for GameStop from a different URL.

## Plot Tesla Stock Graph

This section utilizes the `make_graph` function to plot the historical share price and revenue data for Tesla. The stock data is filtered to include only a specific date range.

## Plot GME Stock Graph

Similar to the previous section, this part uses the `make_graph` function to plot the historical share price and revenue data for GameStop. The stock data is also filtered to a specific date range.

---

To execute the code and visualize the graphs for Tesla, you can call the `make_graph` function at the end of the code with the appropriate parameters:

```python
make_graph(tesla_data, tesla_revenue, 'TSLA')
```

Please note that you may need to install the required libraries (`yfinance`, `pandas`, `requests`, `bs4`, `plotly`) if you haven't done so already.

I hope this description helps! Let me know if you have any further questions.
