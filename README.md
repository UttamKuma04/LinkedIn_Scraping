# LinkedIn Job Scraper

A Python script to scrape job postings for Python internships from LinkedIn using Selenium. The script collects job titles, locations, and links across multiple pages and saves the data to a CSV file.

## Features
- Scrapes job titles, locations, and application links.
- Supports pagination (currently set to scrape 3 pages).
- Saves the scraped data into a CSV file for easy analysis.

## Prerequisites
- Python 3.x
- Google Chrome browser
- [ChromeDriver](https://sites.google.com/chromium.org/driver/) (compatible with your Chrome version)
- Required Python packages:
  - selenium
  - pandas

## Installation
1. Clone this repository:
   
2. Install the required Python packages:
   
3. Download and set up ChromeDriver. Ensure it is in your system's PATH or provide the path in the script.

## Usage
1. Update the `base_url` variable in the script if needed.
2. Run the script:
   
3. The scraped data will be saved as `linkedin_jobs_multi_page.csv` in the current directory.

## Notes
- Ensure you have proper permissions to scrape LinkedIn data.
- Adjust the `WebDriverWait` timeout values based on your internet speed.
- Modify the `range` in the `for` loop to scrape more or fewer pages.

## License
This project is licensed under the MIT License.

## Disclaimer
This script is for educational purposes only. Use it responsibly and adhere to LinkedIn's terms of service.


