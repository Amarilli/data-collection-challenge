# Mars News and Weather

## Part 1: Scrape Titles and Preview Text from Mars News

- I used automated browsing to visit [the Mars news](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
  
- I inspected the page to identify which elements to scrape.

- I created a Beautiful Soup object and used it to extract text elements from the website.

- I extracted the titles and preview text of the news articles scraped. 

- I stored the scraping results in Python data structures

  a. title-and-preview pair in a Python dictionary
  b. each dictionary has two keys: title and preview. 

- I printed the list in the notebook.

- I stored the scraped data in a JSON file
  
## Part 2: Scrape and Analyze Mars Weather Data

- I used automated browsing to visit [the Mars Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html).

- I inspected the page to identify which elements to scrape.

- I created a Beautiful Soup object and used it to scrape the data in the HTML table.

- I assembled the scraped data into a Pandas DataFrame. 

- I analyzed the dataset by using Pandas functions and answer the following questions:

 a. How many months exist on Mars?
 b. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
 c. What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
 d. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
 e. I found the average daily atmospheric pressure of all the months.
 
- I plotted the results as a bar chart.

- I exported the DataFrame to a CSV file.
