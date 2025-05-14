Stock Price Prediction Using News Sentiment Analysis

This project predicts stock prices using news sentiment analysis. It utilizes Long Short-Term Memory (LSTM) for stock price prediction and FinBERT for news sentiment analysis. The goal is to predict future stock prices by analyzing both historical stock data and the sentiment of related news articles.

Overview
This project uses historical stock data and sentiment analysis of news articles to predict future stock prices. The sentiment of news articles is processed using FinBERT—a pre-trained BERT model for financial sentiment analysis. These sentiment scores are then used along with historical price data to train an LSTM model to forecast stock prices.

Technologies Used
LSTM (Long Short-Term Memory): For predicting stock prices based on historical data.

FinBERT: A pre-trained BERT-based model for sentiment analysis on financial news.

Pandas, NumPy: For data manipulation and processing.

Matplotlib, Seaborn: For data visualization.

TensorFlow/Keras: For building and training the LSTM model.

BeautifulSoup, requests: For scraping news articles.

yfinance: For downloading historical stock data.

Dataset
The dataset includes:

Stock Price Data: Downloaded using the yfinance library.

News Articles: Scraped or fetched via APIs for financial news (such as from Yahoo Finance or similar sources).

Model Architecture
LSTM for Stock Price Prediction:
LSTM (Long Short-Term Memory) networks are used to predict stock prices based on time-series data. The LSTM model is trained on historical stock prices and sentiment scores to generate future stock price predictions.

FinBERT for Sentiment Analysis:
FinBERT is a fine-tuned BERT model specifically for analyzing financial text. News articles related to the stock market are processed through FinBERT to extract sentiment scores, which are then used as features for the LSTM model.
