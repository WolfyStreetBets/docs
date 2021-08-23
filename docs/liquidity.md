
# Liquidity Providers

This section of the documentation hosts guides and tutorials for how to provide liquidity to a Prediction Market on [WolfyStreetBets](https://wolfystreetbets.com)   

This section also details how the decentralized liquidity protocol works within WolfyStreetBets Prediction Markets, including APR calculation, withdrawal periods and more.

*** 

## How it works

Sustainable liquidity is a dominant issue in Crypto-based Prediction Markets. That's why at WolfyStreetBets we've decentralized everything.   
This means the liquidity is completely managed by the users and community. 

On each stake, prediction market participants pay 2% of their total stake as a fee - which gets auto-distributed to Liquidity Providers (LPs).    
By supplying liquidity to a prediction market, you are effectively mining single-asset liquidity. This is beneficial in comparison to more traditional mining because you don't have to supply two assets to earn interest on one. On WolfyStreetBets, just like Prediction Market Stakers, LPs have the power to choose both an asset and a market risk factor to supply liquidity to. 

### APR

Annual Percentage Rate (APR) is calculated in a similar way to Uniswap APY. However, because fees are not auto-compounded and put back into liquidity, the yield is not compounding. 

Of course, you could collect LP rewards (at any time) and re-supply to boost your LP and therefore increase your LP rewards.

APR is therefore dependent on staking volume. 

On weekly pools:

APR = (Staking Volume * 52) / 50
Annual Percentage Rate = 2% of (Staking Volume x 52 weeks) 

*A simple calculation that could be more accurate and factor in a user's % of pool. However, APR would then have to be calculated to be specific to each user (after they've provided liquidity)*

### Liquidity Cycles

A Liquidity Cycle (LC) in WolfyStreetBets is an event that occurs at the end of a Prediction Market period. 

It is a 12 hour time-box where LPs can withdraw their previously supplied liquidity. This window is activated immediately after a pool is stopped and all calculations (loss, reward etc.) have been executed. 

A Liquidity Cycle enables 'natural', or user-governed evolution of a prediction market in terms of liquidity. This way, it remains truly decentralized. The 'house' is never a winner.

***

## How to Add Liquidity

### Choose an Asset

Choose an asset from the dropdown list. Once you select an asset, click 'Initialize' and the dApp will auto-update by connecting to the asset-specific smart contract and fetching values like your spend allowance and market/liquidity statistics.

### Approve an amount

Enter an amount you'd like to use on WolfyStreetBets and click the 'Approve' button.

### Choose a view

If you'd like to quickly add liquidity, choose the 'Quick View' dropdown and click on the 'Liquidity' tab. Or, choose 'Detailed View' if you'd like to view resources like charts &amp; news to help your decision making. 

### Supply!

* Select a risk factor (Each risk factor has its' own liquidity/market managed. In the code, they are 2 separate markets - for ease of liquidity management &amp; distribution)
* Enter an amount to supply.
* Click Add Liquidity! 
* Sign the transaction via your wallet (notice, no gas fee!)
* That's it! Check the stats to view your supplied liquidity and updated totals.

## How to Collect LP Rewards

LP Rewards are distributed instantly, upon each Stake transaction. You can withdraw LP Rewards at anytime by scrolling to the 'Collect LP Fees section'.