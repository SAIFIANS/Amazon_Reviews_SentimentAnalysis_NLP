# Amazon_Reviews_WebScraping_And_SentimentAnalysis_NLP

## Project Overview
In this project we carry out WebScraping to Extract the Reviews of a product using Beautiful Soup and requests library and then perform Sentimental Analysis on it and predict whether the overall review is 'Positive', 'Neutral', 'Negative' using Afinn Library.


## Steps Involved -
Step 1: Using Beautiful Soup and requests to scrape reviews from amazon and store it to a text file.

Step 2: Joining all the reviews and then using re library to perform simple tasks such as lowering the letters and removing numbers. Performing tokenization followed by removing all the spaces.

Step 3 : Using NLTK and str functions for tokenization, Lemmatization and Removing Stop words and punctuations. Then joining all the token and plot a wordcloud visualization

Step 4 : Converting to a Pandas Data Frame and then performing Sentiment Analysis Using Afinn Database.

Step 5: Creating distribution plot, line and scatter plot to understand the relation between Sentence Sentiment Value and sentence word count.
