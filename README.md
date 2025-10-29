
# Web Scraping Project – Largest U.S. Companies by Revenue

This project scrapes data from Wikipedia’s "List of largest companies in the United States by revenue" page using Python. It extracts the company table, stores it in a pandas DataFrame, and saves it as a CSV file.

## Overview
The goal of this project is to practice web scraping using Python libraries such as requests, BeautifulSoup, and pandas. The scraped data is cleaned, organized, and exported for analysis.

## Tools and Libraries
- Python 3
- requests
- BeautifulSoup (bs4)
- pandas
- os

## Steps
1. Sent an HTTP request to fetch the Wikipedia page.
2. Parsed the HTML using BeautifulSoup to locate the target table.
3. Extracted table headers and row data.
4. Created a pandas DataFrame to store the data.
5. Saved the cleaned data as a CSV file in the specified directory.

## Code Summary
- Data source: Wikipedia page containing the list of the largest U.S. companies by revenue.
- Parsing: BeautifulSoup was used to extract the data within the <table> tags.
- Storage: DataFrame created using pandas.
- Export: Saved to CSV using `df.to_csv()`.

## Output
- File name: Companies.csv  
- File location: /Users/rohita/file_sorting_files/csv files/  
- Columns: Rank, Name, Industry, Revenue (USD millions), Revenue growth, Employees, Headquarters  
- Total records: 100 companies

## How to Run
1. Install dependencies:
   ```bash
   pip install requests beautifulsoup4 pandas
