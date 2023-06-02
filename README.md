# RNN-LSTM-GRU on on Sentiment Analysis

This repository contains code examples and resources related to sentiment analysis using recurrent neural networks (RNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU).

## Introduction
Sentiment analysis is a natural language processing task that involves determining the sentiment or emotional tone of a given text. 
It is commonly used to analyze the sentiment of customer reviews, social media posts, movie reviews, and more.
Recurrent neural networks, including LSTM and GRU, are popular architectures for sentiment analysis tasks due to their ability to capture sequential information and long-term dependencies in text data.

Preprocessing
To prepare the text data for sentiment analysis, the following preprocessing steps are performed:

    1) Tokenization: The input text is tokenized into individual words using the word_tokenize function from the NLTK library.

    2) Maximum Length Calculation: The maximum length of the tokenized text is calculated to determine the input sequence length for the models.

    3) Out-of-Vocabulary Token: An out-of-vocabulary (OOV) token is defined to replace words that are not present in the vocabulary. The <OOV> token is commonly used for this purpose.

 ## Model Examples
This repository provides examples of sentiment analysis models using RNN, LSTM, and GRU. Each model is implemented using popular deep learning frameworks TensorFlow.
