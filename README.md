# Twitter_sentiment_analysis<br />
This project demonstrates the use of two machine learning models for sentiment analysis on a dataset of Twitter tweets: a Long Short-Term Memory (LSTM) model and a Logistic Regression model.<br />

**Project Overview**<br />
The main objective of this project is to build a machine learning model that can accurately classify the sentiment of a given tweet as either positive or negative. The project follows a standard machine learning workflow, including data preprocessing, model training, and model evaluation.<br />

**Dataset**<br />
The dataset used in this project is the "Sentiment140" dataset, which contains 1.6 million tweets labeled as either positive or negative. The dataset is available for download from here.<br />

**Dependencies**<br />
The following Python libraries are required to run this project:<br />
pandas<br />
numpy<br />
tensorflow<br />
sklearn<br />
nltk<br />
termcolor<br />

**Usage**<br />
Download the "Sentiment140" dataset and extract the training.1600000.processed.noemoticon.csv file.<br />
Update the file path in the pd.read_csv() function calls to point to the extracted CSV file.<br />
Run the Python script to preprocess the data, train the LSTM model, and evaluate its performance.<br />

The script will output the following:<br />
Data preprocessing steps and information<br />
Training and evaluation of the LSTM model<br />
Training and evaluation of the Logistic Regression model<br />
Accuracy, precision, recall, and F1-score for both models<br />

**Model Architectures**<br />

**LSTM Model**<br />

The LSTM model used in this project has the following architecture:<br />
Embedding layer: Maps the input text into a dense vector representation.<br />
LSTM layer: Processes the text sequence and learns the temporal dependencies.<br />
Dense layer: Classifies the output of the LSTM layer into positive or negative sentiment.<br />

**Logistic Regression Model**<br />

The Logistic Regression model used in this project has the following architecture:<br />
TF-IDF Vectorizer: Converts the input text into a numerical feature representation.<br />
Logistic Regression: Applies a logistic function to the input features to classify the sentiment as positive or negative.<br />

