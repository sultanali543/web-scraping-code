# Web-Scrapping-code

# Product Details Scraper

A simple Python script to scrape product details from a given URL using the `requests` and `BeautifulSoup` libraries. This script is designed to fetch the title, price, rating, and description of a product from a webpage.

---

## Features

- Extracts the following product details:
  - **Title**: The product's name.
  - **Price**: The product's current price.
  - **Rating**: The customer review rating.
  - **Description**: A short description of the product.
- Uses the `requests` library to fetch webpage content.
- Uses `BeautifulSoup` to parse and extract relevant data from the HTML.

---

## Requirements

- Python 3.x
- Libraries:
  - `requests`
  - `beautifulsoup4`

Install the required libraries using:
```bash
pip install requests beautifulsoup4
