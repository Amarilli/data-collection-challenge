# Mars News and Weather

## Part 1: Scrape Titles and Preview Text from Mars News

- I used automated browsing to visit [the Mars news](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
  
- I inspected the page to identify which elements to scrape.

- I created a `Beautiful Soup` object and used it to extract text elements from the website.

- I extracted the titles and preview text of the news articles scraped. 

- I stored the scraping results in Python data structures

    a. title-and-preview pair in a Python dictionary
  
    b. each dictionary has two keys: `title` and `preview`. 

- I printed the list in the notebook.

- I stored the scraped data in a [JSON file](https://github.com/Amarilli/data-collection-challenge/blob/main/output.json)
  
## Part 2: Scrape and Analyze Mars Weather Data

- I used automated browsing to visit [the Mars Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html).

- I inspected the page to identify which elements to scrape.

- I created a `Beautiful Soup` object and used it to scrape the data in the `HTML` table.

- I assembled the scraped data into a Pandas DataFrame. 

- I analyzed the dataset by using Pandas functions and answered the following questions:

   a. How many months exist on Mars?
 
   b. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
 
   c. What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
 
   d. Which months have the lowest and the highest atmospheric pressure on Mars?
 
   e. I found the average daily atmospheric pressure of all the months.

  ![pressure](https://github.com/Amarilli/data-collection-challenge/blob/main/avg_pressure_Mars_sorted.png)
 
- I plotted the results as a bar chart.
  
![Average Temperature on Mars](https://github.com/Amarilli/data-collection-challenge/blob/main/avg_temp_Mars_sorted.png)

- I created a graph about the daily minimum temperature on Mars over time

   ![min temp](https://github.com/Amarilli/data-collection-challenge/blob/main/min_temp_Mars.png)

- I exported the DataFrame to a [CSV file](https://github.com/Amarilli/data-collection-challenge/blob/main/mars_weather_data.csv).
