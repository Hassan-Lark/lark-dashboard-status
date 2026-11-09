# Lark Dashboard - Nightly Sync Report

- **Run (local / ET):** 2026-11-08 20:00
- **Run (New York):** 2026-11-08 20:00 EST
- **Outcome:** SUCCESS - refreshed and deployed

## Summary

| Step | Result |
|---|---|
| Ticker universe | 18 symbols |
| Historical prices | 1 rows added - latest 2026-11-08 - 1 ticker(s) with no data: SPN.V |
| Live prices | n/a symbols refreshed |
| FX (CAD/USD) | 1 CAD = 0.7086 USD (2026-11-06) |
| Cache stamp | PRELOAD_TS = Nov 8, 2026 8:00 PM |
| Deploy | (dashboard deployed) |

_Note: fund NAVs and new transactions are entered manually and are not part of this automated nightly sync - it refreshes market prices, FX, and redeploys the current dashboard._

## Errors / notes

- SPN.V: Yahoo reports no price data (possibly delisted / symbol change) - non-fatal, last known price kept
- Step failure: update-portfolio (see raw log)
