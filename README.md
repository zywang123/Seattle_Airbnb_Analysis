# Seattle Airbnb Analysis
20220428 Udactiy Nenodegree Project 1  
Author: Zeyao Wang   

### Libraries used
I used python to conduct analysis. Followings are the libraries I used. 
- import pandas as pd
- import numpy as np
- from time import strptime
- import matplotlib.pyplot as plt
- import seaborn as sns
- import statsmodels.api as sm
- from sklearn.linear_model import LinearRegression
- from sklearn import linear_model
- import nltk
- from nltk import word_tokenize
- from nltk.sentiment import SentimentIntensityAnalyzer
- import operator
- from nltk.tokenize import TweetTokenizer
- from nltk.corpus import stopwords
- from nltk.stem import WordNetLemmatizer
- from nltk.stem import PorterStemmer


### Motivation for the project
At present, due to economic problems and war happened, banks have raised interest rates and thus affect the housing market price, so the price of Airbnb has also changed. Therefore I chose to look at the pre-pandemic 2015-2016 Seattle Airbnb data. Before the pandemic, no mask was required and oil price was reasonable, which travelers were all around the world, thus Airbnb started to take off. However recently a firestorm over fees on Airbnb erupted on social media, in which most customers pointed out the hotel was much cheaper then Airbnb and hotel became a better option. Therefore, I would like to find what important factors affect Airbnb price a lot and correlation between price and those factors.

### Description of File
- Code_Zeyao_Wang.ipynb: This is my code file which contains models, analysis, and visualations. 
- Report_Zeyao_Wang.md: This is the report including business questions and insights coming from current environment and codes. 
- correlation.png: Visualization of the correlation between price and other variables. 
- important_feature.png: Visualization of the important features that affect price mostly. 
- model2.png: Summary of the final model
- price1.png: Visualization of price distribution
- price2.png: Visualization of log(price) distribution
- words_count.png: Visualization of the relationship between comment word counts and price. 

### Necessary acknowledgments
I write the code and analysis by myself and thank you Udacity's training and guidance. 

