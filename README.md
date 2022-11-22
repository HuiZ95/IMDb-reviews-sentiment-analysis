# IMDb reviews Sentiment Analysis
In this project we will perform a sentiment analysis and other visual analysis on the reviews of 21 Disney movies from the 1950's to the 2010's (3 movies for each decade) taken from the IMDb website.
<br> At the end we will be able to tell **which decade has the highest reviewed movies** based on our sample.
<br>The project is divided in three sections:
<br> **1. Web Scraping
<br> 2. Database creation
<br> 3. Analysis**

<br> **1. Web Scraping**
<br> We will be using the **selenium** and **BeautifulSoup** and **nltk** packages for our web scraping purposes.
<br>**1. selenium** is a powerful tool for  **browser automation**. In other words it allows users to automate browser related tasks such as searching for specific items on Chrome,  loading new pages store their content into a HTML file.
<br>**2. BeautifulSoup** is is a Python package for pulling data out of HTML files. We can use it to organize our reviews data in **tabular form**

<br> **2. Database creation**
<br> In this section we will store the data that we have scraped from the web in **sqlite database**.
<br> The **sqlite3** library will allow us to use the SQL language for the creation and manipulation of the database in a Python environment.

<br> **3. Analysis**
<br> In this section we will analyze the audience sentiment towards the selected Disney movies.
<br> After import the sqlite table as a pandas dataframe, we will divide our reviews according to their release year, obtaining 7 smaller dataframes in total. Then we will define functions to perform **lemmatization** and other graphical analyses (Wordclouds, word frequency charts etc...) that we will use in the latter part of the section. 
<br> We will be using the **pandas** and **nltk** packages for our purposes 


<br> **4. Key takeaways**
<br> 
