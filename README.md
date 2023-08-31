# Transfer Learning for Sentiment Analysis

This Jupyter notebook explores the use of transfer learning techniques for sentiment analysis. The goal is to use pre-trained word embeddings and language models to train a sentiment analysis model for multiple domains.

The notebook is structured as follows:

* **Google Drive Import:** This section imports the necessary datasets from Google Drive.
* **Distribution of Sentiment Labels:** This section visualizes the distribution of sentiment labels in the training data.
* **ETL Pipeline:** This section cleans and prepares the data for model training.
* **Data Sampling, Train-Test Split, and Preparation:** This section splits the data into training and test sets and prepares the data for model training.
* **TFIDF SUPPORT VECTOR MACHINE TRAINING:** This section trains a baseline model using TFIDF and support vector machines.
* **TrainEval_Word2Vec_BiGRU_LSTM_Attention_EarlyStop:** This section trains a model using pre-trained word embeddings and BiGRU, LSTM, and attention layers.
* **DistilBERT:** This section trains a model using the DistilBERT pre-trained language model.
* **Statistic:** This section performs statistical tests on the results of the experiments.

