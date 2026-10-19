# `crypto_9395_hold`

**Label:** Crypto 93–95c (any)  
**Status:** live  
**Category:** crypto_short  
**Config:** `config/paper_crypto_9395_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-crypto-9395`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $10,500.35 / $500.35  
**Started (UTC series):** 2026-10-08T07:27:25Z  

## Summary

2026-10-08 user-approved PAPER ledger crypto_9395_hold. PAPER ONLY. Same crypto_short definition as bin/paper_crypto_5m.py (Up or Down with a time-of-day ET; not daily). Entry is the FIRST fast-collector snapshot whose real ask is in [0.93, 0.95] and best_ask-best_bid <= 0.03, any time before close. A token that already printed that band on an earlier fast row is not entered (not the first touch). Hold to resolution: no stop, no take-profit. The same market MAY also be open in crypto_5m_4050 (di

## Rule (one-line)

ask [0.93-0.95]; hold-to-res

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `crypto_9395_hold` |
| engine | `crypto_first` |
| entry ask | 0.93 – 0.95 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | crypto_short | any | 93-95c | all | hold |
| ROI train/test | 0.023 / 0.021 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

