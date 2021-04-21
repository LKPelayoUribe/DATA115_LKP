# DATA115_LKP



## Motivation
Is there a relationship between stocks that have a direct connection to a specific cryptocurrency? Bitcoin, the first cryptocurrency, was worth less than a penny in 2010 but now in 2021 it has surpassed $60,000. Riot Blockchain is a company that mainly focuses on creating the software to mine Bitcoin. Does the stock price of Riot depend on the current price of Bitcoin? 

## Data Process
I pulled in the stock prices into R using library(tidyquant). The stock prices are from Yahoo finance. I made the choice of using over a years’ worth of data from March 02, 2020 to March 19, 2021. The pandemic crashed both the stock and crypto market, in a sense “resetting” their prices and I wanted to see how RIOT and BTC overcame the crash. Once I pulled in my data, the cleaning process began. Stocks only trade Monday-Friday from 9:30AM-4PM Eastern time. Cryptocurrencies do not have a set “open” and “close” time, they are available for trade on the exchange 24/7. When cleaning the data, I removed the weekend dates for BTC in order to have each date have a match. I also removed the trading volume column, I only focused on open and closing prices analysis. 

## Price Distribution for Bitcoin and Riot Blockchain

<img src="https://raw.githubusercontent.com/LKPelayoUribe/DATA115_LKP/main/BTC_PriceDistribution.PNG">

<img src="https://raw.githubusercontent.com/LKPelayoUribe/DATA115_LKP/main/RIOT_PriceDistribution.PNG">

## Analysis

<img src="https://raw.githubusercontent.com/LKPelayoUribe/DATA115_LKP/main/OpenRiotVsOpenBTC.PNG">

<img src="https://raw.githubusercontent.com/LKPelayoUribe/DATA115_LKP/main/RIOTCloseVsBTCClose.PNG">

We can see correlation between the opening prices of Riot and BTC as well as the closing prices of Riot and BTC. What I find interesting is how strong the correlation is when BTC was below 20k, what some would have considered a “stable” state. BTC has been growing rapidly the last few months and BTC is still finding a new price to settle into. BTC is unstable right now and Riot shows that because of how scattered the price becomes when BTC is above 20k, unable to settle on the line with BTC as it was when BTC was stable. Regardless, Riot is still trending upwards with BTC. 
