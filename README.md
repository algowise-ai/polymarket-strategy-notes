# Polymarket strategy notes (Keep Record)

Paper-only strategy documentation so Alan and friends (e.g. Tai Lai / emillaii) can **learn from written MD**, not only chat.

## How to read

1. **[`REGISTRY.md`](REGISTRY.md)** — all paper/live sleeves: id, status, bankroll, stake, launchd, rule, last Action.
2. **[`weekly/`](weekly/)** — dated digests (`YYYY-MM-DD.md`): Summary + Action log for the week.
3. **[`books/`](books/)** — short per-strategy pages (Summary / Keep Record / Action).

## Weekly cadence

Roughly **once a week** (or after any material Action: new sleeve, pause, resume, bankroll change):

```bash
cd "/Users/alan/Grok Bot/Polymarket"
bin/strategy_notes_refresh.sh
cd docs/strategies
git add -A
git status
git commit -m "weekly strategy notes $(date +%Y-%m-%d)"
# optional: git push  (if remote polymarket-strategy-notes is set)
```

The refresh script rebuilds `REGISTRY.md` and creates/updates `weekly/YYYY-MM-DD.md` from:

- `config/paper_*.json` + `config/football_ev.json`
- `out/dashboard_data.json` (run `bin/dashboard_refresh.sh` first if stale)
- launchd paper labels

## Conventions (Tai Lai request)

| section | meaning |
|--------|---------|
| **Keep Record** | Durable facts: ledger, bankroll, stake, launchd, entry band, freeze notes |
| **Summary** | What the strategy does in plain language |
| **Action** | What we did (launch / pause / resume / change) and when |

## Safety

- Phase-1 **PAPER ONLY** — no wallets, no live orders, no API keys in these MD files.
- This folder is its **own git repo** (not the whole Polymarket tree) so secrets under `config/secrets/` never get committed here.
- Public push is optional; local commit is the source of truth on Mac Mini.

## Local dashboard

`http://127.0.0.1:8765/dashboard.html` — refresh equity before weekly notes if needed.
