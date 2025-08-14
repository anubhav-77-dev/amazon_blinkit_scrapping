# Web Scraping Tools for Amazon and Blinkit

This repository contains web scraping tools for extracting data from Amazon and Blinkit (formerly Grofers) e-commerce platforms.

## Project Structure

- `amazon_scraper.py`: Script for scraping Amazon product reviews
- `blinkit_scraper.py`: Main scraper for Blinkit product data
- `download_blinkit_page.py` & `download_pages.py`: Utilities for downloading web pages
- `requirements.txt`: Python dependencies

## Data Files

- Multiple CSV files containing scraped data from different locations (pincodes)
- Processed Excel files with combined and cleaned data
- Exported visualizations in the `exports/` directory
- Cached HTML pages in `html_pages/` directory

## Setup

1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Amazon Scraper
```python
python amazon_scraper.py
```

### Blinkit Scraper
```python
python blinkit_scraper.py
```

## Data Analysis

The project includes Jupyter notebooks for data analysis:
- `Blinkit_Analysis.ipynb`: Analysis of scraped Blinkit data

## Generated Data

The scrapers generate various output files:
- Individual CSV files per pincode/location
- Combined data in Excel format
- Visualizations (HTML files in exports/)

## License

MIT License
