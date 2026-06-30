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
- policy audit section shows the fixed utility objective, live signal ledger
  summary, BTC/ETH asset gates, distribution weak spots, and refresh watchdog;
- prediction history is published as `history.json`;
- machine-readable governance artifacts are published under `reports/` as
  `policy_audit.json` and `robust_evaluation.json`;
- no user dollar amounts are published.

Refresh cadence:

- 06:30 ET live intraday snapshot;
- 09:30-16:00 ET live intraday snapshots every 30 minutes;
- 20:30 ET close snapshot, which writes the historical close record.

Research / educational only. Not investment advice.
