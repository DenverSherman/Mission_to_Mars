# Mission_to_Mars
Webscraping NASA website

# Overview
In this assignment, we launch an app that details the latest from NASA on Mars. Data is scraped straight from the NASA website and organized into a mobile-responsive, updatable Mars newsboard.

## Web scraping
We use the browser library in combination with chromedriver to navigate webpages within python. Our base_url is 'https://astrogeology.usgs.gov/' which is updated to an absolute url for each image as our webscraper loops through to extract link information. This information, along with fact and detail text, is reorganized into a dataframe for storage in our Mongo database.

## Flask and Bootstrapping
The app runs through flask, which connects our database to visualizations in html.