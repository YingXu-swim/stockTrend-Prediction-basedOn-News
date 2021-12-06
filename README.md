# using-news-to-predict-price-trend
predict stock price trends based on news and prices by using LDA and XGboost

## 1 background
With the development of information technology, massive news comes into view every day. Often the hot news of the previous day will become an important factor in stock volatility that day or the next day. Therefore, forecasting trends through news and stock price can assist investors in making decisions.

## 2 experiment set
I sets up two sets of experiments:    

- predict the current day’s news and price trends    
- predict the next day’s price trends     
## 3 experiment process
split dataset: 70% for training, 30% for testing.      
**step1: preprossing and baseline.**    
- uses the Bag-of-words, TF-IDF, Word2vec and sentiment analysis to characterize news   
- uses LR, LDA, KNN, CART, NB, SVM, RF and XGboost to classify trends   


**step2: choose suitable models to improve: LDA and XGboost**    

## 4 results
LDA: accuracy of basic LDA  is about 95%       
XGboost: the accuracy has been increased from about 59% of the basic model to about 94%    
