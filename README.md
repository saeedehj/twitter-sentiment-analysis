# Sentiment Analysis on Twitter Data

Sentiment Analysis on Twitter Data is a project that aims to predict the sentiment of tweets as either positive or negative. This repository contains the code for performing sentiment analysis on Twitter data using machine learning techniques.

## Problem Overview
Sentiment analysis is a classification problem where we use machine learning techniques to determine the polarity of words and classify them into different categories. In this project, we focus on Twitter data, where people express their opinions and emotions, making it an ideal source for sentiment analysis.

## Proposed Approach
The project consists of three main stages:
  1. **Data preprocessing**: This includes cleaning and transforming the raw Twitter data, including steps like removing URLs, usernames, and punctuation, and applying stemming.
  2. **Model selection**: Two machine learning models are used for classification: Support Vector Machine (SVM) and Naïve Bayes.
  3. **Hyperparameter tuning**: The models are fine-tuned using a grid search to optimize their performance.

## Results
The project achieved an accuracy of 0.81 with the linearSVC classifier. Notably, some preprocessing steps such as removing URLs, stop words, and numbers had impact on accuracy.

## Dependencies

Make sure you have the following dependencies installed before running the code:

- Python 3.x
- Libraries: `numpy`, `pandas`, `csv`, `nltk`, `sklearn`, `seaborn`, `wordcloud`, `matplotlib`

You can install these dependencies using pip:
```bash
  pip install numpy pandas nltk scikit-learn seaborn wordcloud matplotlib
```
