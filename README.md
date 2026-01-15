## Amazon Product Web Scraper

A Python-based web scraping tool built using Beautiful Soup and Requests to extract Amazon product information such as title and price. This project demonstrates real-world web scraping techniques, HTTP request handling, and HTML parsing for data extraction.

## Project Overview

Tracking product prices and collecting e-commerce data is a common real-world use case for web scraping. This repository provides a simple yet practical scraper that:

Extracts Amazon product titles and prices

Sends browser-like HTTP requests using custom headers

Parses HTML content using Beautiful Soup with lxml

Handles errors gracefully during extraction

The project is intended for educational purposes, showcasing how automated data extraction works on dynamic websites like Amazon.

## Features

Product Title Extraction – Scrapes the product name using HTML element inspection

Price Extraction – Cleans and formats product pricing correctly

Header-Based Requests – Mimics browser behavior to reduce request blocking

Lightweight & Simple – Minimal dependencies and easy to extend

Beginner-Friendly – Clear logic suitable for learning and interviews

## Usaging
Clone the repository
```bash
git clone https://github.com/Mathewku/amazon-products-scraper.git
cd amazon-products-scraper

```
Create a Python virtual environment
```bash
python -m venv venv
```

Activate the virtual environment
```bash

venv\Scripts\activate         
```

Install dependencies
```bash
pip install requests beautifulsoup4 lxml
```

Run the scraper
```bash
python scraper.py
```


Enter an Amazon product URL when prompted to receive extracted details.

Sample Output
```bash
{
  'title': 'Apple AirPods Pro (2nd Generation)',
  'price': '$199.99'
}
```

## Future Enhancements

Extract ratings and availability status

Export scraped data to CSV or database

Add retry logic and proxy support

Implement automated price tracking
