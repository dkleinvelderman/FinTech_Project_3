# FinTech Project 3: STAGE

![STAGE](./STAGE-med.gif)

## Statistical Arbitrage: Mean Reversion Analyses in the Crypto Market
*A Python-powered quantatative, analytical approach to pairs trading on the Crypto Market by Juan Cajigas, Francisco Lopez, Daniel Klein Velderman and Steffen Westerburger*

## Introduction

This project focuses on the concept of statistical arbitrage on the Crypto Currency market. As the conceptual basis of this project we used the research paper ['Statistical Arbitrage in the U.S. Equities Market'](https://www.math.nyu.edu/faculty/avellane/AvellanedaLeeStatArb071008.pdf) (Avellenda, Lee 2008).

Statistical arbitrage is a trading strategy which utilizes mean reversion to invest in diverse pairs and/or portfolios. It does so by investing and divesting in these pairs for very short periods of time/high frequency trading (from only seconds up to a couple of days). In doing so it heavily relies on market prices to return to a historical or predicted normal which is called the mean reversion (Investopedia)

Statistical arbitrage strategies are market neutral. This is the case because for each position that is taken, a long position and short position is taken. In doing so the aim is to profit from inefficient pricing differences in correlated securities. One could for example think of an analysis between American Airlines and Delta Airlines. If data shows American Airlines is undervalued and Delta is overvalued - you would subsequently open a long position in American Airlines and a short position in Delta Airlines. 

We developed an algorithm using Python to help us trade on potentially correlated pairs of crypto currencies. This algorithm allows us to trade correlated currencies on inefficient pricing differences for which the user can determine the conditions (in terms of standard deviations from the mean).

## Data

In this project we build on two main data sources. We use the [Binance](www.binance.com) exchange API integration for Python to pull in realtime time minute to minute price information on the crypto currencies of choice. Binance is a well known name in the industry and operates as the worlds biggest bitcoin exchange and altcoin crypto exchange in the world by volume. To use the Binance integration with Python, one needs to sign up to receive API-keys as well as install the Binance library by using  **pip install python-binance**.

The second source we use is [Kucoin](www.kucoin.com) which is a Bitcoin exchange that provides users with a unique sandbox environment to test their trading strategies. Using Kucoin we were able to place automated fictional trades with our Pythin algorithm based on real time price information we pulled in from Binance. To use Kucoin one needs to sign up for the Sandbox environment and install the Kucoin library by using **pip install python-kucoin**.

## Our Algorithm

SHORT OVERVIEW OF THEORY / MATHEMATICAL CHOICES / REGRESSION AR AND ARMA


## Trading with the Algorithm: Binance and Kucoin

As aforementioned, we use both Binance and Kucoin in this project to trade based on our developed algorithm. Kucoin provides a free sandbox environment to this end. 

ADD SCREENSHOTS

## Backtesting

In order to test whether our algorithm is a could potentially provide us with valuable/profitable trading insights, it is important to properly backtest our algorithm by testing it with historical data. In doing so we can determine the performance of our algorithm, as well as determine under what conditions it performs best (for exmaple in terms of number of standard deviations from the mean between to correlated stocks).

We backtested our algorithm using historical data of the correlarion between BTC and ETH. We tested out code's performance with three different standard deviation levels: 0.5, 1 and 1.5.

ADD SCREENSHOTS/ EXPLANATION

## Post-Mortem

This project provided us with a unique opportunity to explore several trade strategies focusing on statistical arbitrage. Statistical arbitrage is a very theoretical and complicated subject which heavily relies on being able to engage in well informed high-frequency trading.

For pratical reasons we used two different exchanges for pulling in price information and making the actual trades. In any real world trading situation this would not be a clever strategy since even the tiniest of discrepencies between exchanges potentially have great impact on the success or failure of these strategies. 

Also, in this project we focused on the trading of just one pair of potentiallt correlated crypto currencies. In a real world situation statistical arbitrage usually involves diverse portfolios of up to thousands of securities. 

OTHER TAKE AWAYS/ MAYBE LINK TO A TRADING TOKEN?










