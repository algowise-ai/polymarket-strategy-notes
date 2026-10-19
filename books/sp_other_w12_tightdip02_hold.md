# `sp_other_w12_tightdip02_hold`

**Label:** sp_other_w12_tightdip02_hold  
**Status:** live  
**Category:** sports:other  
**Config:** `config/paper_sp_other_w12_tightdip02_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-sp-other-w12-tightdip02`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** — / —  
**Started (UTC series):** —  

## Summary

2026-10-16 user-approved PAPER ledger sp_other_w12_tightdip02_hold (Hermes task186 P2 / task197 YES #1; noon widget open_both). PAPER ONLY: no orders, no wallet, no keys, no AI. Book-confirmed entry = collector best ask in [0.60, 0.82] with best_ask-best_bid <= 0.03. Universe: classify() tag sports:other. Side YES (outcome_index 0). Window: end_date within 12h. Filter: mean_reversion — YES mid fell >= 0.02 over 1h lookback. Hold to resolution; no stop, no take-profit. Fee = shares*rate*p*(1-p), 

## Rule (one-line)

sports:other; ask [0.6-0.82]; MR dip>=0.02/1h; window 12h; hold-to-res; side=yes

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `sp_other_w12_tightdip02_hold` |
| engine | `favourite_dip` |
| entry ask | 0.6 – 0.82 |
| max spread | 0.03 |
| new_entries | `True` |
| backtest cell | sports:other | yes | 0.60-0.82 | 12h | mean_reversion 0.02/1h | hold |
| ROI train/test | 0.024 / 0.084 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

