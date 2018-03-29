# Detecting spam text messages

The aim of this Natural Language Processing project is to predict whether a text message is spam or legitimate. We take the following steps:
- preprocessing: 
    - making text lowercase
    - removing punctuation
    - removing stop-words
    - stemming words
- new features generation
- bag-of-words approach comparison: CountVectorizer vs. TfidfVectorizer
- classifiers: Logistic Regression, Multinomial Naive Bayes, Support Vector Classifier
- final model optimisation

The dataset we use is from the UCI Machine Learning Repository and is [available here](https://www.kaggle.com/uciml/sms-spam-collection-dataset). It is a collection of 5,572 text messages tagged legitimate (0) or spam (1).

**Toolkit:** Python, NLTK, Scikit-learn, Logistic Regression, Multinomial Naive Bayes, SVC, Seaborn
