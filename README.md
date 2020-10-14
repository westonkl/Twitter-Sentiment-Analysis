# Twitter Sentiment Analysis: Project Overview

Analyzed tweets to determine positive, negative, or neutral sentiment from kaggle competition data.

# Resources Used:

**Python Version:** 3.6
**Packages:** pandas, numpy, plotly, SpaCy, nltk

# Exploratory Data Analysis

Distribution of sentiments in training data
![alt text](https://github.com/WestonKing-Leatham/Twitter-Sentiment-Analysis/blob/main/Visualizations/SentimentDistribution.png)

To evaluate my models I used the Jaccard index, which determines the similarity of two sample sentences.

Here are the distributions of Jaccard scores on tweets compared with training tweets and selected parts of a tweet.
![alt text](https://github.com/WestonKing-Leatham/Twitter-Sentiment-Analysis/blob/main/Visualizations/DistributionNumofWords.png)
![alt text](https://github.com/WestonKing-Leatham/Twitter-Sentiment-Analysis/blob/main/Visualizations/NormedDistributedWords.png)

List of the most common words (after removal of stopwords)
![alt text](https://github.com/WestonKing-Leatham/Twitter-Sentiment-Analysis/blob/main/Visualizations/MostCommonWords.png)
![alt text](https://github.com/WestonKing-Leatham/Twitter-Sentiment-Analysis/blob/main/Visualizations/MostCommonWordsinTxt.png)

# Model Building

I used SpaCy to teach my named entity recogniser
![alt text](https://github.com/WestonKing-Leatham/Twitter-Sentiment-Analysis/blob/main/Visualizations/Spacy.png)
My steps:
1. Load the model
2. Shuffle and loop over selected training examples
3. Save the model
4. Test the model
