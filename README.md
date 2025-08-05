# Real-Time-Sentiment-Analysis-Dashboard
📄 Project Description :
This project implements a Real-Time Sentiment Analysis Dashboard using Python, Streamlit, and pre-trained NLP models to classify the sentiment of social media text data. The primary objective is to visualize the sentiment distribution of tweets in real-time using a simulated environment based on a Kaggle dataset.

The dashboard supports multiple sentiment analysis backends:

TextBlob for rule-based polarity scoring,

VADER for social media-specific sentiment detection,

BERT for transformer-based contextual sentiment classification.

The application allows users to select the sentiment analysis model, adjust the sample size, and visualize outputs such as:

Sentiment distribution (bar chart / pie chart)

Word clouds for positive, negative, and neutral tweets

Example tweet classifications

The frontend is developed using Streamlit, enabling an interactive and user-friendly experience. The backend logic handles preprocessing (cleaning, tokenization), inference using selected models, and visualization.

🔧 Tech Stack:
Language: Python

Libraries: pandas, numpy, nltk, matplotlib, seaborn, TextBlob, VADER (nltk), transformers (BERT), wordcloud

App Framework: Streamlit

Data Source: Twitter US Airline Sentiment – Kaggle Dataset

Model Types: Rule-based (TextBlob, VADER), Deep Learning (BERT)
