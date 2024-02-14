# WaveTrend Plus

WaveTrend Plus is a custom indicator developed by Forex Robot Easy Team. It is designed to provide precision entry signals in the forex market. This indicator calculates the WaveTrend Line and WaveTrend Signal Line based on price and momentum calculations.

## Indicator Variables

- `wtLine`: An array to store the WaveTrend Line values.
- `wtSignal`: An array to store the WaveTrend Signal Line values.
- `overboughtLevel`: The overbought level.
- `oversoldLevel`: The oversold level.

## Indicator Initialization

The `OnInit` function is responsible for initializing the indicator. It sets the indicator buffers, label, and oversold/overbought levels.

## Indicator Calculation

The `OnCalculate` function is called for each tick to calculate the indicator values. It iterates through the bars and computes the WaveTrend Line and WaveTrend Signal Line using the `ComputeWaveTrendLine` and `ComputeWaveTrendSignal` functions.

## Compute WaveTrend Line

The `ComputeWaveTrendLine` function computes the WaveTrend Line based on price and momentum calculations. You can add your logic in this function to customize the calculation.

## Compute WaveTrend Signal Line

The `ComputeWaveTrendSignal` function computes the WaveTrend Signal Line based on price and momentum calculations. You can add your logic in this function to customize the calculation.

## Custom Trading Function

The `OnTick` function is called for each tick and is responsible for checking for oversold and overbought conditions. If the WaveTrend Line is above the overbought level, it indicates an oversold condition. If the WaveTrend Line is below the oversold level, it indicates an overbought condition. You can add your logic in these conditions to place trades or take necessary actions.

## Divergence Detection

The `DetectDivergence` function is a custom function for detecting divergence. You can add your logic in this function to detect divergence. The function should return true if divergence is detected, and false otherwise.

Please note that Forex Robot Easy is not the official developer of this product. This code is provided as a sample and may not function exactly as described in the product review. To find the official developer of this product, please refer to the [MQL5](https://www.mql5.com/) website.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/wavetrend-plus-review-precision-entry-with-forex-software/).
