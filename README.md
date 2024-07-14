## **Real-time-Stock-Market-predictor-using-Candlestick-patterns**

### Candlestick Chart
A candlestick chart is a financial chart used to represent an asset's price movements over a specified period. Each "candlestick" typically shows four key pieces of information: the opening price, closing price, highest price, and lowest price during that period. The body of the candlestick represents the range between the opening and closing prices, while the wicks (or shadows) show the high and low prices. Candlesticks are colour-coded, green for price increases and red for price decreases, to easily indicate market trends. This chart type is widely used in technical analysis to identify potential market direction and trading opportunities.

This code obtains real-time Stock Market data from Alpha Vantage API and detects two of my favourite Candlestick Patterns: Doji and Tweezer

### Doji Pattern 
A Doji candlestick pattern occurs when an asset's opening and closing prices are nearly equal, resulting in a very small body that appears as a thin horizontal line. This pattern suggests indecision or a balance between buyers and sellers in the market, often signalling a potential reversal or continuation depending on its context and the preceding price action. Traders interpret the Doji as a potential reversal signal when a pattern with the same trend colour follows it. As in, a Green candlestick after a Bullish Doji might hint at a stock rise. Whereas, a Bearish Doji followed by a Red candlestick indicates a potential fall in stock value.

### Tweezer
A Tweezer pattern in candlestick charting consists of two consecutive candlesticks with almost identical highs and lows, appearing side by side. This pattern typically signals a potential reversal of the prevailing trend when it forms at key support or resistance levels. 

### Generate API Key
To obtain the real-time stock data, go to Alpha Vantage API's website (https://www.alphavantage.co/) and generate a free API Key. This key needs to be mentioned in the code so that it can fetch the required data.
