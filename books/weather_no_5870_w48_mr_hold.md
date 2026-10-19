# `weather_no_5870_w48_mr_hold`

**Label:** weather_no_5870_w48_mr_hold  
**Status:** live  
**Category:** weather  
**Config:** `config/paper_weather_no_5870_w48_mr_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-weather-no-5870-w48-mr`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** — / —  
**Started (UTC series):** —  

## Summary

2026-10-17 user-approved PAPER ledger weather_no_5870_w48_mr_hold (Hermes task225 YES pm28_weather_no_5870_w48_mr03lb6_hold; noon ABC). PAPER ONLY: no orders, no wallet, no keys, no AI. Book-confirmed entry = collector best ask in [0.58, 0.70] with best_ask-best_bid <= 0.03. Universe: classify() tag weather. Side NO (outcome_index 1). Window: end_date within 48h. Filter: mean_reversion — NO mid fell >= 0.03 over 6h lookback. Hold to resolution; no stop, no take-profit. Fee = shares*rate*p*(1-p),

## Rule (one-line)

weather; ask [0.58-0.7]; MR dip>=0.03/6h; window 48h; hold-to-res; side=no

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `weather_no_5870_w48_mr_hold` |
| engine | `favourite_dip` |
| entry ask | 0.58 – 0.7 |
| max spread | 0.03 |
| new_entries | `True` |
| backtest cell | weather | no | 0.58-0.70 | 48h | mean_reversion 0.03/6h | hold |
| ROI train/test | 0.051 / 0.113 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

