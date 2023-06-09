# Tweet Sentiment Analysis - CS419 Project

This project is an implementation of a Tweet Sentiment Analysis model for a CS419 Machine Learning course. The goal of this project is to classify tweets from various personalities across the sentiment spectrum. The model is based on a Naive Bayes classifier, providing a simple yet effective solution for this task.

## Dataset

The dataset consists of tweets from various personalities, including Elon Musk, Andrew Tate, and others. These personalities have been selected to cover a wide range of sentiments in their tweets. The dataset is stored as a CSV file with two columns: 'text' (the tweet content) and 'sentiment' (the corresponding sentiment label).

## Model

The model used for this project is a Multinomial Naive Bayes classifier. The classifier is trained on preprocessed tweet text, where URLs, mentions, hashtags, and stop words are removed. The text data is transformed into numerical features using the bag-of-words representation and TF-IDF weighting.

## Python Notebook

The project code is implemented in a Python notebook. The notebook contains the following sections:

1. Importing necessary libraries and loading the dataset
2. Preprocessing tweet text
3. Splitting the dataset into training and testing sets
4. Training the Multinomial Naive Bayes classifier
5. Evaluating the model's performance using classification metrics and a confusion matrix

## How to run the notebook

1. Clone the repository to your local machine.
2. Ensure that you have the required libraries installed. You can use the provided `requirements.txt` file to install the necessary packages using pip: `pip install -r requirements.txt`.
3. Open the Python notebook using Jupyter or Google Colab.
4. Run the notebook cells in order to load the dataset, preprocess the data, train the model, and evaluate its performance.

## Future work

While the Multinomial Naive Bayes classifier is simple and easy to understand, more advanced models such as deep learning techniques (e.g., LSTM, GRU, or Transformer-based models) could potentially achieve better performance. However, these models might require more computational resources and may not be suitable for an introductory machine learning course.
