# BTC-PERP-Price-Prediction

This project's goal was to develop a ML based price prediction model for determining the micro fairvalue of BTC-PERP (FTX). Datasets were sourced from Tardis.dev and downsampled to 1s freq. Target variables tested:
1) average of BBO,
2) volume weighted average of BBO and,
3) volume weighted average (5 levels) with exponential smoothing parameter

Mainly tested on the following models:
- hurdle model approach for inflated zeros 
- Ridge regression,
- Random Forest and,
- LGBM

Features incorporated:
- Price spread ratio
- Average ask
- Average Bid
- Volume Imbalance
- Volume Difference
- Volume spread ratio
- Accumulated Vol Difference
- Average Volume Ask
- Average Volume Bid
- Realized Volatility
- Funding Rate
- Open Interest
- Funding to OI ratio
- Liquidation Size
- Moving Average
- Previous time step log returns 
- Hour of Day
- Log Returns (mid-price Binance)
- Liquidation size (binance)
