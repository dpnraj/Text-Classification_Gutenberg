# Text Classification (Group Assignment 1)
## About the project
The objective of this project is to classify five books of similar genre and semantics into their respective authors and genres. This is achieved by preprocessing the data, transforming it into BOW, TF-IDF, and n-gram, and then training a machine learning model using ten-fold cross-validation and error analysis to identify potential biases and author-specific characteristics.
## Built with
This project was created using the Python programming language and a variety of Python data frames, including numpy, pandas, and others.
## Getting Started
In this project we download 5 digital Gutenberg books by mentioning the numbers of the book which are of the same drama genre.
We perform various operations on the text data of the books
We processes the text to clean and prepare it for analysis, and then applies various NLP techniques to the text. 
The techniques applied include:
Removing line breaks and other unwanted characters,
Converting the text to a list of words,
Selecting 200 random partitions of 100 words each from the list of words,
Stemming the words to get their root form,
Lemmatizing the words to get their base form,
Converting the words to lowercase,
Encoding the labels for the text partitions,
Creating a bag of words representation of the text partitions using a count vectorizer,
Performing train-test split on the data,
Fitting a Naive Bayes classifier to the training data,
Predicting the label of the partitions in the test set. 
Finally the resulting data i.e output  is saved to a CSV file.
Performing train-test split on the data
##  About Coding part
i) Labelling data

  First of all we import all the packages required for this function and then we get the samples of 5 gutenberg digital books which are of different authors and same genre and then we label the data of those digital books
  
ii) Preprocessing and data cleaning

 Here the data obtained from the samples is preprocessed and cleaned. We removed all the stopwords and unwanted characters and the words which are of two letters or less were also removed  by using the concepts of lemmatization and stemming for more accuracy.
 
iii) Feature Engineering

After preprocessing and cleaning the data it is represented in various forms such as Bag of words where the frequency of each word is alone considered  and TF-IDF where the importance of each word is taken into account.
  
iv) Usage of different Machine learning models

The data is trained by using different machine learning models like Decision tree, Cross Validation, Random tree classifier etc and the accuracy is 
measured in each case
    
v) Evaluations

Now we run the above code and evaluate the performance of the model using ten fold cross validation
    
vi) Deciding which algorithm is best

After checking the performance of each model we concluded that TF-IDF with Support vector Machine (SVM) and stemming is the best practice is to be 
used to get more accuracy
    



