As part of assignment for my MSBA program at the University of Virginia, I employed complex NLP techniques to analyze customer reviews online to determine if a product would be profitable or not.

Here is what I did:


## Online Reviews Analysis: NLP & Machine Learning

This repository focuses on Natural Language Processing (NLP) and Machine Learning techniques to analyze online reviews. The project aims to classify sentiment, extract meaningful insights from text data, and build predictive models to understand customer feedback patterns.

## Project Overview

Online reviews are a critical source of data for businesses to understand customer satisfaction. This project demonstrates a complete end-to-end data science pipeline, including:

Data Cleaning & Preprocessing: Handling noise in text data, including stopword removal, lemmatization, and tokenization.

Exploratory Data Analysis (EDA): Visualizing word frequencies, sentiment distribution, and review lengths.

Feature Engineering: Converting text into numerical representations using techniques like TF-IDF or Bag of Words.

Machine Learning Modeling: Implementing and evaluating an LSTM classification algorithms to predict review sentiment.

## Repository Structure

main.ipynb: The primary Jupyter Notebook containing the full workflow—from data loading and preprocessing to model evaluation and visualization.

data/: Please message me for the data

requirements.txt: List of Python dependencies required to run the project.

## Requirements

To run the notebook locally, ensure you have Python 3.8+ installed. You can install the necessary libraries using pip:

Bash
pip install -r requirements.txt
Note: Core libraries used include pandas, numpy, matplotlib, seaborn, nltk/spacy, and scikit-learn.

## Methodology

1. Preprocessing

Text data is often messy. We apply several NLP techniques to prepare the data:

Lowercasing and removing punctuation/special characters.

Tokenization and removal of common stopwords.

Stemming or Lemmatization to reduce words to their root forms.

2. Feature Extraction

To make the text readable by machine learning models, we transform it into a vector space:

TF-IDF (Term Frequency-Inverse Document Frequency): Used to highlight words that are unique and important to specific reviews.

3. Modeling & Evaluation

We evaluate the classifier to determine how well it can distinguish the two classes from one another.

## License
This project is MIT licensed.
