# QuantFinance-Streaming-Services-Portfolio

## Project Goal:
2020 brought a lot of changes into the world and some things became more popular than ever - streaming services are almost a necessity today. Consumers are not going outside and investors would want to look into streaming stocks. Therefore, in this project I wanted to improve my quantitative finance skills in R and look and the current boom streaming stocks are experiencing, specifically analysing AAPL, NFLX, ROKU, SPOT, DIS. Using Plotly and building visualizations from the scratch, applying Quantmod functions for performance analysis, and implementing feature engineering for ML models to perform adequte forecasting was a great way to truly learn and showcase financial engineering. 

---

## Portfolio Data:
For this project I am using data from a trustworthy source - [Yahoo Finance](https://finance.yahoo.com/). Using Quantmod, `data.frame(getSymbols.yahoo('X', from=dt, auto.assign=F))`

---

## Development:
### R Markdown EDA (RStudio):
- Preparing datasets for visual portfolio analysis by calculating relevant metrics such as SMA, EMA, Beta, Sharpe ratio, Doji candle, Bollinger Bands and more
- Creating _Candlestick_ plot with all metrics included from above to fully analyse each stock performance, price movements, changes and volume distribution
- Outputing annualized performance and returns in table and _Line_ plot, and comparing equally weighted porfolio to S&P 500 benchmark
- Feature engineering perfomed to retrieve daily Return, SMA-10, EMA-10, Upper Bolinger Band, Bottom Bolinger Band, Doji or Not, Webscrapping Article Score , Volume change, Volatility (*in progress*)
- Creating and outputing performance of ML models in form of Support Vector Machine, Naive Bayes, Random Forest, and single layer Neural Network

### Deployment (Github Pages):
- R Markdown notebook deployed as a `.html` file on Github Pages

View [Quant Finance (Streaming Services Portfolio)](https://denigomonov.github.io/QuantFinance-Streaming-Services-Portfolio/Quantitative_Trading_R.nb.html)

GIF
