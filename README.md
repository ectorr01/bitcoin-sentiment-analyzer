# Bitcoin Sentiment Analyzer

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ectorr01/bitcoin-sentiment-analyzer/blob/main/bitcoin_sentiment.ipynb)

A simple machine learning project that analyzes the sentiment of tweets about Bitcoin and compares it with the cryptocurrency's price over time.

This project is part of my learning journey in **Python, machine learning, and data analysis**. It uses:
- Twitter API (X API) to collect recent tweets
- Natural Language Processing (NLP) to classify sentiment (positive/negative)
- Yahoo Finance data to plot Bitcoin price
- A Logistic Regression model trained on public datasets

## 📌 Disclaimer

⚠️ **This code is not final or production-ready.**  
It is a **work in progress** created for educational purposes. The goal is to practice:
- Data collection from APIs
- Text preprocessing and sentiment analysis
- Data visualization
- Integration of machine learning models

Some parts may be unstable or require adjustments (e.g., Twitter API access, data cleaning).

## 🚀 Features
- Scrapes recent tweets about Bitcoin
- Classifies each tweet as positive or negative
- Plots daily average sentiment vs. Bitcoin price
- Simple and readable code for learning

## 🛠️ How to Run
1. Get a free Twitter Developer API key at [developer.twitter.com](https://developer.twitter.com)
2. Insert your `BEARER_TOKEN` in the notebook
3. Run the Google Colab notebook (or locally)
4. View the sentiment vs. price chart

## 📂 Files
- `bitcoin_sentiment_analysis.ipynb`: Main Jupyter notebook (Google Colab compatible)
- `tweets.csv`: Sample dataset used for training (optional)

## 📈 Goal
To explore whether public sentiment on Twitter can anticipate or correlate with Bitcoin price movements — a common concept in algorithmic trading.

## 🔮 Next Steps
- Improve text cleaning and model accuracy
- Add support for multiple languages
- Use more historical data
- Deploy as a simple dashboard (e.g., with Gradio)

## 💡 Want to Help?
Contributions, feedback, and suggestions are welcome! This is a learning project, so any improvement is appreciated.
