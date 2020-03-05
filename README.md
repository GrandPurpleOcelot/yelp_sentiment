# Sentiment Analysis on Yelp Reviews
A comprehensive exploration of the Yelp reviews dataset, including interesting insights, trends, emotions and machine learning model that predict the sentiment of customer review on this platform.


# Introduction

With the rise of the digital presence and social media, customer reviews have become an increasingly important factor that influences purchase decisions for many people. When we hear about the new restaurant just open a few blocks away from the office, we often find yourself reaching for our phone and look up the information about the said restaurant before deciding to spend some money on a hopefully delicious meal. Yelp is the go-to application for many people, largely due to the crowd-sourced nature of the reviews. Yelp provides an open platform for customers to voice their opinion about the quality of certain services, and as a result, incentives businesses to raise to the standard of expectation. Conveniently, Yelp published their dataset for personal, educational, and academic uses.


## Data
The data is provided directly by Yelp and can be downloaded at https://www.yelp.com/dataset. The data is composed of single object type, one JSON-object per-line. 5 files that contains different attribute about businesses, reviews, user information, check-ins, and tips written by a user on a business. In total, there are:

• 6,685,900 user reviews

• Information on 192,609 businesses

• The data spans 11 metropolitan areas

## Exploratory Data Analysis
There is much to learn in this dataset. Besides the traditional descriptive techniques, different visualization techniques can highlight the significant trends and patterns in the data. Since the data is rich in geographical information (coordinate), I will analyze the data with the aid of mapping visualization. I will also use NLP methods to clean, vectorized and assess sentiment in user reviews.

EDA notebook can be found [here]().

## Sentiment Analysis
Sentiment analysis is an important application of data science. It the process of determining whether a piece of writing is positive, negative or neutral. This can help us deriving the opinion or attitude of the audience regarding business products and services. 

Using text data from user reviews, I was able to train a Logistic Regression model that can predict sentiment (negative or positive) with 95% accuracy. 

Sentiment Analysis notebook can be found [here]().
