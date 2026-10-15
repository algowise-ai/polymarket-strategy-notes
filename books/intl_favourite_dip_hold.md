# `intl_favourite_dip_hold`

**Label:** Intl favourite dip  
**Status:** live  
**Category:** sports:international  
**Config:** `config/paper_intl_favourite_dip_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-intl-favourite-dip`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $10,000.00 / $0.00  
**Started (UTC series):** 2026-10-12T02:08:39Z  

## Summary

2026-10-12 user-approved PAPER ledger intl_favourite_dip_hold (Hermes 157 PASS). PAPER ONLY: no orders, no wallet, no keys, no AI. Book-confirmed entry = collector best ask in [0.62, 0.90] with best_ask-best_bid <= 0.03. Universe: classify() tag sports:international (same as grid_scan / task-157 harness — includes national-team football and any market the classifier tags international). Side YES (outcome_index 0). Window: end_date within 48h. Filter: mean_reversion — YES mid fell >= 0.06 over 6h

## Rule (one-line)

sports:international; ask [0.62-0.9]; MR dip>=0.06/6h; window 48h; hold-to-res; side=yes

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `intl_favourite_dip_hold` |
| engine | `favourite_dip` |
| entry ask | 0.62 – 0.9 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | sports:international | yes | 0.62-0.90 | 48h | mean_reversion 0.06/6h | hold |
| ROI train/test | 0.214 / 0.047 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

