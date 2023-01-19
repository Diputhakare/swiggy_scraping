# swiggy_scraping

Question 1: Scrape the API from swiggy + find the cheapest items list in your area + the restaurant and item details.
Restaurant details: Name, Area, Timing, Distance, Discount, Delivery Fee, Rating
Item Details: Name, Price, Rating 

For getting the API: Login to to swiggy website and open chrome developer tools, navigate to Network tab, and look for relevant API's. Click on it then you will see Header, Payload,etc
How to scrape API: After the above steps, go to the Headers tab, copy the API Url, and look for payload. 

#Libraries
import requests
Import json
import pandas

#Data stored in 'scraped_data.csv'
