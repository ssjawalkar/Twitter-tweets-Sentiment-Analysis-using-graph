# Twiter-tweet-Sentiment-Analysis-using-graph
Following repositiory has code having Sentiment Analysis with NLTK and plotting graph for polarity and subjective

In this repository I have use twitter API's for getting specific tweets consisting of given keyword.

You can generate your own twitter tokens from 'https://developer.twitter.com/en/apps/create' 
and use this tokens to access twitter APIs


After getting tweets I have used TextBlob function. TextBlob is an NLTK function which provide API for processing NLP task such as part of speech tagging , sentiment analysis, classification, translation etc.

I will be using sentiment analysis to analysis polarity and subjectivity. polarity measure how positive or negative the text is and its values lies between [-1.0,1.0]. Subjective measure how much of opinion or how much of factual it is and its values lies between [0.0,1.0].

With the help of values of polarity and subjectivity I get, I would plot a graph using pyplot function from matplotlib library. 
 
