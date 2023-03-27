# Supercar-Fans-Twitter-Analysis
Team natural language processing (NLP) and machine learning project to analyse tweets from Supercar fans.

Objective: The objective of this project is to perform sentiment analysis on a dataset of tweets related to Supercars. Furthermore, this project explored the impact of the Second Screen Phenomenon in which our team investigated how tweets impact TV viewership data. Upon understanding the scope of the project, our team narrowed four questions that were deemed insightful for Supercars official team:

1. What is the most popular topic for each event?
2. Is there any correlation between sentiment score and popularity of each game?
3. How do eWOM communications impact TV rating and online engagements
  3.1 How do eWOM communications impact TV viewers in different Australian cities?
  3.2 How do eWOM communications impact online engagements on different race weekends?
  
Data collection: The data was provided by the University of Sydney 

Data preprocessing: The tweets data is processed by tokenizing the tweets, removing stop words, standardising text into all lower cases, and using Wordnet Lemmatizer by NLTK.  

Data analysis: Three main machine learning techniques were used to analyse the data. NLP techniques including topic modeling and sentiment analysis were performed to answer the first two questions. Sentiment analysis was performed using VADER (Valence Aware Dictionary and sEntiment Reasoner) library in Python that is specifically designed for analyzing social media content. It provides a score for each tweet indicating its positive, negative, or neutral sentiment. In addition, to investigate the impact of eWOM communications, OLS regression analysis was conducted. 


