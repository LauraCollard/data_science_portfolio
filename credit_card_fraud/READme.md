
# Detecting credit card fraud

In this project, we predict instances of credit card fraud using different strategies. The objective is of course to correctly detect all fraudulent transactions without issuing false positives. We use the following models:

- Logistic Regression,
- Random Forest,
- Deep Learning approach: 5-layer neural network built with the Keras framework.

The dataset we use is [available here](https://www.kaggle.com/mlg-ulb/creditcardfraud) on the Kaggle website. It contains 284,807 transactions made in September 2013 by European cardholders.

In the first part of this project, we only use a subset of this dataset (21,693 transactions). After having built and tested our Deep Learning model on this subset, we make use of the full dataset to improve our neural network's performance.

**Toolkit**: Python, Keras, Neural Network, Scikit-learn, Logistic regression, Random Forest, GridSearchCV, Seaborn
