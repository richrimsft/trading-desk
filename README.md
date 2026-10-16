# trading-desk (private backup)

Trading Desk notes and scripts. No API keys or secrets are stored here. Kraken credentials come from the env vars `KRAKEN_API_KEY` and `KRAKEN_API_SECRET`.

- `pumpfun/`: autonomous pump.fun trading. `trade-log.md` is the main log. The `scout-*.md` and `scan-*.md` files are coin scouting reports, and `scan*.py` and `expand*.py` are the scanner scripts.
- `markets/`: Kraken spot desk. `kraken.py` is the API client, `RULES.md` holds the trading rules, and `trades.log` and `snapshots.log` record trades and balance snapshots.
- `audit/`: backtests of the Kraken and Polymarket strategies, with specs, results and the verdict (no edge found).
- `polymarket-sim/`: Polymarket paper-trading sim (`sim.py`, `run.sh`). `copy/` holds the copy-trading sim, which started Oct 15, 2026.

Raw JSON dumps and large data files over 1 MB are left out on purpose.

Note: to keep the backup compact, `pumpfun/` packs the original files into bundles. `scout-reports.md` has every scout and scan report, `scripts-bundle.py.txt` has every scanner script, and `lists-bundle.txt` has the mint and coin lists. Each original file starts with a `# ===== filename =====` header.
