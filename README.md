# 2024 Olympics medal winners

### Table of Contents
- [Data Source](#data-source)
- [Tool](#tool)
- [Tasks to perform](#tasks-to-perform)
- [Results](#results)


### Project Overview
This is a web scraping project of the just concluded 2024 summer Olympics medal winners, this data was scrapped off of Wikipedia. 

### Data Source
- Wikipedia.

### Tool
- Jupyter Notebook

### Tasks to perform
#### Data Preparation
1. import the necessary libraries for the task.
2. Copy the url of the desired page of the website and save in a placeholder. 
3. Parse the url into the "Beautiful Soup" library for readability of the HTML data.
4. Extract all tables using the "Soup.find_all()" function
5. Filter table headers under all tables-- "table.find_all()" -- and parse into a placeholder.
6. Call the "text.strip" to remove tags and spaces
7. Using a "For Loop" iterate each table header in the stripped table headers and parse into a pandas dataframe.
8. In the table headers, use a "Nested Loop" iterating table rows and table cells
9. Save in a pandas dataframe and export as a csv file.
10. Load data in pandas
11. Perform Exploratory Data Analysis
12. Drop null values
13. Perform statistical data analysis


### Results

![snip 1](https://github.com/user-attachments/assets/915e852a-9bec-46f6-8e25-9e25a2a8b8f5)

![snip 2](https://github.com/user-attachments/assets/57626974-8ffc-4798-be82-1a231732553e)

![snip 3](https://github.com/user-attachments/assets/072cb01d-a046-4616-b7a7-2dbe7ab41315)











