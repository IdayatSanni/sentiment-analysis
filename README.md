# Sentiment Analysis

A machine learning project for classifying text sentiment using Natural Language Processing (NLP), TF-IDF feature extraction, and Logistic Regression.

The project explores how text can be transformed into numerical features and used to train a supervised machine learning model for sentiment classification.

## Overview

This project demonstrates a complete NLP classification workflow, including:

- Text preprocessing
- TF-IDF vectorization
- Feature extraction using unigrams and bigrams
- Supervised machine learning
- Logistic Regression classification
- Model evaluation
- Saving and reusing a trained model

The trained model is saved using `joblib` so it can be reused without retraining from scratch.

## Features

- Text preprocessing and normalization
- TF-IDF feature extraction
- Unigram and bigram features
- Logistic Regression classification
- Model training and evaluation
- Saved machine learning model
- Reusable prediction workflow

## Technology Stack

- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook
- Joblib

## How It Works

### 1. Text Preprocessing

The text data is cleaned and prepared before being passed to the machine learning model.

The preprocessing workflow includes steps such as:

- Converting text to lowercase
- Cleaning text
- Preparing text for feature extraction

### 2. TF-IDF Vectorization

The cleaned text is transformed into numerical features using **Term Frequency-Inverse Document Frequency (TF-IDF)**.

TF-IDF helps represent words based on how important they are within individual text samples and across the dataset.

The project also uses n-gram features to capture combinations of words rather than relying only on individual words.

### 3. Model Training

A **Logistic Regression** classifier is trained using the TF-IDF features.

The model learns patterns in the text that can be used to classify sentiment in previously unseen examples.

### 4. Model Evaluation

The trained model is evaluated using classification metrics to understand how well it performs on unseen data.

The project explores metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## Model

The primary model used in this project is:

**TF-IDF + Logistic Regression**

The trained model is saved as:

```text
models/sentiment_tfidf_logreg.joblib

## What I Learned

This project helped me strengthen my understanding of:

- Natural Language Processing
- Text preprocessing
- Feature extraction
- TF-IDF vectorization
- N-grams
- Supervised machine learning
- Logistic Regression
- Model evaluation
- Confusion matrices
- Saving and reusing trained machine learning models

One of the key lessons was understanding how unstructured text can be transformed into numerical representations that traditional machine learning algorithms can use.

## Future Improvements

Potential improvements include:

- Experiment with additional classification models
- Compare Logistic Regression with Naive Bayes, Linear SVM, and Random Forest
- Perform hyperparameter tuning
- Improve text preprocessing
- Experiment with word embeddings
- Add a simple web interface for real-time predictions
- Deploy the model as an API
- Explore transformer-based sentiment classification

## Author

**Idayat Sanni**

AI Integration & Governance | Web Development | AI & Machine Learning

[LinkedIn](https://www.linkedin.com/in/idayat-sanni/)