# Codex Crypto Cycle Dashboard

A public dashboard for the Codex BTC / ETH cycle model.

**Live:** https://attm-agenticcoding.github.io/crypto-cycle-dashboard-codex/

The site is generated from:

`/Users/block/agentic-coding/Claude/crypto-cycle-detection-codex/CryptoCycleDetection/dashboard.py`

Current display contract:

- first section shows calibrated future-low price distribution and downside
  odds;
- action sizing uses the raw structural posterior, with deployment policy
  layers for reserve, catch-up, redeployment, and fast-crash overlay;
- accumulation regimes show historic accumulation deployment charts;
- distribution-side regimes show Codex top/distribution history charts;
- prediction history is published as `history.json`;
- no user dollar amounts are published.

Refresh cadence:

- 10:30 ET live intraday snapshot;
- 14:30 ET live intraday snapshot;
- 20:30 ET close snapshot, which writes the historical close record.

Research / educational only. Not investment advice.
