#  Freelancer Reviews Scraper

This Python script is designed to scrape freelancer reviews from the  website. It uses Selenium to automate the login process and fetch the reviews from the authenticated user's profile.

## Requirements

- Python 3.x
- Chrome web browser (you may need to download the appropriate version of chromedriver)
- ChromeDriver (compatible with your Chrome version)

## Installation

1. Clone this repository to your local machine:


2. Set up a virtual environment (optional but recommended):


3. Install the required dependencies:


## Usage

1. Before running the script, make sure you have the correct chromedriver executable for your Chrome version. You can download chromedriver from the official website: [https://sites.google.com/a/chromium.org/chromedriver/downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads)

2. Update the script:

- Replace `YOUR_LOGIN_URL` in `reviews.py` with the actual login URL of the  website.
- Replace `your_email@example.com` with your email address.
- Replace `TARGET_CLASS` and the inner HTML for reviews with what you need to scrape
- Replace `YOUR_REVIEWS_SLUG` with the slug of where your reviews can be found

3. Run the script using python3/python reviews.py

4. The script will prompt you to enter the verification code sent to your email. After entering the code, it will scrape the last 10 freelancer reviews from your  profile.

5. The reviews will be exported to a CSV file named `reviews.csv`.

## Disclaimer

This script is intended for educational and personal use only. Use it responsibly and ensure that you comply with the terms and conditions of the website you are scraping.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.







