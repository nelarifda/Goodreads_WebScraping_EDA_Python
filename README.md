# Goodreads_WebScraping_EDA_Python

**About**

This Python project consists of web scraping from Goodreads website about best book ever list and exploratory data analysis from the dataset. Web scraping was used to extract the titles, links, author names, average ratings, and scores. The dataset was saved in CSV file to be analyzed for data exploration.

**Libraries used**

Libraries used for web scraping are BeautifulSoup, requests, pandas, and csv. While for exploratory analysis are pandas, seaborn, and matplotlib.pyplot

**Techniques**
1.	Web scraping
Best book ever by Goodreads was scraped using BeautifulSoup and request libraries in Python. Titles, links, author names, average ratings, and scores were extracted from 1 page. Furthermore, 10 pages were extracted and the dataset was saved in CSV. 
2.	Data cleaning
Data cleaning was started by standardizing decimal numbers into 2 decimal numbers for rating column, checking for duplicate and missing values, and understanding dataset information.
3.	Feature relationship
Observed the correlation between features. Changed the data type into numbers to create the correlation table and heatmap. Creating heatmap using seaborn library
4.	Ask questions about the data
Doing an exploratory analysis of the data by asking questions. The first question was author with the most books. Got the answer by groupby and sort_values. The result was visualized with bar chart. Other questions are about the top 10 best authors, list of Stephen King’s books, and the highest rating book.

**Summarized insights**

Web scrape from Goodreads about best book ever having result dataset in csv file. The dataset has titles, links, author names, average ratings, and scores columns with 1000 data. From the dataset, the exploratory analysis was done having results highest correlation features were rating and score. Stephen King was the author with the highest book in the list with 18 books, while author with the highest book rating was Jerry Weaver with title The Addiction Manifesto.
