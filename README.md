# Trading Strategy: Quantitative Analysis on Moving Averages and Price Lows/Highs

This repository contains the implementation of a quantitative trading strategy that utilizes a combination of moving averages and price lows/highs to determine market entry and exit points. Below, we provide a detailed explanation of the strategy and how it is implemented.

## Strategy Overview
The trading strategy is designed around two main principles:

1. **Market Entry Criteria:**
   - Enter the market if the current closing price is lower than the previous 20-day low.
   - The current market must also be trading above the 200-day Simple Moving Average (SMA).

2. **Market Exit Criteria:**
   - Exit the market if the current closing price is higher than the previous 20-day high.
   - The current market must still be above the 200-day SMA.
