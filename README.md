# Spam Message Detection Using Machine Learning
This project focuses on building a machine learning model to detect and classify spam messages. The goal is to provide a reliable tool for filtering out unwanted messages in various applications such as SMS, email, and social media platforms.

Spam messages are a common nuisance in our daily communication. This project aims to build an effective model to detect and classify messages as either "spam" or "ham" (non-spam) using popular machine learning techniques. The model is trained and evaluated using a dataset of labeled spam and non-spam messages.

# Dataset
The model is trained using the SMS Spam Collection Dataset. It contains a collection of SMS labeled messages tagged as either 'ham' or 'spam'. The dataset consists of 5,574 messages.

# Model Architecture
This project implements various machine learning algorithms including:

# Logistic Regression
Naive Bayes
Support Vector Machine (SVM)
Random Forest
The model utilizes Natural Language Processing (NLP) techniques for text preprocessing, including:
Tokenization
Removing stopwords
Lemmatization
Bag of Words / TF-IDF vectorization
Preprocessing Steps
Convert messages to lowercase
Remove special characters and numbers
Tokenize and lemmatize words
Convert the text into feature vectors using TF-IDF
