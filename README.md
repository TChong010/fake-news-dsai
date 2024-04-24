# Welcome to Fake News Detection
Fake News Detection Mini-Project for SC1015 - Introduction to Data Science and Artificial Intelligence

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on the detection of fake news using article text from this specific [Kaggle Dataset](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification/data ). \
Since the dataset is too large, it cannot be uploaded to github but a subset of the processed datasets are provided.

## Contents
Data Cleaning \
Data Visualization \
Using TFIDF \
Using Word Count \
Classifying: Naive Bayes \
Classifying: Random Forest \
Optimizing: Lemmatization \
Optimizing: Named Entities Removed \
Optimizing: Lemmatization + NER \
Optimizing: Finding Best Hyperparameter for Naive Bayes

## Contributors
tinghao - Data Extraction, Data Cleaning, TFIDF, Bag of Words, Optimization \
darrel - Data Visualization, Naive Bayes Classifier, Random Forest Classifier

## Problem Definition
Are we able to accurately detect fake news based on its contents? (Accuracy > 0.9) \
Which approaches and model have the best results?

## Approaches
Word Count (Bag of Words) \
TF-IDF (Term Frequency - Inverse Document Frequency)

## Models Used
Naive Bayes Classifier \
Random Forest Classifier

## Conclusion
* TFIDF is a better method for Random Forest while Word Count is a better method for Naive Bayes 
* Lemmatization, removing named entities have little effects on model accuracy 
* Random Forest Model did very well in predicting if an article is fake or real (best accuracy: around 95.6% using TFIDF and no optimizations) 
* Naive Bayes Model also did quite well in predicting if an article is fake or real, however it is less accurate than Random Forest (best accuracy: around 88.2% using Word Count, with NER and best hyperparameter settings) 
* Our best performing model is the Random Forest Model using TFIDF and no optimizations 
* Yes, we can predict if an article is fake or not based on its contents

## What did we learn from this project?
* Naive Bayes and Random Forest Classifiers from sklearn 
* Concepts of lemmatization, named entities, stopwords, TFIDF, hyperparameters 
* Using GridSearch and Cross Validation to find best hyperparameters for specific model and dataset 
* Processing documents into data (TFIDF and Word Count) for model usage 
* Word visualization techniques such as Word Clouds 
* Libraries: nltk and spaCY

## References
https://towardsdatascience.com/fake-news-detector-with-deep-learning-approach-part-i-eda-757f5c052 
https://commons.lib.jmu.edu/cgi/viewcontent.cgi?article=1754&context=honors201019 
https://www.geeksforgeeks.org/fake-news-detection-using-machine-learning/
https://www.geeksforgeeks.org/python-lemmatization-with-nltk/
https://spacy.io/universe/project/video-spacys-ner-model-alt
https://www.geeksforgeeks.org/hyperparameter-tuning/
