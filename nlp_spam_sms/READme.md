# Detecting SMS spam
The aim of this Natural Language Processing project is to predict whether a text message is spam or legitimate. We take the following steps:
- preprocessing: 
    - making text lowercase
    - removing punctuation
    - removing stop-words
    - stemming words
- new features generation
- bag-of-words approach comparison: CountVectorizer vs. TfidfVectorizer
- final model tuning


We start by preprocessing the messages: making text lowercase, removing punctuation and stop-words, stemming words. We then generate new features from the text messages. We compare the effect of using CountVectorizer vs. TfidfVectorizer and train several models....

The dataset we use is from the UCI Machine Learning Repository and is [available here](https://www.kaggle.com/uciml/sms-spam-collection-dataset). It is a collection of 5,572 text messages tagged legitimate (0) or spam (1).
