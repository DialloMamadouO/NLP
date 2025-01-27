In this project, we will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. We will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles. We will complete a Sentiment Analysis, Natural Language Processing and Named Entity Recognition.

#### Sentiment Analysis

We will use the News API, to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?


#### Natural Language Processing

In this section, we will use NLTK and Python to tokenize the text for each coin. 

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Next, look at the ngrams and word frequency for each coin.

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

Finally, generate word clouds for each coin to summarize the news for each coin.

#### Named Entity Recognition

In this section, we will build a named entity recognition model for both coins and visualize the tags using SpaCy.
