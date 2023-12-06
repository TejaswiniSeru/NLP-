Movie Genre Classification using NLP
Overview:
This repository contains Python code for genre classification of movie descriptions using various techniques such as Naive Bayes, LSTM (Long Short-Term Memory), and BERT (Bidirectional Encoder Representations from Transformers). The dataset used for this classification task is the "Genre Classification Dataset" from IMDb.

Prerequisites:
Google Colab environment (for seamless execution)
Kaggle API key for dataset download
Python libraries: pandas, numpy, seaborn, matplotlib, nltk, scikit-learn, torch, transformers

Setup Instructions:
Mount Google Drive to the Colab environment to access and store files.
Install and configure the Kaggle API by copying the Kaggle API key (kaggle.json) to the appropriate directory and setting permissions.
Install required Python packages, including Kaggle version 1.5.6.
Download the IMDb genre classification dataset using Kaggle API.
Unzip the downloaded dataset.

Data Preprocessing:
Load and inspect the dataset using pandas.
Perform text cleaning on movie descriptions, including lowercasing, removing special characters, and eliminating stopwords.
Use TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text data into numerical format.

Naive Bayes Classification:
Implement Naive Bayes classification using the MultinomialNB classifier.
Evaluate the model's accuracy and display classification reports.

LSTM (Long Short-Term Memory) Classification:
Tokenize and pad movie descriptions for input to the BiLSTM (Bidirectional LSTM) model.
Train a BiLSTM model for genre classification.
Evaluate the model's performance on the validation set.

BERT (Bidirectional Encoder Representations from Transformers) Classification:
Fine-tune a BERT model for sequence classification using the Hugging Face Transformers library.
Tokenize and encode movie descriptions for input to the BERT model.
Train the BERT model and evaluate its performance on the validation set.

Results and Analysis:
Display the distribution of genres in the training data using visualizations.
Provide accuracy and classification reports for Naive Bayes and LSTM models.
Evaluate BERT model performance using F1 score and accuracy per class.

Conclusion:
This repository demonstrates the implementation of genre classification for movie descriptions using different machine learning approaches. The Naive Bayes, LSTM, and BERT models offer varying levels of complexity and performance, providing insights into the effectiveness of these methods for text classification tasks.

