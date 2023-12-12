## web_scraping

In this project, I was tasked to complete a full web-scrape and data analysis. I used Splinter automated browsing and Beautiful Soup HTML parsing to complete the required web-scraping. I converted the scraping results to a dataframe and used Pandas and Matplotliob for data analysis.

# Part 1: Scrape Titles and Preview Text from Mars News

Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted with Beautiful Soup.

The titles and preview text of the news articles were scraped and extracted

The scraped information was stored in a Python list of dictionaries

# Part 2: Scrape and Analyze Mars Weather Data

The HTML table was extracted into a Pandas DataFrame. 

The data was analyzed to answer the following questions:
How many months exist on Mars?
How many Martian days' worth of data are there? 

The data was analyzed to answer the following questions, and a data visualization was created to support each answer:

Which month, on average, has the lowest temperature? The highest?
Which month, on average, has the lowest atmospheric pressure? The highest?
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. 

The DataFrame was exported into a CSV file. (5 points)