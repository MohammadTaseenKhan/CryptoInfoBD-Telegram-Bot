# 📊 CryptoInfoBD Telegram Bot

> **A powerful Telegram-based crypto and financial market assistant for real-time prices, market analysis, charts, alerts, portfolios, and more.**

[![Telegram Bot](https://img.shields.io/badge/Telegram-Bot-26A5E4?logo=telegram\&logoColor=white)](https://t.me/cryptoinfobd_bot)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)](#)
[![Source](https://img.shields.io/badge/Source-Private-lightgrey)](#)

**CryptoInfoBD** is a feature-rich Telegram bot built to make cryptocurrency and financial market information accessible directly from Telegram.

Instead of opening multiple websites or apps, users can check crypto prices, compare assets, view charts, monitor markets, manage watchlists and portfolios, set alerts, and access additional financial market data — all from within Telegram.

The bot also supports **Telegram Inline Mode**, allowing users to query market information directly from chats where the bot does not need to be a member.

> 🔒 **This repository contains documentation only. The bot's source code is private and is not open source.**

---

## ✨ Features

### 💰 Cryptocurrency Prices

Get real-time cryptocurrency market information by simply sending a coin symbol or using commands.

Examples:

```text
btc
eth
5 btc
5000 bdt btc
```

The bot can provide information such as:

* Current price
* 24-hour price change
* Trading volume
* Market capitalization
* USD pricing
* BDT conversion
* Price charts
* Interactive market information

The bot uses multiple data sources and fallback mechanisms to improve reliability when a primary market-data provider is unavailable.

---

### 📈 Market Overview

Explore the broader cryptocurrency market with commands for:

* Top cryptocurrencies
* 24-hour gainers
* 24-hour losers
* Market snapshots
* Crypto market sentiment
* Market risk analysis
* Trend analysis
* Market scanners

The bot's trend analysis can evaluate technical indicators such as **RSI** and **SMA-based signals** to produce a simplified market interpretation.

> ⚠️ Market analysis is provided for informational purposes only and should not be considered financial advice.

---

### 📊 Charts & Technical Analysis

View historical market data through generated charts and technical analysis.

Supported chart timeframes include:

* 1 Day
* 7 Days
* 30 Days
* 1 Year

Depending on the asset and feature, the bot can provide:

* Price charts
* OHLC/candlestick data
* RSI analysis
* SMA20
* SMA50
* Bullish/Bearish/Neutral trend interpretation

---

### ⚖️ Cryptocurrency Comparison

Compare two cryptocurrencies directly.

```text
btc vs eth
```

or:

```text
btc/eth
```

This makes it easy to quickly compare two assets without manually checking each one separately.

---

### 💱 Multi-Asset Quotes

The bot is not limited to cryptocurrency.

It also supports market quotes for:

#### Forex

Examples:

```text
/quote eurusd
/quote usdjpy
/quote usdbdt
```

#### Indices & Commodities

Examples:

```text
/quote spx
/quote nasdaq
/quote dow
/quote gold
/quote silver
/quote oil
/quote vix
```

This allows CryptoInfoBD to act as a broader financial market information tool rather than a crypto-only price bot.

---

### 🔄 Currency & Asset Conversion

Convert values between supported assets and currencies.

Example:

```text
/convert 5 btc to eth
```

The conversion system is designed to work across supported:

* Cryptocurrencies
* Fiat currencies
* Forex pairs
* Market assets

---

### ⭐ Watchlists

Users can maintain their own personal cryptocurrency watchlist.

Examples:

```text
/watch btc eth sol
```

Remove an asset:

```text
/unwatch btc
```

View the watchlist:

```text
/mywatchlist
```

Users can quickly monitor selected assets without repeatedly searching for individual coins.

---

### 🔔 Price Alerts

Set price-based alerts for cryptocurrencies.

Examples:

```text
/alert btc > 100000
```

```text
/alert eth < 3000
```

Manage alerts with:

```text
/myalerts
```

Remove an alert:

```text
/delalert <number>
```

The bot also supports periodic price updates for selected coins, including hourly updates with charts.

---

### 💼 Portfolio Tracking

Track cryptocurrency holdings and monitor potential profit and loss.

Add a position:

```text
/portfolio add btc 0.5 60000
```

View portfolio performance:

```text
/portfolio
```

Clear the portfolio:

```text
/portfolio clear
```

The portfolio feature is designed to provide a convenient overview of holdings and estimated P&L directly inside Telegram.

---

### 🔥 Binance Alpha & Market Discovery

The bot includes features for exploring Binance Alpha-related assets and market movements.

Available functionality includes:

* Binance Alpha token listings
* Trending Alpha assets
* Global market movers
* Market scanning
* Binance-related announcements

Inline queries can also be used for quick Alpha-related searches.

---

### 😨 Fear & Greed / Sentiment

Check overall cryptocurrency market sentiment using the Fear & Greed Index.

Example:

```text
/sentiment
```

This provides a quick way to understand whether the broader market is currently leaning toward fear or greed.

---

### 📰 Crypto News

Retrieve market-related news and headlines for supported assets.

Example:

```text
/news btc
```

This allows users to combine price information with current market news from within Telegram.

---

### ⛽ Gas Prices

Check supported blockchain network gas information.

Example:

```text
/gas
```

Useful for users who want a quick overview of network transaction costs.

---

### 🚀 Binance Launchpool Alerts

Groups that add the bot can receive automatic notifications when new Binance Launchpool projects are detected.

The system is designed to:

* Track groups where the bot is active
* Send Launchpool announcements
* Avoid duplicate announcements
* Persist previously announced project IDs
* Continue tracking across bot restarts

This feature is intended to provide groups with timely Launchpool notifications without requiring manual setup.

---

## 🔎 Telegram Inline Mode

One of the bot's most convenient features is Telegram Inline Mode.

Users can type the bot's username directly into any Telegram chat:

```text
@cryptoinfobd_bot btc
```

No need to open the bot separately.

Supported inline queries include examples such as:

```text
btc
5 eth
btc vs eth
top
gainers
losers
alpha
alpha hot
sentiment
globalalpha
binanceevent
leaderboard
users
offers
```

The result can then be selected and sent directly into the current conversation.

This makes the bot particularly useful in:

* Telegram groups
* Private chats
* Community discussions
* Crypto communities
* Trading discussions

The bot's help system explicitly supports inline price lookups, comparisons, market snapshots, gainers/losers, Alpha data, sentiment, and other information.

---

## 🧠 Performance & Reliability

The bot uses several techniques to improve responsiveness and API reliability.
---

## 👥 Group Features

CryptoInfoBD can be added to Telegram groups and provides group-oriented functionality.

The bot maintains lightweight group activity information for features such as:

* Group activity rankings
* Launchpool notifications
* Group statistics

The `/leaderboard` feature can show active groups based on bot usage.

The bot also handles Telegram group migration events to prevent duplicate group registrations when a basic group becomes a supergroup.

---

## ⭐ Telegram Stars Support

Users can optionally support the project using Telegram Stars.

```text
/donate
```

The bot uses Telegram's native Stars payment system and confirms successful payments directly inside Telegram.

Donations are entirely optional and help support the infrastructure and API costs required to operate the bot.

---

## 📢 Channel Integration

The bot can be connected to an official Telegram channel for:

* Market updates
* Bot announcements
* Price cards
* News
* Launchpool-related updates

Users may receive occasional, non-forced invitations to join the official channel.

Administrators can also publish supported content directly to the channel using bot administration tools.

---

## 📋 User Command Overview

| Command               | Description                                  |
| --------------------- | -------------------------------------------- |
| `/start`              | Open the interactive help menu               |
| `/top`                | View top cryptocurrencies                    |
| `/gainers`            | View top 24-hour gainers                     |
| `/losers`             | View top 24-hour losers                      |
| `/cbrates`            | View supported currency rates                |
| `/alpha`              | Explore Binance Alpha assets                 |
| `/gas`                | View supported gas prices                    |
| `/profit`             | Profit-related calculations                  |
| `/news`               | View market news                             |
| `/risk`               | Market risk information                      |
| `/sentiment`          | Fear & Greed sentiment                       |
| `/trend`              | Technical trend analysis                     |
| `/binanceevent`       | View Binance-related events                  |
| `/leaderboard`        | View active group rankings                   |
| `/globalalpha`        | View major market movers                     |
| `/scanner`            | Scan the market                              |
| `/quote`              | Query crypto, forex, indices, or commodities |
| `/alert`              | Create a price alert                         |
| `/myalerts`           | View active alerts                           |
| `/delalert`           | Delete an alert                              |
| `/enable_price_alert` | Configure periodic price updates             |
| `/watch`              | Add coins to a watchlist                     |
| `/unwatch`            | Remove coins from a watchlist                |
| `/mywatchlist`        | View your watchlist                          |
| `/portfolio`          | Manage your portfolio                        |
| `/convert`            | Convert between supported assets             |
| `/offers`             | View available sponsored offers              |
| `/donate`             | Support the bot with Telegram Stars          |

The bot also accepts simple text queries such as:

```text
btc
eth
5 btc
5000 bdt btc
btc vs eth
```

The command and text-query architecture is designed to make basic market lookups possible without requiring users to memorize complex syntax.

---

### External Data Sources

The bot integrates with or uses data from services including:

* Binance
* CoinGecko
* FreeCryptoAPI
* Exchange-rate APIs
* Yahoo Finance market data endpoints
* mempool.space
* Additional market/news data providers

Availability and coverage may vary depending on the external service and its API policies.

---

## 🔐 Privacy & Security

The bot is designed as a private service and its source code is **not open source**.

This GitHub repository exists only to provide public documentation and information about the project.

The private source code, infrastructure configuration, credentials, and internal administration logic are not included in this repository.

### Important

Market information can change rapidly. Data may occasionally be delayed, unavailable, or incorrect due to external API failures or provider limitations.

**CryptoInfoBD is an informational tool and does not provide financial, investment, or trading advice.**

Always conduct your own research before making financial decisions.

---

## 📌 Project Status

**Status:** Active

CryptoInfoBD is continuously improved with new market tools, data sources, reliability improvements, and Telegram features.

The project may evolve over time, and individual commands or integrations may be added, changed, or removed.

---

## 🤖 Try the Bot

Start using CryptoInfoBD on Telegram:

**[@cryptoinfobd_bot](https://t.me/cryptoinfobd_bot)**

---

## 📢 Official Channel

Follow the project's Telegram channel for:

* Crypto market updates
* Important announcements
* Bot updates
* Market alerts
* Launchpool notifications

**[@CryptoInfosBD](https://t.me/CryptoInfosBD)**

---

## ⭐ Support

If you find CryptoInfoBD useful, you can support the project directly through Telegram Stars using:

```text
/donate
```

Your support helps cover the ongoing costs of:

* API services
* Server infrastructure
* Development
* Maintenance
* Monitoring

Thank you for using CryptoInfoBD. ❤️

---

## 📄 License

The **CryptoInfoBD bot source code is proprietary and private**.

This repository contains documentation about the bot and does not grant permission to:

* Copy the bot's private source code
* Reproduce the service without authorization
* Redistribute private implementation details
* Use the project's private credentials or infrastructure

The README itself may be reused or referenced according to the license terms specified by the repository owner.

---

<p align="center">
  <b>CryptoInfoBD</b><br>
  Real-time crypto & financial market information, directly in Telegram.
</p>
