# Job Scraper for Wuzzuf

## Overview

This Python script is designed to automate the process of collecting job listings from the popular job search website, Wuzzuf. It extracts and organizes essential job-related information, saving it in a CSV file for further analysis or reporting.

## How It Works

1. *Prerequisites:*

   - To run this script, make sure you have Python installed on your system.

   - Install the required Python libraries:
     - `selenium` for web automation using a WebDriver.
     - `numpy` for data processing.
     - `requests` for HTTP requests.
     - `BeautifulSoup` for parsing HTML content.
     - `csv` for writing data to a CSV file.
     - `time` for pausing the script.

2. *Setting Up WebDriver:*

   - Download the appropriate WebDriver for your web browser (e.g., Chrome WebDriver).

   - Update the path to the WebDriver in the code to match your system's configuration.

3. *Running the Script:*

   - Execute the Python script, and it will start the web scraping process.

4. *Data Fields:*

   - The script extracts and records the following job-related information in a CSV file named "JOBS.csv":
     - Job name
     - Job type
     - Company name
     - Job location
     - Job date
     - Number of people
     - Job details 1 to 5
     - Skills and tools
     - Job description
     - Job requirements

5. *Customization:*

   - Adjust the `job` variable to specify your desired job search query.

   - Modify the sleep time (in seconds) to allow for WebDriver initialization, if necessary.

6. *Dependencies:*

   - [Selenium Documentation](https://selenium-python.readthedocs.io/)

   - [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

   - [Requests Documentation](https://docs.python-requests.org/en/latest/)

7. *Important Notes:*

   - Web scraping should be done responsibly and in accordance with the website's terms of service.

   - Keep in mind that websites may change their structure over time, which can affect the functionality of web scraping scripts.

## Author

- [Mostafa Saber](www.linkedin.com/in/mostafasaber22)

Feel free to customize this ReadMe file to provide additional information, project-specific details, and any additional instructions or usage guidelines. Be sure to replace "Your Name" and the GitHub profile link with your own information.

