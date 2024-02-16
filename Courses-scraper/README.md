# Courses scraper
- Sample data:
![image](https://github.com/VlahovskiAndrej/finki-scraper/assets/95543841/fe911eb3-8b64-4bd9-b608-5df27f5cad73)


## Description
The Python script performs the following tasks:
- Scrapes details about every course available at FINKI(FCSE) from a **www.finki.ukim.mk** using Selenium
- Processes and structures the scraped data.
- Saves the processed data to a JSON file
-  Provides error handling for missing elements during scraping.

## Installation ## Usage

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

## Configuration

- You can customize the script to scrape data from different websites by modifying the `website_url` variable in the script.
- You can change the script to save the data fto a different file by modifying the `output_path` variable.
- Additionally, ensure that the XPath expressions used to locate elements on the website are up-to-date and accurate.

## Dependencies

- Python 3.11
- Selenium

## File Structure

project/
│
├── script.py
├── chromedriver.exe
└── output.json
