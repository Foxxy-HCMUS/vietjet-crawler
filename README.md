# Vietjet Crawler using Python Selenium

This is a Python script for crawling flight information from the Vietjet website using the Selenium library. The script automates the process of extracting flight details such as departure time, arrival time, and ticket prices.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Selenium library (`pip install selenium`)
- Chrome web browser
- ChromeDriver (compatible with your Chrome browser version)

## Usage

1. Clone this repository or download the script `vietjet_crawler.py`.

1. Install the required dependencies by running the following command:

   ````
   pip install -r requirements.txt
   ```

   ````

1. Download the appropriate ChromeDriver version from the [official website](https://sites.google.com/a/chromium.org/chromedriver/downloads) based on your Chrome browser version. Make sure to place the `chromedriver` executable in the same directory as the `vietjet_crawler.py` script.

1. Open the `vietjet_crawler.py` script in a text editor and modify the following variables:

   - `DEPARTURE_CITY`: The departure city for the flight search.
   - `ARRIVAL_CITY`: The arrival city for the flight search.
   - `DEPARTURE_DATE`: The departure date for the flight search in the format "YYYY-MM-DD".

1. Run the script using the following command:

   ```
   python vietjet_crawler.py
   ```

1. Sit back and relax while the script automates the process of navigating to the Vietjet website, searching for flights, and extracting the flight details. The results will be displayed in the console and saved in a CSV file named `flight_details.csv`.

## Notes

- Please ensure that you use this script responsibly and in compliance with the Vietjet website's terms of service.

- The script is built using Selenium, which controls the Chrome browser. By default, it uses the ChromeDriver executable placed in the same directory. Make sure to update the ChromeDriver version if you encounter any compatibility issues.

- You can customize the script further to extract additional flight information or implement other functionalities based on your requirements.

- For any issues or questions, please feel free to open an issue in this repository.

Happy crawling!
