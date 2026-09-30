# Candlestick Chart Engine & Paper-Trading Simulator

## Project Overview

**Candlestick Chart Engine & Paper-Trading Simulator** is an interactive web-based trading simulation application developed using **HTML, CSS, and vanilla JavaScript**. The project provides a realistic trading-terminal experience where users can analyze simulated market price movements through candlestick charts and practice buying and selling assets using virtual money without any real financial risk.

The application combines a custom-built **candlestick chart rendering engine** with a **paper-trading system**, allowing users to observe simulated price movements, place market orders, manage long and short positions, and monitor portfolio performance in real time.

## Key Features

* **Interactive Candlestick Chart**

  * Displays Open, High, Low, and Close (OHLC) price data.
  * Dynamically renders bullish and bearish candles using HTML5 Canvas.
  * Includes a current-price reference line.

* **Multiple Timeframes**

  * Supports 1-minute, 5-minute, 15-minute, 1-hour, and 4-hour views.
  * Allows users to switch between different chart perspectives.

* **Paper Trading**

  * Provides a virtual trading account with configurable starting capital.
  * Supports simulated BUY and SELL market orders.
  * No real money or brokerage account is involved.

* **Long & Short Positions**

  * Users can open long positions by buying an asset.
  * Users can open short positions by selling an asset.
  * Opposite orders automatically match and close existing positions.

* **Real-Time P&L Calculation**

  * Calculates unrealized profit/loss for open positions.
  * Tracks realized profit/loss after positions are closed.
  * Continuously updates account equity and available cash.

* **Position Management**

  * Displays quantity, entry price, position type, and unrealized P&L.
  * Supports multiple open positions.

* **Trade History**

  * Records executed orders, quantities, prices, timestamps, and realized P&L.

* **Chart Interaction**

  * Mouse wheel zooming.
  * Drag-to-pan functionality.
  * Dynamic chart scaling based on visible price data.

* **Persistent Data**

  * Uses browser **LocalStorage** to preserve the simulated trading account and trade history between sessions.

* **Responsive Interface**

  * Designed with a modern dark trading-terminal interface.
  * Works across desktop, tablet, and mobile screen sizes.

## Technologies Used

| Technology            | Purpose                                       |
| --------------------- | --------------------------------------------- |
| **HTML5**             | Application structure and interface           |
| **CSS3**              | Responsive layout, styling, dark trading UI   |
| **JavaScript (ES6+)** | Trading logic, chart engine, P&L calculations |
| **HTML5 Canvas**      | Real-time candlestick rendering               |
| **LocalStorage API**  | Persistent account and trade data             |

## How It Works

The application generates simulated OHLC market data using JavaScript. The chart engine processes this data and renders each candlestick on an HTML5 Canvas.

When the user places a BUY or SELL order, the simulator calculates the order value using the current market price. If an opposite position already exists, the system automatically matches the new order against that position and calculates the resulting realized profit or loss. Any remaining quantity becomes a new long or short position.

The application then recalculates:

**Account Equity = Cash + Market Value of Open Positions**

and continuously displays the user's cash balance, equity, realized P&L, and unrealized P&L.

## Project Objective

The main objective of this project is to demonstrate how a browser-based trading simulation system can be developed without relying on external trading platforms or financial APIs. It combines concepts from **data visualization, financial calculations, JavaScript programming, UI/UX design, and state management** into one practical web application.

## Learning Outcomes

Through this project, the following technical skills are demonstrated:

* JavaScript programming and DOM manipulation
* HTML5 Canvas-based data visualization
* Financial P&L calculations
* Trading position management
* Event-driven programming
* Browser LocalStorage
* Responsive web design
* Interactive UI development
* Object and array-based state management
* Algorithmic handling of long and short positions

## Future Enhancements

The simulator can be further extended with:

* Real-time cryptocurrency or stock market APIs
* Technical indicators such as RSI, MACD, EMA, and Bollinger Bands
* Limit and stop-loss orders
* Take-profit functionality
* Portfolio performance charts
* Risk management tools
* Transaction fees and slippage
* Multiple trading assets
* Advanced drawing tools
* Login and cloud-based portfolio storage
* Backtesting functionality
* Trading strategy automation
* WebSocket-based live market data

## Project Type

**Frontend Web Application / Financial Technology (FinTech) Simulation**

## Conclusion

The **Candlestick Chart Engine & Paper-Trading Simulator** demonstrates the development of a complete browser-based trading environment using core web technologies. By combining interactive chart visualization with simulated order execution, position management, and portfolio analytics, the project provides a practical demonstration of how financial applications can be designed and implemented using **HTML, CSS, and JavaScript**.

