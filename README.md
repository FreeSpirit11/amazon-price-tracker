# Amazon Price Tracker

Welcome to the Amazon Price Tracker repository! This Python script monitors the price of a specific Amazon product. When the price drops below a set threshold, an email alert is sent.

## Getting Started

1. Clone this repository: `git clone https://github.com/your-username/amazon-price-tracker.git`
2. Install Python and required libraries: `pip install beautifulsoup4 requests`
3. **Replace the following variables with your own credentials:**

   - `my_email`: Your email address for sending alerts.
   - `my_password`: Your email password (use secure methods to store).
   - `PRODUCT_URL`: The URL of the Amazon product you want to track.
   - `BUY_PRICE`: Set the price threshold for receiving alerts.
   - `to_addrs` : Recipient email address.

4. Customize the request headers to mimic a web browser.
5. Run the script: `python main.py`
6. Stay updated with Amazon deals via email alerts!

## Technologies Used

- Python
- BeautifulSoup
- SMTP (email)

## Disclaimer

Ensure compliance with Amazon's terms of use and use secure methods to store sensitive information.

## Acknowledgements

This project is a part of #100daysofcode by Angela Yu. 

