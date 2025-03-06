
# Extracting Stock Data Using Python Library

## Overview

This repository contains a Jupyter Notebook that demonstrates how to extract stock market data using Python libraries. The notebook fetches stock data from various sources and processes it for analysis.

A company's stock share is a piece of the company more precisely.
**A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This
entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares".**

## Tools & Techniques

- **Pandas :** Data manipulation and analysis

- **YFinance :** Fetching stock market data

- **Matplotlib :** Data visualization

- **Jupyter Notebook :** Interactive code execution

## Using the yfinance Library to Extract Stock Data

Using the **Ticker** module I had created an object that allowed me to access functions to extract data. To do this I had to provide the ticker symbol for the stock, here the company is Apple & AMD and the ticker symbol used are **AAPL** & **AMD**.

Using the attribute **info** I had extracted information about the stock as a Python dictionary.

## Extracting Share Price

A share is the single smallest part of a company's stock that we can buy, the prices of these shares fluctuate over time.

Using the **history()** method we can get the share price of the stock over a certain period of time. Using the **period** parameter we can set how far back from the present to get data. The options for period are 1 day (1d), 5d, 1 month (1mo) , 3mo, 6mo, 1 year (1y), 2y, 5y, 10y, ytd, and max.

## Extracting Dividends

Dividends are the distribution of a companys profits to shareholders. In this case they are defined as an amount of money returned per share an investor owns. Using the variable **dividends** we can get a dataframe of the data. The period of the data is given by the *period* defined in the history() function.

## Result & Impact

- **Data Processing :** Efficient transformation and handling of stock data

- **Data Retrieval :** Real-time and historical stock data availability

- **Visualization :** Clear and informative stock trend charts

- **Usability :** Easy-to-use interactive data exploration

## Author
- **Email**: vineetgupta798@gmail.com
- **LinkedIn**: [vineet-gupta-01b317231](https://www.linkedin.com/in/vineet-gupta-01b317231/)
