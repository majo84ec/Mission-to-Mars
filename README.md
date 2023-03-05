# Mission-to-Mars

## Overview:

This project consists in web-scraping and data analysis mission to Mars project. Part 1 is a Jupyter notebook (part_1_mars_news.ipynb) that contains the code that scrapes Mars news titles and preview text, this information is stored in a dictionary and exported to JSON file and save as titles.csv.

Then, we visited the Mars temperature data site. Then, we have extracted the HTML code with Beautiful Soup , scraped and extracted the Mars temperature data rows into a Pandas DataFrame and cleaned the table data by editing its data types.

We used this table to analyze and visualize the data by answered to the following questions:

### 1. How many months exist on Mars? 
![image](https://user-images.githubusercontent.com/120151872/222986402-00ce33e0-fa57-4a00-b59c-2078462c8176.png)

### 2.How many Martian days' worth of data are there? 
![image](https://user-images.githubusercontent.com/120151872/222986436-8f749681-7170-472f-a04d-4592e6f6cc6d.png)

### 3. What is the average low temperature by month?
![image](https://user-images.githubusercontent.com/120151872/222986555-33ccdbdf-558b-41ca-8d80-84eae12fe387.png)

Which month, on average, has the lowest temperature?  The highest?
![image](https://user-images.githubusercontent.com/120151872/222986506-00bffc3d-23ed-4da6-8ecb-fcaded653137.png)

### 4. Average pressure by Martian month
![image](https://user-images.githubusercontent.com/120151872/222986615-94f3a2a2-3802-4407-ba43-7591dc3bbf11.png)

Which month, on average, has the lowest atmospheric pressure? The highest?
![image](https://user-images.githubusercontent.com/120151872/222986626-f9406586-b397-4c14-ba85-29fd9be53d09.png)

### 5. How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
![image](https://user-images.githubusercontent.com/120151872/222986653-f9136c18-e1ec-4dd8-88e8-6f216ba83528.png)


Finally, the last step was to export our data as mars_table.csv
