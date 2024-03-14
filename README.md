# Day Trader WorkTime Indicator

## Description
The Day Trader WorkTime indicator is designed to calculate and display the range of the Asian trading session on the chart. It helps traders identify whether the range of the Asian session exceeds a specified maximum range. 

This indicator is not developed by ForexRobotEasy. It is a sample code provided for educational purposes. For detailed reviews and trading results of the official product, please visit [this link](https://forexroboteasy.com/forex-robot-review/day-trader-worktime-review-optimize-your-forex-trades/).

## Input Parameters
The following input parameters can be customized:

- `AsianSessionStartHour` (default: 22): Start hour of the Asian session
- `AsianSessionStartMinute` (default: 0): Start minute of the Asian session
- `AsianSessionEndHour` (default: 6): End hour of the Asian session
- `AsianSessionEndMinute` (default: 0): End minute of the Asian session
- `AsianSessionBoxColor` (default: clrDodgerBlue): Color of the Asian session box
- `MaxAsianSessionRangeInPips` (default: 50): Maximum range of the Asian session in pips

## Variables
The indicator uses the following variables:

- `AsianSessionStart`: Start time of the Asian session
- `AsianSessionEnd`: End time of the Asian session
- `AsianSessionRangeExceeded`: Flag to indicate if the Asian session range is exceeded

## Initialization
The Asian session start and end times are calculated based on the input parameters during the initialization process.

## Calculation
The `OnCalculate` function is responsible for calculating the Asian session range and checking if it exceeds the maximum range. It also draws or deletes the Asian session box on the chart based on the result.

## Removal
The `OnDeinit` function removes the Asian session box from the chart when the indicator is removed.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.
