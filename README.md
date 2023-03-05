# Mission-to-Mars

## Overview:

This project consists in web-scraping and data analysis mission to Mars project. Part 1 is a Jupyter notebook(part_1_mars_news.ipynb) that contains the code that scrapes Mars news titles and preview text, this information is stored in a dictionary and exported to JSON file and save as titles.csv.

Using Splinter to visit the Mars temperature data site. Then, we have extracted the HTML code with Beautiful Soup and we have scraped and extracted the Mars temperature table into a Pandas DataFrame and we have cleaned the table data by editing its data types.

After extracting Mars temperature table, we used this table to analyze and visualize the data by answered to the following questions:

How many months exist on Mars? 12
Which month, on average, has the lowest temperature? The highest?
Which month, on average, has the lowest atmospheric pressure? The highest?
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.

Finally, the last step was to export our data as mars_table.csv
