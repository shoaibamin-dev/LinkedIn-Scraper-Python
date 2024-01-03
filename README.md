# LinkedIn Profile Scraper
This Python script is designed to scrape data from LinkedIn profiles. It uses the Selenium WebDriver to automate the process of logging in to LinkedIn and extracting information from a list of specified profile links.

## Prerequisites
Before running the script, make sure you have the following installed:

#### Python: The script is written in Python. You can download it from python.org.
#### ChromeDriver: WebDriver for Chrome. Download the appropriate version for your Chrome browser from ChromeDriver Downloads.
## Installation
Clone this repository to your local machine:

```
git clone https://github.com/your-username/linkedin-scraper.git
cd linkedin-scraper
```
Install the required Python packages:

```
pip install selenium pandas
Place the downloaded ChromeDriver executable in the project folder.
```

## Usage
Open the main.py file and update the profile_links list with the LinkedIn profile URLs you want to scrape.

python
Copy code
profile_links = [
    "https://www.linkedin.com/in/first-profile",
    "https://www.linkedin.com/in/second-profile",
    # Add more profile links as needed
]
Run the script:
```
python main.py
```
The script will open a Chrome browser, log in to LinkedIn, and start scraping the specified profiles. Extracted data will be saved in a CSV file named profile_data.csv.

## Script Structure
main.py: The main script that initializes the Selenium WebDriver, logs in to LinkedIn, and iterates through the list of profile links to extract information.

chromedriver.exe: The ChromeDriver executable. Make sure it matches your Chrome browser version.

README.md: This documentation file providing information on how to set up and use the script.

profile_data.csv: The output CSV file where the scraped data is stored. The file includes fields such as name, description, address, company, education, etc.

Important Note
LinkedIn may have policies regarding automated scraping. Ensure that you comply with LinkedIn's terms of service and privacy policies when using this script.

Happy scraping!