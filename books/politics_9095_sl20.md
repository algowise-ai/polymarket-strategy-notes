# `politics_9095_sl20`

**Label:** Politics 90–95c SL20  
**Status:** live  
**Category:** politics  
**Config:** `config/paper_politics_9095_sl20.json`  
**Launchd:** `com.algowise.polymarket.paper-politics-9095-sl20`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $9,864.26 / $-135.74  
**Started (UTC series):** 2026-10-09T13:20:54Z  

## Summary

2026-10-09 user-approved PAPER ledger politics_9095_sl20. PAPER ONLY. NEW parallel book — does NOT change politics_9099 HOLD. Politics category (grid_scan.classify). Enter the FIRST time the 30-min collector best ask is in [0.90, 0.95] with best_ask-best_bid <= 0.03. First touch = previous snapshot was not a valid in-range print, AND no valid in-range print in the prior 7 days (scan 'any' window). One position per market, hold to resolution UNLESS best bid <= entry-0.20 (SL20c); stop fills at th

## Rule (one-line)

ask [0.9-0.95]; SL±0.2

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `politics_9095_sl20` |
| engine | `politics_first` |
| entry ask | 0.9 – 0.95 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | politics | any | 90-95c | all | SL20c |
| ROI train/test | 0.021 / 0.055 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

