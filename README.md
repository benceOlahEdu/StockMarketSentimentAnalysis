# StockMarketSentimentAnalysis
## MSc Thesis
## Subject description
Using deep learning for stock market prediction is currently seeing increased popularity and various experiments have already appeared aimed towards researching the potential use of incorporating financial news into machine learning mode.
The topic aims to incorporate the financial related news into the model of the stock market price prediction, because several studies claims that the news-derived information could predict the direction of movement of a stock, however the number of studies in this field is low compared to the studies of prediction based on historical stock price.
## Files/folders and their short description
### Folder structure
├───Baseline
├───complex_results
│   ├───complex_model
│   ├───news_model
│   └───numerical_model
├───data
├───DataScrape
│   ├───Economist
│   ├───Financial
│   ├───Kaggle dataset
│   │   ├───Benzinga news with ticker
│   │   ├───Financial News Headlines
│   │   ├───Investing news archive
│   │   ├───New York Times APL & MS
│   │   ├───Reddit Top 25 DJIA
│   │   └───Tweets about the Top Componies from 2015 to 2020
│   └───Reuters
├───KaggleReproduce
├───linear_automat_results
│   └───model
├───lstm_automat_results
│   └───model
└───sentiment_analys_result
### Folder description
Baseline: contains all of the python notebooks for the various solutions I tried for the problem eg. fitlering, merging, VADER, numerical prediction, complex models etc.
complex_results: containt the results for the complex (news + numerical) models, including the .pt files for the models, teaching curve and prediction curve if applicable. complex_model contains for the complex model, news_model for the sentiment analysis, numerical_model for the numerical prediction
data: contains the DJIA data which was the base for almost all of my work
DataScrape: contains several datasets, which I scraped from websites, or I collected from github or kaggle. The source can be found in a txt file in the corresponding folder
KaggleReproduce: contains one reproduction from kaggle website for the part of my problem. It was used for comparing my results with it
linear_automat_results: contains the results (prediction and learning curves, model .pt files for weights) for my linear automatation learning code
lstm_automat_results: contains the results (prediction and learning curves, model .pt files for weights) for my lstm automatation learning code
sentiment_analys_result: contains a compare table for my results for the sentiment analysis part of the work
