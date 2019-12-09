# Project 3: Web APIs & Classification

## Problem Statement: To find out which subreddit the given posts belong to

To identify which subreddit a particular post belongs to by creating Logistic Regression and Multinomial Naive Bayes classifier model.


## Executive Summary

Reddit is a discussion forum based in America that covers a variety of topics such as food, music, moves, news, etc. A recent research in July 2019 shows that Reddit ranks fifth in the most visited website in the states and thirteenth in the world.

With many people posting in subreddit everyday, it is important to classify the posts to the correct subreddit. By classifying the posts into the correct subreddit, users will be able to have a good user experience and website engagement may increase.

The solution to classify the posts correctly is to build a strong model with high accuracy rate of classification. 

We are able to provide a solution as we have built various model for others and have a good track record for the past years.

We would love to take on this challenge to further improve our current method of building a model and to build a more efficient model to suit your needs.


## Contents:
- Import Libraries

- Webscraping and Preparation of the 1st subreddit

- Webscraping and Preparation of the 2nd subreddit

- EDA, Data Cleaning and Preprocessing

- Train-Test-Split the Data and Build a Logistic Regression Model

- Train-Test-Split the Data and Build a Multinomial Naive Bayes

- Conclusion and Recommendation



## Conclusions and Recommendations
In this project, we are tasked to identify posts that belong to either 'todayilearned' or 'worldnews' subreddit. After webscraping the subreddits for data, we preprocessed it and we built a Logistic Regression model as well as a Multinomial Naive Bayes model to train the data. Both models performed fairly well with 0.72 accuracy rate for Logistic Regression and 0.728 for Multinomial Naive Bayes model but Multinomial Naive Bayes model would be recommended because MultinomialNB model is more stable compared to Logistic Regression model when comparing their scores for the train set against their test set. 

For the Receiver Operating Characteristic Curve above, we want the yellow line to be as far away from the blue line as much as possible which is also represented as the Area Under Curve. The AUC for the above ROC is 0.852 which means that it is quite accurate and this is considered acceptable for our Multinomial Naive Bayes model.

