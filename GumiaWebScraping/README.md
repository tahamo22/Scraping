# Jumia Egypt Mobile Phones Scraper

An efficient Python-based web scraper that extracts mobile phone data from **Jumia Egypt**. This tool crawls through multiple pages, extracts product details (Model, Price, Image URLs), and handles different image encoding formats (Standard URLs and Base64).

## 🚀 Features
- **Multi-page Scraping:** Automatically iterates through 25 pages of product listings.
- **Data Extraction:** Scrapes phone models, prices, and image links.
- **Image Handling:** Includes advanced logic to detect and decode **Base64** images and download standard image URLs.
- **CSV Storage:** Saves all collected data into a structured `jumia_phones.csv` file for easy analysis.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** - `BeautifulSoup4`: For parsing HTML content.
  - `Requests`: For making HTTP requests to the website.
  - `CSV`: For data storage.
  - `Base64 & Re`: For processing encoded image data.

## 📋 Prerequisites
Make sure you have Python installed, then install the required libraries:
```bash
pip install beautifulsoup4 requests
