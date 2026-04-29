# Ease Buy – Smart Confluence Trading Signal Indicator

Ease Buy is a TradingView Pine Script indicator built to help traders identify high-probability BUY and SELL opportunities using strong technical confluence instead of single-indicator guesses.

It combines trend, momentum, volume, and breakout confirmation into one clean and simple trading system.

---

## Features

* BUY and SELL signal generation
* Multi-confirmation trade logic
* EMA + SMA trend validation
* RSI momentum filtering
* Volume spike confirmation
* Pivot breakout detection
* Live HUD dashboard (top-right)
* Signal strength score (1–4)
* Fully customizable inputs
* Label and background visual controls

---

## Signal Logic

## BUY Signal Conditions

A BUY signal is generated when:

### Trend Confirmation

* EMA 21 > EMA 50 > SMA 200

### Momentum Confirmation

* RSI stays between 50–70

### Volume Confirmation

* Volume spike appears on a bullish candle

### Strongest Confirmation (Optional)

* Price breaks above a recent pivot high

---

## SELL Signal Conditions

A SELL signal is generated when:

### Trend Confirmation

* EMA 21 < EMA 50 < SMA 200

### Momentum Confirmation

* RSI stays between 30–50

### Volume Confirmation

* Volume spike appears on a bearish candle

### Strongest Confirmation (Optional)

* Price breaks below a recent pivot low

---

## Live HUD Dashboard

The indicator includes a real-time HUD table displayed on the top-right of the chart showing:

* Trend status
* RSI status
* Volume confirmation
* Breakout confirmation
* Current signal direction
* Signal strength score (1–4)

This helps traders quickly understand market conditions before taking entries.

---

## Customizable Settings

All values can be adjusted from the TradingView Settings panel:

* Fast EMA Length
* Slow EMA Length
* Long SMA Length
* RSI Length
* RSI Buy/Sell Zones
* Volume Spike Multiplier
* Pivot Lookback Range
* Signal Labels ON/OFF
* Background Highlights ON/OFF

---

## Best Use Cases

Ease Buy works well for:

* Scalping
* Intraday Trading
* Swing Trading
* Breakout Trading
* Trend Following Strategies

---

## Why Ease Buy?

Most indicators generate too many weak signals.

Ease Buy focuses only on strong confluence setups, helping traders avoid noise and improve decision-making with structured entries.

Less confusion.
Better setups.
Smarter trades.

---

## Installation

1. Open TradingView
2. Go to Pine Editor
3. Copy and paste the script
4. Click Add to Chart
5. Adjust settings based on your strategy

---

## Built With

* Pine Script v5
* TradingView

---

## License

This project is for educational and trading research purposes.

Use proper risk management before live trading.

---

## Author

Built for traders who prefer confirmation over prediction.
