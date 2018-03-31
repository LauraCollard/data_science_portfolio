# Sentiment analysis: US airlines on Twitter

In this Natural Language Processing project, we predict the sentiment of tweets about different US airlines. We start by preprocessing the tweets (replacing emojis by text, removing hashtags and punctuation, converting to lowercase). We then encode each tweet to a vector of integers. We use a pre-trained GloVe embedding downloaded from [this source](https://nlp.stanford.edu/projects/glove/) and create a weight matrix of the words contained in the tweets. Finally, we build, train and compare the performance of two different Recurrent Neural Network models: a bidirectional GRU and a bidirectional LSTM.

The dataset we use is available [here](https://www.kaggle.com/bertcarremans/predicting-sentiment-with-text-features/data). It consists of 11,541 tweets scraped in February 2015 categorised as negative or positive.

**Toolkit:** Python, NLP, Keras, GloVe word vectors, RNN, bidirectional GRU, bidirectional LSTM
