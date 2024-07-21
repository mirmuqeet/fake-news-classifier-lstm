**# Fake News Classifier Using LSTM**

This repository contains an implementation of a fake news classifier using an LSTM neural network. 

**## Dataset**

The model is trained on the dataset from the [Kaggle Fake News Challenge](https://www.kaggle.com/c/fake-news/data#) and can predict whether a given news article is real or fake.



**## Installation**

To run the project, you need to have Python installed along with the required libraries.


**Natural Language Processing (NLP) Steps**

Text Cleaning and Tokenization:

Remove non-alphabetic characters to retain only letters.
Convert text to lowercase to ensure uniformity.
Split text into words (tokens).

**Removing Stop Words:**

Use NLTK's stopwords list to remove common English words that do not contribute to the meaning (e.g., 'the', 'is', 'in').

**Stemming:**


Apply Porter Stemming to reduce words to their base or root form (e.g., 'running' to 'run').

**One-Hot Encoding:**

Convert each word to a unique integer using the one_hot method.

**Padding Sequences:**

Ensure all sequences (titles) have the same length by padding shorter sequences with zeros.


**Model Architecture**

The model architecture includes an embedding layer, an LSTM layer, and dropout layers for regularization.

**Results**

Accuracy: 90%
Precision: 0.89 for fake news, 0.91 for real news
Recall: 0.89 for fake news, 0.92 for real news
F1-Score: 0.89 for fake news, 0.92 for real news

