# `football_totals_2h_9799`

**Label:** Football totals 97–99c 2h  
**Status:** live  
**Category:** football / totals  
**Config:** `config/paper_football_totals_2h_9799.json`  
**Launchd:** `com.algowise.polymarket.paper-football-totals-2h`  
**Bankroll / stake:** $10,000.00 / $100.00  
**Equity (all) / PnL:** $9,956.83 / $-43.17  
**Started (UTC series):** 2026-10-09T13:20:54Z  

## Summary

2026-10-09 user-approved PAPER ledger football_totals_2h_9799. PAPER ONLY: no orders, no wallet, no keys, no AI. Real-fill rules match research/high_winrate: entry = collector best ask, only if best_ask-best_bid <= 0.03, fee = shares*rate*p*(1-p), rate = markets.fee_rate else 0.03. Hold to resolution. Universe: soccer (is_football) totals / O/U only (not 1X2, not exact score, not props). Book must be <= 2400s old (scan 2h SNAP_TOL). Entry clock is the snapshot time, 1.5-2.5h before game_start_ti

## Rule (one-line)

ask [0.97-0.99]; 1.5-2.5h pre-start; hold-to-res

## Keep Record

| field | value |
|---|---|
| mode | `PAPER_ONLY` |
| ledger | `football_totals_2h_9799` |
| engine | `football_totals` |
| entry ask | 0.97 – 0.99 |
| max spread | 0.03 |
| new_entries | `default/on` |
| backtest cell | football_totals | 2h | 97-99c | all | hold |
| ROI train/test | 0.014 / 0.021 |

## Action

- **Current:** entries on
- Log material pauses / resumes / bankroll changes here in weekly digests.

## Links

- [REGISTRY](../REGISTRY.md)
- Local dashboard: `http://127.0.0.1:8765/dashboard.html`

