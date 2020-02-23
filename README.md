# New York Times Sentiment Analysis

This repo contains a Jupyter notebook detailing the process used for performing sentiment analysis on over 150 years of front page articles from the New York Times. After having heard many statements regarding the general sentiment and tone of modern news, I decided to take a look at some data to try and visualize the change in the tone of the news throughout the years.

In the Jupyter notebook I have included the code needed to scrape the New York Times' archive API for all news articles from 1852 to 2018, as well as the code to clean the data, perform the sentiment analysis, and generate several visualizations of the data.

# Sentiment Analysis

For the sentiment analysis, the Valence Aware Dictionary and sEntiment Reason (VADER) tool was used. I had tested using a distilBERT model for sentiment classification, but the VADER tool proved to be far more efficient computationally, and natively provided more grainular output.

# Results

![Sentiment Distribution Visual](https://github.com/thebrianmcmurray/nytsentiment/blob/master/plot.png)

# To Do
* Add graph showing sum values of VADER pos, neg, and neu values.
* Add graph showing sentiment distribution by month.
* Test additional sentiment analysis models.
