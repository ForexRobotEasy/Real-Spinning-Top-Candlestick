# Real Spinning Top Candlestick Indicator

This is a custom indicator for the MetaTrader 4 platform that identifies and plots spinning top candlestick patterns on the chart. Spinning tops are candlestick patterns that have a small body and long upper and lower wicks. These patterns indicate indecision in the market and can signal potential trend reversals.

## Indicator Input Parameters

- `bodyToWickRatio`: Ratio of body height to wick height. Default value is 2.
- `iconType`: Icon type to represent spinning tops. Default value is 83 (wingdings icons).

## Indicator Initialization Function

The `OnInit()` function is called when the indicator is initialized. It adds the indicator name and parameters to the chart using the `Comment()` function. It also sets up the chart properties to show icons using the `ChartSetInteger()` function.

## Indicator Iteration Function

The `OnCalculate()` function is called for each bar on the chart. It calculates the body and wick height of each candlestick using the open, high, low, and close prices. It then calculates the body to wick ratio. If the ratio is less than or equal to the specified `bodyToWickRatio`, it plots the spinning top icon on the chart using the `ChartSetInteger()` function.

## Indicator Deinitialization Function

The `OnDeinit()` function is called when the indicator is removed from the chart. It removes the indicator name and parameters from the chart using the `Comment()` function.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to the following link: [Real Spinning Top Candlestick - Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-real-spinning-top-candlestick-precise-forex-indicator/)

For detailed reviews and trading results of this product, please visit the link provided above.
