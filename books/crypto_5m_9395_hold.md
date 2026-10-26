# `crypto_5m_9395_hold`

**Label:** Crypto 93–95c 5m  
**Status:** live  
**Category:** crypto_short  
**Config:** `config/paper_crypto_5m_9395_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-crypto-5m-9395`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $9,095.57 / $-904.43  
**Started (UTC series):** 2026-10-10T17:25:07Z  

## Summary

2026-10-11 user-approved PAPER ledger crypto_5m_9395_hold. PAPER ONLY. Separate from crypto_9395_hold and from crypto_5m_4050 (40-50c pause book). Universe: crypto_short 5-MINUTE Up/Down only (market_type=5m via question ET window). Entry: FIRST fast snapshot whose real ask is in [0.93, 0.95] and spread <= 0.03, any time before close. Hold to resolution; no stop. Overlap with crypto_9395_hold allowed (5m is a subset of any-timing). Fee = shares*rate*p*(1-p). Stake $100, bankroll $10k.

## Rule (one-line)

ask [0.93-0.95]; hold-to-res

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `crypto_5m_9395_hold` |
| engine | `crypto_first` |
| entry ask | 0.93 – 0.95 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | crypto_short | 5m-markets-only | 93-95c | all | hold |
| ROI train/test | None / None |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

