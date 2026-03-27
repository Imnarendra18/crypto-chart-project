# 🚀 Crypto Chart Web App

<p align="center">
  📊 Real-time Cryptocurrency Charts using TradingView Widgets  
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/Imnarendra18/crypto-chart-project?style=social" />
  <img src="https://img.shields.io/github/forks/Imnarendra18/crypto-chart-project?style=social" />
  <img src="https://img.shields.io/github/license/Imnarendra18/crypto-chart-project" />
</p>

---

## 🌐 Live Demo

👉 https://imnarendra18.github.io/crypto-chart-project/

---

## 📸 Preview

<p align="center">
  <img src="screenshots/chart.png" width="80%" alt="Crypto Chart Preview"/>
</p>

---

## ✨ Features

* 📊 Interactive Crypto Charts
* ⚡ Real-time Market Data
* 📈 Technical Analysis Tools
* 🔄 Multiple Chart Views
* 📱 Fully Responsive Design

---

## 🧑‍💻 Tech Stack

* HTML5
* CSS3
* JavaScript
* TradingView Embed API

---

## 📁 Project Structure

```
HTML-Crypto-Currency-Chart-Snippets/
│── Chart.html
│── Overview-Chart.html
│── Mini-Chart.html
│── Ticker.html
│── README.md
```

---

## ⚡ Getting Started

### 🔹 Run Locally

1. Clone repo:

```bash
git clone https://github.com/Imnarendra18/crypto-chart-project.git
```

2. Open any file:

```
Overview-Chart.html
```

3. Run using Live Server or browser

---

## 📊 Example Symbols

* COINBASE:BTCUSD
* COINBASE:ETHUSD
* BINANCE:SOLUSDT

---

## 📝 Notes

* Internet required (uses TradingView CDN)
* Disable ad-block if charts not loading
* Refresh page if widget is blank

---

## 🤝 Credits

* 👨‍💻 Developed & Customized by **Narendra Kumar Yadav**
* 📊 Chart Integration: TradingView Widgets
* 🔗 Based on open-source implementation

---

## 👨‍💻 Author

**Narendra Kumar Yadav**

---

## ⭐ Support

If you like this project, please ⭐ star the repo!


![Customizable Cryptocurrency Dashboard with Chart Candlestick Price Movement Volume Stoch RSI](Images/Customizable-Cryptocurrency-Dashboard-with-Chart-Binance.png)



![Crypto Currency Chart Cryptocurrencies Candle Candlestick with indicators TradingView API RSI Stoch](Images/Chart.png)

```
<div class="tradingview-widget-container">
  <div id="tradingview_74048"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/symbols/BITFINEX-IOTUSD/" rel="noopener" target="_blank"><span class="blue-text">IOTUSD Chart</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
  <script type="text/javascript">
  new TradingView.widget(
  {
  "autosize": true,
  "symbol": "BINANCE:IOTAUSD",
  "interval": "D",
  "timezone": "Europe/Zurich",
  "theme": "Dark",
  "style": "1",
  "locale": "en",
  "toolbar_bg": "#f1f3f6",
  "enable_publishing": false,
  "hide_side_toolbar": false,
  "allow_symbol_change": true,
  "studies": [
    "RSI@tv-basicstudies",
    "StochasticRSI@tv-basicstudies"
  ],
  "container_id": "tradingview_74048"
}
  );
  </script>
</div>
```



![Crypto Currency Ticker Cryptocurrencies Chart TradingView API](Images/Crypto-Ticker.png)

```
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com" rel="noopener" target="_blank"><span class="blue-text">Quotes</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-tickers.js" async>
  {
  "symbols": [
    {
      "description": "",
      "proName": "COINBASE:BTCUSD"
    },
    {
      "description": "",
      "proName": "COINBASE:ETHUSD"
    },
    {
      "description": "",
      "proName": "BINANCE:IOTAUSD"
    }
  ],
  "colorTheme": "dark",
  "isTransparent": false,
  "locale": "en"
}
  </script>
</div
```

## [💲 Crypto Currency Ticker Tape 💲](https://Imnarendra18.github.io/HTML-Crypto-Currency-Chart-Snippets/Ticker-Tape)

![Crypto Currency Ticker Cryptocurrencies Chart TradingView API](Images/Crypto-Currency-Ticker.png)

```
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com" rel="noopener" target="_blank"><span class="blue-text">Ticker Tape</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-ticker-tape.js" async>
  {
  "symbols": [
    {
      "description": "",
      "proName": "COINBASE:BTCUSD"
    },
    {
      "description": "",
      "proName": "COINBASE:ETHUSD"
    },
    {
      "description": "",
      "proName": "BINANCE:IOTAUSD"
    }
  ],
  "colorTheme": "dark",
  "isTransparent": false,
  "displayMode": "adaptive",
  "locale": "en"
}
  </script>
</div>
```

## [💹 Mini Chart 💹](https://Imnarendra18.github.io/HTML-Crypto-Currency-Chart-Snippets/Mini-Chart)

![Crypto Currency Mini Chart Cryptocurrencies TradingView API](Images/Mini-Chart.png)

```
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/" rel="noopener nofollow" target="_blank"><span class="blue-text">IDEXUSD Rates</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-mini-symbol-overview.js" async>
  {
  "symbol": "BINANCE:IDEXUSDT",
  "width": "100%",
  "height": "100%",
  "locale": "en",
  "dateRange": "12m",
  "colorTheme": "dark",
  "trendLineColor": "rgba(164, 194, 244, 1)",
  "underLineColor": "rgba(201, 218, 248, 0.15)",
  "isTransparent": false,
  "autosize": true,
  "largeChartUrl": ""
}
  </script>
</div>
```

## [💹 Overview Chart 💹](https://Imnarendra18.github.io/HTML-Crypto-Currency-Chart-Snippets/Overview-Chart)14

![Crypto Currency Overview Chart Cryptocurrencies Chart TradingView API](Images/Overview-Chart.png)

```
<div class="tradingview-widget-container">
  <div id="tv-medium-widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/symbols/COINBASE-BTCUSD/" rel="noopener" target="_blank"><span class="blue-text">BTC</span></a>, <a href="https://www.tradingview.com/symbols/COINBASE-ETHUSD/" rel="noopener" target="_blank"><span class="blue-text">ETH</span></a> <span class="blue-text">and</span> <a href="https://www.tradingview.com/symbols/BITFINEX-IOTUSD/" rel="noopener" target="_blank"><span class="blue-text">IOT Quotes</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
  <script type="text/javascript">
  new TradingView.MediumWidget(
  {
  "container_id": "tv-medium-widget",
  "symbols": [
    [
      "BTC",
      "COINBASE:BTCUSD|12m"
    ],
    [
      "ETH",
      "COINBASE:ETHUSD|12m"
    ],
    [
      "IOT",
      "BINANCE:IOTAUSD|12m"
    ]
  ],
  "greyText": "Quotes by",
  "gridLineColor": "#e9e9ea",
  "fontColor": "#83888D",
  "underLineColor": "#dbeffb",
  "trendLineColor": "#4bafe9",
  "width": "100%",
  "height": "100%",
  "locale": "en"
}
  );
  </script>
</div>
```

## [💹 Technical Analysis 💹](https://Imnarebdra18.github.io/HTML-Crypto-Currency-Chart-Snippets/Technical-Analysis)

![Crypto Currency Technical Analysis Cryptocurrencies Symbol TradingView API](Images/Technical-Analysis.png)

```
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/symbols/COINBASE-BTCUSD/technicals/" rel="noopener" target="_blank"><span class="blue-text">Technical Analysis for BTCUSD</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-technical-analysis.js" async>
  {
  "showIntervalTabs": true,
  "width": "100%",
  "colorTheme": "dark",
  "isTransparent": false,
  "locale": "en",
  "symbol": "COINBASE:BTCUSD",
  "interval": "1W",
  "height": "100%"
}
  </script>
</div>
```

## [💲 Single Ticker 💲](https://Imnarendra18.github.io/HTML-Crypto-Currency-Chart-Snippets/Single-Ticker)

![Crypto Currency Single Ticker Cryptocurrencies Bitcoin TradingView API](Images/Single-Ticker.png)

```
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/symbols/COINBASE-BTCUSD/" rel="noopener" target="_blank"><span class="blue-text">BTCUSD Rates</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-single-quote.js" async>
  {
  "symbol": "COINBASE:BTCUSD",
  "width": "100%",
  "colorTheme": "dark",
  "isTransparent": false,
  "locale": "en"
}
  </script>
</div>
```

## [💲 Symbol Info 💲](https://Imnatrendra18.github.io/HTML-Crypto-Currency-Chart-Snippets/Symbol-Info)

![Crypto Currency Symbol Info Cryptocurrencies IDEX TradingView API](Images/Symbol-Info.png)

```
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/" rel="noopener nofollow" target="_blank"><span class="blue-text">Track all markets on TradingView</span></a></div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-symbol-info.js" async>
  {
  "symbol": "BINANCE:IDEXUSDT",
  "width": "100%",
  "locale": "en",
  "colorTheme": "dark",
  "isTransparent": false
}
  </script>
</div>
```## Credits

- 👨‍💻 Developed & Customized by **Narendra Kumar Yadav**
- 📊 Chart powered by TradingView Embed Widgets
- 🔗 Based on original open-source project

![Binance Ready to give crypto a try ? buy bitcoin and other cryptocurrencies on binance](Images/binance.jpg)
