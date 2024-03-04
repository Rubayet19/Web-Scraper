# Hacker News Scraper

## Introduction
The Hacker News Scraper is a Python script designed to scrape news stories from Hacker News that have garnered a significant number of votes. Utilizing the BeautifulSoup library for parsing HTML and the Requests library for HTTP requests, this tool efficiently compiles a list of high-vote stories from the first two pages of Hacker News. The goal of this project is to provide users with an easy way to access the most popular stories without manually browsing through the site.

## Features
- Scrapes the top stories from the first two pages of Hacker News.
- Filters stories to include only those with more than 99 votes.
- Utilizes BeautifulSoup for parsing HTML and Requests for HTTP requests, ensuring efficient and effective scraping.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.x installed on your machine.
- `requests` and `beautifulsoup4` libraries installed in your Python environment.

## Usage
To use the Hacker News Scraper, follow these steps:

Clone this repository to your local machine.
Navigate to the directory containing the script.
Run the script using Python. For example:
bash
Copy code
python hacker_news_scraper.py
The script will output a sorted list of popular stories based on the number of votes each story has received.

## How It Works
The script makes HTTP GET requests to the Hacker News website to fetch the HTML content of the first two news pages. It then parses this HTML to extract the titles, links, and vote counts of each story using BeautifulSoup. Only stories with more than 99 votes are included in the final list, which is sorted in descending order by the number of votes.

## Contributing
Contributions to the Hacker News Scraper project are welcome! If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Please ensure your pull request adheres to the following guidelines:

Non-trivial changes should be discussed in an issue first.
Update the README.md with details of changes to the interface, if applicable.
License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
Thanks to the creators of the Requests and BeautifulSoup libraries for making web scraping accessible to the Python community.

## Disclaimer
This tool is intended for educational and personal use only. Please respect the terms of service of any website you scrape.
