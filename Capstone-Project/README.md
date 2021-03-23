# Capstone-Project-Machine-Learning-Engineer-Nanodegree

This is a submission to the Capstone Project for the Udacity's Machine Learning Engineer Nanodegree Program.

The project is based on solving the [**Toxic Comment Classification**](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview) Challenge at Kaggle.

The blog post written for the project can be viewd at https://ajay-byan.medium.com/toxic-comments-classification-8d8a9a9b99e6

**Data**
- The data required for the project can be downloaded from the [**Kaggle Comeption Page**](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data)
- The primary source of data used for the modeling is **train.csv** file.
- The **test.csv** file is used for creating submission files to kaggle.

**Libraries Used**
- pandas==1.1.5               - for reading and data manipulation
- numpy==1.19.5               - numerical operation
- matplotlib                  - for visualiztion
- seaborn==0.11.1             - for visualiztion
- scikit-learn                - for machine learning, TFIDF vectorizer, classifier chain
- scikit-multilearn==0.2.0    - for Binary Relevance
- texthero==1.0.9             - text processing
- wordcloud==1.8.1            - visualizing wordcloud
- gensim==3.6.0               - downloading word2vec model
- tensorflow==2.4.1           - deep learning, LSTM
- tensorflow-hub==0.11.0      - transfer learning with BERT
- tensorflow-text==2.4.3      
- tf-models-official==2.4.0   - AdamW optimizer
