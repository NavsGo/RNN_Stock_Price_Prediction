# RNN_Stock_Price_Prediction
# CNN Waste Segregation

## Table of Contents

* [Introduction](#introduction)
    * [Business Problem](#business-problem)  
    * [Key business benefits](#key-business-benefits)
* [Insights](#insights)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Dataset](#dataset)
* [Contact](#contact)


## Introduction

### Business Problem
A stock market, equity market, or share market is the aggregation of buyers and sellers of stocks (also called shares), which represent ownership claims on businesses; these may include securities listed on a public stock exchange, as well as stock that is only traded privately, such as shares of private companies which are sold to investors through equity crowdfunding platforms. Investment in the stock market is most often done via stock brokerages and electronic trading platforms. Investment is usually made with an investment strategy in mind.


### Key business benefits:

* Predict the next day stock prices given a trend for last 3 days for price and volume.
* Help to decide which stock to buy that are likely to increase in price and then sell stocks that are probably to fall.

## Insights:

* All stocks are equally represented for a period of 10 years from 2006 - 2015
* In terms of prices, Microsoft stock price is consistenly lowest followed by IBM, Google and Amazon.
* All stock prices dropped significantly in year 2008 followed by a huge price jump in year 2010.
* Microsoft is most traded(highest volumes) stock with highest fluctuations in volume over time
* All prices are highly co-rrelated, hence only close price and Volume are taken for modeling
* Based on price trend, 3 days window is taken along with 1 stride

## Conclusions:

* While LSTM model performed far better than SimpleRNN model, both models are quite inaccurate. Possible reason can be small data set. More data is needed to train the model further.

## Technologies Used

- seaborn 0.11.1
- jupyter 1.0.0
- numpy 1.20.1
- anaconda 2021.05
- python 3.8.8 
- matplotlib 3.3.4
- tensorflow 2.19.1

# Dataset
available in repository

## Contact

Created by [@NavsGo](@navsgo) - feel free to contact me!

