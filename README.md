# CSE-3200-Project
This is a Machine Learning based work for my academic project- "Software Development Project II"
# Project Title
Sentiment analysis of twitter data and determine it's accuracy.
# Table of contents
This project includes-
  1. See basic informations about the dataset.
  2. Preprocess tweets and give them proper shape.
  3. Understand about the classes of the dataset and plot them on a graph based on their classes.
  4. Train all the tweets and for this separate them in two axes. This classification is based on their type.
  5. Use TF-IDF vectorization on every tweet.
  6. See which type of tweet use which type of words most and see those words in wordcloud.
  7. Determine the accuracy of the training dataset using three Machine learning algorithms.
  8. Plot the confusion matrices of those accuracy.
# Basic Information of the dataset
Dataset contains 74681 rows and 4 columns
# Preprocesssing
For text preprocessing, we have done several approaches. We convert all the letters into lower case, then we split all words one from another, we remove unnecessary stop words from everey tweets, use lematiztion and then join all changes in one place.
# Plot results into separate classes
There are 4 types of tweets we find. Positive, Negative, Neutral, Irrelevent. We plot their number and how often they come in our dataset.
# Training, Testing and TF-IDF Vectorization
We train 80% data and test 20% data. After training, we use TF-IDF vectorizer refers to the term Frequency - Inverse Document Frequency. Here, we have counted how many times and in which respect the words come in each sentence.
# Used algorithms
We have used three algorithms to check how machine can predict the original values. We have used Logistic Regression, Random Forest and Decision tree algorithm. Here we get highest 91% accuracy from Random forest algorithm.
# Word Cloud
We have represented the words which are frequently being available in each class.

# Future Work
This may give better output in Support Vector Machine algorithm and other Deep Learning algorithms.
