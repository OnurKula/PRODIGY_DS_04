# PRODIGY_DS_04
 
Twitter Sentiment Analysis
This project performs sentiment analysis on a dataset of tweets related to various companies. The main objective is to classify tweets into four sentiment categories: Irrelevant, Negative, Neutral, and Positive. By exploring NLP techniques and machine learning models, this project demonstrates a structured approach to text preprocessing, feature extraction, and classification.

Project Overview
Data Preprocessing:

Cleaned and transformed text data by removing URLs, user mentions, hashtags, punctuation, and stop words.
Converted text to lowercase and applied tokenization to standardize tweet formats.
Feature Extraction:

Implemented Bag-of-Words (BoW) and TF-IDF vectorization methods to capture word presence and importance.
Experimented with different n-gram ranges, especially up to bigrams and trigrams, to improve context capture.
Modeling:

Used Logistic Regression with class balancing and hyperparameter tuning for optimal performance.
Additionally implemented Naive Bayes as a baseline model.
Tested various configurations with BoW and TF-IDF vectorization to identify the best approach for sentiment classification.
Evaluation:

Classification accuracy and F1-scores were calculated to assess model performance.
The best model achieved approximately 88.55% accuracy by optimizing hyperparameters and fine-tuning n-gram settings.
Key Results
Logistic Regression (with tuned n-grams and class balancing) achieved an accuracy of 88.55%.
The results demonstrate that a combination of effective preprocessing, feature engineering, and model tuning can yield high accuracy in sentiment analysis tasks.
