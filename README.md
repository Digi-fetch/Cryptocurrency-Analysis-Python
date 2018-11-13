# Cryptocurrency Analysis #

## Table of Contents ##

- [Introduction](#introduction)
- [Studies](#studies)
  * [Sentiment Analysis of Tweets](#sentiment-analysis-of-tweets)
    + [TweeterScraperDatewise.py](#tweeterscraperdatewisepy)
    + [Cryptocurrency Sentiment Analysis.ipynb](#cryptocurrency-sentiment-analysisipynb)
  * [Turtle Trading Strategy](#turtle-trading-strategy)
    + [Bitcoin_Turtle_Strategy.ipynb](#bitcoin_Turtle_Strategyipynb)
- [Conclusion](#conclusion)

## Introduction ##
A cryptocurrency is a digital or virtual currency designed to work as a medium of exchange. It uses cryptography to secure and verify transactions as well as to control the creation of new units of a cryptocurrency. Essentially, cryptocurrencies are limited entries in a database that no one can change unless specific conditions are fulfilled.  
Holding Bitcoin means to have a share in this venture. If Bitcoin ever replaces monetary reserves of central banks or becomes the dominant currency for international trades – just to name two examples — the value of one Bitcoin will be far beyond 10,000 Dollar. Buying and keeping cryptocurrencies is a bet on the success of this silent revolution of money. Its like a security of a large ecosystem.   
This study was done for personal purpose to understand the investment opportunity in cryptocurrency, so its not a full-fledged study about investment opportunities. Anyone is free to reuse the codes for their personal needs.


## Studies ##
- Sentiment Analysis of Tweets
- Applying Turtle Trading Strategy
- - - - 
### Sentiment Analysis of Tweets ##
Twitter is an online social network with over 330 million active monthly users as of February 2018. Twitter employs a message size restriction of 280 characters or less which forces the users to stay focused on the message they wish to disseminate. This very characteristic makes messages on twitter very good candidates for the __Machine Learning (ML)__ task of sentiment analysis. Using sentiment analysis on tweets we will get a general view about the minds of people. More the people having a positive outlook towards cryptocurrency means people will invest more and it will not crash soon. This is specifically useful during bubble phases of the coin which happened in end of 2017. 
On side note -> When one sees that the general sentiment of people are more negative that’s when one should take out one's investment.

### TweeterScraperDatewise.py ###
- Helps in extracting Tweets according to the keyword ie., here mainly bitcoin, ethereum, ripple etc.
- It gets all the top tweets on the particular topic for __each day__ and saves it in a __txt file__ format.
- It uses __selenium__ to surf through the net and scrape the tweets.

### Cryptocurrency Sentiment Analysis.ipynb ###
It plots two plots:
- Positive, Neutral, Negative and No. of tweets line plot
- Polarity vs Closing Price

These plots help in understanding the sentiments better. We can also derive relationships between the market value and sentiment, and to a great extend it shows a similar trends.
- - - - 
## Turtle Trading Strategy ##
It is a system developed by Richard Dennis and William Eckhardt in 1983 to help in trading stocks. It is a very old formula, and it may not be relevant in the case of cryptocurrency. Nevertheless, it will surely give an idea about insight on when to Buy and Sell cryptocurrency  based on closing prices.
### Bitcoin_Turtle_Strategy.ipynb ###
Here we plot two plots : 
- Close, Rolling Max and Rolling Min line chart
- Close Price time series chart with Buy and Sell points mentioned

- - - - 
> Note -> Some of the obtained graphs are available in 'Graphs' folder

> Note -> Some sample data are available in 'Database' folder

# Conclusion #
From these studies we will get a brief idea on when to invest your money in cryptocurrency and when not to. Use the information wisely.  
Quoting Warren Buffet "Never invest in something you don't understand". As simple as that. Read a lot on cryptocurrency, understand it and be your own judge.