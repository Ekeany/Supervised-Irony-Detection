# Supervised-Irony-Detection

This project uses two machine learning approaches to learning irony detection from a labeled dataset.

* The first model is a simple Naive Bayes classifier using a  simple Bag of words model to vectorize the sentences in the training set. This model could easily have been improved simply by using a better translation model such as TD-IDF or word embeddings.

* The second apprach uses an LSTM coupled with word embeddings from the Word2vec model provided by the gensim package as the training data was comprised of twitter or real langauge a new model had to be trained on the unique slang.  
