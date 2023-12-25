# Machine-Learning-Amazon-Stock-Analysis
The objective is to apply machine learning techniques to predict Amazon's next day's stock price movements based on historical data.
# Project Overview:
This project, under the guidance of Prof. Krystyn Gutu, focuses on analyzing Amazon's stock using machine learning techniques. The goal is to understand the logic, methods, and types available to implement machine learning classifiers. In this project, we deal with specific types of input data - financial data and try to build a trading (security) strategy for future stock purchases based on historical values.
### Strategy 1: 
If the next trading day's close price is greater than today's close price then the signal is ‘buy’, otherwise ‘sell’
### Strategy 2:
Utilize the 50-day moving average vs the 200-day moving average. A golden cross (or golden crossover) is a chart pattern that involves a short-term moving average crossing above a long-term moving average. Typically, the 50-day MA is used as the short-term average, and the 200-day MA is used as the long-term average. This is an indicator of a bullish (buying) signal.
# Data:
Data source: The data is sourced from Yahoo Finance, a reliable provider of historical stock performance data. <br> Features: The dataset includes key stock indicators such as opening/closing prices, highs/lows, and volume.
# Modeling methods:
### Libraries used: 
The project employs libraries like Yfinance for financial data fetching, Numpy and Pandas for data manipulation, Sklearn for model selection and evaluation, and Seaborn & Matplotlib for data visualization, among others.
### Classifiers implemented (Algorithms):
The project uses several models including KNeighborsClassifier, RandomForestClassifier, GradientBoostingClassifier, SVC, and XGBClassifier. Each model was selected for its suitability in handling time-series data and stock price prediction.
# Model tuning:
Focus on hyperparameter tuning for models like KNN, Gradient Boosting, and Random Forest was given, to enhance model accuracy. Hyperparameter tuning: For KNN, parameters like the number of neighbors and weight function were adjusted. The impact of these changes on model efficiency and prediction accuracy was analyzed.
# Findings & Conclusion:
The highest accuracy was achieved with the KNN Classifier (54.42%), while the lowest was with the Gradient Boosting classifier (50.79%). An intriguing observation was the underperformance of Gradient Boosting compared to XGBoost, despite both employing optimization techniques. The data's non-optimality was considered a factor in the lower accuracy rates, leading to the exploration of alternative strategies.
