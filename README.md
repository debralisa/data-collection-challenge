# data-collection-challenge
##Background

###You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

##Deliverable 1: Scrape titles and preview text from Mars news articles.

###Part 1: Scrape Titles and Preview Text from Mars News

Automated browsing was used to to visit the Mars news site and using ChromeDev Tools, I was able to inspect the page to identify which elements I would scrape.

1. A Beautiful Soup object was created and used to extract text elements from the website.  
2. The titles and preview text of the news articles that were scrape3d were then stored in a Python dictionary.  
3. Each dictionary was given two keys: title and preview and then the dictionaries were stored into a Python list (mars_list) and then printed in my Notebook.  
4. I did complete the optional portion of the challenge by exporting the list to a JSON file (json_mars), printed it in my Notebook and saved it to a csv file.


##Part 2: Scrape and Analyze Mars Weather Data

###Once again automated browsing was used to visit the Mars Temperature Data Site . Using Chr4omeDev Tools to inspect the page to identify which elements to scrape. 

1. A Beautiful Soup object was created and was used to scrape the data in the HTML table.  
2. The scraped data was then assembled into a Pandas DataFrame using the same column headings as the website table.  
3. The data types were viewed and some were converted and re checked for later data manipulation.
4. Using Pandas functions, the dataset was analyzed in order to answer the following questions:
  A. How many months exist on Mars?
  B. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  C. What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
    1. Find the average minimum daily temperature for all of the months.
    2. Plot the results as a bar chart.
  F. Which months have the lowest and the highest atmospheric pressure on Mars?
    1. Find the average daily atmospheric pressure of all the months.
    2. Plot the results as a bar chart.
  G. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    1. Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    2. Visually estimate the result by plotting the daily minimum temperature.
  H. Export the DataFrame to a CSV file.
  
###File Names/Folder Names

#part_1_mars_news.ipynb (Jupyter notebook and python code), part_2_mars_weather.ipynb (Jupyter notebook and python code), data files: 2 csv data files (mars_csv export from Part 1 and mars_table.csv exported DataFrame from Part 2) and Readme.md file.
