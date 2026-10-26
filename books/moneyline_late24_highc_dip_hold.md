# `moneyline_late24_highc_dip_hold`

**Label:** Moneyline late24 highc dip  
**Status:** live  
**Category:** sportskind:1x2_moneyline  
**Config:** `config/paper_moneyline_late24_highc_dip_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-moneyline-late24-highc-dip`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $11,140.56 / $1,140.56  
**Started (UTC series):** 2026-10-14T20:15:24Z  

## Summary

2026-10-15 user-approved PAPER ledger moneyline_late24_highc_dip_hold (Hermes 183 + task185 PASS). PAPER ONLY: no orders, no wallet, no keys, no AI. Book-confirmed entry = collector best ask in [0.60, 0.82] with best_ask-best_bid <= 0.03. Universe: classify() tag sportskind:1x2_moneyline. Side YES (outcome_index 0). Window: end_date within 24h. Filter: mean_reversion — YES mid fell >= 0.02 over 1h lookback (price_history else price_snapshots mid). Hold to resolution; no stop, no take-profit. Fee

## Rule (one-line)

sportskind:1x2_moneyline; ask [0.6-0.82]; MR dip>=0.02/1h; window 24h; hold-to-res; side=yes

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `moneyline_late24_highc_dip_hold` |
| engine | `favourite_dip` |
| entry ask | 0.6 – 0.82 |
| max spread | 0.03 |
| new_entries | `True` |
| backtest cell | sportskind:1x2_moneyline | yes | 0.60-0.82 | 24h | mean_reversion 0.02/1h | hold |
| ROI train/test | 0.092 / 0.2 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

