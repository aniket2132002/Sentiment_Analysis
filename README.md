# Sentiment_Analysis
This project implements a sentiment analysis application that uses the OpenAI GPT model to classify text as Positive, Negative, or Neutral. The application analyzes user-provided text and stores the results (including the input text, sentiment classification, and timestamp) into an SQLite database.

Features:
Sentiment Analysis: The application uses OpenAI's GPT model to classify the sentiment of the input text.
Database Storage: Results are stored in an SQLite database, ensuring persistence of sentiment analysis results.
Real-Time Logging: Every sentiment analysis result is logged with a timestamp.
Database Schema: The database stores three fields:
Input Text: The original text input by the user.
Sentiment: The result of sentiment analysis (Positive, Negative, or Neutral).
Timestamp: The date and time when the sentiment analysis was performed.

Database:
Database Name: sentiment_analysis.db
Table Name: sentiment_analysis
Table Schema:
id (INTEGER): A unique identifier for each record (Primary Key).
input_text (TEXT): The input text provided by the user for sentiment analysis.
sentiment (TEXT): The sentiment classification (Positive, Negative, or Neutral).
timestamp (TEXT): The date and time the sentiment analysis was performed.
