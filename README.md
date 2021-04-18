# DATA115_LKP



## Motivation
Is there be a relationship between stocks that have a direct relationship to a specific cryptocurrency? Bitcoin was the first cryptocurrency, and it uses blockchain technology. A single Bitcoin was worth less than a penny in 2010 now in 2021 it has surpassed $60,000. Riot Blockchain is a company that mainly focuses on creating the software to mine Bitcoin. Does the stock price of Riot depend on the current price of Bitcoin? Riot was just above a dollar a year ago and now it is at $49. BTC was struggling just to stay at 10k a year ago but after the crash in March of 2020, it dropped to 5K but it has been on the rise, right now at 60k.

## Data Process
I pulled in the stock prices into R using library(tidyquant). The stock prices are from Yahoo finance. I made the choice of using over a years’ worth of data from March 02, 2020 to March 19, 2021 because a lot has happened during this time. Especially because the pandemic crashed the market, affecting both stock and crypto, in a sense “resetting” their prices. Once I pulled in my data, the cleaning process began. There are many differences in stock and crypto. For example, RIOT only trades Monday-Friday from 9:30AM-4PM. Cryptocurrencies do not have a set “open” and “close” time, they are available for trade 24/7. When cleaning the data, I removed the weekend dates for BTC in order to have each date have a match. 

## Price Distribution for Bitcoin and Riot Blockchain

<img src="https://raw.githubusercontent.com/LKPelayoUribe/DATA115_LKP/main/BTC_PriceDistribution.PNG">

<img src="https://raw.githubusercontent.com/LKPelayoUribe/DATA115_LKP/main/RIOT_PriceDistribution.PNG">

## Analysis

<img src="https://raw.githubusercontent.com/LKPelayoUribe/DATA115_LKP/main/OpenRiotVsOpenBTC.PNG">

<img src="https://github.com/LKPelayoUribe/DATA115_LKP/blob/main/CloseRiotVsOpenBTC.PNG">
