# Module-11-Mars

mars-web-scraping

Utilized the following sources to assist in writing my code: pandas.pydata.org, matplotlib.org, Google, Stack Overflow, BCS (by watching cloud recordings, referring to instructor activity solutions, and using class activities as references).

Part 1: Scrape Titles and Preview Text from Mars News

In tackling this challenge, I employed automated browsing to navigate, inspect, and pinpoint the elements to scrape from the Mars news site. Using Beautiful Soup, I created an object to extract text elements from the website, focusing on scraping titles and preview text from news articles. The extracted results were organized into a Python dictionary and subsequently stored in a Python list. As an additional task, I exported the scraped data to a JSON file.

Part 2: Scrape and Analyze Mars Weather Data

In this part of the challenge, I utilized automated browsing to navigate, inspect, and determine the elements to scrape from the Mars Temperature Data Site. Using Beautiful Soup, I created an object to extract data from the HTML table on the site. Subsequently, I organized the scraped data into a Pandas DataFrame and ensured each column was converted to its respective data type. Utilizing Pandas functions, I analyzed the dataset and employed Matplotlib for visualization. Finally, I exported the DataFrame to a CSV file.