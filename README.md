# Web_Scraping_Challenge
Module 11 Challenge - Deliverable 1: Scrape Titles and Preview Text from Mars News

Overview

This project involves scraping titles and preview text from the Mars news website using Splinter and BeautifulSoup libraries in Python. The scraped data is then stored in a Python list of dictionaries and saved to a JSON file.

Prerequisites

To run the code for this project, ensured I have the following installed:

Python

Splinter

BeautifulSoup

Chrome WebDriver

Usage

The Python script mars_news_scraper.py performed the following steps:

Imported the necessary libraries: Splinter, BeautifulSoup, and json.

Set up automated browsing with Splinter and visits the Mars news site.

Created a BeautifulSoup object to extract text elements from the website.

Extracted titles and preview text of the news articles and stores them in a Python list of dictionaries.

Printed the list of dictionaries to the console.

Saved the data to a JSON file named mars_news.json.


Deliverable 2: Scrape and Analyze Mars Weather Data

Overview

This project involves scraping and analyzing Mars weather data from the Mars temperature data site using Splinter, BeautifulSoup, and Pandas libraries in Python. The scraped data is then assembled into a Pandas DataFrame and analyzed to answer various questions about Martian weather conditions.

Prerequisites

To run the code for this project, ensured I have the following installed:

Python

Splinter

BeautifulSoup

Pandas

Matplotlib

Chrome WebDriver

Usage

The Python script mars_weather_scraper.py performed the following steps:

Imported the necessary libraries: Splinter, BeautifulSoup, Pandas, Matplotlib.

Set up automated browsing with Splinter and visits the Mars temperature data site.

Created a BeautifulSoup object to scrape the data from the HTML table.

Assembled the scraped data into a Pandas DataFrame.

Converted the data types of columns to appropriate types for analysis.

Analyzed the dataset using Pandas functions to answer questions about Martian weather conditions.

Ploted the analyzed data using Matplotlib for visualization.

Saved the analyzed data to a CSV file named mars_weather.csv.