# Fake News Classifier Using LSTM

This project involves building a Fake News Classifier using LSTM (Long Short-Term Memory) networks. The classifier is trained on a dataset of news articles to predict whether a news article is fake or real.

## Dataset

The dataset used for this project is sourced from the [Kaggle Fake News Competition](https://www.kaggle.com/c/fake-news/data). It contains news articles labeled as real or fake.

## Project Structure

- `Fake_News_Classifier_LSTM.ipynb`: Jupyter notebook containing the implementation of the LSTM model.
- `Bidirectional LSTM RNN.ipynb`: Python script implementing the Bidirectional LSTM model.
- `train.csv`: The dataset used for training the models.
- `README.md`: Project documentation.

## Requirements

- Python 3.x
- pandas
- numpy
- tensorflow
- sklearn
- nltk

## Installation

Install the required libraries using pip:


**Usage**

**LSTM Model**

To train and evaluate the LSTM model, run the Jupyter notebook Fake_News_Classifier_LSTM.ipynb.

**Bidirectional LSTM Model**

To train and evaluate the Bidirectional LSTM model, run the Python script Bidirectional LSTM RNN.ipynb

**NLP Preprocessing**

The preprocessing involves:

Removing non-alphabetical characters
Converting text to lowercase
Removing stopwords
Stemming words using the Porter Stemmer

**Performance Metrics**

The performance of the models is evaluated using:

**Confusion Matrix**

Accuracy Score
Classification Report (Precision, Recall, F1-Score)

**Results**

The LSTM model achieved an accuracy of 90% on the test set. The Bidirectional LSTM model's performance can be evaluated similarly.

