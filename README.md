This project scrapes motivational quotes and their authors from a public demo website and saves them into a CSV file for easy analysis.

The scraper automatically handles pagination and stops when no more pages are available.

### Website Used

Data is scraped from:

#### https://quotes.toscrape.com

Specifically the Life tag pages.

This site is designed for scraping practice and learning.

### Tech Stack

Python

requests

BeautifulSoup (bs4)

pandas

lxml parser

### What the Script Does

Starts from page 1

Requests each page in sequence

Parses the HTML

Extracts:

Quote text

Author name

Stores everything in a list

Converts the data into a Pandas DataFrame

Exports it to data.csv

Stops automatically when:

the page returns a non-200 status code

OR no quotes are found

### What I Learned From This Project

How to scrape paginated websites

Using BeautifulSoup to navigate HTML

Handling infinite loops safely

Checking HTTP status codes

Storing scraped data with Pandas

Exporting results to CSV
