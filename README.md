Fake news refers to news containing deceptive or fabricated contents that are actually groundless; they are intentionally overstated or provide false information. This project module proposes a fake news analysis modelling method to identify a variety of features in terms of spreading information.
Our objectives are:
* Pre-processing of the data using NLP techniques.
* Identification and extraction of novel features that can best capture the deception. 
* Apply neural network based fake news classifiers
* Apply visualization and statistical analysis techniques to investigate the features. 
* Test model to successfully classification of tweets into fake and real

**Dataset Used**

For the fake news and real news to be used in the analysis, data provided by Kaggle were used.
The dataset used is:
https://www.kaggle.com/rmisra/news-category-dataset
https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

**Model**

Extracted many features for determining fake and real news.This features can be identified as user and tweet features.Twint, an advanced twitter scraping tool written in Python that allows us to scrape Tweets from Twitter profiles without using Twitter's API was used. Removed unwanted characters, words, obtained cleaned text. 
Text Analysis Tool(Polarity):  NaiveBayes classifier.
We extracted the following features:
* Special characters from the tweets(Hashtags, exclamation marks etc)
* No. of usable words in the tweet
* Number of URLs in tweet
* Polarity of the tweet – Positive, Negative and Neutral
* No. of likes
* No. of retweets
* No.of replies
* Following
* Followers
* Media
* Private or verified user
* Age of the user’s account
* Bio

**Results Achieved**

Using the MLP Classifier classified the users into fake or real based on certain parameters.Statistics of the user like age of account, number of followers, following, total number of likes, tweets, media shared, and some description of their bio were used as parameters.The data was labelled as either real or fake and split into train and test data and the model was fit to the training data.A maximum average accuracy of 77.5 % was achieved while classifying.







