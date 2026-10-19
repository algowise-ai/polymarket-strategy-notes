# `politics_9099`

**Label:** Politics 90–99c HOLD  
**Status:** live  
**Category:** politics  
**Config:** `config/paper_politics_9099.json`  
**Launchd:** `com.algowise.polymarket.paper-politics-9099`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $9,914.20 / $-85.80  
**Started (UTC series):** 2026-10-08T07:27:25Z  

## Summary

2026-10-08 user-approved PAPER ledger politics_9099. PAPER ONLY. Politics category (grid_scan.classify, same as the scan). Enter the FIRST time the 30-min collector best ask is in [0.90, 0.99] with best_ask-best_bid <= 0.03. First touch = previous snapshot was not a valid in-range print, AND no valid in-range print in the prior 7 days (scan 'any' window). One position per market, hold to resolution. EXIT: HOLD, no stop. The stronger real-book cell was politics | any | 90-99c | all | SL20c (n 213

## Rule (one-line)

ask [0.9-0.99]; hold-to-res

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `politics_9099` |
| engine | `politics_first` |
| entry ask | 0.9 – 0.99 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | politics | any | 90-99c | all | hold |
| ROI train/test | None / None |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

