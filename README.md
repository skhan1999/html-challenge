# html-challenge

Part 1: Scrape Titles and Preview Text from Mars News

Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.

Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 
Print the list in your notebook.

Part 2: Scrape and Analyze Mars Weather Data

Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.

Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 

Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.

Export the DataFrame to a CSV file.

