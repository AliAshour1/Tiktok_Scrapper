# TikTok Hashtag Scraper

This project is a TikTok hashtag scraper that retrieves data for a given hashtag, including information about videos and related hashtags.

## Requirements

- Python 3.x
- Requests library
- BeautifulSoup library
- Matplotlib library

## Installation

1. Clone the repository:


2. Install the required dependencies:


## Usage

To scrape TikTok data for a hashtag and visualize the number of videos for each related hashtag, follow these steps:

1. Import the required libraries:

```python
import json
import matplotlib.pyplot as plt
import requests
from bs4 import BeautifulSoup



Define the scrape_tiktok() function, which takes the hashtag, number of videos, and optional proxy settings as parameters. This function scrapes the TikTok data and returns it as a JSON string

def scrape_tiktok(hashtag, num_videos=10, proxy_ip=None, proxy_port=None, proxy_username=None, proxy_password=None):
    # Implementation of the function
    ...


Call the scrape_tiktok() function with the desired hashtag and optional parameters to retrieve the data

hashtag = "your_hashtag"
scraped_data = scrape_tiktok(hashtag, num_videos=10, proxy_ip=None, proxy_port=None, proxy_username=None, proxy_password=None)




Parse the JSON data using json.loads().
parsed_data = json.loads(scraped_data)




