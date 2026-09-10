Project Overview

This project demonstrates how to scrape and extract data from a web page using Python. The project collects information about the largest companies in the United States by revenue from Wikipedia and converts the extracted data into a structured CSV dataset.

The project was developed as part of my Data Analytics portfolio to demonstrate practical skills in web scraping, data extraction, and data organization using Python.

Objectives

1. Extract company information from a web page
2. Practice web scraping using Python
3. Parse HTML tables using BeautifulSoup
4. Convert scraped data into a Pandas DataFrame
5. Export the cleaned data into a CSV file
6. Create a reusable workflow for collecting structured web data

---

Tools & Technologies

1. Python
2. Requests — Retrieve web page content
3. BeautifulSoup — Parse and extract HTML data
4. Pandas — Structure and manage the scraped data
5. Jupyter Notebook — Develop and document the analysis
6. CSV — Store the extracted dataset

---

Dataset

The dataset contains information on the 100 largest companies in the United States.

Variables

| Column                   | Description                    |
| ------------------------ | ------------------------------ |
| `Rank`                   | Company's ranking              |
| `Name`                   | Company name                   |
| `Industry`               | Company's industry             |
| `Revenue (USD millions)` | Annual revenue in USD millions |
| `Revenue growth`         | Revenue growth percentage      |
| `Employees`              | Number of employees            |
| `Headquarters`           | Company headquarters location  |

---

Project Workflow

The project follows these main steps:

1. Import the required Python libraries
2. Send a request to the source webpage using `Requests`
3. Parse the HTML content using `BeautifulSoup`
4. Identify the relevant HTML table
5. Extract the table headers
6. Extract company information from each row
7. Store the extracted information in a Pandas DataFrame
8. Export the DataFrame as a CSV file
