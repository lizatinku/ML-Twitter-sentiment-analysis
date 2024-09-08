# Sentiment Analysis on Twitter Data
Sentiment analysis is the process of determining the emotional tone behind words. This project involves sentiment analysis on a large dataset of 1.6 million tweets. The goal is to classify tweets as either positive or negative using various machine learning models.

## Key Features:
- Data preprocessing including cleaning and text normalization
- Implementation of 2 ML algorithms
- Model evaluation using various metrics like accuracy, AUC, and confusion matrix
- Visualization of model performance with ROC curves

## Dataset
The dataset used for this project is the Sentiment140 dataset from Kaggle, which contains 1.6 million tweets. The target variable is binary, indicating whether a tweet is positive (1) or negative (0).

## Preprocessing
The data preprocessing steps included:
Removing URLs, mentions, hashtags, and punctuation, Converting text to lowercase, Tokenizing and stemming words using NLTK, Removing stopwords, Vectorizing the text using TF-IDF, Modeling

## The following machine learning models were used:
- Logistic Regression
- Naive Bayes

## Evaluation
The models were evaluated using the following metrics:
- Accuracy: The percentage of correct predictions
- AUC: A performance measurement for classification problems
- Confusion Matrix: To visualize the performance of the model

## Results
- Logistic Regression: AUC = 0.78
- Naive Bayes: AUC = 0.76

## How to Use
1. Clone the repository: git clone https://github.com/yourusername/sentiment-analysis-twitter.git
2. Install the required libraries: pip install -r requirements.txt
3. Download the dataset from Kaggle and place it in the project directory.
4. Run the Jupyter notebook or Python script to preprocess the data, train the models, and evaluate their performance.
