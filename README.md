# Trade Assistant 38 in 1

[![Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/trade-assistant-38-in-1-review-simplify-and-automate-your-trading-process/)](https://forexroboteasy.com/forex-robot-review/trade-assistant-38-in-1-review-simplify-and-automate-your-trading-process/)

Trade Assistant 38 in 1 is a powerful trading tool developed by the Forex Robot Easy Team. It provides various functions to simplify and automate the trading process. This readme file provides an overview of the code and explains how it works.

## Table of Contents
- [Lot Calculator function](#lot-calculator-function)
- [Risk Calculator function](#risk-calculator-function)
- [Risk/Reward Ratio function](#riskreward-ratio-function)
- [Activation triggers for orders](#activation-triggers-for-orders)
- [Virtual Stop Loss/Take Profit levels](#virtual-stop-losstake-profit-levels)
- [Smart SL/Entry levels](#smart-slentry-levels)
- [Hidden Pending Orders](#hidden-pending-orders)
- [Scheduled Pending Orders](#scheduled-pending-orders)
- [Usage example](#usage-example)

## Lot Calculator function
The `CalculateLot` function calculates the lot size based on the risk size and stop loss specified. It uses the account balance and the risk percentage to determine the lot size.

## Risk Calculator function
The `CalculateRisk` function calculates the risk amount based on the lot size and stop loss specified. It uses the account balance and the lot size to determine the risk amount.

## Risk/Reward Ratio function
The `CalculateRR` function calculates the risk/reward ratio based on the take profit and stop loss specified. It divides the take profit by the stop loss to determine the ratio.

## Activation triggers for orders
The `SetBuyStopLimit` and `SetSellStopLimit` functions set buy stop and sell stop orders with the specified price, stop loss, and take profit. The stop loss and take profit levels are calculated relative to the price.

## Virtual Stop Loss/Take Profit levels
The `SetVirtualSL` and `SetVirtualTP` functions modify the stop loss and take profit levels of an existing order. The levels are calculated relative to the price.

## Smart SL/Entry levels
The `SetSmartSL` function modifies the stop loss level of an existing order based on the current close price. If the calculated stop loss level is lower than the current close price, it is adjusted to the current close price.

## Hidden Pending Orders
The `PlaceHiddenOrder` function places a hidden pending order with the specified type, price, stop loss, and take profit. The order is given a unique identifier and does not display any arrow symbol.

## Scheduled Pending Orders
The `PlaceScheduledOrder` function places a scheduled pending order with the specified type, price, stop loss, take profit, and expiration time. The order is given a unique identifier and does not display any arrow symbol.

## Usage example
The `OnStart` function provides an example of how to use the functions described above. It sets the risk size, stop loss, take profit, and retrieves the current ask price. It then calculates the lot size, risk amount, and risk/reward ratio. Finally, it demonstrates the usage of various order activation triggers, virtual stop loss/take profit levels, smart SL/entry levels, hidden pending orders, and scheduled pending orders.

Please note that ForexRobotEasy is not the official developer of this product. We only provide this code as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/trade-assistant-38-in-1-review-simplify-and-automate-your-trading-process/).
