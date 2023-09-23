# Flipkart Mobile Phone Data Scraper
## Overview
The Flipkart Mobile Phone Data Scraper is a Python-based web scraping application designed to collect comprehensive data about mobile phones available on Flipkart's e-commerce platform. This tool automates the process of gathering information about various mobile phone models, including their names, user ratings, total ratings, total reviews, original prices, discounted prices, and calculates the discount percentages. The scraped data is stored in a structured format, making it convenient for further analysis, research, or comparison of mobile phone offerings.

## Features
- Web Scraping: Utilizes web scraping techniques to extract data from Flipkart product listings.
- Data Collection: Retrieves detailed information about mobile phones, including their specifications and pricing details.
- Data Calculation: Automatically calculates the discount percentage to help users identify attractive deals.
- Data Export: Stores the collected data in a CSV file, making it accessible for analysis in various data analysis tools.

## Getting Started
### Prerequisites
Before using the Flipkart Mobile Phone Data Scraper, ensure that you have the following prerequisites installed on your system:

- Python 3: The scraper is written in Python 3, so you need Python installed.
- Required Packages: Install the necessary Python packages by running 
    pip install -r requirements.txt.
## Installation
1. Clone the Repository: Begin by cloning this repository to your local machine using the following command:
2.     git clone https://github.com/your-username/flipkart-mobile-scraper.git
3. Navigate to the Project Directory: Move into the project directory:
4.     cd flipkart-mobile-scraper
5. Install Dependencies: Install the required Python packages using pip:
6.     pip install -r requirements.txt
## Usage
1. To collect data from Flipkart and generate a dataset of mobile phones, follow these steps:
2. Run the Scraper Script: Execute the scraping script by running the following command:
3.     python scrape_flipkart_mobiles.py
4. Access the Scraped Data: Once the scraping process is complete, the scraped data will be stored in a CSV file named Flipkart_mobile1.csv.
## Data
The scraped dataset includes the following fields:
- Name: The name of the mobile phone.
- Link: The URL link to the mobile phone's image.
- Rating: The average user rating (if available).
- Total_Ratings: The total number of ratings (if available).
- Total_Reviews: The total number of reviews (if available).
- Actual_Price: The original price of the mobile phone.
- Discounted_Price: The discounted price of the mobile phone.
- Discount %: The percentage of discount on the mobile phone.
# Contributing
Contributions to this project are welcome. If you would like to contribute, please open an issue to discuss potential changes or submit a pull request.

# License
This project is open-source and is licensed under the MIT License. You are free to use, modify, and distribute the code for your purposes.

## Feel free to customize this description to provide additional context or details about your specific project.

