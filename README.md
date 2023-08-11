# Food_review_classification-NLP
 Sentiment Analysis
Aim : To determine the sentiment of a given review. (Negative/ Neutral/ Positive)
ML Task : Supervised Learning Multi-Class Text Classification
The dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10
Approach:

Classified sentiment based on review text, performed data cleaning and pre-processing by Stemming, stop-word removal, and Lemmatization.
Class imbalanced problem handled by under sampling and for train-test splitting time-based sampling was used.
Feature extracted using Bag of Words, TF-IDF, Average Word2Vec, TF-IDF Word2Vec.
Applied Logistic Regression, Random Forest Classification, Support Vector Machine, Naïve Bayes, K-Nearest Neighbors with Hyperparameter tuning.
Used Accuracy, Precision, Recall and F1-Score as metrics for comparison.
Best Model was Logistic Regression with TF-IDF
