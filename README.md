# Lutos V2 ReadMe File

This ReadMe file provides a brief overview of the Lutos V2 code and how it works. Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Program Details

- Program Name: Lutos V2
- Developer Site: [forexroboteasy.com](https://forexroboteasy.com)
- Development Name: Forex Robot Easy Team

## Trading Functions

### Support for Multiple Currency Pairs

The Lutos V2 code supports trading on multiple currency pairs. The currency pairs currently included in the code are: USDCHF, NZDCHF, CADCHF, EURAUD, EURCAD, AUDJPY, AUDNZD, EURJPY, USDCAD, CADJPY, NZDCAD, GBPCAD, and EURGBP. 

The current currency pair is selected based on the `currentPairIndex` variable.

### Minimum Deposit Requirement

To use Lutos V2, a minimum deposit of $100.00 is required. The code checks if the current account balance meets this requirement before proceeding with trading.

### Timeframe Optimization

Lutos V2 allows you to optimize the timeframe for trading. The selected timeframe can be either M5 or M1. The `selectedTimeframe` variable determines the timeframe.

### Risk Management

The code includes risk management features. The stop loss limit is set at $35.00. The stop loss price is calculated based on the entry price and the market point.

## Main Program Execution

The main program execution is handled by the `OnStart` function. Here's an overview of what happens in this function:

1. It checks if the account balance meets the minimum deposit requirement. If not, it prints an error message and exits the function.
2. It selects the current currency pair based on the `currentPairIndex`.
3. It sets the selected timeframe based on the `selectedTimeframe`.
4. It calculates the entry price and stop loss price for the trade.
5. It prints the trade details including the selected currency pair, entry price, and stop loss price.

## Logical Conclusion

The `OnTick` function handles the logical conclusion of the program. Here's an overview of what happens in this function:

1. It checks if all trades for the currency pairs have been placed. If so, it prints a message and exits the function.
2. If there are more currency pairs to trade, it closes the current trade, increments the `currentPairIndex`, and calls the `OnStart` function to place a trade for the next currency pair.

## Product Description

Lutos V2 is an advanced scalping system for forex trading. It is designed to support multiple currency pairs and offers risk management features to protect your investments. With the ability to optimize the timeframe and a minimum deposit requirement of $100.00, Lutos V2 provides flexibility and accessibility for traders of all levels.

For detailed reviews and trading results of Lutos V2, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/lutos-v2-review-advanced-scalping-system-for-forex-trading/).
