# `crypto_5m_4050_fade_100k`

**Label:** Crypto 5m 40–50c FADE $100k  
**Status:** live  
**Category:** crypto_short  
**Config:** `config/paper_crypto_5m_4050_fade_100k.json`  
**Launchd:** `com.algowise.polymarket.paper-crypto-5m-4050-fade-100k`  
**Bankroll / stake:** $100,000.00 / $100.00  
**Equity (all) / PnL:** $68,194.34 / $-31,805.66  
**Started (UTC series):** 2026-10-13T05:28:20Z  

## Summary

2026-10-13 user-approved PAPER ledger crypto_5m_4050_fade_100k. Fresh Phase-1 $100k FADE/mirror book: when original 40-50c signal fires, buy other_side_ask (binary reverse). Same timing window [240,360]s, SL/TP ±0.05 on fade fill. Independent ledger. Mini reverse-sim said fade still −EV after fees; user explicitly overrides and wants paper anyway. PAPER ONLY. Fixed stake only — NO Martingale, NO hedge.

## Rule (one-line)

ask [0.4-0.5]; FADE other_side; secs_to_end [240-360]; SL±0.05

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `crypto_5m_4050_fade_100k` |
| engine | `—` |
| entry ask | 0.4 – 0.5 |
| max spread | — |
| new_entries | `True` |
| backtest cell | crypto_short | 5m | FADE other_side_ask of 40-50c signal | SL5c 1:1 | $100k |
| ROI train/test | None / None |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

