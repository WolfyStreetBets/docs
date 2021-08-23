
# Staking in Prediction Markets

This section of the documentation hosts guides and tutorials for how to stake in a prediction market on [WolfyStreetBets](https://wolfystreetbets.com)

***

## Pre-requisites

1. Ensure you have authenticated your WOLFY balance. See here for details on how to do this: [WOLFY Requirement](requirements.md)

2. Ensure you are using the right network &amp; consequently, the right assets. See which assets are currently supported below.

### Supported Assets

* Polygon
    * Tether (USDT) [0xc2132d05d31c914a87c6611c10748aeb04b58e8f](https://polygonscan.com/token/0xc2132d05d31c914a87c6611c10748aeb04b58e8f)
    * Wrapped Ether (wETH) [0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619](https://polygonscan.com/token/0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619)
    * Wrapped Bitcoin (wBTC) [0x1bfd67037b42cf73acf2047067bd4f2c47d9bfd6](https://polygonscan.com/token/0x1bfd67037b42cf73acf2047067bd4f2c47d9bfd6)

* Binance Smart Chain
    * Binance USD (BUSD) [0xe9e7cea3dedca5984780bafc599bd69add087d56](https://bscscan.com/token/0xe9e7cea3dedca5984780bafc599bd69add087d56)
    * PancakeSwap (CAKE) [0x0e09fabb73bd3ade0a17ecc321fd13a19e81ce82](https://bscscan.com/token/0x0e09fabb73bd3ade0a17ecc321fd13a19e81ce82)
    * Bitcoin Bep2 (BTCB) [0x7130d2a12b9bcbfae4f2634d864a1ee1ce3ead9c](https://bscscan.com/token/0x7130d2a12b9bcbfae4f2634d864a1ee1ce3ead9c)

***

## How to stake

NOTE: A 2% Liquidity Provider (LP) fee is paid upon each Stake.

### Connect to WolfyStreetBets

When you are directed to the dApp page after authenticating e.g. https://polygon.wolfystreetbets.com you will be prompted to connect your web3 wallet.   
Clicking 'Connect' will then initialize, and register your wallet/account.

### Choose an Asset

Choose an asset from the dropdown list. Once you select an asset, click 'Initialize' the dApp will auto-update by connecting to the asset-specific smart contract and fetching values like your spend allowance and market/liquidity statistics.

### Approve an amount

Enter an amount you'd like to use on WolfyStreetBets and click the 'Approve' button.

### Choose a view

If you'd like to quickly stake, choose the 'Quick View' dropdown and click on the 'Predict' tab. Or, choose 'Detailed View' if you'd like to view resources like charts &amp; news to help your prediction decision making. 

### Stake!

* Select a risk factor (notice the update in reward/loss ratio)
* Enter an amount to stake (notice the LP fee update)
* Click Stake! 
* Sign the transaction via your wallet (notice, no gas fee!)
* That's it! Check the stats to view your stake and updated totals.

***

## Limits

**There are Staking Limits** which are derived from the total amount available in liquidity.   
For low risk markets, the staking limit is 6x total liquidity. For high risk, 3x total liquidity.