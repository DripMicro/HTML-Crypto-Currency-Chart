# 💹 HTML Crypto Currency Chart Snippets 💹
💹 Simple HTML Snippets to create Tickers / Charts of Cryptocurrencies with the TradingView API 💹

## [💲 Crypto Currency Ticker 💲](https://ayidouble.github.io/HTML-Crypto-Currency-Chart-Snippets/Ticker)

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
      "proName": "BITFINEX:IOTUSD"
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

## [💹 Mini Chart 💹](https://ayidouble.github.io/HTML-Crypto-Currency-Chart-Snippets/Mini-Chart)

![Crypto Currency Mini Chart Cryptocurrencies TradingView API](Images/Mini-Chart.png)

```
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/symbols/BITFINEX-IOTUSD/" rel="noopener" target="_blank"><span class="blue-text">IOTUSD Rates</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-mini-symbol-overview.js" async>
  {
  "symbol": "BITFINEX:IOTUSD",
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

## [💹 Candle Chart with Indicators 💹](https://ayidouble.github.io/HTML-Crypto-Currency-Chart-Snippets/Chart)

![Crypto Currency Chart Cryptocurrencies Candle with indicators TradingView API RSI Stoch](Images/Chart.png)

```
<div class="tradingview-widget-container">
  <div id="tradingview_74048"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com/symbols/BITFINEX-IOTUSD/" rel="noopener" target="_blank"><span class="blue-text">IOTUSD Chart</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
  <script type="text/javascript">
  new TradingView.widget(
  {
  "autosize": true,
  "symbol": "BITFINEX:IOTUSD",
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

## [💹 Overview Chart 💹](https://ayidouble.github.io/HTML-Crypto-Currency-Chart-Snippets/Overview-Chart)

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
      "BITFINEX:IOTUSD|12m"
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

## [💹 Technical Analysis 💹](https://ayidouble.github.io/HTML-Crypto-Currency-Chart-Snippets/Technical-Analysis)

![Crypto Currency Overview Chart Cryptocurrencies Chart TradingView API](Images/Technical-Analysis.png)

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
