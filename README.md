# Token Velocity iPython Algorithm
---
This iPython script contains the algorithm used to parse BitShares's blockchain for historical data on the transaction history of top BTS holders to estimate the velocity of BTS tokens. **Token velocity** is defined as the total BTS transaction volume divided by the amount of BTS holdings in the same time period. In this analysis, we looked at the past year's worth of trading history for the top 200 holders of BTS tokens (available at http://cryptofresh.com/a/BTS). 

![alt text](https://user-images.githubusercontent.com/35355919/36357666-4227e8a8-14cf-11e8-89f3-12f37ee209fe.jpg "Top BTS holders")

As can be seen in the table above, there are shareholders with low BTS balances as many of them do not actually sell their BTS holdings to buy other assets, but instead they borrow in SmartCoins (i.e. BitUSD, BitCNY) against their BTS holdings as collateral and then invest that proceed in other assets (such as User Issued Assets). This utility of BTS reduces token velocity as it allows long-term shareholders to retain their voting power and exposure to price appreciation while providing expanding their purchasing power. The ability to borrow in SmartCoins against their collateral provides BitShares shareholders access to liquidity and removes an incentive to sell BTS.
