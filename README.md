##Headline Sentiment and Stock Market Movement Prediction

This project explores the potential correlation between emotions extracted from news headlines and stock market movements. The provided notebook summarizes the research conducted to find this correlation using various machine learning models. Additionally, fine-tuning was employed to improve the prediction success rate of one of the models.

##Data Acquisition

News headlines: Scraped from Finnhub.io using a custom wrapper class for API requests.
Financial data (labels): Obtained from yfinance (Yahoo Finance) after processing.

##Models Explored

SVC (Support Vector Classifier)
Random Forest Classifier
Voting Classifier (Ensemble of Logistic Regression, Random Forest Classifier, and SVC)
Gradient Boosting Regressor
Simple Deep Neural Network (Dense layers only)
Recurrent Neural Network (LSTM layer, Dense layer, output layer)
GridSearch was employed for hyperparameter optimization of the RNN model.

Enjoy:)
