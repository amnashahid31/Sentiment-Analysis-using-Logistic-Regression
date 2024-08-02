# Sentiment-Analysis-using-Logistic-Regression

This repository contains code for performing sentiment analysis on IMDB movie reviews. The project includes data preprocessing, text cleaning, feature extraction using TF-IDF, and model training using Logistic Regression. Additionally, the model is evaluated for accuracy, precision, recall, and F1 score.

## Table of Contents
1. Installation
2. Data Preprocessing
3. Model Training and Evaluation
4. Sample Predictions

## Installation
To run this project, you'll need to install the necessary libraries, which include pandas, beautifulsoup4, nltk, and scikit-learn. Additionally, you'll need to mount your Google Drive if you're using Google Colab. Make sure to download the required NLTK resources as well.

## Data Preprocessing
Cleaning Text Data
The project includes a function to clean the raw movie reviews by performing the following steps:

1. Removing HTML tags.
2. Removing special characters.
3. Converting text to lowercase.
4. Tokenizing the text.
5. Removing stopwords and lemmatizing the words.
6. Preprocessing the Data

The project reads the dataset, applies the text cleaning function, and returns a DataFrame with cleaned reviews and their sentiments. The cleaned data is then saved to a new file for further processing.

## Model Training and Evaluation
Loading the Cleaned Data
The cleaned data is loaded from the saved file for model training and evaluation.

## Feature Extraction
TF-IDF Vectorizer is used for feature extraction, transforming the cleaned text data into numerical features suitable for machine learning models.

## Splitting Data
The data is split into training and testing sets to evaluate the performance of the model.

## Model Training
A pre-defined Logistic Regression model is initialized and trained on the training data. This model is chosen for its simplicity and effectiveness in binary classification tasks.

## Model Evaluation
The model is evaluated using various metrics, including accuracy, precision, recall, and F1 score, to determine its performance.

## Sample Predictions
The trained model is tested with sample sentences to demonstrate its capability in predicting the sentiment of new, unseen reviews.
