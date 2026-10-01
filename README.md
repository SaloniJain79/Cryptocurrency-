# 🪙 Cryptocurrency Market — Live Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-2563eb)
![API](https://img.shields.io/badge/Data-CoinGecko%20API-16a34a)
![Refresh](https://img.shields.io/badge/Refresh-Auto%20enabled-brightgreen)
![Pages](https://img.shields.io/badge/Pages-4-blueviolet)

A **live, auto-refreshing** Power BI dashboard tracking the top **36 cryptocurrencies** — prices, market cap, volume, dominance and 24h movement — powered by the **CoinGecko API**.

> 🟢 **LIVE**  Powered by CoinGecko API  Auto-refresh enabled  Last update `25-08-2026 12:26:20`

---

## 📑 Pages

### 📊 Page 1 — Market Live Overview
The whole market in one screen.
- 🎯 **KPI cards:** Total Market Cap ($3T)  Total Volume 24h  BTC Dominance (63.92%)  # of Coins (36)
- 📈 **Visuals:** ticker strip (live prices)  market dominance donut (Bitcoin 63.9%, Ethereum 11.9%, Tether 7.3%, BNB 3.8%, XRP 3.7%, Others 9.4%)  complete coin list table  BTC dominance gauge  market cap by coin (top 10)  24h price change (top 10 gainers)
- 💡 **Insight:** Bitcoin dominates at 63.9% of a $3T market; Stellar led gainers at +9.90%.

### 🫧 Page 2 — Market Cap vs Price
Valuation vs price relationships.
- 🎯 **Filters:** Coin name  Category
- 📈 **Visuals:** market cap vs price scatter (bubble = market cap)  market cap vs volume  Top 10 coins table (Bitcoin $1.62T → Stellar $0.01T)  ATH vs current price (distance from peak)  Key Influencers  AI market summary
- 💡 **Insight:** Bitcoin is 26,773% larger than the smallest coin in the set and accounts for ~65% of total market cap.

### 🔍 Page 3 — Coin Detail *(drill-through)*
Deep-dive on any single coin — right-click a coin → drill through.
- 🎯 **Metrics:** Price  Market Cap  24h Volume  24h Change  ATH  ATL
- 📈 **Visuals:** circulating / total / max supply  price change breakdown (1h vs 24h)  detailed coin table (24h high/low, ATH & ATL dates, last updated)  Back button
- 💡 **Insight:** Every coin's full profile — supply, volatility and historical extremes — in one click.

### 🤖 Page 4 — AI Insights
Machine-learning view of what moves the market.
- 📈 **Visuals:** Q&A (natural language)  Key Influencers (drivers of 24h price change)  decomposition tree (Coin → Market Cap → Symbol → Category)  AI market summary
- 💡 **Insight:** Rising 24h volume is the strongest signal for price increases — volume moves price more than market cap does.

---

## 🗄 Data & Model

| Item | Detail |
|---|---|
| 🔌 Source | CoinGecko API (live) |
| 🔄 Refresh | Automatic (scheduled) |
| 🪙 Coverage | Top 36 coins  prices, market cap, volume, supply, ATH/ATL, 1h & 24h change |
| 🧱 Model | Flat live table + category/segment mapping |

---

## ⚡ Features

🟢 Live API feed  ⏱️ auto-refresh with timestamp  🧭 drill-through coin detail  🎛️ synced slicers  🤖 Key Influencers, Q&A, decomposition tree, Smart Narrative  🎨 custom theme.

---

## 🚀 Run It

1. Open `cryptocurrency_live_dashboard.pbix` in **Power BI Desktop**.
2. Enter your **CoinGecko API key** when prompted, then **Refresh**.
3. Explore: hover the ticker, right-click any coin → **drill through** → Coin Detail, ask the Q&A a question.

> ⚠️ The Q&A visual retires in **Feb 2027** — plan to replace it with Copilot / natural-language visual for long-term use.

---

## 👤 Author

**Saloni Jain** — API integration, data modelling, DAX measures, report design and custom visual identity.
