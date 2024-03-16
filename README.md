# Africa Breakout Expert Advisor ReadMe

This ReadMe file provides information about the Africa Breakout Expert Advisor code. Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Description

The Africa Breakout Expert Advisor is designed to identify and trade breakouts in the Forex market. It uses the Camarilla indicator to determine potential breakout levels and opens trades accordingly. The Expert Advisor is programmed to enter a buy trade when the closing price is above the R3 pivot point and the opening price is below the R3 pivot point. Similarly, it enters a sell trade when the closing price is below the S3 pivot point and the opening price is above the S3 pivot point.

## Input Parameters

The Expert Advisor has the following customizable input parameters:

- `StopLoss`: The Stop Loss value in points (default: 100)
- `TakeProfit`: The Take Profit value in points (default: 200)
- `LotSize`: The Lot Size value (default: 0.1)
- `Slippage`: The maximum allowed slippage (default: 3)

## Indicator Handles

The Expert Advisor uses the following indicator handle:

- `iCamarilla`: Camarilla indicator handle

## Initialization Function

The `OnInit()` function is responsible for initializing the Expert Advisor. It creates the Camarilla indicator and checks if the creation was successful. If the indicator creation fails, an error message is printed, and the initialization fails.

## Deinitialization Function

The `OnDeinit()` function is called when the Expert Advisor is being shut down. It deletes the Camarilla indicator from the chart.

## Start Function

The `OnTick()` function is the main entry point for the Expert Advisor. It is called on each tick of the price. The function retrieves the daily high, low, open, and close prices. It also calculates the R3 and S3 pivot points using the Camarilla indicator. If a bullish breakout is detected (closing price above R3 and opening price below R3), a buy trade is opened. If a bearish breakout is detected (closing price below S3 and opening price above S3), a sell trade is opened. Error messages are printed if there are any issues with opening the trades.

## Product Description

Product Name: Africa Breakout Expert Advisor
Product Link: [Africa Breakout](https://www.forexroboteasy.com)
Developer: Forex Robot Easy Team

The Africa Breakout Expert Advisor is designed to optimize Forex trading with the USD/ZAR currency pair. It utilizes breakout strategies to identify potential trading opportunities. The Expert Advisor is programmed to enter trades based on the Camarilla indicator, which helps determine breakout levels. It automatically opens buy trades when a bullish breakout occurs and sell trades when a bearish breakout occurs. The Expert Advisor allows customization of parameters such as Stop Loss, Take Profit, Lot Size, and Slippage to suit individual trading preferences.

For detailed reviews and trading results of this product, please visit [Africa Breakout Review - Optimize Forex with USD/ZAR Backtest](https://forexroboteasy.com/forex-robot-review/africa-breakout-review-optimize-forex-with-usdzar-backtest/).

Please note that ForexRobotEasy is not the official developer of this product. We are showcasing sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
