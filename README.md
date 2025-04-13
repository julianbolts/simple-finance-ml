## Simple Finance Machine Learning

A simple project space for learning and experimenting with traditional ML 
techniques for financial data, like Random Forest classifiers and Gradient 
Boosting. Backtests are included as well.

We will look at data from the classic yahoo finance API, as well as Alpaca API
and Numerai. 

While these are relatively naive approaches to trading, and I would not implement them as shown here, it is good practice for understanding the building blocks of ML for financial data / quant finance.


### See the notebooks live on Google collab:

* Project 1: find probability of positive MSFT price movement using Random Forests (naive approach)

    - [Project Info](https://colab.research.google.com/github/julianbolts/simple-finance-ml/blob/main/p1_msft/sfm_p1_msft_info.ipynb) - readme info with interactive notebook
    - [MSFT project with Random Forests](https://colab.research.google.com/github/julianbolts/simple-finance-ml/blob/main/p1_msft/sfm_p1_msft_project.ipynb) - data from yfinance, data prep with pandas, and RandomForestClassifier with scikit-learn
    - attribution: project from [dataquestio](https://github.com/dataquestio/project-walkthroughs)

* Project 2: find probability of positive S&P 500 price movement using Random Forests (naive approach)

    - [S&P500 index project with Random Forests](https://colab.research.google.com/github/julianbolts/simple-finance-ml/blob/main/p2_sp500/sfm_p2_sp500_project.ipynb) - data from yfinance, data prep with pandas, and RandomForestClassifier with scikit-learn
    - attribution: project from [dataquestio](https://github.com/dataquestio/project-walkthroughs)
