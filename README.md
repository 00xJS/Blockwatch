# Project: Blockwatch

A live Bitcoin on-chain dashboard. Surfaces real-time market data, network health, and sentiment in a single page that auto-refreshes every 60 seconds:

- **Market** — price, market cap, 24h volume, ATH, circulating supply (CoinGecko)
- **Bitcoin vs. US Debt** — total US national debt (TreasuryDirect), the BTC price required to cover it, and multiples of current price and ATH (computed)
- **Network** — block height, mempool size, recommended fees, hash rate, difficulty adjustment ETA, mempool fee histogram (mempool.space)
- **Sentiment** — Fear &amp; Greed gauge with 30-day history (alternative.me)
- **History** — 90-day price chart

All data sources are keyless and CORS-friendly — no backend, no API keys, pure client-side JavaScript. See [`info.html`](info.html) for plain-English explanations of every metric on the dashboard.
