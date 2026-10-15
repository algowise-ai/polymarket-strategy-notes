# `sp_other_w72_highc_dip_hold`

**Label:** Sports other w72 highc dip  
**Status:** live  
**Category:** sports:other  
**Config:** `config/paper_sp_other_w72_highc_dip_hold.json`  
**Launchd:** `com.algowise.polymarket.paper-sp-other-w72-highc-dip`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $10,000.00 / $0.00  
**Started (UTC series):** 2026-10-15T04:54:13Z  

## Summary

2026-10-15 AI-Manager-approved PAPER ledger sp_other_w72_highc_dip_hold (Hermes task186 V3 PASS #1 / P1). PAPER ONLY: no orders, no wallet, no keys, no AI. Book-confirmed entry = collector best ask in [0.62, 0.84] with best_ask-best_bid <= 0.03. Universe: classify() tag sports:other. Side YES (outcome_index 0). Window: end_date within 72h. Filter: mean_reversion — YES mid fell >= 0.03 over 6h lookback. Hold to resolution; no stop, no take-profit. Fee = shares*rate*p*(1-p), rate = markets.fee_rat

## Rule (one-line)

sports:other; ask [0.62-0.84]; MR dip>=0.03/6h; window 72h; hold-to-res; side=yes

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `sp_other_w72_highc_dip_hold` |
| engine | `favourite_dip` |
| entry ask | 0.62 – 0.84 |
| max spread | 0.03 |
| new_entries | `True` |
| backtest cell | sports:other | yes | 0.62-0.84 | 72h | mean_reversion 0.03/6h | hold |
| ROI train/test | 0.104 / 0.075 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

