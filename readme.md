# YC Startup Data Scraper

This repository scrapes data of startups listed on Y Combinator's website and visualizes relationship between team size and location.

## Requirements

* Python 3.x
* `requests`
* `beautifulsoup4`
* `selenium`

## Instructions

1. **Install dependencies:** Run `pip install requests beautifulsoup4 selenium` in your terminal.
2. **Download WebDriver:** Download the appropriate WebDriver for your browser from https://chromedriver.chromium.org/downloads and place it in a directory accessible by your system's PATH environment variable.
3. **Replace WebDriver path:** Update `driver = webdriver.Chrome()` with the path to your downloaded WebDriver (e.g., `driver = webdriver.Chrome('/path/to/chromedriver')`).
4. **Run the notebook**.


