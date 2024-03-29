# Courses scraper

## Description
The Python script performs the following tasks:
- Scrapes details about every course available at FINKI (FCSE) from a **www.finki.ukim.mk** using Selenium
- Processes and structures the scraped data.
- Saves the processed data to a JSON file
-  Provides error handling for missing elements during scraping.

  ![image](https://github.com/VlahovskiAndrej/finki-scraper/assets/95543841/3357e58b-f3f2-474e-a536-7e3e429d106f)

## Installation

1. Clone the repository to your local machine:
```git clone <repository-url>```

2. Navigate to the project directory:
```cd <project-directory>```

3. Install the required packages:
```pip install selenium```

4. Download the appropriate WebDriver for your browser (e.g., ChromeDriver) and place it in the project directory.

## Usage

1. Make sure you have installed all the required dependencies and have the WebDriver in the project directory.

2. Run the Python script:
```python script.py```

3. The script will start scraping data from the specified website and save it to a JSON file named `output.json` in the project directory.

![image](https://github.com/VlahovskiAndrej/finki-scraper/assets/95543841/78613bb7-502a-4cb7-8f04-e39cbb154603)

## Configuration

- You can customize the script to scrape data from different websites by modifying the `website_url` variable in the script.
- You can change the script to save the data fto a different file by modifying the `output_path` variable.
- Additionally, ensure that the XPath expressions used to locate elements on the website are up-to-date and accurate.

## Dependencies

- Python 3.11
- Selenium
