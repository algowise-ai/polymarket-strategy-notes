# `totals_highc_dip_hold`

**Label:** Totals highc dip  
**Status:** live  
**Category:** sportskind:totals  
**Config:** `config/paper_totals_highc_dip_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-totals-highc-dip`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $10,019.33 / $19.33  
**Started (UTC series):** 2026-10-13T13:33:58Z  

## Summary

2026-10-13 proposed PAPER ledger totals_highc_dip_hold (Hermes 160/161 PASS, re-confirmed Hermes 166). PAPER ONLY: no orders, no wallet, no keys, no AI. Book-confirmed entry = collector best ask in [0.62, 0.84] with best_ask-best_bid <= 0.03. Universe: classify() tag sportskind:totals. Side YES (outcome_index 0). Window: end_date within 24h. Filter: mean_reversion — YES mid fell >= 0.03 over 6h lookback (price_history else price_snapshots mid). Hold to resolution; no stop, no take-profit. Fee = 

## Rule (one-line)

sportskind:totals; ask [0.62-0.84]; MR dip>=0.03/6h; window 24h; hold-to-res; side=yes

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `totals_highc_dip_hold` |
| engine | `favourite_dip` |
| entry ask | 0.62 – 0.84 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | sportskind:totals | yes | 0.62-0.84 | 24h | mean_reversion 0.03/6h | hold |
| ROI train/test | 0.125 / 0.127 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

