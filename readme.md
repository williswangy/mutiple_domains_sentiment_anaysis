Transfer Learning for Sentiment Analysis
This Jupyter notebook explores the application of transfer learning techniques for sentiment analysis. The primary goal is to leverage pre-trained models and adapt them to our specific task, making the training process more efficient and potentially achieving better results.

Contents:
Google Drive Import: This section is dedicated to importing necessary datasets from Google Drive. Ensure you have the required datasets in your drive and provide necessary permissions.

Distribution of Sentiment Labels: Before diving into model training, it's crucial to understand the distribution of sentiment labels in our training data. This section provides a visual overview of the dataset's composition.

ETL Pipeline: Data is the backbone of any machine learning project. This section details the Extract, Transform, Load (ETL) process, ensuring that the data is clean and ready for model training. The notebook employs the DataPreprocessor class to facilitate these transformations.

Data Sampling, Train-Test Split, and Preparation: Proper data splitting and preparation are essential for unbiased model evaluation. This section covers the steps involved in sampling the data, splitting it into training and test sets, and additional preparations for model training.
TFIDF - SUPPORT VECTOR MACHINE TRAINING. This section covers the baseline model for the project
TrainEval_Word2Vec_BiGRU_LSTM_Attention_EarlyStop. This is the pretrain wordembedding that compared the performance of the Word2vec, Fasttest and Glove
Shared Layer DistillBERT. This is the pretrain language model that utilise the performance of the distillbert.
Statistic. This is the section where the statistic tests experiment.
