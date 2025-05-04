# Sentiment Analysis
This is part of NLP course assignment 1.

## Overview
In this project, we examined two machine learning algorithms to predict the `overall` score by comparing the performance of multiple combinations of text pre-processing techniques. We also evaluate the performance of using an unsupervised technique using rule-based method with VADER lexicon to evaluate which algorithm best suits our data.  We will also perform exploratory data analysis (EDA) before the model training to gain a better understanding of the data and to ensure that each necessary process is taken to achieve efficient and high perfoming model.

The process included the following steps:
1. Split data into three independent sets: training, testing, and development
2. Exploratory Data Analysis (EDA): rating count, token frequency, text length distribution, n-grams
3. Text preprocessing: regex cleaning, lowercasing, lemmatisation, and stopword removal
4. Oversampling with random duplicating minority classes
5. Sentiment classification supervised: Multinomial Naive Bayes (MNB) and Random Forest (RF)
6. Sentiment classification unsupervised: VADER
7. Evaluation with 10-fold cross validation

The end-to-end process of this project is documented in our notebook named `sentiment_analysis_hotel_reviews.ipynb`.
