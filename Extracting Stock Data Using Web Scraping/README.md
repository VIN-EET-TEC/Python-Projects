# Extracting Stock Data Using Web Scraping

This repository contains a Jupyter Notebook that demonstrates how to extract stock market data using web scraping techniques. The notebook scrapes stock data from financial websites and processes it for analysis.

## Features

- Scrape real-time stock data from financial websites
- Process and clean scraped data
- Visualize stock market trends using Python libraries
- Includes details on tools, techniques, and their impact

## Tools & Techniques

- **BeautifulSoup :** Web scraping and parsing HTML

- **Requests :** Sending HTTP requests to fetch webpage data

- **Pandas :** Data manipulation and analysis

- **Matplotlib :** Data visualization

- **Jupyter Notebook :** Interactive code execution

## Table of Contents

- Extracting data using BeautifulSoup
    - Download the web page Using Requests Library
    - Parse HTML on a web page using BeautifulSoup
    - Extract data and duild a data frame
- Extracting data using pandas

## Using Webscraping to Extract Stock Data of Netflix & Amazon

I had extracted Netflix stock data [https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/netflix_data_webpage.html](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/netflix_data_webpage.html).


Using the **requests** library to download the webpage [https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/amazon_data_webpage.html](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/amazon_data_webpage.html). Saving the text of the response as a variable named **html_data**.

### Steps for extracting the data
1. Send an HTTP request to the web page using the requests library.
2. Parse the HTML content of the web page using BeautifulSoup.
3. Identify the HTML tags that contain the data you want to extract.
4. Use BeautifulSoup methods to extract the data from the HTML tags.
5. Print the extracted data

### What is parsing?

In simple words, parsing refers to the process of analyzing a string of text or a data structure, usually following a set of rules or grammar, to understand its structure and meaning.
Parsing involves breaking down a piece of text or data into its individual components or elements, and then analyzing those components to extract the desired information or to understand their relationships and meanings.

### Working on HTML table

These are the following tags which are used while creating HTML tables.

- &lt;table&gt;: This tag is a root tag used to define the start and end of the table. All the content of the table is enclosed within these tags. 

- &lt;tr&gt;: This tag is used to define a table row. Each row of the table is defined within this tag.

- &lt;td&gt;: This tag is used to define a table cell. Each cell of the table is defined within this tag. You can specify the content of the cell between the opening and closing <td> tags.

- &lt;th&gt;: This tag is used to define a header cell in the table. The header cell is used to describe the contents of a column or row. By default, the text inside a <th> tag is bold and centered.

- &lt;tbody&gt;: This is the main content of the table, which is defined using the <tbody> tag. It contains one or more rows of <tr> elements.

## FAQ

**Question1:** What is the content of the title attribute?

**Question2:** What are the names of the columns in the data frame?

**Question 3:** What is the **Open** of the last row of the amazon_data data frame?


## Author
- **Email**: vineetgupta798@gmail.com
- **LinkedIn**: [vineet-gupta-01b317231](https://www.linkedin.com/in/vineet-gupta-01b317231/)

