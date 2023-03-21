# Amazon-Product-Scraper
This is a Python script that scrapes product information from Amazon India's website. 
The script extracts data such as product name, price, rating, number of reviews, description, ASIN, and manufacturer.

# Getting Started
To use the scraper, follow these steps:

Clone the repository or download the code as a zip file and extract it.
Install the required packages by running pip install -r requirements.txt.
Run the main.py script. The output will be stored in a CSV file named product_data.csv in the same directory.
Usage
The script scrapes data from the Amazon India website by sending HTTP requests and parsing the HTML content using the Beautiful Soup library.

The script consists of two parts:

Part 1: Scrape product information from the product listing pages. This includes the product URL, product name, product price, rating, and number of reviews.
Part 2: Hit each product URL received in the previous step and fetch additional information such as description, ASIN, product description, and manufacturer.
The script can be customized to scrape information for different product categories by modifying the URL in the url_template variable.

# Limitations
Scraping data from websites may violate the website's terms of service and may be illegal in some jurisdictions. This script is for educational purposes only and should not be used to scrape data from websites without their explicit permission. Additionally, Amazon may block IP addresses that send too many requests, so use the scraper at your own risk.




