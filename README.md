# Flipkart_Scrapper
# Flipkart Web Scraping Project

This project involves scraping data of mobile phones from Flipkart and storing the extracted information into a structured format using Python.

## Table of Contents
- [Description](#description)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Output](#output)
- [License](#license)

## Description

The purpose of this project is to extract mobile phone details such as name, price, description, and image links from Flipkart and store the data in an Excel sheet. The script uses web scraping techniques with `BeautifulSoup` to extract the required information from the Flipkart website.

## Technologies Used

- Python
- Requests
- BeautifulSoup 
- Pandas

## How to Use

1. **Install necessary libraries**:
   To begin using the project, install the required Python libraries using pip.

   ```bash
   pip install requests pandas beautifulsoup
Run the script: Download or clone the repository, and run the Python script. It will automatically scrape mobile phone data from Flipkart.

bash
Copy code
python flipkart_scraper.py
Data Storage: The script will store the scraped mobile phone data into a DataFrame and export it into an Excel file at the location:

plaintext
Copy code
C:/Users/majum/Downloads/flipkar/flipkart_mobiles.xlsx
Output
After the script completes, it will generate an Excel file (flipkart_mobiles.xlsx) with the following columns:

Mobile_name: The name of the mobile phone.
Mobile_price: The price of the mobile phone.
Mobile_description: A list of key features or highlights of the mobile phone.
Mobile_image_link: The URL link to the mobile phone's image.
The Excel file will be saved in the specified directory.
