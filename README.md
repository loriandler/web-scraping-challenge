# web-scraping-challenge
Module 11 Challenge UM Bootcamp

# Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

# Overview
This new assignment consists of two technical products. You will submit the following deliverables:
Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## Part 1: Scrape Titles and Preview Text from Mars News
- In the Jupyter Notebook provided, I set up automated browsing to the Mars News Site and identified which elements to scrape.
- A Beautiful Soup object was used to extract text elements from the website.
- Titles and preview of the text was scraped and stored in a Python dictionary.
- Scraped data stored to a json file

## Part 2: Scrape and Analyze Mars Weather Data
 - In the Jupyter Notebook provided, I set up automated browsing to the Mars Temperature Data Site and inspected the elements to scrape.
 - A Beautiful Soup objedct was used to scrape data in the HTML table.
 - A Pandas DataFrame was created with the scraped data.
 - Data types were assigned.
 - Using Pandas functions the following questions were answered:
    - How many months exist on Mars?
    - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    - What are the coldest and the warmest months on Mars (at the location of Curiosity)?
    - Which months have the lowest and the highest atmospheric pressure on Mars?
    - About how many terrestrial (Earth) days exist in a Martian year?
- Data was saved in a csv titled 'mars_weather_data.csv'

# Credits
Thank you to the tutor, Limei Hou, who helped me with some of the part 1 data scraping parts I was having trouble with.  She was amazing at explaining the different steps.

Thank you to Hunter Hollis, instructor, and TA's Randy & Sam for all of their teaching and support during this week's lessons of the Bootcamp.