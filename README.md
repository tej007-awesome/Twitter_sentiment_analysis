# Twitter_sentiment_analysis
This project demonstrates the use of two machine learning models for sentiment analysis on a dataset of Twitter tweets: a Long Short-Term Memory (LSTM) model and a Logistic Regression model.

Project Overview
The main objective of this project is to build a machine learning model that can accurately classify the sentiment of a given tweet as either positive or negative. The project follows a standard machine learning workflow, including data preprocessing, model training, and model evaluation.

Dataset
The dataset used in this project is the "Sentiment140" dataset, which contains 1.6 million tweets labeled as either positive or negative. The dataset is available for download from here.

Dependencies
The following Python libraries are required to run this project:
pandas
numpy
tensorflow
sklearn
nltk
termcolor

Usage
Download the "Sentiment140" dataset and extract the training.1600000.processed.noemoticon.csv file.
Update the file path in the pd.read_csv() function calls to point to the extracted CSV file.
Run the Python script to preprocess the data, train the LSTM model, and evaluate its performance.

The script will output the following:
Data preprocessing steps and information
Training and evaluation of the LSTM model
Training and evaluation of the Logistic Regression model
Accuracy, precision, recall, and F1-score for both models

Model Architectures
LSTM Model
The LSTM model used in this project has the following architecture:
Embedding layer: Maps the input text into a dense vector representation.
LSTM layer: Processes the text sequence and learns the temporal dependencies.
Dense layer: Classifies the output of the LSTM layer into positive or negative sentiment.

Logistic Regression Model
The Logistic Regression model used in this project has the following architecture:
TF-IDF Vectorizer: Converts the input text into a numerical feature representation.
Logistic Regression: Applies a logistic function to the input features to classify the sentiment as positive or negative.

