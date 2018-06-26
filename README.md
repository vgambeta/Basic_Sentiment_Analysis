# Basic_Sentiment_Analysis
An introduction to text sentiment analysis using natural language processing and logistic regression.

The following notebook conducts sentiment analysis on data collected from the 2015 Canadian political election. It uses a pre-determined set of words classified with a sentiment as training set that is used to traing a logisitic regression model. This model is used to determine the sentiment of the unclassified political related tweets from the Canadian election. These tweets are used to gauge the sentiment towards specific parties within the election and is compared to the actual result of the election.

The notebook starts with cleaning of the data and seperating the tweets into parties. Some exploration of the data is conducted via charts which leads into the model preparation.

This project utlizes the NLTK library to manage tokenizing words and other aspects. Word clouds help understand the strongest words and to help further clean the data. The model accuracy is explored through scoring and a learning curve.

Bonus: At the end of the notebook, SVM and Decison Trees are used for classification rather then Logistic Regression. The resuls are briefly discussed.
