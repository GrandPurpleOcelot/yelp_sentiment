# Sentiment Analysis on Yelp Reviews
A comprehensive exploration of the Yelp reviews dataset, including interesting insights, trends, emotions and machine learning model that predict the sentiment of customer review on this platform.

![summary](img/summary.png)

# Introduction

With the rise of the digital presence and social media, customer reviews have become an increasingly important factor that influences purchase decisions for many people. When we hear about the new restaurant just open a few blocks away from the office, we often find yourself reaching for our phone and look up the information about the said restaurant before deciding to spend some money on a hopefully delicious meal. Yelp is the go-to application for many people, largely due to the crowd-sourced nature of the reviews. 

With the text data that contains a wealth of information on user's emotion, sentiment analysis can be used to discover people’s opinions, attitude and feelings about a product or service. The ability to extract insights from this type of data is interesting and impactful.


## Data
The data is provided directly by Yelp and can be downloaded at https://www.yelp.com/dataset. The data is composed of single object type, one JSON-object per-line. 5 files that contains different attribute about businesses, reviews, user information, check-ins, and tips written by a user on a business. In total, there are:

• 6,685,900 user reviews

• Information on 192,609 businesses

• The data spans 11 metropolitan areas

## Exploratory Data Analysis
There is much to learn in this dataset. Besides the traditional descriptive techniques, different visualization techniques can highlight the significant trends and patterns in the data. Since the data is rich in geographical information (coordinate), I will analyze the data with the aid of mapping visualization. I will also use NLP methods to clean, vectorized and assess sentiment in user reviews.

EDA notebook can be found [here](https://nbviewer.jupyter.org/github/GrandPurpleOcelot/yelp_sentiment/blob/master/Yelp%20Exploratory%20Data%20Analysis.ipynb).

## Sentiment Analysis
Sentiment analysis is an important application of data science. It the process of determining whether a piece of writing is positive, negative or neutral. This can help us deriving the opinion or attitude of the audience regarding business products and services. 

Using text data from user reviews, I was able to train a Logistic Regression model that can predict sentiment (negative or positive) with 95% accuracy. 

Sentiment Analysis notebook can be found [here](https://nbviewer.jupyter.org/github/GrandPurpleOcelot/yelp_sentiment/blob/master/Sentiment%20Analysis.ipynb).

## Reference

Hosmer Jr, D. W., Lemeshow, S., & Sturdivant, R. X. (2013). *Applied logistic regression* (Vol. 398). John Wiley & Sons.

Manning, C. D., Manning, C. D., & Schütze, H. (1999). *Foundations of statistical natural language processing*. MIT press.

Pang, B., & Lee, L. (2008). Opinion mining and sentiment analysis. *Foundations and Trends® in Information Retrieval*, 2(1–2), 1-135.

Plisson, J., Lavrac, N., & Mladenic, D. (2004). A rule based approach to word lemmatization. In *Proceedings of IS* (Vol. 3, pp. 83-86).

