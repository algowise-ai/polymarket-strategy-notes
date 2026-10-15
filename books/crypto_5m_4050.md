# `crypto_5m_4050`

**Label:** Crypto 5m 40–50c (old $10k)  
**Status:** paused  
**Category:** crypto_short  
**Config:** `config/paper_crypto_5m.json`  
**Launchd:** `com.algowise.polymarket.paper-crypto-5m`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $1,444.13 / $-8,555.87  
**Started (UTC series):** 2026-10-08T02:23:53Z  

## Summary

2026-10-08 user-approved PAPER ledger crypto_5m_4050 (bin/paper_crypto_5m.py, launchd com.algowise.polymarket.paper-crypto-5m every 60s). PAPER ONLY: no orders, no wallet, no login, no keys, no AI. Source = the 2-min fast collector's order books (fast_snapshots, cls crypto_short). Every NEW fast run is processed once, in time order (exits first, then entries).

## Rule (one-line)

ask [0.4-0.5]; secs_to_end [240-360]; SL±0.05

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `crypto_5m_4050` |
| engine | `—` |
| entry ask | 0.4 – 0.5 |
| max spread | — |
| new_entries | `False` |
| backtest cell | crypto_short | 5m | 40-50c | SL5c 1:1 |
| ROI train/test | 0.068 / 0.102 |

## Action

- **Current:** PAUSED 2026-10-09 12:38 HKT (user-approved): no NEW crypto 5m 40-50c positions; open ones 
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

