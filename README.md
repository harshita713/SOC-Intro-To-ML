# Stock Market Price Predictor using Supervised Learning

### Aim
To examine a number of different forecasting techniques to predict future stock returns based on past returns and numerical news indicators to construct a portfolio of multiple stocks in order to diversify the risk. We do this by applying supervised learning methods for stock price forecasting by interpreting the seemingly chaotic market data.

## Setup Instructions
```
    $ workon myvirtualenv                                  [Optional]
    $ pip install -r requirements.txt
    $ python scripts/Algorithms/regression_models.py <input-dir> <output-dir>
```

Download the Dataset needed for running the code from [here](https://drive.google.com/open?id=0B2lCmt16L_r3SUtrTjBlRHk3d1E).


### Methodology 
1. Preprocessing and Cleaning
2. Feature Extraction
3. Twitter Sentiment Analysis and Score
4. Data Normalization
5. Analysis of various supervised learning methods
6. Conclusions

### Research Paper
- [Machine Learning in Stock Price Trend Forecasting. Yuqing Dai, Yuning Zhang](http://cs229.stanford.edu/proj2013/DaiZhang-MachineLearningInStockPriceTrendForecasting.pdf)
- [Stock Market Forecasting Using Machine Learning Algorithms. Shunrong Shen, Haomiao Jiang. Department of Electrical Engineering. Stanford University](http://cs229.stanford.edu/proj2012/ShenJiangZhang-StockMarketForecastingusingMachineLearningAlgorithms.pdf)


### Datasets used
1. http://www.nasdaq.com/
2. https://in.finance.yahoo.com
3. https://www.google.com/finance



### References
- [ARIMA Models](http://people.duke.edu/~rnau/411arim.htm)
- http://www.investopedia.com/articles/basics/09/simplified-measuring-interpreting-volatility.asp
- [Volatility](http://www.stock-options-made-easy.com/volatility-index.html)
- [Theano](http://deeplearning.net/software/theano/)
