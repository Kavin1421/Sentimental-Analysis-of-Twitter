# Sentimental-Analysis-of-Twitter
This NLP issue involves classifying the positive tweets from the bad tweets using machine learning models for classification, text mining, text analysis, data analysis, and data visualization.

# Introduction

These days, data science study is heavily focused on Natural Language Processing (NLP), and sentiment analysis is one of NLP's most widely used applications. Every data scientist should be knowledgeable in this field because it has fundamentally changed how companies operate, from conducting surveys to developing entire marketing strategies.

In contrast to the hours it would take a team of people to manually complete the same job, thousands of text documents can be sentimentally analyzed in a matter of seconds. We will do so by following a sequence of steps needed to solve a general sentiment analysis problem. We will start with preprocessing and cleaning of the raw text of the tweets.

# Problem Statement

Let's read the problem statement again because it is essential to comprehend the goal before to dealing with the dataset. The following is the problem statement:

This task's goal is to find hate speech in tweets. For ease of use, we define a tweet as having hate speech inside it if it has a racist or sexist emotion. To categorize racist or sexist tweets from other tweets is the challenge at hand.

Formally, your goal is to predict the labels on the supplied test dataset given a training sample of tweets and labels, where label '1' signals the tweet is racist or sexist and label '0' denotes the tweet is neither racist or sexist.

The F1-Score evaluation metric was used for this practice assignment.

# Tweets Preprocessing and Cleaning

You are searching for a document in this office space. In which scenario are you more likely to find the document easily? Of course, in the less cluttered one because each item is kept in its proper place. The data cleaning exercise is quite similar. If the data is arranged in a structured format then it becomes easier to find the right information.

The preprocessing of the text data is an essential step as it makes the raw text ready for mining, i.e., it becomes easier to extract information from the text and apply machine learning algorithms to it. If we skip this step then there is a higher chance that you are working with noisy and inconsistent data. The objective of this step is to clean noise those are less relevant to find the sentiment of tweets such as punctuation, special characters, numbers, and terms which don’t carry much weightage in context to the text.

In one of the later stages, we will be extracting numeric features from our Twitter text data. This feature space is created using all the unique words present in the entire data. So, if we preprocess our data well, then we would be able to get a better quality feature space.

# Story Generation and Visualization from Tweets

In this section, we will explore the cleaned tweets text. Exploring and visualizing data, no matter whether its text or any other data, is an essential step in gaining insights. Do not limit yourself to only these methods told in this tutorial, feel free to explore the data as much as possible.

Before we begin exploration, we must think and ask questions related to the data in hand. A few probable questions are as follows:

What are the most common words in the entire dataset?
What are the most common words in the dataset for negative and positive tweets, respectively?
How many hashtags are there in a tweet?
Which trends are associated with my dataset?
Which trends are associated with either of the sentiments? Are they compatible with the sentiments?

# End Notes

In this article, we learned how to approach a sentiment analysis problem. We started with preprocessing and exploration of data. Then we extracted features from the cleaned text using Bag-of-Words. Finally, we were able to build a couple of models using both the feature sets to classify the tweets and identified the most suitable model.

Hope this project was useful!
