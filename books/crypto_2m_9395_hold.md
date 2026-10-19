# `crypto_2m_9395_hold`

**Label:** Crypto 93–95c 2m  
**Status:** live  
**Category:** crypto_short  
**Config:** `config/paper_crypto_2m_9395_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-crypto-2m-9395`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $9,896.93 / $-103.07  
**Started (UTC series):** 2026-10-10T17:25:07Z  

## Summary

2026-10-11 user-approved PAPER ledger crypto_2m_9395_hold. PAPER ONLY. Separate from crypto_9395_hold (do not change that ledger). Universe: crypto_short (intraday Up/Down via fast_snapshots cls=crypto_short). Entry: real ask in [0.93, 0.95], spread <= 0.03, when secs_to_end in [120, 290] (scan offset 2m=120s + STALE 170s). Price-at-window (not global first-touch). Hold to resolution; no stop. Same market MAY also be open in crypto_9395_hold (allowed; correlated). Fee = shares*rate*p*(1-p), rate

## Rule (one-line)

ask [0.93-0.95]; secs_to_end [120-290]; hold-to-res

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `crypto_2m_9395_hold` |
| engine | `crypto_first` |
| entry ask | 0.93 – 0.95 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | crypto_short | 2m | 93-95c | all | hold |
| ROI train/test | 0.025 / 0.041 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

