# Mars Web Scraping and Weather Analysis

## Overview

This project demonstrates web scraping, data extraction, and exploratory data analysis using Python, BeautifulSoup, Splinter, and Pandas. The data is sourced from static Mars-related websites simulating NASA's Mars exploration content. The project is divided into two main parts:

---

## Deliverables

### Part 1: Mars News Scraper
- Uses Splinter to visit a static version of the Mars News website.
- Scrapes article titles and preview texts.
- Stores data in a list of dictionaries with `title` and `preview` keys.
- (Optional) Outputs data to a JSON file for sharing or storage.

### Part 2: Mars Weather Data Analysis
- Scrapes an HTML table of Mars weather data using BeautifulSoup.
- Cleans and converts data types for analysis (dates, integers, floats).
- Analyzes seasonal patterns in minimum temperature and atmospheric pressure.
- Estimates the length of a Martian year based on minimum temperature cycles.

---

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- BeautifulSoup
- Splinter
- Matplotlib

---

## Key Findings

- Mars has 12 months in its solar calendar.
- Minimum temperatures range from approximately -83°C to -67°C.
- Atmospheric pressure ranges from ~745 Pa to ~913 Pa seasonally.
- A Martian year is approximately 687 Earth days, verified by seasonal cycles.

---

## Usage

1. Run `part_1_mars_news.ipynb` to collect article titles and previews.
2. Run `part_2_mars_weather.ipynb` to scrape, clean, analyze, and visualize Mars weather data.
3. Data is exported to a CSV file for further use or presentation.

---

## Author

Manuel Guevara
