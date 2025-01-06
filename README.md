# Stock Price Prediction with Sentiment Analysis and Historical Data
This project demonstrates how incorporating sentiment analysis data alongside historical stock data can significantly enhance the accuracy of stock price predictions. By combining traditional financial indicators with market sentiment derived from news articles and social media, this project aims to build robust predictive models for stock market forecasting.

Project Overview
Objective
The primary goal of this project is to prove that adding sentiment data to historical stock data improves the accuracy of stock price prediction models.

Data Sources
Historical Stock Data: Extracted using the yfinance library.
Sentiment Data: Collected using the Alpha Vantage API, which provides market sentiment information based on textual analysis.
Methodology
Phase 1: Using Historical Data Alone
Historical stock data was cleaned and preprocessed.
Three machine learning models were trained:
GRU (Gated Recurrent Unit)
XGBoost
Random Forest
Metrics such as accuracy were calculated, and future stock prices were predicted.
Phase 2: Combining Historical and Sentiment Data
Sentiment data was merged with historical stock data to create a comprehensive dataset.
The same three models (GRU, XGBoost, and Random Forest) were retrained using the combined data.
An ensemble model was introduced, which combines the predictions of all three models for improved results.
Results
The comparison between models trained on historical data alone and those trained on the combined dataset revealed that:

Models trained with combined data achieved higher accuracy.
Predictions based on the combined dataset were more reliable and closer to actual stock prices.
Key Findings
Adding sentiment data to historical stock data provides a clearer picture of market trends, making it a valuable addition to stock price prediction models. This approach outperforms models that rely solely on historical data, confirming the importance of integrating market sentiment for accurate financial forecasting.

Repository Contents
Code: Scripts for data preprocessing, model training, and evaluation.
Data: Includes sample historical and sentiment data.
Results: Metrics and future price predictions for all models.
Documentation: Detailed explanations of the methods and findings.
Conclusion
This project underscores the value of combining sentiment analysis with historical stock data to build better predictive models. The findings suggest that integrating sentiment data improves both the accuracy and reliability of stock price predictions, making it a powerful tool for financial analysts and investors.
