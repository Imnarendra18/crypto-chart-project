# HTML Crypto Currency Chart Snippets

Simple and customizable HTML snippets for cryptocurrency widgets powered by the TradingView embed API.

## Author

- Name: user
- Project: HTML Crypto Currency Chart Snippets

## Overview

This repository provides ready-to-use widget pages for crypto dashboards. Each page is standalone and can be opened directly in a browser.

Included widgets:

- Full candlestick chart with indicators
- Multi-symbol ticker list
- Ticker tape
- Mini symbol chart
- Multi-symbol overview chart
- Technical analysis panel
- Single quote ticker
- Symbol information panel

## Project Files

- `Chart.html`: Candlestick chart with RSI and Stochastic RSI.
- `Ticker.html`: Multi-symbol ticker widget.
- `Ticker-Tape.html`: Horizontal ticker tape widget.
- `Mini-Chart.html`: Compact symbol overview chart.
- `Overview-Chart.html`: Multi-symbol overview panel.
- `Technical-Analysis.html`: TradingView technical summary widget.
- `Single-Ticker.html`: Single symbol quote widget.
- `Symbol-Info.html`: Symbol detail widget.
- `Images/`: Screenshots and image assets.

## Quick Start

### Option 1: Open files directly

1. Clone the repository:

```bash
git clone https://github.com/IDouble/HTML-Crypto-Currency-Chart-Snippets.git
cd HTML-Crypto-Currency-Chart-Snippets
```

2. Open any HTML file in your browser, for example:

- `Chart.html`
- `Ticker.html`
- `Technical-Analysis.html`

### Option 2: Run from a local server (recommended)

Using Python:

```bash
python -m http.server 5500
```

Then open:

```text
http://localhost:5500/Chart.html
```

## Customization Guide

You can edit each HTML file and update these widget settings:

- `symbol`: Exchange and pair, for example `BINANCE:BTCUSDT`
- `theme` or `colorTheme`: `dark` or `light`
- `interval`: Timeframe such as `1`, `60`, `D`, `1W`
- `studies`: Indicators such as RSI and MACD
- `locale`: Language code such as `en`

Example symbol changes:

- `COINBASE:BTCUSD`
- `COINBASE:ETHUSD`
- `BINANCE:SOLUSDT`

## Notes

- A stable internet connection is required because TradingView scripts load from their CDN.
- Ad blockers or strict privacy extensions may block embedded scripts.
- If a widget appears blank, refresh the page and confirm the symbol format is valid.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

## Credits

- Widget technology: TradingView Embed Widgets
- Original repository: https://github.com/IDouble/HTML-Crypto-Currency-Chart-Snippets
