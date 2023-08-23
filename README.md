# Assistive-Indicator
Cryptocurrencies, foreign exchange, stock market, gold etc. auxiliary indicator to be used in trading for units. This indicator is made using Pine Script. You can use it as you wish by pasting it instead of the code on the Trading View platform.

The provided code plots multiple indicators, mainly:

1. Four EMAs (Exponential Moving Averages)**: These are plotted in yellow, orange, purple, and maroon colors respectively.
2. Fibonacci Levels based on the recent 'X' bars:
   - Plots High and Low levels.
   - Calculates and plots various Fibonacci retracement levels: 23.6%, 38.2%, 61.8%, and 76.4%.
   - Uses filled zones to indicate different trend regions based on these levels.
3. VWMA-based Channel:
   - Calculates a VWMA (Volume Weighted Moving Average).
   - Calculates a channel around this VWMA using a given standard deviation.

Concise summary, here it is:
The code plots four EMAs of lengths 20, 50, 100, and 200. It also calculates the high and low of the past 'X' bars to create Fibonacci retracement levels which are used to indicate uptrend, middle trend, and downtrend zones. Additionally, it plots a VWMA and a channel around it based on a standard deviation.
