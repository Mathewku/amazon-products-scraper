Amazon Product Web Scraper

A Python-based web scraping tool built using Beautiful Soup and Requests to extract Amazon product information such as title and price. This project demonstrates real-world web scraping techniques, HTTP request handling, and HTML parsing for data extraction.

Project Overview

Tracking product prices and collecting e-commerce data is a common real-world use case for web scraping. This repository provides a simple yet practical scraper that:

Extracts Amazon product titles and prices

Sends browser-like HTTP requests using custom headers

Parses HTML content using Beautiful Soup with lxml

Handles errors gracefully during extraction

The project is intended for educational purposes, showcasing how automated data extraction works on dynamic websites like Amazon.

Features

Product Title Extraction – Scrapes the product name using HTML element inspection

Price Extraction – Cleans and formats product pricing correctly

Header-Based Requests – Mimics browser behavior to reduce request blocking

Lightweight & Simple – Minimal dependencies and easy to extend

Beginner-Friendly – Clear logic suitable for learning and interviews

Usage
Clone the repository
git clone https://github.com/your-username/amazon-web-scraper.git
cd amazon-web-scraper

Create a Python virtual environment
python -m venv venv

Activate the virtual environment
source venv/bin/activate      # Linux / macOS
venv\Scripts\activate         # Windows

Install dependencies
pip install requests beautifulsoup4 lxml

Run the scraper
python scraper.py


Enter an Amazon product URL when prompted to receive extracted details.

Sample Output
{
  'title': 'Apple AirPods Pro (2nd Generation)',
  'price': '$199.99'
}

Notes

Amazon frequently updates its website structure; selectors may require updates

Excessive scraping may trigger CAPTCHAs or temporary IP blocking

Always respect website terms of service

Intended strictly for learning and demonstration purposes

Future Enhancements

Extract ratings and availability status

Export scraped data to CSV or database

Add retry logic and proxy support

Implement automated price tracking
