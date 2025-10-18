# LinkedIn Job Scraper

This Python project scrapes LinkedIn job listings for **Data Analyst** positions in Berlin, Germany, and saves the results into a CSV file.

## Features
- Scrolls through all job listings automatically
- Clicks "See more jobs" to load additional listings
- Extracts job details:
  - Job title
  - Company name
  - Location
  - Job link
- Saves the results into `linkedin_jobs_berlin.csv`

## Tools Used
- Python
- Selenium WebDriver
- WebDriver Manager
- Pandas

## How to Run
1. Install required packages:
```bash
pip install selenium webdriver-manager pandas

2. Run the script:

bash
Copy code
python linkedin_scraper.py

3. The CSV file linkedin_jobs_berlin.csv will be created in the same folder.
