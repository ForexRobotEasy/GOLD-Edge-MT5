# GOLD Edge MT5

This code is a sample implementation of the GOLD Edge MT5 expert advisor. The expert advisor is developed by the Forex Robot Easy Team and is designed for trend-following trading on the GOLD symbol. 

## Product Description

GOLD Edge MT5 is a trend-following expert advisor specifically designed for trading the GOLD symbol. It uses moving averages and the Relative Strength Index (RSI) to identify profitable trading opportunities. The expert advisor is fully automated and can be used on the MetaTrader 5 platform.

Key Features:

- Trend following strategy: The expert advisor identifies trends using moving averages and RSI indicators, allowing it to enter trades with high-profit potential.
- Grid trading: The expert advisor has a grid trading feature that allows it to enter multiple trades at different price levels, optimizing profit potential.
- Dynamic drawdown reduction: The expert advisor monitors drawdowns and automatically reduces them by closing unprofitable trades.
- Trailing stop: The expert advisor uses a trailing stop feature to lock in profits and minimize losses.
- Customizable parameters: The expert advisor allows users to customize parameters such as moving average period, RSI period, grid trading step, and trailing stop value to suit their trading preferences.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/gold-edge-mt5-review-trend-following-forex-ea-with-dd-reduce/). 

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Code Explanation

The code starts by including the necessary libraries for trading, moving averages, and RSI calculations. It then defines the input parameters such as moving average period, RSI period, grid trading step, and trailing stop value.

The code initializes the expert advisor by setting the expert magic number. 

The `OnTick()` function is executed on each tick and contains the main logic of the expert advisor. It checks if grid trading is enabled and enters buy orders when the current price is below the grid level. It also checks if drawdown reduction is enabled and closes unprofitable trades when a drawdown occurs.

The `OnNewBar()` function is executed on each new bar and updates the last profit and loss values.

The `OnPanelInput()` function handles user input from the panel and enables or disables grid trading based on the user's input.

Overall, this code implements a trend-following strategy with grid trading and drawdown reduction features, allowing the expert advisor to identify profitable trading opportunities and optimize profits while minimizing losses.
