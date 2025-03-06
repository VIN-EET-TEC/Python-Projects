
# Extracting Stock Data Using Python Library

A company's stock share is a piece of the company more precisely:

**A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This
entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares".**

An investor can buy a stock and sell it later. If the stock price increases, the investor profits, If it decreases,the investor with incur a loss. Determining the stock price is complex; it depends on the number of outstanding shares, the size of the company's future profits, and much more. People trade stocks throughout the day the stock ticker is a report of the price of a certain stock, updated continuously throughout the trading session by the various stock market exchanges.

In this project I'll be extracting stock data using a Python library. I'll use the yfinance library, it allows me to extract data for stocks returning data in a pandas dataframe.

## Table of Contents

- Using yfinance to Extract Stock Info
- Using yfinance to Extract Historical Share Price Data
- Using yfinance to Extract Historical Dividends Data

## Using the yfinance Library to Extract Stock Data

Using the ***Ticker*** module we can create an object that will allow us to access functions to extract data. To do this we need to provide the ticker symbol for the stock, here the company is Apple & AMD and the ticker symbol is ***AAPL*** & ***AMD***.

### Stock Info

Using the attribute **info** I had extracted information about the stock as a Python dictionary.

## Extracting Share Price

A share is the single smallest part of a company's stock that we can buy, the prices of these shares fluctuate over time. Using the ***history()*** method we can get the share price of the stock over a certain period of time. Using the ***period*** parameter we can set how far back from the present to get data. The options for **period** are 1 day (1d), 5d, 1 month (1mo) , 3mo, 6mo, 1 year (1y), 2y, 5y, 10y, ytd, and max.

## Extracting Dividends

Dividends are the distribution of a companys profits to shareholders. In this case they are defined as an amount of money returned per share an investor owns. Using the variable **dividends** we can get a dataframe of the data. The period of the data is given by the period defined in the ***history()*** function.

## Author
- **Email**: vineetgupta798@gmail.com
- **LinkedIn**: [vineet-gupta-01b317231](https://www.linkedin.com/in/vineet-gupta-01b317231/)

Tool

Technique

Pandas

Data manipulation and analysis

YFinance

Fetching stock market data

Matplotlib

Data visualization

Jupyter Notebook

Interactive code execution
