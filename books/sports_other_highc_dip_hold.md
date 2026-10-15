# `sports_other_highc_dip_hold`

**Label:** Sports other highc dip  
**Status:** live  
**Category:** sports:other  
**Config:** `config/paper_sports_other_highc_dip_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-sports-other-highc-dip`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $10,183.40 / $183.40  
**Started (UTC series):** 2026-10-12T04:30:48Z  

## Summary

2026-10-12 user-approved PAPER ledger sports_other_highc_dip_hold (Hermes 160 PASS). PAPER ONLY: no orders, no wallet, no keys, no AI. Book-confirmed entry = collector best ask in [0.62, 0.84] with best_ask-best_bid <= 0.03. Universe: classify() tag sports:other (deepest non-listed-league bucket). Side YES (outcome_index 0). Window: end_date within 24h. Filter: mean_reversion — YES mid fell >= 0.05 over 6h lookback (price_history else price_snapshots mid). Hold to resolution; no stop, no take-pr

## Rule (one-line)

sports:other; ask [0.62-0.84]; MR dip>=0.05/6h; window 24h; hold-to-res; side=yes

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `sports_other_highc_dip_hold` |
| engine | `favourite_dip` |
| entry ask | 0.62 – 0.84 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | sports:other | yes | 0.62-0.84 | 24h | mean_reversion 0.05/6h | hold |
| ROI train/test | 0.195 / 0.1 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

