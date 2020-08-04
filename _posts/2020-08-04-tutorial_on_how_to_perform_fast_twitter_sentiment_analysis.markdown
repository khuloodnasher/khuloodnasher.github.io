---
layout: post
title:      "Tutorial on How to Perform Fast Twitter Sentiment Analysis"
date:       2020-08-04 14:46:02 +0000
permalink:  tutorial_on_how_to_perform_fast_twitter_sentiment_analysis
---


The complete blog can be found in the url below:


https://medium.com/@khuloodnasher72/tutorial-on-how-to-perform-fast-twitter-sentiment-analysis-explained-in-the-topic-of-72458662c91c


In this blog, I’m going to explain how to perform a fast twitter sentiment analysis from scratch especially, if you were asked to practice NLP or choose any project in sentiment analysis.
Well, twitter is the best harborage for your search.
First: you need to find a trend to collect your data of tweets. The best way to find trends is through https://www.trendsmap.com/, or through this website: https://getdaytrends.com/united-states/ where you can search the trend in the United States or in any country. You can also search per topic and find all the trends in that topic. If you choose the United States, for example, you can choose the state and a map of trends will pop up in each state with the recent trends at the moment. You can also look for the hashtags at the current moment or the hashtags during the last 24 hours.
For me, I wrote this article on July 6th,2020. One of the most active trends on that day was the F1 student visa. And, I used this hashtag to explain NLP sentiment analysis techniques.
After you choose your trend and decide what topic you will base your research on, You can simply scrape tweets from Tweepy’s Twitter API.
For fast scraping, you can use the following website https://www.vicinitas.io/ which allows you to collect the tweets of one week, and it does some useful analysis as well, and at the same time, you can collect the tweets in the form of an excel sheet and then change it to a CSV file.
Now, I’m going to explain my fast and basic sentiment analysis on a hashtag of student visa that was a trend on July 6th,2020.
For the whole code, you can see my GitHub. We will accomplish this by completing the following tasks:
Task #1: Understand the Problem Statement
Task #2: Import libraries and datasets
Task #3: Perform Exploratory Data Analysis
Task #4: Plot the word cloud
Task #5: Create a pipeline, perform data cleaning and removing punctuation and stopwords, and perform tokenization and Vectorization
Task #6:Model with Bayes Classifier and assess the model.
