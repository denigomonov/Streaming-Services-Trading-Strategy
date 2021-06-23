# Streaming-Services-Netflix-Trading-Strategy

## Project Goal:
2020 brought a lot of changes into the world and some things became more popular than ever - streaming services are almost a necessity today. Consumers are not going outside and investors would want to look into streaming stocks. Therefore, in this project, I wanted to improve my quantitative finance skills and dive into the recent boom streaming stocks experienced, specifically analyzing Netflix (NFLX). Throughout this project, I was able to build visualizations from the scratch, perform feature engineering and fine-tune ML models for buy/sell signal trains. Overall, it was a great way to truly learn and showcase financial engineering.

---

## Portfolio Data:
For this project I am using data from a trustworthy source - [Yahoo Finance](https://finance.yahoo.com/).

---

## Development:
### EDA:
- Preparing the NFLX dataset for visual portfolio analysis by performing feature engineering via calculating relevant metrics such as SMA, EMA, Rate of Change, Relative Strength Index, Sharpe ratio, Doji candle, Bollinger Bands, and more
- Creating dynamic _Candlestick_ plot with all metrics included from above to fully analyze each stock performance, price movements, changes, and volume distribution over time
- Creating dynamic _RSI_ plot with Oversold/Overbought Indicators showcasing how many times the stock was oversold or overbought over time

<img src="https://user-images.githubusercontent.com/34199193/123125600-a48cec00-d416-11eb-9045-f9d25f6a84c1.gif">


### Machine Learning:
- Establishing a buy/sell signal over the comparison of the short-term and long-term price trends, indicating 1230 buy and 813 sell signals
- Creating a list consisting of classification algorithms (Logistic Regression, KNeighbors Classifier, Decision Tree Classifier, Random Forest Classifier) and performing _k_-fold cross-validation indicating Random Forest Classifier (ensemble model) best performance
-  Performing GridSearchCV on Random Forest model and determining best performance with an accuracy of 0.93, _entropy_ criterion, max depth of 10 and 40 estimators 
- Using Random Forest Classifier with discovered parameters to output multilabel classification accuracy score of 0.91

<img src="https://user-images.githubusercontent.com/34199193/123126334-4d3b4b80-d417-11eb-8a76-4ba63b8426bd.png" width=600>

