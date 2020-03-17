## FART-Set

### Intro
This repository contains all code for backtesting for the [FART Set](https://set-beta.tokensets.com/set/fart).

#### Description
* Find long/short signals for ETH/BTC
  * Long = Buy ETH and Sell BTC
  * Short = Buy BTC and Sell ETH


### Directories
* Backtests
  * Contains CSV's of backtested results (both compounded and absolute)


### To-Do
* [x] Pick time frame for candlesticks (4h)
* [x] Create signals
* [ ] Compare signal performance
* [ ] Add slippage / fees
* [ ] Determine relationship of ETH to BTC to DAI
* [ ] How long to keep a trade open?
  1. Specific time duration
  2. Specific percent
    - Static percent or based on recent price?
* [ ] How long to wait after a trade to allow a second trade?