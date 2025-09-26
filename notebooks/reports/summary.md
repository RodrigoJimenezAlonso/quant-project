# Quant Project — Summary

- Generated at: **2025-09-26T10:25:51**
- Universe: **AAPL, MSFT, AMZN, GOOG**
- Date range: **2015-01-02 → 2024-12-30**
- Benchmark: **SPY**

## Baseline Strategy (net) — Metrics
- **CAGR**: -0.0588
- **Vol**: 0.2304
- **Sharpe**: -0.1474
- **Sortino**: -0.1920
- **MaxDD**: -0.5633

## Best Params from Train (Grid Search)
- fast=15, slow=20, mom=10, freq=W-FRI
- Grid table: `reports/grid_search_train.csv`

## Hedge & Leverage Comparison
- See: `reports/metrics_hedge_leverage.csv`

## Volatility Targeting
- Target annual vol: **10%**  | Window: **20d**  | Caps: **[0.25×, 2.0×]**