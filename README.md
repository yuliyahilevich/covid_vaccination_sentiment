# Tweeter altitude to vaccination
 
That project is my very first project after finishing the DS Bootcamp with _AllWomen_. 

The time of our final project perfectly correlated with vaccination campaigns happening all over the world. So the goal of this project was to analyze the Twitters comments and the opinions of Twitters users regarding Covid Vaccination campaign.

## SNScrape

In order to scrape the Tweets, I have used this article as a guideline https://medium.com/better-programming/how-to-scrape-tweets-with-snscrape-90124ed006af from _Martin Beck_. I have used the development version of snscrape Python Wrapper which base its scraping on using the hashtag. For this particular study, I have used the "Covid vaccination" hashtag.

## Vader Sentiment Analysis (NLP) of Twitter mentions

The model used to analyze the twetts was **VADER Sentiment Analysis** model. Vader belongs to a type of sentiment analysis that is based on lexicons of sentiment-related words. In this approach, each of the words in the lexicon is rated as positive or negative, and in many cases, how positive or negative. The big majority of tweets as expected were in English and due to the restricted time of the project I decided to drop all other mentions of vaccination in other languages and follow with only mentioned in English. Also, I have tried other scrapes in order to see if there are any differences mentioning different types of vaccines, but as I haven't found any big differences in a sentiment analysis I haven't included those data in my final project

