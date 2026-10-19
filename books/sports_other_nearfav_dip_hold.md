# `sports_other_nearfav_dip_hold`

**Label:** Sports other nearfav dip  
**Status:** live  
**Category:** sports:other  
**Config:** `config/paper_sports_other_nearfav_dip_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-sports-other-nearfav-dip`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $10,132.04 / $132.04  
**Started (UTC series):** 2026-10-14T20:15:25Z  

## Summary

2026-10-15 user-approved PAPER ledger sports_other_nearfav_dip_hold (task185 MAYBE/REVIEW). PAPER ONLY: no orders, no wallet, no keys, no AI. Book-confirmed entry = collector best ask in [0.70, 0.90] with best_ask-best_bid <= 0.03. Universe: classify() tag sports:other. Side YES (outcome_index 0). Window: end_date within 48h. Filter: mean_reversion — YES mid fell >= 0.03 over 6h lookback. Hold to resolution; no stop, no take-profit. Fee = shares*rate*p*(1-p), rate = markets.fee_rate else 0.03. S

## Rule (one-line)

sports:other; ask [0.7-0.9]; MR dip>=0.03/6h; window 48h; hold-to-res; side=yes

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `sports_other_nearfav_dip_hold` |
| engine | `favourite_dip` |
| entry ask | 0.7 – 0.9 |
| max spread | 0.03 |
| new_entries | `True` |
| backtest cell | sports:other | yes | 0.70-0.90 | 48h | mean_reversion 0.03/6h | hold |
| ROI train/test | 0.025 / 0.029 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

