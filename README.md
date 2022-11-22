# IMDb reviews Sentiment Analysis
In this project we will perform a sentiment analysis and other visual analysis on the reviews of 21 Disney movies from the 1950's to the 2010's (3 movies for each decade) taken from the IMDb website.
<br> At the end we will be able to tell **which decade has the highest reviewed movies** based on our sample.
<br>The project is divided in three sections:
<br> **1. Web Scraping
<br> 2. Database creation
<br> 3. Analysis**

---

<br> **1. Web Scraping**  
<br> We will be using the **selenium** and **BeautifulSoup** and **nltk** packages for our web scraping purposes.
<br>**1. selenium** is a powerful tool for  **browser automation**. In other words it allows users to automate browser related tasks such as searching for specific items on Chrome,  loading new pages store their content into a HTML file.
<br>**2. BeautifulSoup** is is a Python package for pulling data out of HTML files. We can use it to organize our reviews data in **tabular form**

---

<br> **2. Database creation**
<br> In this section we will store the data that we have scraped from the web in **sqlite database**.
<br> The **sqlite3** library will allow us to use the SQL language for the creation and manipulation of the database in a Python environment.

---

<br> **3. Analysis**
<br> In this section we will analyze the audience sentiment towards the selected Disney movies.
<br> After import the sqlite table as a pandas dataframe, we will divide our reviews according to their release year, obtaining 7 smaller dataframes in total. Then we will define functions to perform **lemmatization** and other graphical analyses (Wordclouds, word frequency charts etc...) that we will use in the latter part of the section. 
<br> We will be using the **pandas** and **nltk** packages for our purposes 

---

<br> **4. Key takeaways**

<br> **4.1 WordCloud**
<br>![image](https://user-images.githubusercontent.com/117392795/203279197-40d609ce-378b-46bd-994e-53d511c97239.png)
<br> The above **wordcloud** is made by the review of all the selected Disney movies from the 1950's to the 2010's.
We can spot words such as *good*, *fun*, *great*, *classic* which suggest a positive sentiment for all the movies.


<br> **4.2 Word Frequency plot**
<br> ![image](https://user-images.githubusercontent.com/117392795/203281905-7f720dee-5c41-47ae-8b19-ab9fb8eed172.png)
<br> We have also created a **Word Frequency plot** by plotting the top 50 most used words in the reviews. We can see words such as **Nemo**, **Dory**, **finding** which suggest that movies from the 2000's may be the most popular among the audience.

<br> **4.3 Average score by decade**
<br> ![image](https://user-images.githubusercontent.com/117392795/203285518-e9c27aa7-bc91-4bc0-9ac2-534b69523953.png)
<br> As we can see from the **Average score by decade** plot, the movies from the 1990's and 2000's are the highest rated by the audience.

<br> **4.4 Sentiment Analysis**
<br> ![image](https://user-images.githubusercontent.com/117392795/203302521-928c18d8-8f4a-4dbe-acfb-12ebb0d1376e.png)
<br> From the **Sentiment Analysis** plot, we can see that to all the selected decades is associated a positive sentiment with the 2000's, 1990's and 1960's being the most favourite among the audience. 
