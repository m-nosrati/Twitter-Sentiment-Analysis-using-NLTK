# Twitter-Sentiment-Analysis-using-NLTK

For code go to Notebooks

For raw data go to Data

Full Report

Presentation Slides

 Sentiment Analysis of Electronic Products of Netizens
Context 
Sentiment analysis remains one of the key problems that has seen an extensive application of natural language processing. Customers reflect their opinions in texts. The tweets from them about various tech firms who manufacture and sell mobiles, computers, laptops, etc, is very important. Identifying whether the positive or negative tweets are affecting such companies or products is the main task of this project.
Content
Sentiment analysis is contextual mining of text which identifies and extracts subjective information in the source material and helps a business to understand the social sentiment of their brand, product, or service while monitoring online conversations. Brands can use this data to measure the success of their products objectively. For this project, tweet data will be used to predict sentiment on electronic products of netizens.
The dataset contains a test and train dataset. Dataset details:
Test dataset:
ID: The id of the tweet (9873)
tweet : the text of the tweet (Most viewed this week)
Train dataset:
ID: The id of the tweet (9873)
label: 0-positive and 1-negative
tweet : the text of the tweet (Most viewed this week)
The test dataset has 1953 raw and 2 columns with names ID, and tweet. The train dataset has 7920 raw and 3 columns with names ID, Label and tweet.
The source of the data is from the following link.
The following techniques will be applied to find the best model that classifies the tweet as positive or negative.  
After exploratory data analysis, the text of the dataset will be preprocessed and cleaned. Most of the text data are cleaned by following steps. Removing punctuations, tokenization - converting a sentence into a list of words, removing stopwords, lemmatization/stemming - transforming any form of a word to its root word, etc. After label encoding and Word Embedding like GloVe & Word2Vec, model training will be done by  LSTM. After model optimization, the accuracy and the confusion matrix of the performance of the model will be calculated and reported. 
Potential challenges 
Potential challenges for this project can be text preprocessing and model tunning as there may be many parameters to check.

The proposed model at the end of the project will help the model users in web applications to check the attitude of their customers toward their company or products by classifying the customers' tweets or reviews. 
