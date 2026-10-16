

# ===== scan-1931.md =====

# Pump.fun scout scan — 19:31 ET Oct 15 2026

**Recommendation: HOLD** — no clean rotate target that clearly beats current holdings.

## Holdings snapshot (refreshed ~19:34 ET)

| Coin | MC | vs entry | Value | m5 | h1 | m5 b/s | h1 b/s | Liq |
|------|-----|----------|-------|----|----|--------|--------|-----|
| SPOOKY | $192,126 | -42.6% | $4.50 | -6.5% | +15.4% | 13/17 | 747/448 | $40,267 |
| SYCAMORE | $329,221 | +9.7% | $6.76 | +1.2% | +10.8% | 17/11 | 256/184 | $54,863 |
| NULLCASH | $35,893 | +48.3% | $5.97 | -4.5% | +76.5% | 43/45 | 256/156 | $0 |

- SOL left: ~0.00766 (~$0.81)
- **Est total portfolio: ~$18.04**

### Holdings notes
- **SPOOKY** (~$192k, −43%): softest. m5 sells>buys; h1 still +15% with buys>sells. Dump rule (~$180k + h1 neg + sells≥buys) **not met** — watch only.
- **SYCAMORE** (~$329k, +10%): stable, buys>sells on m5 and h1. Hold.
- **NULLCASH** (~$36k, +48%): still strong h1 (+76%). Liq shows $0 on Dex (bonding-curve / pumpfun pair). Past +20% — would rotate only into a *clean* replacement; none found this scan.

## Scan coverage

- Unique `*pump` mints collected (boosts/profiles/searches/pump.fun API): **219** (+ refresh batch)
- Mints with DexScreener pair data scored: **197**
- Sources: DexScreener token-boosts latest/top, token-profiles latest, searches (solana pump, pump.fun, meme solana, pumpswap, new pump, trending, etc.), frontend-api-v3.pump.fun coin lists

## Numeric passers (all filters)

| Symbol | Mint | MC | Liq | Age | h1 | m5 | h1 b/s | m5 b/s |
|--------|------|----|----|-----|----|----|--------|--------|
| APU | `E7eCZS2cq655qJ7uVx3dSHR2zK31kwNQsWS6P6Hpump` | $105k | $26.6k | 232.0h | +22.0% | +23.5% | 49/31 | 45/27 |
| EGO | `BbJJUTuGV2B7tJ99YeryiCBFLG39Hoc4RTzEwchtpump` | $71k | $29.6k | 270.8h | +65.3% | -5.8% | 348/229 | 0/4 |

## RugCheck results

### EGO (`BbJJUTuGV2B7tJ99YeryiCBFLG39Hoc4RTzEwchtpump`)
- Score: 1 | rugged: False
- Mint revoked: True | Freeze revoked: True
- Top10 ex-LP: **25.4%** (ideal <40%)
- graphInsidersDetected: **64** | insiderNetworks: 9
- totalHolders: 13949 | market liq (RC): $31,945

### APU (`E7eCZS2cq655qJ7uVx3dSHR2zK31kwNQsWS6P6Hpump`)
- Score: 1 | rugged: False
- Mint revoked: True | Freeze revoked: True
- Top10 ex-LP: **30.1%** (ideal <40%)
- graphInsidersDetected: **54** | insiderNetworks: 2
- totalHolders: 2311 | market liq (RC): $25,164

### Chinese (`Tm2iqbxYjKpW8xCMe6q1xUraNMNzcG5xMztAir3pump`)
- Score: 1 | rugged: False
- Mint revoked: True | Freeze revoked: True
- Top10 ex-LP: **25.6%** (ideal <40%)
- graphInsidersDetected: **7** | insiderNetworks: 1
- totalHolders: 4725 | market liq (RC): $43,176

## Qualitative verdict on passers

- **EGO**: numeric OK, but **64 graph insiders / 9 networks** — same “many flagged insiders” failure mode as prior rejects (e.g. DacityCoin ~63). Also m5 buys < sells. **Reject as rotate.**
- **APU**: numeric OK (m5 strong), top10 ex-LP ~30% OK, but **54 graph insiders** (one net size 47). **Reject as rotate.**
- **Chinese** (near): RugCheck cleaner (7 insiders, top10 ex-LP ~26%), but h1 only +14% (< +20% filter). Not a passer.

## Known rejects re-checked (not re-recommended)
- KWIF: botty (4k+ h1 buys) + known reject
- STREAM / DacityCoin / CRS / 250 / BACKED: still fail filters / known rejects
- Age<1h heat (XBAY, Motion, MCP): excluded by age rule

## Clear action recommendation

### **HOLD**

- Do **not** rotate NULLCASH → EGO/APU (insider-network risk; do not clearly beat NULLCASH’s own +76% h1 momentum).
- Do **not** dump SPOOKY yet (mc ~$192k > $180k line; h1 still positive; h1 buys>sells).
- Keep SYCAMORE.
- Any buy still needs a sell first (SOL dust only).

Scout only — no trades executed.

# ===== scan-1950.md =====

# Pump.fun scout — 19:50 ET Oct 15 2026 (aborted early; parent steer → HOLD)

**Recommendation: HOLD**

## SPOOKY dump
- At scout start (~19:50): mc ~$182–188k, h1 −33%, buys>sells → near dump gate, not triggered.
- Parent refresh: SPOOKY bounced ~$202k, m5 +9% → **dump gate NOT met**. **NO dump.**

## Numeric passers (this agent, 298 mints → 293 pairs; RugCheck not finished)
| Symbol | Mint | MC | Liq | Age | h1 | m5 | h1 b/s | m5 b/s | Notes |
|--------|------|----|-----|-----|----|----|--------|--------|-------|
| ACat | `266ZxiEW9Y2Lm33zNM7J2wnng5DJ7hHc7HQTXf2ipump` | $125k | $31.2k | 3.6h | +70% | +38% | 2199/1529 | m5 sells>buys; high txn — not clear upgrade |
| APP | `6MnQ921sqsShymdoqPv2RfhL5g2Hk2hoqPvgpDGcpump` | $88k | $22.7k | 254h | +44% | −0.2% | 11/6 | thin h1 flow — not clear upgrade |

Near: Macca h1 +14.9% (below +20% here). Parent: Macca h1 +21% only passer on their 107-mint pass — still not clear upgrade vs NULLCASH ripping.

## Action
**HOLD** — no rotate; do not dump SPOOKY; keep SYCAMORE/NULLCASH.

Artifacts: mints-1950.txt/json, pairs-1950.json, scored-1950.json, cands-1950.json, boosts/profiles/search/pf-*-1950.json, scan-1950.md


# ===== scan-1955.md =====

# Pump.fun scout — 19:55 ET Oct 15 2026

**Recommendation: HOLD**

No rotate. No dump. SOL fee buffer still thin (~0.0077) — any buy needs a sell first, and nothing clears the bar.

## SPOOKY dump gate
- Final refresh: mc **$204.3k**, h1 **−33.8%**, m5 **+7.4%**, h1 buys/sells **290/195**, m5 **18/11** (still buy-heavy).
- Gate needs: mc <$180k **AND** h1 neg **AND** (m5 or h1 sells≥buys).
- Result: mc<$180k=**False**, sells≥buys=**False** → **DUMP GATE NOT MET**. Near gate earlier (~$191k) but bounced.

## Holdings snapshot (~19:56–19:57 ET)
| Coin | Mint | MC | Liq | h1 | m5 | h1 b/s | m5 b/s | Notes |
|------|------|----|-----|----|----|--------|--------|-------|
| SPOOKY | `CZ3X9XUxSTc1hN9iGPteG3iKoXGC4q332bmWi4JBpump` | $204k | $41.7k | −33.8% | +7.4% | 290/195 | 18/11 | −~39% vs entry; bounce off dump zone |
| SYCAMORE | `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump` | $231k | $45.7k | −25.6% | −29.5% | 252/238 | 21/71 | Softening hard on m5 sells; still hold vs weak alts |
| NULLCASH | `31GYUbJW5vjF1o7VM5SGP9Emj5WDBHb1cdcR8BM6pump` | $39.8k | bonding | +79.6% | −0.3% | 356/224 | 32/19 | Let run — best book momentum |

Est. book still ~$17–19 (SOL~$105). Fee SOL ~0.0077.

## Numeric passers → RugCheck
392 unique *pump mints → 388 pairs scored → **2 numeric passers**.

| Symbol | Mint | MC | Liq | Age | h1 | h1 b/s | RugCheck | Clear upgrade? |
|--------|------|----|-----|-----|----|--------|----------|----------------|
| APP | `6MnQ921sqsShymdoqPv2RfhL5g2Hk2hoqPvgpDGcpump` | $89.5k | $23.0k | 254h | +46.6% | 13/6 | **REJECT** — 75 graph insiders; top10~46%; LP lock 0%; thin flow | No |
| ACat | `266ZxiEW9Y2Lm33zNM7J2wnng5DJ7hHc7HQTXf2ipump` | $119k | $30.6k | 3.7h | +34.6% | 2183/1742 | Clean (score1, 0 insiders, top10~18%) | **No** — high churn, already extended; not clearly better than SPOOKY bounce or NULLCASH run |

### Near miss
- **XBAY** `E8ZvySLWzHg2oDBPFyeDYzNzVdN7AA4zTC3tUYs9pump` — mc $135k, h1 +220%, age **0.90h** (<1h reject). Rug: 35 graph insiders. Do not chase.

## Rejects of note
- **APP**: numeric pass but **75 graph insiders** → reject (same class as APU/EGO/STREAM).
- **ACat**: rug-clean but fails “clearly beat SPOOKY/NULLCASH” bar (same conclusion as 19:50 scout).
- **XBAY**: age <1h + 35 insiders.
- Known-reject symbols from prior list not re-recommended.
- DIKSHIT near band but h1 only +10% and sells>buys.

## Action
**HOLD** all three. Do not dump SPOOKY (gate unmet; buy-heavy bounce). Do not rotate into APP/ACat/XBAY. Revisit if SPOOKY loses $180k with sells≥buys, or a cleaner ≥+20% h1 passer appears.

## Artifacts
`boosts-*-1955.json`, `profiles-1955.json`, `search-*-1955.json`, `pf-v3-*-1955.json`, `mints-1955.txt/json`, `pairs-1955.json`, `scored-1955.json`, `cands-1955.json`, `rc-sum/full-1955-*.json`, `hold-final-1955.json`, `scan-1955.md`



# ===== scan-2008.md =====

# Pump.fun position watch — 20:08 ET Oct 15 2026

**Recommendation: HOLD** (all three). No ROTATE. No DUMP.

Nothing in the scout clearly beats the current book on upside+safety. NULLCASH is ripping post-grad — let it run. SPOOKY and SYCAMORE are soft but dump gates are **not** met.

## Holdings (fresh DexScreener PumpSwap)

| Coin | Mcap | vs entry | ~USD | m5% | h1% | m5 buys/sells | h1 buys/sells | Liq | Action |
|------|------|----------|------|-----|-----|---------------|---------------|-----|--------|
| NULLCASH | $150,846 | +523% | $25.09 | 112 | 246 | 353/323 | 1120/858 | $32,322 | **HOLD** |
| SPOOKY | $192,208 | -43% | $4.51 | -4.3 | -19.84 | 9/4 | 227/159 | $40,335 | **HOLD** |
| SYCAMORE | $241,060 | -20% | $4.95 | 0.99 | -26.13 | 24/17 | 256/241 | $46,763 | **HOLD** |

- **NULLCASH** `31GYUbJW5vjF1o7VM5SGP9Emj5WDBHb1cdcR8BM6pump` — graduated PumpSwap; strong m5/h1 with buys>sells. Entry ~$24.2k → now ~$151k. Watch for post-migration dump but momentum still intact — **do not rotate out of this**.
- **SPOOKY** `CZ3X9XUxSTc1hN9iGPteG3iKoXGC4q332bmWi4JBpump` — dump gate: mcap <$180k **AND** h1 negative **AND** sells≥buys on m5/h1. Status: mcap $192k (still above), h1 -19.84% (neg), but **buys>sells** on m5 (9/4) and h1 (227/159). **Gate NOT triggered.**
- **SYCAMORE** `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump` — dump if breaks ~$200k with sells≥buys on h1. Status: mcap $241k, h1 buys/sells 256/241. **Gate NOT triggered.**

**Est. portfolio:** holdings $34.55 + SOL $0.81 ≈ **$35.36**  
SOL 0.007658134 @ $105.40 — **thin fee buffer; any buy needs a sell first.**

## Scout

- Mints scanned: **218** (Dex boosts latest/top, profiles, multi search, pump.fun v3 last_trade — v3 for-you 404; unauth sometimes 403)
- Tokens with Solana pairs: **176**
- Numeric passers (mc $50–450k, liq>$15k, age>1h, h1>+20%, buys>sells h1, non-botty, not known-bad): **0**
- Soft passers (h1≥15% same other filters): **0**
- Rotate targets: **0**

### Notable rejects
| Name | Why rejected |
|------|----------------|
| MOO / ALT / SpaceX | Fresh graduated, strong h1 but **botty** (age <1–2h, thousands of buys/h) |
| Motion `87SsFmfc...pump` | Age ~1h, mc~$85k, liq~$25k, h1 +131% — but buys_h1 ~5911 (**botty**); rugcheck score 1 |
| Macca `AKotzk1d...pump` | mc/liq/age OK, RugCheck score 1 — but h1 only mid-single digits; **does not beat NULLCASH upside** |
| FOMO / saluteface | Too young and/or mc under range / dumping m5 |
| STREAM / DacityCoin / TrumpCoin / CRS / Trump* / Dacity* | Known-bad repeats (concentration/insiders) — skipped |

## Clear call

**HOLD.** Do not dump SPOOKY or SYCAMORE yet (gates unmet). Do not rotate — no candidate clears filters and beats the book. Preserve NULLCASH. Re-check SPOOKY if mcap slips under $180k with sell pressure; SYCAMORE if under ~$200k with h1 sells≥buys.

As of: 2026-10-15 20:12:40 ET


# ===== scan-latest.md =====

# Pump.fun scout scan — 19:31 ET Oct 15 2026

**Recommendation: HOLD** — no clean rotate target that clearly beats current holdings.

## Holdings snapshot (refreshed ~19:34 ET)

| Coin | MC | vs entry | Value | m5 | h1 | m5 b/s | h1 b/s | Liq |
|------|-----|----------|-------|----|----|--------|--------|-----|
| SPOOKY | $192,126 | -42.6% | $4.50 | -6.5% | +15.4% | 13/17 | 747/448 | $40,267 |
| SYCAMORE | $329,221 | +9.7% | $6.76 | +1.2% | +10.8% | 17/11 | 256/184 | $54,863 |
| NULLCASH | $35,893 | +48.3% | $5.97 | -4.5% | +76.5% | 43/45 | 256/156 | $0 |

- SOL left: ~0.00766 (~$0.81)
- **Est total portfolio: ~$18.04**

### Holdings notes
- **SPOOKY** (~$192k, −43%): softest. m5 sells>buys; h1 still +15% with buys>sells. Dump rule (~$180k + h1 neg + sells≥buys) **not met** — watch only.
- **SYCAMORE** (~$329k, +10%): stable, buys>sells on m5 and h1. Hold.
- **NULLCASH** (~$36k, +48%): still strong h1 (+76%). Liq shows $0 on Dex (bonding-curve / pumpfun pair). Past +20% — would rotate only into a *clean* replacement; none found this scan.

## Scan coverage

- Unique `*pump` mints collected (boosts/profiles/searches/pump.fun API): **219** (+ refresh batch)
- Mints with DexScreener pair data scored: **197**
- Sources: DexScreener token-boosts latest/top, token-profiles latest, searches (solana pump, pump.fun, meme solana, pumpswap, new pump, trending, etc.), frontend-api-v3.pump.fun coin lists

## Numeric passers (all filters)

| Symbol | Mint | MC | Liq | Age | h1 | m5 | h1 b/s | m5 b/s |
|--------|------|----|----|-----|----|----|--------|--------|
| APU | `E7eCZS2cq655qJ7uVx3dSHR2zK31kwNQsWS6P6Hpump` | $105k | $26.6k | 232.0h | +22.0% | +23.5% | 49/31 | 45/27 |
| EGO | `BbJJUTuGV2B7tJ99YeryiCBFLG39Hoc4RTzEwchtpump` | $71k | $29.6k | 270.8h | +65.3% | -5.8% | 348/229 | 0/4 |

## RugCheck results

### EGO (`BbJJUTuGV2B7tJ99YeryiCBFLG39Hoc4RTzEwchtpump`)
- Score: 1 | rugged: False
- Mint revoked: True | Freeze revoked: True
- Top10 ex-LP: **25.4%** (ideal <40%)
- graphInsidersDetected: **64** | insiderNetworks: 9
- totalHolders: 13949 | market liq (RC): $31,945

### APU (`E7eCZS2cq655qJ7uVx3dSHR2zK31kwNQsWS6P6Hpump`)
- Score: 1 | rugged: False
- Mint revoked: True | Freeze revoked: True
- Top10 ex-LP: **30.1%** (ideal <40%)
- graphInsidersDetected: **54** | insiderNetworks: 2
- totalHolders: 2311 | market liq (RC): $25,164

### Chinese (`Tm2iqbxYjKpW8xCMe6q1xUraNMNzcG5xMztAir3pump`)
- Score: 1 | rugged: False
- Mint revoked: True | Freeze revoked: True
- Top10 ex-LP: **25.6%** (ideal <40%)
- graphInsidersDetected: **7** | insiderNetworks: 1
- totalHolders: 4725 | market liq (RC): $43,176

## Qualitative verdict on passers

- **EGO**: numeric OK, but **64 graph insiders / 9 networks** — same “many flagged insiders” failure mode as prior rejects (e.g. DacityCoin ~63). Also m5 buys < sells. **Reject as rotate.**
- **APU**: numeric OK (m5 strong), top10 ex-LP ~30% OK, but **54 graph insiders** (one net size 47). **Reject as rotate.**
- **Chinese** (near): RugCheck cleaner (7 insiders, top10 ex-LP ~26%), but h1 only +14% (< +20% filter). Not a passer.

## Known rejects re-checked (not re-recommended)
- KWIF: botty (4k+ h1 buys) + known reject
- STREAM / DacityCoin / CRS / 250 / BACKED: still fail filters / known rejects
- Age<1h heat (XBAY, Motion, MCP): excluded by age rule

## Clear action recommendation

### **HOLD**

- Do **not** rotate NULLCASH → EGO/APU (insider-network risk; do not clearly beat NULLCASH’s own +76% h1 momentum).
- Do **not** dump SPOOKY yet (mc ~$192k > $180k line; h1 still positive; h1 buys>sells).
- Keep SYCAMORE.
- Any buy still needs a sell first (SOL dust only).

Scout only — no trades executed.

# ===== scout-0000.md =====

# Scout 2026-10-16 00:00 ET

## Wallet
- SOL: **0.378250232** (RPC getBalance; lamports 378250232) @ ~$105.03 → ~$39.72
- Meme holdings: **none** (SYCAMORE/NULLCASH/SPOOKY Token-2022 ATAs uiAmount 0; all 11 T22 zero; SPL dust USDC 0.000006 only)

## Data refresh
- DexScreener: `boosts-latest-0000.json`, `boosts-top-0000.json`, `profiles-latest-0000.json` → `lists.txt` (3 lines)
- pump.fun: `pump-live-0000.json` OK (50); created/last-trade/mcap → Cloudflare challenge pages (skipped)
- `python3 scan.py` → `scan-0000.out` (**142 mints**, 81 vol/age rows)
- Filter dump: `interesting-0000.json`

## Filters
Prefer: mc $15k–450k, liq≥$15k or bonding w/ real buyers, age 0.5–3.5h, h1≥+20%, buys>sells h1, not botty (≪3k buys/h), no crowded copycat.

## Numeric passers → autopsy
| mint | symbol | result | why |
|------|--------|--------|-----|
| `hps4Xy4goXuV9zxdTAuF35tN58Gpks8Ho5zX529pump` | 123456 | **FAIL** | Prior reject; top10 ex-curve ~33.7%; creatorBalance 0 |
| `4XUmT22L7LN2e1us3bLHpPFKtkGUk9cAKQXEr3wXpump` | ETERNAL | **FAIL** | Prior; creatorBalance 0; insider transfer net 4 |
| `BEiJVDNjUYmgMEKeDuLTMqPRDVCW8Pgm5GuLk6Pxpump` | StayDown | **FAIL** | Age 6.5h past window; creator 0; top10 ~32% |

RugCheck raw: `autopsy-raw-hps4Xy4g.json`, `autopsy-raw-4XUmT22L.json`, `autopsy-raw-BEiJVDNj.json`

## Decision
**NO_TRADE** — stay in SOL. No clean autopsy passers.

## Kraken
Watch-only. No fresh `/workspace/markets` data this run; last snapshot (2026-10-15 09:50 ET) USD=$0.81 below min — no proposal.


# ===== scout-0004.md =====

# Scout 0004 — 2026-10-16 00:04 ET

## Wallet
- SOL: **0.378250232** (~$39.7 @ ~$105)
- SPL Token: dust USDC 0.000006 only
- Token-2022: 11 ATAs, **all zero** (no meme positions)
- Book: **all SOL** since SYCAMORE dump ~23:19 ET

## Scout
- Feeds: `boosts-latest-0004.json`, `boosts-top-0004.json`, `profiles-latest-0004.json`, `pump-live-0004.json` (OK), pf mcap/last/created OK; king-of-hill 404
- `lists.txt` → `scan.py` → **141 mints**, 77 vol/age rows → `scan-0004.out` / `cands.json`
- **Strict numeric passers: 0** (mc $15–450k, age 0.5–3.5h, h1≥+20%, buys>sells, not botty, not prior)

## Near / priors (not rebuy)
- `123456` hps4Xy4… — still on curve ~$43k / h1 +1276%; prior reject (top10 concentration + creator dumped)
- `1` FSJb… — $306k, **6.7k buys/h** botty
- BANANA / ROADSTER Eizz — weak / copycat priors
- ETERNAL live ~$16.8k — creatorBal 0 prior

## Extra hunt (pf last-trade, age~0.4–0.5h) — all REJECT
| Sym | Mint | Mc | Autopsy |
|-----|------|-----|---------|
| BARRON | `7z48Gs…XrDQ` | ~$139k pumpswap | **FAIL** botty **14.4k buys/h**; creator still **11.6%**; top10 ~37% |
| RUNNER | `Fko4w9…pump` | ~$42k | **FAIL** creatorBalance **0**; h1 **−4%**; pool-heavy top10; age pair ~minutes |
| VIMP | `9Hwgyh…pump` | ~$28k curve ~92% | **FAIL** creatorBalance **0**; **16 graph insiders**; m5 **−26%** |

## Decision
**NO_TRADE** — stay in SOL. No autopsy-clean candidate better than parking ~0.38 SOL.

## Kraken
Watch-only. Last `/workspace/markets/snapshots.log` 2026-10-15 09:50 ET: USD cash **$0.81** below min — no fresh markets pull this run; no proposal.


# ===== scout-0016.md =====

# Scout 0016 — 2026-10-16 00:16 ET

## Decision
**NO_TRADE** — stay in SOL. No autopsy-clean rotate target.

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.378250232** (RPC getBalance)
- SPL: dust USDC 0.000006; Token-2022 ATAs (11) all zero
- SOL price ~$105.10 (DexScreener) → est. total ~**$39.75**

## Scout counts
- Feeds: boosts-latest/top + profiles-latest (200) + pf currently-live / mcap / last-trade / created (all 200; not Cloudflare-blocked this run)
- lists.txt: 207 pump-ending addresses → scan.py **250 mints** → `cands.json` 130 vol/age rows
- Strict numeric passers (mc $15–450k, age 0.5–3.5h, h1≥+20%, buys>sells, buys≲3k, mint*pump): **3** — all prior rejects
- Autopsy-clean buys: **0**

## Strict passers (rejected as priors)
| Sym | Mint | Why |
|-----|------|-----|
| 123456 | hps4Xy4…529pump | prior: top10 concentration + creator dumped |
| roadster | CbAeScGT…pump | prior: borrowed tweet, 5 insiders, copycat |
| ROADSTER | Eizz6UJU…pump | prior: revived/borrowed socials, copycat |

## Fresh near-misses
- **WAITIE** `zVXkMzD6…pump` — REJECT (`autopsy-summary-WAITIE-0016.json`): h1 +15.6% misses +20% gate; m5 −16% dumping; borrowed atrupar status link; top10 ex-LP ~27%.
- **EI** `DDaqBWhR…pump` — REJECT (`autopsy-summary-EI-0016.json`): mc ~$10k < $15k; creatorBalance 0; otcdesks + borrowed tweet.
- LUMINOUS / Eloncoin — dump or botty; skip.

## Kraken
Watch-only. Last markets snapshot 2026-10-15 09:50 ET: USD cash **$0.81** below min order — no proposal.


# ===== scout-0020.md =====

# Scout 0020 — 2026-10-16 00:20 ET

## Decision
**NO_TRADE** — stay in SOL. No autopsy-clean rotate target.

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.378250232** (RPC getBalance; unchanged)
- SPL: dust USDC 0.000006; Token-2022 ATAs (11) all zero
- SOL price ~$105.30 (DexScreener) → est. total ~**$39.83**

## Scout counts
- Feeds: boosts-latest/top + profiles-latest (200) + pf currently-live (200); pf mcap/last/created **Cloudflare 403**
- lists.txt: 95 unique pump addresses → scan.py **143 mints** → `cands.json` 72 vol/age rows
- Strict numeric passers (mc $15–450k, age 0.5–3.5h, h1≥+20%, buys>sells, buys≲4k, *pump): **3** — all prior rejects
- Autopsy-clean buys: **0**

## Strict passers (rejected)
| Sym | Mint | Why |
|-----|------|-----|
| 123456 | hps4Xy4…529pump | prior + RC Low Liquidity ~$133, creatorBal 0, score 2867 |
| roadster | CbAeScGT…pump | prior: creatorBal 0, 5 graph insiders, top10 ex-curve ~29%, copycat |
| ROADSTER | Eizz6UJU…pump | prior: creator rug history (RC score 117601), whale ~26%, borrowed socials |

## Other clutter
- `1` FSJb botty 9.8k buys/h; BANANA/GTA/RDSTR/TESLON dumping; ETERNAL on pf-live (prior creator dump).

## Kraken
Watch-only. Last markets snapshot 2026-10-15 09:50 ET: USD cash **$0.81** below min order — no proposal.


# ===== scout-0036.md =====

# Scout 0036 — 2026-10-16 00:36 ET (America/New_York)

## Decision: **NO_TRADE**

## Wallet snapshot
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL (RPC getBalance): **0.378250232** (378250232 lamports) — unchanged
- Token-2022 ATAs: all **0** (empty positions: XsCPL…, TTWof…, 31GYU…pump, 3EC7g…pump, EBgMj…pump, cnNgF…pump, BMKd…, pumpCm…, NFLX7…, AKotz…pump, CZ3X9…pump)
- Classic SPL: USDT 0; USDC dust **0.000006** only
- Book: **all SOL**, no meme positions
- Est. total ≈ **$39.86** (SOL ~$105.37)

## Scout counts
- Feeds tagged 0036: DexScreener boosts-latest / boosts-top / profiles-latest OK; pump.fun currently-live OK (50); mcap/last-trade **404**; created **403** Cloudflare
- lists.txt: 4 lines (solana *pump from boosts+profiles+live)
- scan.py: **144 mints** → **79 cands** (`scan-0036.out`, `cands.json`)
- Strict numeric passers: **2** → autopsy-clean: **0**
- Near-misses noted: SXTR (botty 5.3k buys/h), FLOKI (mc $7.5k under floor), ROADSTER/GTA priors dumping

## Strict passers

### 1) GUILD `ABmp7kvhMFXEUvjq9cybBPPbrju8uv8GTQPCDbvLpump` — PRIOR STANDS (REJECT)
- pumpfun curve mc ~$25.5k, age ~0.67h, h1 +684%, 462b/346s
- Prior autopsy 0031: creator sent 52.1M (5.21%) to fresh #2 → dev+linked ~6.6% >5%; top10 ex-curve ~29%; wallet split into fresh bag
- Not drastically improved → **prior stands**. See `autopsy-summary-GUILD-0031.json` / `autopsy-summary-GUILD-0036-prior.json`

### 2) DarkStar / "OG Roadster" `9JYbTj84nzPQrS3zpkNGdwDRmmDA6i6wVaEtu1x5pump` — NEW → **REJECT**
- Numeric PASS: pumpfun curve mc ~$18.4k (was under floor at 0031), age ~2.4h, h1 +154%, m5 +35%, 213b/147s, not botty, mid-curve (~36% on bonding curve)
- Autopsy FAIL (any one enough to skip):
  - **Dev**: creatorBalance **0** (dumped early) — hard fail
  - **Holders**: top10 ex-curve **~30.7%** at/over 25–30% cap
  - **Socials / narrative**: name **OG Roadster**; website = Wikipedia Tesla Roadster; only social = borrowed X status link — ROADSTER copycat clutter (priors already burned this narrative)
  - Bundle: funders mostly aged/diverse — not the kill reason
  - RC score 1, mint/freeze none, graphInsiders 0 — not enough to override dumps/copycat
- Files: `autopsy-raw-DarkStar-0036.json`, `autopsy-summary-DarkStar-0036.json`, `funders-DarkStar-0036.json`

## Other window clutter (not strict / prior)
- SXTR GU3JGZr2… — h1 +458% but **5374 buys/h botty** → reject numeric
- ROADSTER 2B69… — 10k buys/h botty + prior family
- ROADSTER Eizz… / GTA / BANANA / `1` FSJb / VIMP / RDSTR / STARMAN / RUNNER / 123456 — priors stand or failing tape
- FLOKI FTbLCDt9… — h1 +56% but mc ~$7.5k under $15k floor

## Kraken
Watch-only. Last `/workspace/markets` snapshot showed USD cash **~$0.81** below min — no proposal (no fresh markets pull this run).

## Action
**None — stay in SOL.** Parent executes any future buy via browser; this scout does not trade.


# ===== scout-0043.md =====

# Scout 0043 — 2026-10-16 00:43 ET (America/New_York)

## Decision: **NO_TRADE**

## Wallet snapshot
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL (RPC getBalance): **0.378250232** — unchanged since SYCAMORE dump ~23:19
- Token-2022 / SPL: dust USDC only; all meme ATAs **0**
- Book: **all SOL**, no meme positions
- Est. total ≈ **$39.84** (SOL ~$105.33)

## Scout counts
- Feeds: DexScreener boosts-latest/top + profiles OK; pump.fun currently-live OK (50); mcap/last/newest **404**
- scan.py: **144 mints** → **85 cands** (`scan-0043.out`)
- Strict numeric passers: **3** → autopsy-clean: **0**
- Loose/botty clutter: SXTR 6.1k buys/h; ROADSTER 2B69 12k buys/h; BANANA sells>buys

## Strict passers

### 1) GUILD `ABmp7kvhMFXEUvjq9cybBPPbrju8uv8GTQPCDbvLpump` — PRIOR STANDS (REJECT)
- curve mc ~$26.5k, age ~0.77h, h1 +715%, 478b/353s
- Prior 0031/0036: creator sent 52.1M (5.21%) to fresh #2 → dev+linked ~6.6% >5%; top10 ex-curve ~29%

### 2) RDSTRWHALE `6zVwic7BRVTcMjhuEruV52HV8iXgcaRA3UsgSv6zpump` — NEW → **REJECT**
- Numeric PASS: curve mc ~$26.4k, age ~0.55h, h1 +493%, m5 −5.8%, 1190b/687s (not botty <2.5k)
- Autopsy FAIL:
  - **Dev/history**: RugCheck score **91201**, risk **Creator history of rugged tokens** (danger)
  - **Socials/narrative**: name "The Roadster Whale"; Dex socials/websites empty — ROADSTER copycat clutter
  - m5 already red (−5.8%) into the print
- Files: `autopsy-raw-RDSTRWHALE-0043.json`, `autopsy-summary-RDSTRWHALE-0043.json`

### 3) DarkStar / "OG Roadster" `9JYbTj84nzPQrS3zpkNGdwDRmmDA6i6wVaEtu1x5pump` — PRIOR STANDS (REJECT)
- creatorBal 0; top10 ex-curve ~31%; ROADSTER copycat (0036)

## Other
- currently-live in-window: only ETERNAL (prior reject, creator dumped)
- Boost extras (SI276/OWLDACITY/VICE/Whaleoween/QUENTRA/…): all past narrative window, botty, or dead mc
- Priors stand: BANANA/`1`/GTA/ROADSTER×N/TESLON/MENTOR/NINNY/STREAM/PONK/…

## Kraken
Watch-only. Last `/workspace/markets` snapshot still shows USD cash **~$0.81** below min — no proposal (no fresh markets pull).

## Action
**None — stay in SOL.**


# ===== scout-0113.md =====

# scout 01:13 ET 2026-10-16
Book: all SOL 0.378250232 (~$40.15 @ $106.15). No meme positions.
Scan: 143-ish mints via boosts/profiles/pf-live + scan.py → interesting-0113.json
Strict numeric passers (2), both PRIOR rejects:
- GUILD ABmp7kvh… mc~$29k age 1.3h h1+46% m5+10% — FAIL: #2 holder still 5.21% (prior linked from creator); creatorBal ~1.95e13; top10_ex1~27%. Prior autopsy-summary-GUILD-0031 stands.
- DarkStar 9JYbTj84… ("OG Roadster") mc~$20k age 3.0h h1+329% m5-6% — FAIL: creatorBal 0; ROADSTER copycat; top10_ex1~45%.
Botty: SXTR 7k buys/h; RDSTRWHALE RC creator rug; VIMP dumping.
ETERNAL live mid-curve — prior (creatorBal 0 + transfer insider net).
Action: none — stay in SOL.


# ===== scout-0137.md =====

# scout 01:37 ET 2026-10-16 (tag 0137)
Book: all SOL **0.29760554** (~$31.50 @ ~$105.87). No meme positions (OPENSTOCK dumped 01:33 ET, −66%).

Feeds: boosts-latest/top + profiles + pf-live OK; pf mcap/last-trade/created **404**; dex-search pump/pumpswap OK.
`lists.txt` rebuilt (6 lines; ~113 unique solana *pump from feeds+search).
Scan: **139 mints** → **78 cands** (`scan-0137.out` / `cands.json`) → `interesting-0137.json`.

## Strict (5) — all PRIOR, no re-autopsy
| sym | mint | mc | age | h1 | m5 | buys/h | dex | note |
|-----|------|----|-----|----|----|--------|-----|------|
| DarkStar | 3vMEBLJAAwx7… | ~$12.2k | 1.4h | +264% | +1.8% | 330/258 | pumpfun | ROADSTER/DarkStar copycat prior |
| SXTR | GU3JGZr26TXN… | ~$390k | 1.6h | +44% | +5% | **5121**/3291 | pumpswap | botty (5k+ buys/h) prior |
| DarkStar | 9JYbTj84nzPQ… | ~$26.6k | 3.4h | +42% | +2.7% | 219/155 | pumpfun | creatorBal 0; ROADSTER copycat; top10~45% prior |
| GUILD | ABmp7kvhMFXE… | ~$27.5k | 1.7h | +11% | +0.3% | 92/56 | pumpfun | #2 linked ~5%; top10_ex~27% prior |
| STARMAN | D1X5Fa2yb4h5… | ~$12.0k | 1.7h | +0.5% | −8.9% | 351/206 | pumpswap | prior; momentum dead |

## Loose (4) — all PRIOR
- FLOKI FTbLCDt9… mc~$8.8k (under floor) h1+49% — prior clutter
- BOT FR2kf3ht… mc~$8.6k age 4.7h — prior
- VIMP 9HwgyhM3… mc~$25k h1−27% — dumping prior
- RDSTRWHALE 6zVwic7B… mc~$15.9k h1−41% m5+17% — RC creator rug history prior

## NEW near-misses (under floor / not autopsy)
- SQD `B2zvzWAksM94gXZTNcu971AByycaSG2hgkmrhMK7pump` — curve mc~$5.2k age 0.95h h1+0.8% 9b/7s — **mc under $10k**, thin
- Veilmarket `6CSmvjkTLiRgdJE53kPKozsAAx8zfsr3DbCramvfpump` — curve mc~$9.1k age 3.0h h1−15% — under floor, dumping

## Autopsies this run
**0** — no NEW in-window (age 0.5–4h, mc≥$10k, h1>0) candidates. Lesson from OPENSTOCK: same-size ~2–3% holders on thin holder count = cabal tell.

## Action
**NO BUY — stay in SOL.**


# ===== scout-0142.md =====

# scout 01:42 ET 2026-10-16 (tag 0142)
Book: all SOL **0.29760554** (~$31.50 @ ~$105.5). No meme positions (OPENSTOCK dumped 01:33 ET, −66%).

Feeds: boosts-latest/top + profiles + pf-live OK; pf for-you/king **404**, coins?created **403**/CF; dex-search pump/pumpswap OK.
`lists.txt` rebuilt (1 line; **105** unique solana tokens from boosts+profiles+pf-live).
Scan: **140 mints** → **78 cands** (`scan-0142.out` / `cands.json`) → `interesting-0142.json`.

## Strict (3) — all PRIOR, no re-autopsy
| sym | mint | mc | age | h1 | m5 | buys/h | dex | note |
|-----|------|----|-----|----|----|--------|-----|------|
| DarkStar | 3vMEBLJAAwx7… | ~$13.4k | 1.5h | +300% | −5.8% | 366/284 | pumpfun | ROADSTER/DarkStar copycat prior |
| SXTR | GU3JGZr26TXN… | ~$415k | 1.7h | +45% | +5.4% | **5016**/3203 | pumpswap | botty (5k+ buys/h) prior |
| GUILD | ABmp7kvhMFXE… | ~$27.7k | 1.8h | +13% | +0.5% | 85/53 | pumpfun | #2 linked ~5%; top10_ex~27% prior |

## Loose (7) — all PRIOR / dumping
- DarkStar 9JYbTj84… mc~$20.8k h1−4% m5−20% — creatorBal 0; ROADSTER copycat; top10~45% prior
- STARMAN D1X5Fa2y… mc~$10.8k h1−19% — prior; momentum dead
- ROADSTER Eizz6UJU… mc~$13.0k h1−21% — copycat prior
- VIMP 9HwgyhM3… mc~$28.4k h1−24% — dumping prior
- roadster CbAeScGT… mc~$9.1k h1−32% — copycat prior
- RDSTRWHALE 6zVwic7B… mc~$15.7k h1−34% — RC creator rug history prior
- GTA 6S7jwQuV… mc~$17.9k h1−39% — prior clutter

## NEW near-misses (under floor / not autopsy)
- DAEMON `Hf3rEfh9DxsMhv44bq4y9kveZn8mKSo2hppJURYrpump` — curve mc~$7.3k age 1.9h h1−10% 30b/27s — **mc under $10k**, soft tape
- CUCKCODING 5php3frs… mc~$3.8k age 0.6h dumping; COCAINU CsRrYtPx… mc~$3.3k — floor trash
- RIZO 2AX8GEVb… now pumpswap ~$26k h1−43% — prior (creatorBal 0 / top10) still stands, dumping hard

## Autopsies this run
**0** — no NEW in-window (age 0.5–4h, mc≥$10k, h1>0, buys>sells, non-botty) candidates. OPENSTOCK lesson: same-size ~2–3% holders on thin holder count = cabal tell → still rejecting that profile.

## Action
**NO BUY — stay in SOL.**


# ===== scout-0144.md =====

# scout 0144 / 2026-10-16 01:46 ET
Book: all SOL **0.29760554** (~$31.44 @ ~$105.59). No meme positions (OPENSTOCK dumped 01:33 ET). Dust USDC 0.000006 only; Token-2022 ATAs all zero.

Feeds: boosts-latest/top + profiles + pf-live OK; pf newest/for-you/king returned empty/error dicts; pf mcap/last/created Cloudflare. Extra dex searches (sol meme, new pump, pumpfun, ai/cat/dog/elon/roadster/guild).
`lists.txt` **220** unique pump mints → scan.py **231 mints** → **114** cands → **0** strict numeric passers.

## Strict — none

## Loose / window (age≤4.5h mc≥$8k)
| sym | mint | mc | age | h1 | m5 | buys/h | note |
|-----|------|----|-----|----|----|--------|------|
| NASA | 5McoDDm3…pump | ~$1.7M | 0.97h | +3841% | +7% | **20151**/17120 | FAIL botty + RC holder correlation 2701 + graduated |
| TZERO | 5So1AMS2…pump | ~$8–10k | 3.54h | +164–234% | +67–122% | 137/75 | FAIL autopsy (below) |
| DarkStar | 3vMEBLJA… | ~$11k | 1.5h | +228% | −18% | 369/299 | PRIOR ROADSTER copycat |
| FLOKI | FTbLCDt9…pump | ~$8.8k | 2.15h | +59% | +8% | 142/103 | FAIL autopsy (below) |
| SXTR | GU3JGZr2… | ~$452k | 1.7h | +55% | +12% | **4858**/3118 | PRIOR botty |
| GUILD / STARMAN | … | … | … | flat | … | … | PRIOR |

## Autopsies
- **TZERO** `5So1AMS2aibd6ZFZ4a8A7Ho8ckmKRuzJRqZVsp6Kpump`: RC score 1, mint/freeze revoked, 0 graph insiders, 90 holders. **FAIL**: creatorBalance **0**; top10 ex-curve ~**36%** (uniform ~3% wallets = cabal tell per OPENSTOCK lesson); mc under $15k floor; age 3.54h past narrative window; no socials. `autopsy-raw-TZERO-0144.json`
- **FLOKI** `FTbLCDt9XQUF3VnqRikkM3XNnbRMXJUPUtpra51Dpump`: **FAIL** creatorBal 0; top10 ex-curve ~32%; mc under floor. `autopsy-raw-FLOKI-0144.json`
- **NASA** `5McoDDm3XmbkAjeaCjfMmnewR1XAfZxeLa6e4rtFpump`: **FAIL** botty 20k buys/h; RC score 2701 high holder correlation; creatorBal 0; already ~$1.7M pumpswap. `autopsy-raw-NASA-0144.json`

## Action
**NO BUY — stay in SOL.**


# ===== scout-0152.md =====

# scout 0152 / 2026-10-16 01:52 ET
Book: all SOL **0.29760554** (~$31.53 @ ~$105.94). No meme positions (OPENSTOCK dumped 01:33 ET). Dust USDC only; Token-2022 ATAs assumed zero (SOL RPC unchanged).

Feeds: boosts-latest/top + profiles + pf-live OK; pf mcap/last/created Cloudflare/empty. Extra dex searches (sol meme, new pump, ai/cat/pepe/moon/frog).
`lists.txt` → scan.py **175 mints** → **80** cands → **0** strict numeric passers → **0** NEW in-window (age≤4h mc≥$10k h1>0) → **0** autopsy-clean buys (`scan-0152.out` / `scan-0152b.out` / `interesting-0152.json`).

## Strict — none

## Loose / window (all priors)
| sym | mint | mc | age | h1 | m5 | buys/h | note |
|-----|------|----|-----|----|----|--------|------|
| DarkStar | 3vMEBLJA… | ~$11–13k | 1.7h | +231–289% | +6–25% | ~400 | PRIOR ROADSTER copycat |
| FLOKI | FTbLCDt9… | ~$8.9k | 2.3h | +72% | flat | 143 | PRIOR under floor / creatorBal 0 |
| SXTR | GU3JGZr2… | ~$374–391k | 1.8h | +18–21% | ± | **~5k** | PRIOR botty |
| GUILD | ABmp7kvh… | ~$27k | 1.9h | +1–9% | +6–9% | 80 | PRIOR dev+linked |
| VIMP / RIZO | … | … | … | dump | … | … | PRIOR |

## Fresh boosts (age <0.5h — too early; logged for next run)
- **RL** "Roadster League" `DRNqV2V6WxjjgDqa4tgf1KfpsGLDNSvraSc9k6L9pump` (curve ~$21k, **0.19h**, h1 +503%, m5 −5%) — FAIL: under 30m window; **creatorBal 0**; ROADSTER copycat narrative; top10 ex-curve ~24% borderline. `autopsy-raw-RL-0152.json`
- **FMC** "Flying Memecoin" `BBHbbon3T4Z2H2mwZjoV4wVPtoocSmF2W8B8kWmXpump` (pumpswap ~$74k, **0.24h**, h1 +71%, m5 +34%, 2.4k buys/h) — FAIL: under 30m + graduation-spike risk; **creatorBal 0**; whale #2 ~17% ex-LP. `autopsy-raw-FMC-0152.json`
- **PVSN** `edWxH37c…pump` (~$63k, 0.49h, m5 **−33%**, **5k buys/h**) — FAIL botty + dumping. `autopsy-raw-PVSN-0152.json`

## Action
**NO BUY — stay in SOL.**


# ===== scout-0207.md =====

# Scout 02:07 ET 2026-10-16

Wallet SOL 0.29760554 (~$31.45 @ $105.63). All SOL, no meme positions.

Scan: boosts+profiles+pf-live + expanded dex → 152 mints → 7 in-window → 0 autopsy-clean.

## NEW rejects
- **ERIC** `DuaSA2YynBhqyW26n48EX7qtdRWKHtnVjR8fsE5spump` (Elons Pet Goldfish, curve ~$21–23k, 0.57h, h1 +445%, m5 −14%, 569b/389s) — FAIL holders: top10 ex-curve **~33.6%** (#2 8.6% ui0 + many ~2.2–2.8%); creatorBal 0; RC Low Liquidity score 2846; community-only X. `autopsy-summary-ERIC-0207.json`
- **FR** `CB5k84Kyue6WR8Uh3iPJuzbVVhmXDqnGT2UR8Tmcpump` (Flying Rizo, curve ~$13k, 0.4h, h1 +330%, m5 **−42%**) — FAIL: hard dump; no socials; creatorBal 0; RIZO-name reuse; uniform ~2–4% band. `autopsy-summary-FR-0207.json`
- **dih** `D7FuQ8bPxLLSDS3pubBkG2cSStrm3raeAJ9rPTevpump` (dog in helmet, curve ~$14k, 0.46h, h1 +315%, m5 −22%) — FAIL: 10/10 top holders in 1.7–4.3% band (cabal tell); no socials; creatorBal 0. `autopsy-summary-dih-0207.json`

## Priors stand
- RL Roadster League DRNqV2V6… — copycat + **4 graph insiders** + m5 −30%; `autopsy-summary-RL-0207.json`
- PVSN / SXTR — botty 5–6k buys/h
- DarkStar 9JYb… — ROADSTER copycat, ~3.9h past preference window

Action: stay in SOL.


# ===== scout-0214.md =====

# Scout 02:14 ET 2026-10-16

Wallet SOL **0.29760554** (~$31.46 @ $105.67). All SOL, no meme positions. Dust USDC 0.000006; T22 ATAs zero.

Scan: boosts latest/top + profiles + pf-live (created/mcap 404) + expanded dex → **154 mints** → 143 pairs → **6** in-window → **1** NEW → **0** autopsy-clean (`scan-0214.out` / `interesting-0214.json` / `inwindow-0214.json`).

## NEW reject
- **Optimus** `5b8F5y5uK3JgRTowCxfKbtMS3397DtSwxKMHjRZhpump` (curve ~$19.8k, 2.57h, h1 +44%, m5 −3.8%, 70b/55s, curve holds ~36%) — FAIL: top10 ex-curve **~26.5%** with **10/10 in 1.5–4.5% uniform band** (OPENSTOCK cabal tell); shared funders A77HErqt… (identical **1.007908 SOL** ×2) + u6PJ8DtQ… ×3; brand-new X @OptimusRobotX (created ~02:06 ET, **0 followers**, 2 tweets); creatorBal 0 + creator SOL 0. RC score 1 / mint+freeze revoked — not enough. `autopsy-summary-Optimus-0214.json`

## Prior rechecks (material m5 moves, still FAIL)
- **FR** CB5k84Ky… (Flying Rizo, ~$14–17k, m5 recovered +21% from −42%) — still FAIL: no socials; creatorBal 0; RIZO-name reuse.
- **ERIC** DuaSA2Yy… (~$18k) — top10 ex-curve ~33.7%; RC Low Liquidity score 2871; uniform band 8/10.
- **RL** DRNqV2V6… (~$12k) — ROADSTER copycat; uniform 10/10 band; prior 4 graph insiders.
- **dih** D7FuQ8bP… (~$11k, m5 −22%) — uniform 10/10; no socials; creatorBal 0.

## Priors stand / too young
- PVSN (6.4k buys/h botty), DarkStar 3vMEBLJA… (copycat)
- Near-new under window: BRYAN 0.09h, TCAT 0.21h mc~$8.7k, CLAUDEMAN 0.32h mc~$8.7k m5 −29%

Action: stay in SOL.


# ===== scout-0231.md =====

# Scout 0231 — 2026-10-16 02:31 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **297605540 lamports = 0.29760554 SOL**
- SPL/Token-2022: dust USDC only + zero-balance meme ATAs (no positions)

## Feeds
- `boosts-latest-0231.json` (30), `boosts-top-0231.json` (30), `profiles-latest-0231.json` (30)
- `pf-live-0231.json` (50)
- `lists.txt` rebuilt → `scan-0231.out` / `cands.json` (**76** mints)

## In-window filter
Criteria: age ≤4h, marketCap ≥10000, priceChange.h1 > 0

| Symbol | Mint (short) | NEW? | dex | mc | age_h | h1 |
|--------|--------------|------|-----|-----|-------|-----|
| CLAUDEMAN | DjrijJNopHhe… | YES | pumpfun | 27739 | 0.61 | +594 |
| RL | DRNqV2V6… | prior | pumpfun | 17018 | 0.84 | +378 |
| ERIC | DuaSA2Yy… | prior | pumpfun | 16333 | 0.98 | +328 |
| Optimus | 5b8F5y5u… | prior | pumpfun | 19597 | 2.87 | +30.6 |
| ELON-SAN | DkKywKTo… | prior | pumpswap | 93008 | 1.90 | +24.1 |

**In-window: 5 | NEW: 1**

## NEW autopsy — CLAUDEMAN
- Mint: `DjrijJNopHheVub1JdtJ7snqHS55kNY6kC5HNViTpump`
- Curve: ~61.0 SOL in pump.fun pool (~72% toward ~85 SOL grad) — phase OK
- RugCheck: score 1, not rugged, creatorBal **0**, 496 holders
- top10 ex-curve/LP: **~22.7%** (OK alone)
- Uniform 1.5–4.5% band: **13** wallets — cabal tell
- Socials: **none** (dex `info` null; empty meta description)
- Funders: no identical multi-wallet SOL bundle; **linked**: AArB9dpo (holder) funded Ayrxby7b (3.07%)
- pump.fun `/coins/<mint>`: 404 this run (used RugCheck + Dex instead)

### Decision: **FAIL**
Reasons: empty socials; creatorBal 0 + uniform cabal band; graph insider link.

## Decision
# **NO-TRADE** — remain in SOL. Prefer SOL over dirty autopsy.

## Key files
- `wallet-sol-0231.json`, `wallet-spl-0231.json`, `wallet-t22-0231.json`
- `boosts-*-0231.json`, `profiles-latest-0231.json`, `pf-live-0231.json`
- `lists.txt`, `scan-0231.out`, `cands.json`, `inwindow-0231.json`
- `autopsy-raw-CLAUDEMAN-0231.json`, `funders-CLAUDEMAN-0231.json`, `autopsy-summary-CLAUDEMAN-0231.json`
- `dex-CLAUDEMAN-0231.json`, `pf-coin-CLAUDEMAN-0231.json` (404)
- `trade-log.md`, `scout-0231.md`


# ===== scout-0240.md =====

# Scout 0240 — 2026-10-16 02:40 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **297605540 lamports = 0.29760554 SOL** (~$31.63 @ $106.29)
- SPL/Token-2022: dust/empty only — no meme positions

## Feeds
- boosts-latest/top + profiles + pf-live + expanded dex → scan → loose-0240.json

## In-window (strict: age≤4h, mc≥$10k, h1>0)
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| RL | prior | ~15k | 0.98 | +319 | copycat / uniform band |
| Optimus | prior | ~20k | 3.0 | +33 | cabal + empty X |
| ELON-SAN | prior | ~76k | 2.03 | +7.6 | whale + insiders |

## Loose NEW
| Symbol | mint | mc | age_h | h1 | decision |
|--------|------|-----|-------|-----|----------|
| ELON | `5xqdoeabeV7T9dwpMgM6BVKcg8ZZUgjKcwi8hNwCpump` | ~$10.2k | 0.17 | +186 | **FAIL** |

### ELON autopsy
- Curve ~46.7% held (phase early); RC score 1, mint/freeze revoked
- creatorBal **0**; socials **none**; age **0.17h < 30m**
- top10 ex-curve ~18.7%; 14 wallets in 1–4.5% band
- Narrative: generic ELON copycat

## Decision
**NO-TRADE** — stay in SOL. Prefer SOL over too-young / dirty autopsy.


# ===== scout-0303.md =====

# Scout 0303 — 2026-10-16 03:03 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** — SPL: dust USDC only — no meme positions

## Feeds
- boosts-latest/top + profiles + pf-live (50) + expanded dex → **224 mints** → scan/filter
- pf created/mcap/last: **403**

## Strict in-window (age≤4h, mc≥$10k, h1>0)
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| CCAT | prior | ~143k | 0.82 | +225 | post-grad; creatorBal 0 |
| ELON-SAN | prior | ~122k | 2.41 | +48 | whale + insiders |
| RIZO | prior | ~20k | 2.01 | +52 | prior reject |
| Optimus | prior | ~20k | 3.38 | +13 | cabal + empty X |
| neuron | prior | ~13k | 0.66 | +337 | creatorBal 0 |

## NEW (too young / fail)
| Symbol | mint | mc | age_h | decision |
|--------|------|-----|-------|----------|
| Muskpad | `UZcE4ws4kERR6prnmgGMCSfUL1XynhZbzJCyKo5pump` | ~$21k | 0.12 | **FAIL** age&lt;30m, creatorBal 0, no socials, 13×1–5% band |
| LOOM | `7GCMYJcykHZ3qJH3e5vQi4J9qAPdb3Xninkgk6sYpump` | ~$52k | 0.17 | **FAIL** age&lt;30m, creatorBal 0, 2k buys/h botty post-grad |

## Decision
**NO-TRADE** — stay in SOL.


# ===== scout-0311.md =====

# Scout 0311 — 2026-10-16 03:11 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (RPC 297605540 lamports) — SPL: dust USDC 6e-06 only — Token-2022 ATAs empty — **no meme positions**
- Est. total ~$31.5 at SOL ~$106

## Feeds
- boosts-latest/top + profiles (200) + pf-live (200, 50 coins) + expanded dex search
- pf newest **404**; created/mcap **403**
- scan.py: **139 mints** → 81 cands (`scan-0311.out` / `cands-0311.json`)
- expanded universe: **150 mints** → filter (`expanded-0311.json`)

## Strict in-window (age≤4h, mc≥$10k, h1>0)
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| ELON-SAN | prior | ~115k | 2.58 | +44 | whale + graph insiders |
| LOOM | prior | ~107k | 0.34 | +144 | still <30m; botty post-grad |
| CCAT | prior | ~99k | 0.99 | +126 | creatorBal 0 / no project X |
| Muskpad | prior | ~47k | 0.11 | +11 | still <30m; creatorBal 0 |
| miBrains | **NEW** | ~16k | 0.08 | +323 | FAIL age/creatorBal/socials |
| neuron | prior | ~11k | 0.84 | +256 | creatorBal 0 / no socials |

## NEW autopsies
| Symbol | mint | mc | age_h | decision |
|--------|------|-----|-------|----------|
| ROADSTER | `TB6QtGti9j2zadAryKYKCm7tX1zVvTH4ZQcoXd9pump` | ~$33k | 1.11 | **FAIL** ROADSTER copycat; creatorBal 0; 26 graph insiders; top10 ex-LP ~54% (whale ~25%); RC score 33029 |
| miBrains | `7m8uQMAD1hkKuf4ooWFhJuBq4hSD8PoBcwojDLfQpump` | ~$16k | 0.08 | **FAIL** age&lt;30m; creatorBal 0; no socials; botty band |

## Rechecks
- **CCAT** ~$99k (~31% off 03:05 ~$143k print) but m5 −16%, still creatorBal 0 / no project X — prior FAIL stands; not a clean dip-and-hold entry.
- **LOOM** 0.34h / **Muskpad** 0.11h — still under 30m entry window.
- **neuron** — creatorBal 0 / empty socials stand.

## Decision
**NO-TRADE** — stay in SOL. Autopsy-clean buys: **0**.


# ===== scout-0316.md =====

# Scout 0316 — 2026-10-16 03:16 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (RPC 297605540 lamports) — SPL: dust USDC 6e-06 only — Token-2022 ATAs empty (0/12 nonzero) — **no meme positions**
- Est. total ~$31.7 at SOL ~$106.41

## Feeds
- boosts-latest/top + profiles → `boosts-latest-0316.json` / `boosts-top-0316.json` / `profiles-latest-0316.json`
- pf-live (50 coins) → `pf-live-0316.json`
- lists.txt: **89** pump mints from boosts+profiles+live
- scan.py: **141 mints** → 79 cands (`scan-0316.out` / `cands-0316.json`)
- expanded universe: **129 mints** → filter (`inwindow-0316.json`)

## Strict in-window (age≤4h, mc≥$10k, h1>0)
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| ELON-SAN | prior | ~131k | 2.64 | +118 | whale + graph insiders (prior) |
| LOOM | prior | ~129k | 0.39 | +193 | still <30m; botty post-grad |
| CCAT | prior | ~112k | 1.04 | +165 | creatorBal 0 / no project X; ~22% off 03:05 peak |
| Muskpad | prior | ~61k | 0.16 | +46 | still <30m; creatorBal 0 |
| Optimus | prior | ~20k | 3.61 | +0.7 | cabal band + empty X |
| FMC | prior | ~18k | 1.62 | +11.5 | prior FAIL |

## NEW autopsies
**None** — 0 NEW in-window (all 6 priors). Near-misses with h1≤0 (ROADSTER, GUILD, CLAUDEMAN, RL) not re-autopsied; priors stand. neuron mc ~$9.2k below floor.

## Rechecks
- **CCAT** ~$112k (~22% off 03:05 ~$143k) — still mid post-grad chop; creatorBal 0 / no project X stand. Not a clean 30–60% dip entry. `autopsy-summary-CCAT-recheck-0316.json`
- **LOOM** 0.39h — still under 30m entry window; botty prior stands. `autopsy-summary-LOOM-recheck-0316.json`
- **Muskpad** 0.16h — still under 30m; creatorBal 0 stands. `autopsy-summary-Muskpad-recheck-0316.json`
- **neuron** ~$9.2k / 0.9h — below $10k floor; creatorBal 0 / no socials stand. `autopsy-summary-neuron-recheck-0316.json`

## Decision
**NO-TRADE** — stay in SOL. Autopsy-clean buys: **0**.
Book all SOL (~0.30); want clean buy at ~0.09–0.10 SOL if one appears — none this cycle.
Kraken: watch-only; last known USD cash ~$0.81 below min buy — no proposal.


# ===== scout-0335.md =====

# Scout 0335 — 2026-10-16 03:35 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (verified this run; all SOL, no meme positions)
- Est. total ~$31.55 at SOL ~$106
- Fee reserve ≥0.01 SOL; max deployable ~0.25–0.28 if a clean buy appeared

## Feeds
- boosts-latest/top + profiles + CTOs (7) → `lists.txt`
- pf-live currently-live 50 coins (`pf-live-0335.json`)
- scan.py + expanded dex queries (elon/tesla/roadster/musk/brain/…)
- scan.py: **146 mints** → 81 cands (`scan-0335.out` / `cands-0335.json`)
- expanded universe: **254 mints** → **241** pairs (`expanded-0335.json`)

## Strict in-window (age≤4h, mc≥$10k, h1>0)
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| LOOM | prior | ~163k | 0.72 | +291 | botty post-grad; creatorBal 0 |
| ELON-SAN | prior | ~153k | 2.97 | +145 | whale + graph insiders |
| ROADSTER | prior | ~30k | 1.49 | +15 | copycat; creatorBal 0; insiders |
| Cloudboi | **NEW** | ~26k | 0.21 | +497 | FAIL age/creatorBal/socials/band |
| Optimus | prior | ~20k | 3.94 | +0.4 | cabal band + empty X |
| FMTR | **NEW** | ~17k | 0.65 | +373 | FAIL **shared-funder bundle** |
| Alex | **NEW** | ~13k | 1.19 | +168 | FAIL creatorBal/socials/band |
| miBrains | prior | ~10k | 0.46 | +160 | age/creatorBal/socials |

## NEW autopsies
| Symbol | mint | mc | age_h | decision |
|--------|------|-----|-------|----------|
| Cloudboi | `8EtQDY7hUddahsbJ8stYYe64ZV9NkGhdrY44Df3npump` | ~$15–26k | 0.21–0.24 | **FAIL** age&lt;30m; creatorBal 0; no socials; 19×1–5% band |
| FMTR | `8rAhJEyM72smDNgGUcPETXoVi21x7k2R8u2AMXGQpump` | ~$17k | 0.65–0.68 | **FAIL** **12/12 top holders share funder `is6MTR…`**; creatorBal 0; whale ~9.6%; top10 ~29%; 18×1–5% band. Has X/site but cabal-funded. |
| Alex | `79euwaxxwh8qYbHLpKvk9isQiuzpqTNobBsqPXvipump` | ~$13k | 1.19–1.22 | **FAIL** creatorBal 0; no project X (status+IG only); 19×1–5% band. Funders: no shared-funder (old traders). |

Artifacts: `autopsy-raw-{Cloudboi,FMTR,Alex}-0335.json`, `autopsy-summary-*-0335.json`, `funders-{FMTR,Alex}-0335.json`

## Rechecks
- **LOOM** ~$157k, m5 flat, h1 +277%, 6.8k buys — still post-grad botty spike; prior FAIL stands. `autopsy-summary-LOOM-recheck-0335.json`
- **CCAT** ~$47k (~67% off 03:05 ~$143k), h1 −46%, m5 +32 bounce — still collapsing / not a clean hold; prior FAIL stands. `autopsy-summary-CCAT-recheck-0335.json`
- **Muskpad** ~$49k post-grad, ~0.49h, 4.5k buys — prior FAIL stands; not chasing. `autopsy-summary-Muskpad-recheck-0335.json`
- **ELON-SAN / ROADSTER / Optimus / miBrains / neuron** (~$7.4k below floor) — priors stand.

## Decision
**NO-TRADE** — stay in SOL. Autopsy-clean buys: **0**. Prefer SOL over any of these (especially FMTR cabal bundle).


# ===== scout-0346.md =====

# Scout 0346 — 2026-10-16 03:46 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (RPC verified this run; all SOL, dust USDC ~6e-06 only, no meme positions)
- Est. total ~$31.62 at SOL ~$106.23
- Fee reserve ≥0.01 SOL; max deployable ~0.25–0.28 if a clean buy appeared

## Feeds
- boosts-latest/top + profiles + CTOs (7) + pf-live 47 → `lists.txt`
- scan.py: **143 mints** → 82 cands (`scan-0346.out` / `cands-0346.json`)
- expanded universe (extra dex: elon/tesla/roadster/musk/ai/brain/cat/…): **260 mints** → **247** pairs (`expanded-0346.json`)

## Strict in-window (age≤4h, mc≥$10k, h1>0)
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| LOOM | prior | ~145k | 0.91 | +247 | botty post-grad (~8.4k buys); creatorBal 0 |
| ELON-SAN | prior | ~144k | 3.16 | +80 | whale + graph insiders |
| Muskpad | prior | ~62k | 0.68 | +54 | post-grad botty (~4.9k buys); creatorBal 0 |
| TCAT | **NEW** | ~14k | 1.35 | +273 | FAIL creatorBal/socials/band |
| RL | prior | ~13k | 2.10 | +29 | prior FAIL stands |
| CatNose | **NEW** | ~11k | 0.22 | +80 | FAIL age&lt;30m + creatorBal + coordinated funder cluster |

## NEW autopsies
| Symbol | mint | mc | age_h | decision |
|--------|------|-----|-------|----------|
| TCAT | `34HExr1pEVFWkx99AXVwSBPcy3XmBYKkSyorxPzVpump` | ~$13–14k | 1.35 | **FAIL** creatorBal **0**; no project X (status tweet only); 19×1–5% band. Funders: no 8+ shared-funder (diverse old wallets). |
| CatNose | `GgmAS6ibUzxNnABcMnGtNiYEdJSP8FiDpa8DqM2Zpump` | ~$11k | 0.22–0.26 | **FAIL** age &lt;30m; creatorBal **0**; no project X (status only); 14×1–5% band; **4 holders share funder `5tzFki…` with ~identical 1.345 SOL**. |

Artifacts: `autopsy-raw-{TCAT,CatNose}-0346.json`, `autopsy-summary-*-0346.json`, `funders-{TCAT,CatNose}-0346.json`

## Rechecks (priors; structure unchanged — no full re-autopsy)
- **LOOM** `7GCMYJcykHZ3…` ~$145k, h1 +247%, ~8.4k buys — still post-grad botty spike; prior FAIL stands.
- **ELON-SAN** ~$144k, h1 +80% — prior FAIL stands (whale ~10.9%, graph insiders).
- **Muskpad** ~$62k, ~0.7h, ~4.9k buys — prior FAIL stands; not chasing post-grad.
- **RL** ~$13k curve — prior FAIL stands.
- **CCAT** ~$57k, h1 −43%, m5 +32 bounce — still collapsing / not a clean 30–60% hold; prior FAIL (creatorBal 0, no project X) stands.
- **Cloudboi** ~$8.7k below floor / **FMTR** ~$3.5k dumped / **Alex** ~$6k below floor — out of window; priors confirmed dead.

## Decision
**NO-TRADE** — stay in SOL. Autopsy-clean buys: **0**. Prefer SOL over TCAT/CatNose (dev out + status-only socials + holder bands / coordinated cluster).


# ===== scout-0356.md =====

# Scout 0356 — 2026-10-16 03:56 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (RPC verified this run; all SOL, dust USDC ~6e-06 only, no meme positions)
- Est. total ~$31.62 at SOL ~$106.24
- Fee reserve ≥0.01 SOL; max deployable ~0.25–0.28 if a clean buy appeared

## Feeds
- boosts-latest/top + profiles + CTOs (7 via community-takeovers) + pf-live 50 → `lists.txt`
- pf mcap/created/last-trade: **Cloudflare 403** (skipped)
- scan.py: **148 mints** → 86 cands (`scan-0356.out` / `cands-0356.json`)
- expanded universe (extra dex: elon/tesla/roadster/musk/ai/brain/cat/dog/…): **273 mints** → **259** pairs (`expanded-0356.json`)

## Strict in-window (age≤4h, mc≥$10k, h1>0) — at scan time
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| LOOM | prior | ~233k | 1.06 | +893 | botty post-grad (~8.0k buys); creatorBal 0 |
| ELON-SAN | prior | ~158k | 3.31 | +108 | whale + graph insiders |
| Muskpad | prior | ~56k | 0.83 | +40 | post-grad botty (~5.0k buys); creatorBal 0 |
| ROADSTER | prior | ~29k | 1.84 | +4.7 | ROADSTER copycat; later h1 flipped −16 |
| GALAX | **NEW** | ~14k→11k | 2.21 | +1.3→−8.5 | FAIL band + 24 graph insiders + coordinated funders |
| TCAT | prior | ~13k→9.2k | 1.51 | +252 | prior FAIL; now below $10k floor |

## NEW autopsies
| Symbol | mint | mc | age_h | decision |
|--------|------|-----|-------|----------|
| GALAX / GalaxMines | `94BfFHQrAHewvj2aCb1vdCTViCRFGRPnvAu7SJG1pump` | ~$11–14k | 2.2–2.3 | **FAIL** 12×1–5% band; **graphInsiders 24**; coordinated funders (3× `5tzFki…`, 3× `u6PJ8D…`). Creator still holds ~0.76% (not 0); has real X/TG/site — structure still cabal-heavy. Momentum faded (h1 flipped negative during autopsy). |

Artifacts: `autopsy-raw-GALAX-0356.json`, `autopsy-summary-GALAX-0356.json`, `funders-GALAX-0356.json`

## NEW skipped (failed entry gate — no full autopsy)
| Symbol | mint | mc | age_h | reason |
|--------|------|-----|-------|--------|
| Puter | `D2obxUYEgBZcJTjGJGH8M9eVMvG6FXCmE2Y3V46rpump` | ~$40k | 0.08 | age &lt;30m; already PumpSwap; h1 −6 (not in strict window) |

## Rechecks (priors; structure unchanged — no full re-autopsy)
- **LOOM** ~$304k, h1 +503%, ~8.1k buys — still post-grad botty spike; prior FAIL stands.
- **ELON-SAN** ~$162k, h1 +58% — prior FAIL stands (whale + graph insiders).
- **Muskpad** ~$50k, ~0.9h, ~5.0k buys — prior FAIL stands; not chasing post-grad.
- **ROADSTER** ~$28k, h1 −16% — prior FAIL stands (copycat / creatorBal 0 / whale band).
- **TCAT** ~$9.2k below floor, m5 −29% — prior FAIL confirmed fading.
- **CCAT** ~$73k, h1 −44% — still collapsing / not a clean 30–60% hold; prior FAIL stands.
- **CatNose / Cloudboi / FMTR / Alex / RL** — priors stand (out of window or dumped).

## Decision
**NO-TRADE** — stay in SOL. Autopsy-clean buys: **0**. Prefer SOL over GALAX (24 graph insiders + 1–5% band + coordinated funders) and over prior rejects.

## Kraken
Watch-only. Last markets snapshot still shows USD cash ~$0.81 below min order — **no proposal**.


# ===== scout-0409.md =====

# Scout 0409 — 2026-10-16 04:09 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (RPC getBalance 297605540 lamports; verified this run)
- SPL: dust USDC only (~6e-06); **no meme positions** (all SOL since OPENSTOCK dump 01:33 ET)
- Est. total ~$31.65 at SOL ~$106.35
- Fee reserve ≥0.01 SOL; max deployable ~0.20–0.25 if a clean buy appeared

## Feeds
- boosts-latest/top + profiles + CTOs (7 via community-takeovers) + pf-live 50 → `lists.txt`
- pf mcap/created/last-trade: intermittent (one pass 200 earlier, later empty/fail) — noted; not relied on
- scan.py: **145 mints** → 80 cands (`scan-0409.out` / `cands-0409.json`)
- expanded universe (extra dex: elon/tesla/roadster/musk/ai/brain/cat/dog/meme/grok/…): **264 mints** → **248** pairs (`expanded-0409.json`)

## Strict in-window (age≤4h, mc≥$10k, h1>0, pump/pumpswap)
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| LOOM | prior | ~366k | 1.30 | +228 | botty post-grad (~8.7k buys); creatorBal 0 — prior stands |
| ELON-SAN | prior | ~146k | 3.55 | +32 | whale + graph insiders — prior stands |
| Tesla | **NEW** | ~122k | 0.07 | +3992 | age <30m FAIL |
| EVERYTHING | **NEW** | ~53k | 0.37 | +24 | age <30m; Puter narrative; botty 3.3k buys |
| POKESQUAD | **NEW** | ~15k | 0.55 | +371 | past 30m; full autopsy **FAIL** |
| CatNose | prior | ~15k | 0.61 | +132 | prior FAIL stands |
| PUMPKEYS | **NEW** | ~13k | 0.14 | +225 | age <30m FAIL |
| GULP | **NEW** | ~11–12k | 0.18 | +95 | age <30m; has X but band+botty |

## NEW autopsies
| Symbol | mint | mc | age_h | decision |
|--------|------|-----|-------|----------|
| Tesla | `4oaW1mEAHjToJpjhfMffPMUqjUF7PWpEfbHYEvdepump` | ~$122k | 0.07 | **FAIL** age <30m; creatorBal 0; no socials |
| EVERYTHING | `DZVADw7Qkfqg2mqQCQBYD2kNsNbq4c2Q9nhBmhtNpump` | ~$50–53k | 0.37 | **FAIL** age <30m; creatorBal 0; 19×1–5% band; 3.3k buys/h; status-tweet X + puter.com |
| POKESQUAD | `DkXumTAaaE32vGcjo2nbkFmxbcXrx2nceayjwCwWpump` | ~$14–15k | 0.55 | **FAIL** creatorBal **0**; 17×1–5% band; 1.1k buys/h; no socials; 2× funder `5tzFki…` @ 1.999 SOL |
| PUMPKEYS | `21aory2QsMHai8BJUQnRHnZ7Hq3Y9mPcaxctmHgLpump` | ~$13k | 0.14 | **FAIL** age <30m; creatorBal 0; 17×1–5% band; status-tweet X only |
| GULP | `8BwEQTbuKD6DyHsr57FpF8L6RRvzr8Gm4TRMMqfbpump` | ~$11–12k | 0.18 | **FAIL** age <30m; 16×1–5% band; ~1.0–1.1k buys/h (has @playgulpfun + site — structure still cabal-like) |

Artifacts: `autopsy-raw-*-0409.json`, `autopsy-summary-*-0409.json`, `funders-POKESQUAD-0409.json`

## Prior rechecks (stand)
- LOOM ~$366k, h1 +228, ~8.7k buys — prior FAIL (creatorBal 0, botty post-grad)
- ELON-SAN ~$146k — prior FAIL (whale/insiders)
- Muskpad ~$17k, h1 −64 — dumping; prior FAIL
- ROADSTER ~$30k, h1 −10 — prior FAIL
- GALAX ~$4.4k (below floor) — prior FAIL confirmed dead
- TCAT ~$9.9k (below floor) — prior FAIL
- CCAT ~$89k, h1 −13 — prior FAIL (creatorBal 0, no project X)
- CatNose ~$15k — prior FAIL stands
- Optimus ~$19k, age 4.5h, h1 −4 — prior FAIL / out of window

## Decision
**NO-TRADE** — stay in SOL. **0** autopsy-clean PASS.

## Kraken
Watch-only. Latest `/workspace/markets/snapshots.log` (2026-10-15 09:50 ET) still shows **USD ~$0.81** below min order — no proposal.


# ===== scout-0417.md =====

# Scout 0417 — 2026-10-16 04:17 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (RPC getBalance 297605540 lamports; verified this run → `wallet-sol-0417.json`)
- SPL: dust USDC only (~6e-06); **no meme positions** (all SOL since OPENSTOCK dump 01:33 ET) → `wallet-spl-0417.json`
- Est. total ~$31.55 at SOL ~$106.03
- Fee reserve ≥0.01 SOL; max deployable ~0.15–0.22 if a clean buy appeared

## Feeds
- boosts-latest/top + profiles + CTOs (7 via community-takeovers) + pf-live 50 → `lists.txt`
- pf mcap/for-you: 404 — noted; not relied on
- scan.py: **146 mints** → 82 cands (`scan-0417.out` / `cands-0417.json`)
- expanded universe (extra dex: elon/tesla/roadster/musk/ai/brain/cat/dog/meme/grok/starman/optimus/spacex/neuron/puter/pokemon/gulp/…): **290 mints** → **277** pairs (`expanded-0417.json`)

## Strict in-window (age≤4h, mc≥$10k, h1>0, pump/pumpswap)
| Symbol | NEW? | mc | age_h | h1 | note |
|--------|------|-----|-------|-----|------|
| LOOM | prior | ~373k | 1.42 | +204 | botty post-grad (~9.3k buys); creatorBal 0 — prior stands |
| ELON-SAN | prior | ~132k | 3.67 | +2.8 | whale + graph insiders — prior stands |
| Tesla | prior | ~122k | 0.20 | +3994 | age <30m; prior FAIL stands |
| ROADSTER | prior | ~30k | 2.20 | +2.4 | prior FAIL stands |
| LULU | **NEW** | ~23k | 0.46 | +667 | full autopsy **FAIL** (BUNDLE) |
| GULP | prior | ~18k | 0.31 | +210 | prior FAIL stands (past ~30m soon; still band+botty) |
| POKESQUAD | prior | ~15k | 0.68 | +383 | prior FAIL stands |
| Dragon | **NEW** | ~15k | 0.54 | +179 | full autopsy **FAIL** |
| BUDDY | **NEW** | ~11k | 0.10 | +165 | age <30m; full autopsy **FAIL** |
| TCAT | prior | ~11k | 1.87 | +5.3 | prior FAIL stands |

## NEW autopsies
| Symbol | mint | mc | age_h | decision |
|--------|------|-----|-------|----------|
| LULU | `8DQzWohFEMWruKUC5G2hEgBcs4bhJ1y7oJuyxZHpump` | ~$23k | 0.46 | **FAIL** age <30m; creatorBal **0**; 19×1–5% band; **BUNDLE** 11/12 top holders share funder `B48kNVX…` @ identical **1.97878212 SOL** (has X/TG/site — structure still cabal) |
| Dragon | `9gG2evdn4HgPCzyJkeUSFLei5Z4XBba3nSNPqczwpump` | ~$15k | 0.54 | **FAIL** creatorBal **0**; 19×1–5% band; 830 buys/h; no socials; 1× funder `5tzFki…` @ 2.939 SOL |
| BUDDY | `BULfSqtuj5HQLxQTGDQ2AXZ4x7a7uXLTuK4qGoTGpump` | ~$11k | 0.10 | **FAIL** age <30m; creatorBal 0; 18×1–5% band; 860 buys/h; status-tweet X + celestialbuddies.com; uxento deploy |

Artifacts: `autopsy-raw-*-0417.json`, `autopsy-summary-*-0417.json`, `funders-LULU-0417.json`, `funders-Dragon-0417.json`

## Prior rechecks (stand)
- LOOM ~$373k, h1 +204, ~9.3k buys — prior FAIL (creatorBal 0, botty post-grad)
- ELON-SAN ~$132k — prior FAIL (whale/insiders)
- Tesla ~$122k, 0.20h — prior FAIL (age, creatorBal 0, no socials)
- ROADSTER ~$30k — prior FAIL
- GULP ~$18k, 0.31h, m5 +51 — prior FAIL stands (band+botty; not re-buying)
- POKESQUAD ~$15k — prior FAIL stands
- TCAT ~$11k — prior FAIL stands
- CatNose ~$8.6k (below floor), m5 −41 — dumping; prior FAIL
- Muskpad ~$19k, h1 −64 — dumping; prior FAIL
- EVERYTHING ~$35k graduated, h1 −17 — prior FAIL (creatorBal 0, band, Puter)
- PUMPKEYS ~$3.6k — dead; prior FAIL
- GALAX ~$4.1k — dead; prior FAIL
- CCAT / Optimus / Cloudboi / FMTR / Alex — priors stand / out of window or faded

## Decision
**NO-TRADE** — stay in SOL. **0** autopsy-clean PASS. Prefer SOL over marginal/cabal entries; LULU’s socials do not override an 11-wallet identical-SOL bundle.

## Kraken
Watch-only. Latest `/workspace/markets/snapshots.log` (2026-10-15 09:50 ET) still shows **USD ~$0.81** below min order — no proposal.


# ===== scout-0427.md =====

# Scout 0427 — 2026-10-16 04:27 ET

## Wallet
- `BXc3ju3m…` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0427.json`); SPL query 429-limited this run, but SOL unchanged and no buys since 01:33 → still dust USDC only, **no meme positions**.
- SOL ~$106.43 → est. total ~$31.67.

## Feeds
- boosts latest/top + profiles + CTOs + pf-live → `lists.txt`; scan.py **145 mints** → `scan-0427.out` / `cands-0427.json`.

## Strict in-window (age≤4h, mc≥$10k, h1>0, pump/pumpswap)
| Symbol | NEW? | mc | age_h | h1 | note |
|---|---|---|---|---|---|
| LOOM | prior | ~$312k | 1.56 | +150 | m5 −3; botty 8.7k buys — prior FAIL stands |
| EVERYTHING | prior | ~$62k | 0.64 | +50 | graduated; prior FAIL (creatorBal 0, band) stands |
| LULU | prior | ~$23k | 0.60 | +658 | prior BUNDLE FAIL stands |
| TURBO | **NEW** | ~$12k | 0.52 | +219 | autopsy **FAIL** |

## NEW autopsy
- TURBO / Turbo Boost `AgeZ7y4L6KhxXCVyvyrgFvmCPfaNWKbXbmd3hRRKpump` — FAIL: creatorBal **0**; 19×1–5% band (top10 ex-curve ~23%); socials are only status tweets (no project X); $53k h1 volume on ~$12k mc (churn). Mint/freeze null. `autopsy-raw-TURBO-0427.json` / `autopsy-summary-TURBO-0427.json`

## Decision
**NO-TRADE** — stay in SOL. Kraken: watch-only, no proposal (~$0.81 USD cash).


# ===== scout-0433.md =====

# Scout 0433 — 2026-10-16 04:33 ET

## Wallet
- `BXc3ju3m…` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0433.json`); SPL dust USDC only (~6e-06) → **no meme positions** (`wallet-spl-0433.json`). SOL unchanged since OPENSTOCK dump 01:33.
- SOL ~$106.51 → est. total ~$31.70.

## Feeds
- boosts latest/top + profiles + CTOs (7 via community-takeovers) + pf-live → `lists.txt`; scan.py **142 mints** → `scan-0433.out` / `cands-0433.json` (84 cands).
- expanded universe (extra dex: elon/tesla/roadster/musk/ai/brain/cat/dog/meme/grok/starman/optimus/spacex/neuron/puter/pokemon/gulp/dragon/turbo/…): **322 mints** → **310** pairs (`expanded-0433.json`). pf coins/for-you/mcap 404 — noted.

## Strict in-window (age≤4h, mc≥$10k, h1>0, pump/pumpswap)
| Symbol | NEW? | mc | age_h | h1 | note |
|---|---|---|---|---|---|
| LOOM | prior | ~$269k | 1.70 | +55 | m5 −24; botty ~8.4k buys — prior FAIL stands |
| ROADSTER | prior | ~$33k | 2.48 | +10 | prior FAIL stands (copycat / creatorBal 0 / whales) |
| GULP | prior | ~$30k | 0.59 | +414 | age gate cleared; **recheck FAIL** (see below) |
| LULU | prior | ~$22k | 0.74 | +651 | prior BUNDLE FAIL stands |
| TURBO | prior | ~$11k | 0.66 | +199 | prior FAIL stands (creatorBal 0, band, status tweets) |

## NEW autopsy
- **None** — 0 NEW in-window this cycle.

## Prior recheck
- GULP / Gulp `8BwEQTbuKD6DyHsr57FpF8L6RRvzr8Gm4TRMMqfbpump` — age now ~0.6h (past 30m). Recheck **FAIL**: creatorBal **0** (dev sold since 0409); 15×1–5% band; top10 ex-curve ~25%; botty ~1.95k buys/h on ~$30k mc; prior 0409 also flagged creator rugged history. Has real X @playgulpfun + playgulp.fun — not enough. `autopsy-raw-GULP-0433.json` / `autopsy-summary-GULP-0433.json` / `_holders-GULP-0433.json`

## Decision
**NO-TRADE** — stay in SOL. **0** autopsy-clean PASS. Prefer SOL over band/botty/dev-out structure even when age clears.

## Kraken
Watch-only. Latest `/workspace/markets/snapshots.log` (2026-10-15 09:50 ET) still shows **USD ~$0.81** below min order — no proposal.


# ===== scout-0442.md =====

# Scout 0442 — 2026-10-16 04:42 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0442.json`); SPL: dust USDC only (~6e-06) + zero USDT → **no meme positions** (`wallet-spl-0442.json`). SOL unchanged since OPENSTOCK dump 01:33 ET.
- SOL ~$106.56 (`sol-price-0442.json`) → est. total ~$31.71.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0442.json` / `profiles-*-0442.json`
- pump.fun currently-live 50 → `pf-live-0442.json` (+ `_pf-live-as-list-0442.json`)
- `lists.txt` rebuilt (5 lines, ~74 unique + pf-live)
- scan.py: **146 mints** → 88 cands (`scan-0442.out` / `cands-0442.json`)
- expanded narrative dex searches → **292** merged pairs (`expanded-0442.json`)

## In-window (age ≤4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| NEW | SpaceX | ~$392k | 0.05 | +784 | +784 | pumpswap | `vHRVLH6RDNee…pump` |
| PRIOR | LOOM | ~$204k | 1.85 | +26 | −19 | pumpswap | `7GCMYJcykHZ3…pump` |
| PRIOR | GULP | ~$25k | 0.73 | +327 | +46 | pumpfun | `8BwEQTbuKD6D…pump` |
| PRIOR | LULU | ~$23k | 0.88 | +670 | +2 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | Dragon | ~$12k | 0.96 | +118 | +32 | pumpfun | `9gG2evdn4HgP…pump` |

→ **5** in-window, **1** NEW, **0** autopsy-clean PASS (`inwindow-0442.json` / `new-0442.json`)

## NEW autopsy
### SpaceX `vHRVLH6RDNeeMhcAsyNifSBvSRFFv1PD5RwVTempump` — **FAIL**
- Phase: already **PumpSwap** ~$392k, pair age ~3m (post-grad spike).
- Age gate: **FAIL** (<30m).
- Creator `AANH2…` token bal **0** (RPC); deployer wallet ~602 SOL.
- RugCheck: score_norm 40; risks = High holder correlation (17) + **Copycat** (verified SpaceX symbol).
- Holders: **17** wallets with identical ~464072.557 amounts (bot/bundle dust). Funders ambiguous (many oldest-tx None / tiny 0.01 SOL) but identical amounts enough.
- Socials: none (PF `/coins/<mint>` 404).
- Artifacts: `autopsy-summary-SpaceX-0442.json`, `autopsy-raw-SpaceX-0442.json`, `_holders-SpaceX-0442.json`, `funders-SpaceX-0442.json`, `rugcheck-SpaceX-0442.json`, `dex-SpaceX-0442.json`

## Prior rechecks (light)
- **LOOM** (~$204k, botty ~8.2k buys/h) — prior FAIL stands (creatorBal 0 / churn / band).
- **GULP** (~$25k curve, 0.73h, h1 +327) — prior 0433 FAIL stands (creatorBal 0, band, botty).
- **LULU** — prior BUNDLE FAIL stands.
- **Dragon** — prior 0417 FAIL stands (creatorBal 0, band, no socials).

## Decision
**NO-TRADE** — stay in SOL (~0.2976). No autopsy-clean PASS suitable for 0.15–0.25 SOL size.

## Kraken
Watch-only. No material change assumed (~$0.81 USD below min from prior) — no proposal; no orders.



# ===== scout-0501.md =====

# Scout 0501 — 2026-10-16 05:01 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0501.json`); SPL: dust USDC only (~6e-06) + Token-2022 all zero → **no meme positions** (`wallet-spl-0501.json` / `wallet-t22-0501.json`). SOL unchanged since OPENSTOCK dump 01:33 ET.
- SOL ~$106.6 (`sol-price-0501.json`) → est. total ~$31.72.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0501.json` / `profiles-*-0501.json`
- pump.fun currently-live 49 → `pf-live-0501.json` (+ `_pf-live-as-list-0501.json`)
- `lists.txt` rebuilt (4 lines from boosts/profiles/CTO)
- scan.py: **146 mints** → 83 cands (`scan-0501.out` / `cands-0501.json`)
- expanded narrative dex searches + pf-live fill → **198** merged pairs (`expanded-0501.json`)

## In-window (age ≤4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | ROADSTER | ~$30k | 2.93 | +9 | −2 | pumpswap | `TB6QtGti9j2z…pump` |
| PRIOR | GULP | ~$16–25k | ~1.1 | +10..203 | −30 | pumpfun | `8BwEQTbuKD6D…pump` |
| PRIOR | SocialFrnk | ~$24–28k | 0.7 | +651..787 | +5..32 | pumpfun | `62tKjqdvzKrN…pump` |
| PRIOR | LULU | ~$23k | 1.2 | +10..15 | ~0 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | BDOG | ~$12–14k | 0.6 | +232..276 | −3..+10 | pumpfun | `G6NnKQTgN7Dm…pump` |
| PRIOR | TCAT | ~$13k | 2.6 | +27..65 | +44 | pumpfun | `34HExr1pEVFW…pump` |
| NEW | MemeTrace | ~$12–17k | 0.05–0.10 | +256..377 | spike | pumpfun | `HUARGQHB7ovb…pump` |
| NEW | MemeTrace | ~$6–12k | 0.06–0.13 | faded | −32 | pumpfun | `Aunf8ZYfEgRo…pump` |

→ **8** in-window at filter time, **2** NEW, **0** autopsy-clean PASS (`inwindow-0501.json` / `new-0501.json`)

## NEW autopsies
### MemeTrace `HUARGQHB7ovbPkUaYUmsqGBCLG4uHpCEr3q8zGcupump` — **FAIL**
- Phase: curve ~$12–17k, age **~6m** (<30m gate).
- Creator `6a29wP5C…` token bal **0** (RPC).
- Holders: **19×1–5% band**; top10 ex-curve ~22%.
- Funders: 2× share Axiom router dust; no clear 8+ same-funder block-0 bundle, but botty ntx=1000 wallets dominate.
- Socials: **none** (PF twitter/tg/web null; `/coins` empty-ish).
- Copycat: second concurrent MemeTrace mint live.
- Artifacts: `autopsy-summary-MemeTraceHUAR-0501.json`, `autopsy-raw-MemeTraceHUAR-0501.json`, `_holders-MemeTraceHUAR-0501.json`, `funders-MemeTraceHUAR-0501.json`, `rugcheck-MemeTraceHUAR-0501.json`, `dex-MemeTraceHUAR-0501.json`

### MemeTrace `Aunf8ZYfEgRozzi3ddBqu6bnAFgTVC882Ab2y4zVpump` — **FAIL**
- Phase: curve; mc **collapsed ~$6.1k** mid-autopsy (below $10k), age **~8m**, m5 **−32%**.
- Creator `G3p92QcW…` token bal **0**.
- Holders: **16×1–5% band**; top10 ex-curve ~22%.
- Funders: cabal hit `u6PJ8D…` (known from GALAX/prior); plus other sniper wallets.
- Socials: **none**. Copycat same symbol.
- Artifacts: `autopsy-summary-MemeTraceAunf-0501.json`, `autopsy-raw-MemeTraceAunf-0501.json`, `_holders-MemeTraceAunf-0501.json`, `funders-MemeTraceAunf-0501.json`, `rugcheck-MemeTraceAunf-0501.json`, `dex-MemeTraceAunf-0501.json`

## Prior rechecks (light)
- **SocialFrnk** (~$28k curve, 0.77h, h1 +787, m5 +32) — prior 0456 FAIL stands (creatorBal 0, 18× band, no socials). Momentum ≠ clean structure; not a post-grad dip hold.
- **GULP** (~$16k, m5 −30, still ~1.9k buys/h) — prior 0433 FAIL stands (creatorBal 0, band, botty); fading.
- **LULU** — prior BUNDLE FAIL stands (~$23k flat).
- **BDOG** (~$12k, sells>buys) — prior 0456 FAIL stands.
- **ROADSTER** / **TCAT** — prior FAILs stand; no post-grad 30–60% dip-and-hold setup.

## Decision
**NO-TRADE** — stay in SOL (~0.2976). No autopsy-clean PASS suitable for 0.15–0.25 SOL size.

## Kraken
Watch-only. Last snapshot (~Oct 15 09:50 ET) USD cash **$0.81** below min order — no proposal; no orders.


# ===== scout-0509.md =====

# Scout 0509 — 2026-10-16 05:09 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0509.json`); SPL: dust USDC only (~6e-06) + Token-2022 all zero → **no meme positions** (`wallet-spl-0509.json` / `wallet-t22-0509.json`). SOL unchanged since OPENSTOCK dump 01:33 ET.
- SOL ~$106.59 (`sol-price-0509.json`) → est. total ~$31.72.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0509.json` / `profiles-*-0509.json`
- pump.fun currently-live 50 → `pf-live-0509.json` (+ `_pf-live-as-list-0509.json`)
- `lists.txt` rebuilt (4 lines from boosts/profiles/CTO)
- scan.py: **145 mints** → cands (`scan-0509.out` / `cands-0509.json`)
- expanded narrative dex searches + pf-live fill → **207** merged pairs (`expanded-0509.json`)

## In-window (age ≤4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| NEW | GOAT11 | ~$163–175k | 0.61 | +267..292 | −3..+14 | pumpswap | `GjkMsvYmuFR37SyK…pump` |
| NEW | FSR | ~$63–65k | 0.49 | +50..54 | +11..25 | pumpswap | `HiKU8Lsa8aUFkhtC…pump` |
| PRIOR | MemeTrace | ~$24k | 0.20 | +580 | +10 | pumpfun | `HUARGQHB7ovbPkUa…pump` |
| PRIOR | LULU | ~$23k | 1.33 | +1.7 | — | pumpfun | `8DQzWohFEMWruKUC…pump` |
| NEW | Chase | ~$11–16k | 0.07 | +212..379 | spike | pumpfun | `9vz5mXmJnNjmC8on…pump` |
| NEW | SOL | ~$15k | 0.08 | +266 | +266 | pumpfun | `2ezhap3jauQous1Z…pump` |
| PRIOR | GULP | ~$14–16k | 1.17 | +37 | −5 | pumpfun | `8BwEQTbuKD6DyHsr…pump` |
| PRIOR | TCAT | ~$12k | 2.73 | +6 | −10 | pumpfun | `34HExr1pEVFWkx99…pump` |
| PRIOR | BDOG | ~$11k | 0.77 | +194 | −11 | pumpfun | `G6NnKQTgN7Dmo9yr…pump` |

→ **9** in-window at filter time, **4** NEW, **0** autopsy-clean PASS (`inwindow-0509.json` / `new-0509.json`)

## NEW autopsies
### GOAT11 `GjkMsvYmuFR37SyKnJoD8DwccLb3HKMQBnNe5Nqbpump` — **FAIL**
- Phase: **pumpswap post-grad** ~$168–175k; pair created **04:35 ET** (~40m age). Explicit no-chase after graduation spikes.
- Creator `BEWzEmGU…` token bal ~449k (~0.05%) OK; but unlocked LP still held by creator (~22% of LP).
- Holders: band_1_5 **3** OK; top10 ex-pool ~10.6% OK; graphInsiders 0.
- Volume: **~6.4k buys / 5.2k sells / ~$1.5M h1** on ~$170k mc → ~9× churn (botty).
- Funders: **2×** share cabal `5tzFki…` (known GALAX/POKESQUAD/Dragon); 6/12 checked wallets ntx≥1000.
- Socials: X/TG/site present, but X `@GOAT11SOL` **near-empty** (21 followers, 5 tweets; old 2014 handle, dormant/repurposed).
- Artifacts: `autopsy-summary-GOAT11-0509.json`, `autopsy-raw-GOAT11-0509.json`, `_holders-GOAT11-0509.json`, `funders-GOAT11-0509.json`, `rugcheck-GOAT11-0509.json`, `dex-GOAT11-0509.json`

### FSR / Flying Solana Roadster `HiKU8Lsa8aUFkhtCMWp3ySCcpZ899zEhRqzvEgnSpump` — **FAIL**
- Phase: pumpswap ~$63k, age **~0.5h** (≤30m gate borderline).
- Creator `7KocpDKH…` token bal **0**.
- Holders: **16×1–5% band**; top10 ex-pool ~24–27%; graphInsiders **4**.
- RugCheck score **13911** (Large LP Unlocked danger + Low Liquidity).
- Funders: cabal `5tzFki…` @ **~19.6 SOL** into a top holder; 8/12 ntx≥1000.
- Socials: **status-tweet only** (`x.com/solana/status/…`) + otcdesks.cash — not project socials.
- Artifacts: `autopsy-summary-FSR-0509.json`, `autopsy-raw-FSR-0509.json`, `_holders-FSR-0509.json`, `funders-FSR-0509.json`, `rugcheck-FSR-0509.json`, `dex-FSR-0509.json`

### Chase / Chase Chadwick `9vz5mXmJnNjmC8onX5tjfrRADuYYZXJ9qLkm1mWJpump` — **FAIL**
- Phase: curve; age **~5m** (<30m); mc faded ~$16k→~$10.5k mid-run.
- Creator `6o23RbWz…` token bal **0**.
- Holders: **11×1–5% band**; top10 ex-curve ~19%.
- Funders: cabal `u6PJ8D…` hit (known GALAX/MemeTrace).
- Socials: **none**.
- Artifacts: `autopsy-summary-Chase-0509.json`, `autopsy-raw-Chase-0509.json`, `_holders-Chase-0509.json`, `funders-Chase-0509.json`, `rugcheck-Chase-0509.json`, `dex-Chase-0509.json`

### SOL / tesla `2ezhap3jauQous1ZxS4LDq6cXv7NrDLQbziVkbSTpump` — **FAIL**
- Phase: curve ~$15k, age **~6m** (<30m); only 9 buys/5 sells h1.
- Creator `9BXEDSb…` token bal **0**; RugCheck **Creator history of rugged tokens** + single-holder ~51% + high concentration (score 30119).
- Copycat: name **tesla** / symbol **SOL**.
- totalHolders **3**; no socials.
- Artifacts: `autopsy-summary-SOL-0509.json`, `autopsy-raw-SOL-0509.json`, `_holders-SOL-0509.json`, `funders-SOL-0509.json`, `rugcheck-SOL-0509.json`, `dex-SOL-0509.json`

## Prior rechecks (light)
- **MemeTrace HUAR** (~$24k, 0.2h) — prior 0501 FAIL stands (age, creatorBal 0, band, no socials, copycat).
- **LULU** (~$23k flat) — prior BUNDLE FAIL stands.
- **GULP** (~$14–16k, m5 −5) — prior 0433 FAIL stands (creatorBal 0, band, botty); fading.
- **TCAT** / **BDOG** — prior FAILs stand; no clean post-grad 30–60% dip-and-hold setup.

## Decision
**NO-TRADE** — stay in SOL (~0.2976). No autopsy-clean PASS suitable for 0.15–0.25 SOL size. Closest structure (GOAT11) still fails hard on post-grad chase + botty churn + cabal funder + empty X.

## Kraken
Watch-only. Last snapshot (~Oct 15 09:50 ET) USD cash **$0.81** below min order — no proposal; no orders.

## Notes
- `frontend-api-v3.pump.fun/coins/{mint}` returned 404 for all NEW (same as 0501 run); creator/balance/socials taken from RugCheck + DexScreener. `currently-live` still works.


# ===== scout-0525.md =====

# Scout 0525 — 2026-10-16 05:25 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0525.json`); SPL: dust USDC only (~6e-06) + Token-2022 all zero → **no meme positions** (`wallet-spl-0525.json` / `wallet-t22-0525.json`). SOL unchanged since OPENSTOCK dump 01:33 ET.
- SOL ~$106.60 (`sol-price-0525.json`) → est. total ~$31.72.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0525.json` / `profiles-*-0525.json`
- pump.fun currently-live 49 → `pf-live-0525.json` (+ `_pf-live-as-list-0525.json`)
- `lists.txt` rebuilt (4 lines from boosts/profiles/CTO)
- scan.py: **148 mints** → cands (`scan-0525.out` / `cands-0525.json`)
- expanded narrative dex searches + pf-live fill → **137** merged pairs (`expanded-0525.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | GOAT11 | ~$188–200k | 0.86 | +337..365 | +17..38 | pumpswap | `GjkMsvYmuFR37SyK…pump` |
| PRIOR | LULU | ~$23k | 1.58 | +3.1 | ~0 | pumpfun | `8DQzWohFEMWruKUC…pump` |
| PRIOR | TCAT | ~$13–15k | 2.99 | +37..50 | −15..+14 | pumpfun | `34HExr1pEVFWkx99…pump` |
| PRIOR | BDOG | ~$11k | 1.02 | +2..29 | −12..−15 | pumpfun | `G6NnKQTgN7Dmo9yr…pump` |

→ **4** in-window, **0** NEW, **0** autopsy-clean PASS (`inwindow-0525.json` / `new-0525.json`)

## NEW autopsies
None — no NEW names cleared the strict in-window gate this cycle.

## Watch / excluded (not autopsied)
- **SLUDGE** / **DEER** (~$19k / ~$11k, age **0.30h / 0.37h**) — below 30m entry gate; noted in `watch-extra-0525.json` only.
- **GULP** (~$14k, 1.44h, h1 **−31**) — prior FAIL; excluded this cycle (h1≤0); fading.
- **ROADSTER** (~$36k PumpSwap, 3.34h, h1 ~+1) — prior FAIL; flat, not a clean leader dip.

## Prior rechecks (light)
- **GOAT11** (~$188–200k, 0.86h) — still FAIL: post-grad chase + **botty ~14.5k tx/h** (7937/6640) + prior cabal `5tzFki…` + empty X. Structure fails stand (`autopsy-summary-GOAT11-0509.json`).
- **LULU** (~$23k flat) — prior **BUNDLE** FAIL stands (`autopsy-summary-LULU-0417.json`).
- **TCAT** / **BDOG** — prior FAILs stand; no clean post-grad 30–60% dip-and-hold setup.

## Decision
**NO-TRADE** — stay in SOL (~0.2976). Zero NEW autopsy candidates; all in-window names are prior structural FAILs that did not materially improve.

## Kraken
Watch-only. Last known USD cash **~$0.81** below min order — no proposal; no orders.


# ===== scout-0531.md =====

# Scout 0531 — 2026-10-16 05:31 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0531.json`); SPL: dust USDC only (0.000006) + USDT 0; Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0531.json` / `wallet-t22-0531.json`). Unchanged since 01:33 ET.
- SOL ~$106.59 (CoinGecko, `sol-price-0531.json`) → est. total ~$31.72.

## Feeds
- DexScreener boosts latest/top (29+30), profiles latest (30), community-takeovers (8) → `boosts-*-0531.json` / `profiles-*-0531.json`
- pump.fun currently-live 49 → `pf-live-0531.json`
- `lists.txt` rebuilt (4 lines)
- scan.py: **147 mints** → 82 cands (`scan-0531.out` / `cands-0531.json`)
- expanded (lists + pf-live + priors/watch + narrative searches) → **238 mints / 224 pairs** (`expanded-0531.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | GOAT11 | ~$185k | 0.96 | +330 | −0.5 | pumpswap | `GjkMsvYmuFR37SyK…pump` |
| PRIOR | ROADSTER | ~$36k | 3.42 | +9 | −0.6 | pumpswap | `TB6QtGti9j2zadAr…pump` |
| PRIOR | LULU | ~$23k | 1.68 | +3.9 | +0.3 | pumpfun | `8DQzWohFEMWruKUC…pump` |
| PRIOR | TCAT | ~$19k | 3.09 | +137 | +32 | pumpfun | `34HExr1pEVFWkx99…pump` |
| PRIOR | BDOG | ~$12k | 1.12 | +18 | +8.6 | pumpfun | `G6NnKQTgN7Dmo9yr…pump` |

→ **5** in-window, **0** NEW, **0** autopsy-clean PASS (`inwindow-0531.json` / `new-0531.json` / `_prior-rejects-0531.json`)

## NEW autopsies
None — no NEW names in window.

## SLUDGE / DEER (from watch-extra-0525)
Still **under 30m** by DexScreener pairCreatedAt (pump.fun `/coins/{mint}` 404s): DEER **0.46h** (~$11.5k, h1 +202), SLUDGE **0.38h** (~$12.7k, h1 +265, m5 **−34**, off ~$19k). Not in window. RugCheck pre-screen (`rc-DEER-0531.json` / `rc-SLUDGE-0531.json`) already shows standard fail flags on both: **creatorBal 0**, **19×1–5% holder band**, top10 ex-curve ~26% (DEER) / ~22% (SLUDGE), no insiders flagged. Expect FAIL when they age in.
- GITPAID `2MdBA1Yiy3oC…pump` (~$20k, 0.30h, h1 +450) — too young; noted in `watch-extra-0531.json`.

## Prior rechecks (light)
- **TCAT** (~$19k, 3.09h, h1 +137 / m5 +32 — the only material move) — RugCheck recheck (`rc-TCAT-0531.json`): creatorBal **0**, 19×1–5% band, top10 ex-curve ~21%, 256 holders. Still FAIL; also >3h and not the narrative leader.
- **GOAT11** (~$185k, ~15.9k tx/h botty) — FAIL stands (post-grad chase, botty, cabal `5tzFki…`, empty X).
- **ROADSTER** `TB6Q…` — FAIL stands (copycat, creatorBal 0, 26 insiders, whale ~25%; `autopsy-summary-ROADSTER-0311.json`).
- **LULU** (BUNDLE) / **BDOG** (creatorBal 0, band; h1 sells>buys 436/271) — FAILs stand.

## Decision
**NO-TRADE** — stay in SOL (~0.2976). Zero NEW candidates; all in-window names are prior structural FAILs.

## Kraken
Watch-only. Last known USD cash ~$0.81 below min order — no proposal; no orders.


# ===== scout-0538.md =====

# Scout 0538 — 2026-10-16 05:38 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0538.json`); SPL: dust USDC only (0.000006) + USDT 0; Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0538.json` / `wallet-t22-0538.json`). Unchanged since 01:33 ET.
- SOL ~$106.53 (CoinGecko, `sol-price-0538.json`) → est. total ~$31.70.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0538.json` / `profiles-*-0538.json`
- pump.fun currently-live 48 → `pf-live-0538.json`
- `lists.txt` rebuilt (4 lines)
- scan.py: **143 mints** → 82 cands (`scan-0538.out` / `cands-0538.json`)
- expanded (lists + pf-live + priors/watch + narrative searches) → **305 mints / 285 pairs** (`expanded-0538.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | GOAT11 | ~$210k | 1.09 | +165 | +10.6 | pumpswap | `GjkMsvYmuFR37SyK…pump` |
| NEW | Deer | ~$44k | 1.18 | +76 | −5.9 | pumpswap | `4tf5GEXU1dt7Vfj2…Deer` |
| PRIOR | ROADSTER | ~$36k | 3.55 | +5.9 | +0.3 | pumpswap | `TB6QtGti9j2zadAr…pump` |
| PRIOR | LULU | ~$24k | 1.81 | +4.6 | +0.5 | pumpfun | `8DQzWohFEMWruKUC…pump` |
| PRIOR | TCAT | ~$19k | 3.22 | +130 | +5.6 | pumpfun | `34HExr1pEVFWkx99…pump` |
| PRIOR | SOL | ~$15k | 0.56 | +266 | — | pumpfun | `2ezhap3jauQous1Z…pump` |
| PRIOR | BDOG | ~$13k | 1.25 | +18 | +1.5 | pumpfun | `G6NnKQTgN7Dmo9yr…pump` |
| NEW | DEER | ~$11k | 0.59 | +182 | −5.8 | pumpfun | `DYhpuvytVM4SCiR5…pump` |

→ **8** in-window, **2** NEW, **0** autopsy-clean PASS (`inwindow-0538.json` / `new-0538.json` / `_prior-rejects-0538.json`)

## NEW autopsies
### Deer `4tf5GEXU1dt7Vfj21oCu4P96ZEKEm3zMYqpzZsoCDeer` — **FAIL**
- The Kafkaesque Deer — PumpSwap ~$44k, 1.18h, h1 +76 / m5 −5.9, ~717/605 buys/sells.
- creatorBal **0**; **19×** 1–5% holder band; top10 ex-pool **~27.6%**; cabal `5tzFki…` hits ≥1 top holder.
- Socials: X community link + Instagram reel only (same IG as DEER). Post-grad chase.
- `autopsy-raw-Deer-0538.json` / `autopsy-summary-Deer-0538.json` / `_funders-Deer-0538.json`

### DEER `DYhpuvytVM4SCiR56q8oz4nXAN2BPFaYnxVftS9wpump` — **FAIL**
- Deer In Subway — aged in from watch-extra-0531 (was 0.46h). Curve ~57% bonding, ~$10.8k, 0.59h, h1 +182 / m5 −5.8.
- creatorBal **0**; **19×** 1–5% band; top10 ex-curve ~23.8%; status-tweet + same IG reel as Deer (copycat cluster; shared wallets VJSDW6S7 / 3VwmH9qY).
- Confirms prior RC pre-screen. `autopsy-raw-DEER-0538.json` / `autopsy-summary-DEER-0538.json` / `_funders-DEER-0538.json`

## Young watch (<30m) — `watch-extra-0538.json`
- **Irene** `6Vdc…pump` (~$80k PumpSwap, 0.29h, m5 +89) — RC FAIL-likely: creatorBal 0, band 14, 4 graphInsiders, post-grad chase. Do not buy.
- **GITPAID** `2MdBA…pump` (~$11k, 0.45h) — RC FAIL-likely: creatorBal≈0, band 15, top10ex ~29%.
- **BOUNCER / TRELLIS / Womb / Chase** — noted in young raw; not fully screened.
- **SLUDGE** (~$8.3k, 0.53h, m5 −26) — age past 30m but mc <$10k (excluded); still dumping; RC creatorBal 0 + band 19.

## Prior rechecks (light)
- **GOAT11** (~$210k, m5 +10.6, still ~1.3k tx/h) — RC recheck (`rc-GOAT11-0538.json`): prior FAIL stands (post-grad botty, cabal, empty X). creatorBal residual tiny; band 5; structure not clean enough + already chased.
- **TCAT** (~$19k, 3.22h, h1 +130 / m5 +5.6) — prior FAIL stands (creatorBal 0, 19× band); >3h not narrative leader.
- **ROADSTER / LULU / BDOG / SOL** — prior FAILs stand (copycat/BUNDLE/creatorBal 0 / age-gate FAIL at 0509).

## Decision
**NO-TRADE** — stay in SOL (~0.2976). Both NEW autopsies FAIL (creatorBal 0 + sniper bands / copycat deer cluster). No clean PASS.

## Kraken
Watch-only. Last known USD cash ~$0.81 below min order — no proposal; no orders.


# ===== scout-0551.md =====

# Scout 0551 — 2026-10-16 05:51 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0551.json`); SPL: dust USDC only (0.000006) + USDT 0; Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0551.json` / `wallet-t22-0551.json`). Unchanged since 01:33 ET.
- SOL ~$106.41 (CoinGecko, `sol-price-0551.json`) → est. total ~$31.67.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0551.json` / `profiles-*-0551.json`
- pump.fun currently-live 46 → `pf-live-0551.json`
- `lists.txt` rebuilt (4 lines)
- scan.py: **147 mints** → 89 cands (`scan-0551.out` / `cands-0551.json`)
- expanded (lists + pf-live + priors/watch + narrative searches) → **622 mints / 603 pairs** (`expanded-0551.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | Irene | ~$118k | 0.56 | +180 | -20.79 | pumpswap | `6VdcMnBTCj4tJVwt…pump` |
| PRIOR | ROADSTER | ~$37k | 3.83 | +10.4 | — | pumpswap | `TB6QtGti9j2zadAr…pump` |
| PRIOR | FSR | ~$35k | 1.25 | +72.4 | -14.11 | pumpswap | `HiKU8Lsa8aUFkhtC…pump` |
| PRIOR | Deer | ~$34k | 1.46 | +147 | -11.62 | pumpswap | `4tf5GEXU1dt7Vfj2…Deer` |
| PRIOR | TCAT | ~$25k | 3.50 | +200 | +12.65 | pumpfun | `34HExr1pEVFWkx99…pump` |
| PRIOR | LULU | ~$24k | 2.09 | +1.24 | — | pumpfun | `8DQzWohFEMWruKUC…pump` |
| NEW | TRELLIS | ~$21k | 0.59 | +526 | -34.32 | pumpfun | `4VucxZWxDstE6at1…pump` |
| PRIOR | GITPAID | ~$19k | 0.71 | +415 | +45.38 | pumpfun | `2MdBA1Yiy3oCFmwy…pump` |
| PRIOR | SOL | ~$15k | 0.84 | +266 | — | pumpfun | `2ezhap3jauQous1Z…pump` |
| NEW | Womb | ~$13k | 0.68 | +309 | -28.31 | pumpfun | `BxUHuVGyP9kKRoJZ…pump` |

→ **10** in-window, **2** NEW, **0** autopsy-clean PASS (`inwindow-0551.json` / `new-0551.json` / `_prior-rejects-0551.json`)

## NEW autopsies
### TRELLIS `4VucxZWxDstE6at1ZhpjkDYfBejPcaHoKfupHzV4pump` — **FAIL**
- trellistools — pumpfun curve ~49.2% (~41.842590028 SOL), ~$15,322, 0.58h, h1 +367 / m5 -46.74.
- FAIL: creatorBal 0 (dev sold/out)
- FAIL: 19× wallets in 1–5% band (sniper/distribution pattern)
- FAIL: no socials on DexScreener; empty RC description
- FAIL: botty churn ~2262 tx/h on ~$15,322 mc
- FAIL: m5 -46.74% dumping
- creatorBal **0**; **19×** 1–5% band; top10ex ~18.37%; holders 561.
- `autopsy-raw-TRELLIS-0551.json` / `autopsy-summary-TRELLIS-0551.json` / `_funders-TRELLIS-0551.json` / `rc-TRELLIS-0551.json`

### Womb `BxUHuVGyP9kKRoJZ5h8LvWamCZNCTZcMasUxp9Pjpump` — **FAIL**
- Womb — pumpfun curve ~40.4% (~34.330240866 SOL), ~$13,398, 0.67h, h1 +321 / m5 -11.7.
- FAIL: creatorBal residual ~0.012% (effectively out)
- FAIL: 18× wallets in 1–5% band (sniper/distribution pattern)
- FAIL: graphInsiders 4
- FAIL: no socials on DexScreener; empty RC description
- FAIL: botty churn ~2194 tx/h on ~$13,398 mc
- creatorBal residual ~0.0119%; **18×** 1–5% band; graphInsiders **4**; top10ex ~23.6%; holders 536.
- `autopsy-raw-Womb-0551.json` / `autopsy-summary-Womb-0551.json` / `_funders-Womb-0551.json` / `rc-Womb-0551.json`

## Young watch (<30m) — `watch-extra-0551.json`
- **Crow** `6pub1XbJn779…` (~$17.9k, 0.26h, pumpfun, h1 +398, m5 21.27)
- **BOUNCER** `6X3cMFWWNQSV…` (~$159.6k, 0.36h, pumpswap, h1 +1505, m5 53.76) — post-grad chase <$30m; do not buy blind
- **Irene** `2xZjZSFkuFvT…` (~$21.4k, 0.37h, pumpswap, h1 +127, m5 27.29) — different mint from prior Irene; still <30m
- **BOUNCER** `EiSW6PbKGxdx…` (~$16.2k, 0.46h, pumpfun, h1 +379, m5 27.19)
- **Chase** `YwCKitMEdf7n…` (~$13.2k, 0.48h, pumpfun, h1 +227, m5 -5.56) — prior FAIL theme / watch
- **BOUNCER** `EFxr7QmqvoDB…` (~$12.5k, 0.48h, pumpfun, h1 +272, m5 38.19)
- **ElonThrust** `pFibPnQk8ekC…` (~$729.5k, 0.49h, pumpswap, h1 +1547, m5 14.56) — huge post-grad spike; age gate

## Prior rechecks (light)
- **Irene** `6Vdc…pump` (~$102k PumpSwap, aged into window ~0.51h, m5 −16.6) — RC recheck (`rc-Irene-recheck-0551.json` / `rc-Irene-0551.json`): creatorBal **0**; **12** graphInsiders; band 10; prior FAIL-likely **stands**.
- **GITPAID** (~$19k, m5 +45) — prior FAIL stands (top10ex ~31%, high churn); price action bounce does not clear structure. `rc-GITPAID-0546.json`
- **FSR** (~$35k, m5 −14) / **Deer** (~$34k, m5 −12) / **TCAT** (~$25k) / **LULU** (BUNDLE) / **ROADSTER** / **SOL** — prior FAILs stand.
- **GOAT11 / BDOG** — dropped out of in-window this pass (h1≤0 or mc/age filter); prior FAILs stand if they return.

## Decision
**NO-TRADE** — stay in SOL (~0.2976). Both NEW autopsies FAIL (creatorBal 0/residual + sniper bands / insiders / no socials / botty + dumps). No clean PASS.

## Kraken
Watch-only. Last known USD cash ~$0.81 below min order — no proposal; no orders.


# ===== scout-0603.md =====

# Scout 0603 — 2026-10-16 06:03 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0603.json`); SPL: dust USDC only (0.000006) + 1 zero acct; Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0603.json` / `wallet-t22-0603.json`). Unchanged since 01:33 ET.
- SOL ~$105.98 (CoinGecko, `sol-price-0603.json`) → est. total ~$31.54.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0603.json` / `profiles-*-0603.json`
- pump.fun currently-live 48 → `pf-live-0603.json`; pump.fun sorted lists (mcap/last-trade/created) → `pf-sorted-0603.json`
- `lists.txt` rebuilt (4 lines)
- scan.py: **144 mints** → `scan-0603.out` / `cands-0603.json`
- expanded (lists + pf-live + pf-sorted + priors/watch + narrative searches, `expand0603.py`) → **443 mints / 424 pairs** (`expanded-0603.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| NEW | ElonThrust | ~$816k | 0.60 | +1741 | +2.35 | pumpswap | `pFibPnQk8ekCCtuB…pump` |
| PRIOR | Irene | ~$86k | 0.67 | +114 | -10.3 | pumpswap | `6VdcMnBTCj4tJVwt…pump` |
| PRIOR | CCAT | ~$53k | 3.83 | +1.04 | -9.01 | pumpswap | `D4rzv9WAXJh9QZw1…pump` |
| PRIOR | Deer | ~$34k | 1.57 | +141 | -11.61 | pumpswap | `4tf5GEXU1dt7Vfj2…Deer` |
| PRIOR | ROADSTER | ~$32k | 3.95 | +7.5 | — | pumpswap | `TB6QtGti9j2zadAr…pump` |
| PRIOR | LULU | ~$24k | 2.20 | +1.08 | -0.01 | pumpfun | `8DQzWohFEMWruKUC…pump` |
| PRIOR | TCAT | ~$18k | 3.61 | +45 | -14.78 | pumpfun | `34HExr1pEVFWkx99…pump` |
| NEW | YERN | ~$17k | 0.58 | +414 | -8.03 | pumpfun | `PdtREY9H6Fp9jVMp…yern` |
| PRIOR | SOL | ~$15k | 0.96 | +266 | — | pumpfun | `2ezhap3jauQous1Z…pump` |
| NEW | TCAT (2nd mint) | ~$14k | 1.68 | +188 | +18.39 | pumpfun | `6ZDKgWopksQPMBPQ…pump` |
| NEW | Chase | ~$13k | 0.59 | +229 | -13.98 | pumpfun | `YwCKitMEdf7nagej…pump` |
| PRIOR | Womb | ~$12k | 0.79 | +289 | +16.88 | pumpfun | `BxUHuVGyP9kKRoJZ…pump` |
| PRIOR | GITPAID | ~$11k | 0.83 | +201 | +51.27 | pumpfun | `2MdBA1Yiy3oCFmwy…pump` |

→ **13** in-window, **4** NEW, **0** autopsy-clean PASS (`inwindow-0603.json` / `new-0603.json` / `_prior-rejects-0603.json`)

## NEW autopsies
### ElonThrust `pFibPnQk8ekCCtuBoQFJqeJjHVo92dAME3uH8A4pump` — **FAIL**
- ElonThruster — graduated → PumpSwap (liq ~$76k), ~$815k, 0.60h, h1 +1740 / m5 +2.3.
- FAIL: post-grad blind chase (~$815k after +1740% h1)
- FAIL: single non-pool wallet `CkWRijad…` (system acct, 20.1 SOL) holds **14.06%**
- FAIL: creatorBal 0; deployer `G8thC28H…` is 1.5h-old, 673 tx, now holds 11.6 SOL (dev sold)
- FAIL: RC "High holder correlation" (score 30)
- FAIL: fake volume — ~13.6k tx/h for ~$60k h1 vol (~$4/tx micro-churn)
- FAIL: X @melissa31zb9 created 2026-10-03, 2 followers, 1 tweet; no website
- top10ex ~15.1% (incl. 14.06% whale); band 1; holders 2270.
- `autopsy-raw-ElonThrust-0603.json` / `autopsy-summary-ElonThrust-0603.json` / `funders-ElonThrust-0603.json` / `rc-ElonThrust-0603.json`

### YERN `PdtREY9H6Fp9jVMpG36aywtCgxTtsQZetmehKqgyern` — **FAIL**
- yern.fun — pumpfun curve (Printr-config; curve acct holds 38.65% of supply, SOL reserve not readable via lamports), ~$16.7k, 0.58h, h1 +414 / m5 -8.
- FAIL: creatorBal 0 (creator = fee-share PDA, 0.006 SOL)
- FAIL: **19×** wallets in 1–5% band on only 149 holders
- FAIL: holder `4qFGc44W` (2.03%) funded by known cabal `5tzFki…`
- FAIL: X @yerndotfun created 2026-10-14 (24 foll / 10 tweets) — brand-new
- top10ex ~23.2%; graphInsiders 0; RC score 1.
- `autopsy-raw-YERN-0603.json` / `autopsy-summary-YERN-0603.json` / `funders-YERN-0603.json` / `rc-YERN-0603.json`

### TCAT (2nd mint) `6ZDKgWopksQPMBPQvmdZrP13JEPApbNrSUQLPPbQpump` — **FAIL**
- Tesla Roadster Cat — pumpfun curve (Printr-config; curve acct holds 43.53%), ~$13.7k, 1.68h, h1 +188 / m5 +18.
- FAIL: creatorBal 0; deployer `FB5p7woP…` burner (6 tx, 0 SOL)
- FAIL: **19×** 1–5% band on only 73 holders
- FAIL: top10ex ~27.0% (at limit)
- FAIL: copycat of prior-FAIL TCAT theme; X-community link only; thin ($9.6k h1 vol)
- `autopsy-raw-TCAT2-0603.json` / `autopsy-summary-TCAT2-0603.json` / `funders-TCAT2-0603.json` / `rc-TCAT2-0603.json`

### Chase `YwCKitMEdf7nagejZbvpDvxDui5CdoQ3NuJsE5Tpump` — **FAIL**
- Chase Chadwick — pumpfun curve ~38.9% (~33.066 SOL), ~$13.3k, 0.59h, h1 +229 / m5 -14.
- FAIL: creatorBal 0 (creator fee-share PDA)
- FAIL: fresh wallet `RuYU2iRM…` (1 tx, created at launch) holds **5.64%** — linked/sniper bag
- FAIL: **15×** 1–5% band
- FAIL: botty churn ~1.9k tx/h, ~$78k h1 vol on ~$13k mc; m5 -14 fading
- FAIL: socials = link to third-party tweet (@Humanevolvd, 33k foll.) only; no project X
- top10ex ~23.9%; graphInsiders 0. (Different mint from prior FAIL Chase `9vz5…`.)
- `autopsy-raw-Chase-0603.json` / `autopsy-summary-Chase-0603.json` / `funders-Chase-0603.json` / `rc-Chase-0603.json`

## Young watch (<30m) — `watch-extra-0603.json`
- **CSF** `DDw2yrhhZNCp…` (~$11.3k, 0.08h) / **CSF** `6aNXLr6d9m2g…` (~$18.1k, 0.23h, m5 −31) — twin-mint pair, likely copy war
- **NEBULA** `CaGJEqcDsyUr…` (~$11.3k, 0.11h)
- **Irene** `5j7gTphd94qD…` (~$28.8k, 0.11h, pumpswap) / **Irene** `2xZjZSFkuFvT…` (~$22.5k, 0.48h, pumpswap) — copycats of prior-FAIL Irene
- **BOUNCER** `6X3cMFWWNQSV…` (~$188.6k, 0.47h, pumpswap, h1 +1797) — post-grad chase; do not buy blind

## Prior rechecks (light)
- No prior materially improved: Irene ~$86k (down from ~$102k, m5 −10); Womb ~$12.4k (mc down, m5 bounce only); GITPAID ~$10.9k (down from ~$19k, m5 +51 bounce); TCAT ~$17.7k (down); Deer / CCAT / ROADSTER / LULU / SOL flat-to-down — prior FAILs stand.
- TRELLIS dropped out of in-window (h1/mc filter).

## Decision
**NO-TRADE** — stay in SOL (~0.2976). All 4 NEW autopsies FAIL (post-grad whale/botty ElonThrust; creatorBal 0 + 15–19× sniper bands on YERN/TCAT/Chase, plus cabal funder / fresh 5.6% wallet / brand-new socials). No clean PASS.

## Kraken
Watch-only. Last known USD cash ~$0.81 below min order — no proposal; no orders.


# ===== scout-0613.md =====

# Scout 0613 — 2026-10-16 06:13 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0613.json`); SPL: dust USDC only (0.000006) + 1 zero acct; Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0613.json` / `wallet-t22-0613.json`). Unchanged since 01:33 ET.
- SOL ~$105.77 (CoinGecko, `sol-price-0613.json`) → est. total ~$31.48.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0613.json` / `profiles-*-0613.json`
- pump.fun currently-live 48 → `pf-live-0613.json`; pump.fun sorted lists (mcap/last-trade/created) → `pf-sorted-0613.json`
- `lists.txt` rebuilt (4 lines)
- scan.py: **144 mints** → `scan-0613.out` / `cands-0613.json`
- expanded (lists + pf-live + pf-sorted + priors/watch + narrative searches, `expand0613.py`) → **444 mints / 425 pairs** (`expanded-0613.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | ElonThrust | ~$861k | 0.78 | 1851 | 2.55 | pumpswap | `pFibPnQk8ekCCtuB…pump` |
| NEW | BOUNCER | ~$257k | 0.65 | 2485 | — | pumpswap | `6X3cMFWWNQSV2pdK…3rmg` |
| PRIOR | LOOM | ~$130k | 3.35 | 13.14 | -1.84 | pumpswap | `7GCMYJcykHZ3qJH3…pump` |
| PRIOR | Irene | ~$95k | 0.85 | 137 | 38.61 | pumpswap | `6VdcMnBTCj4tJVwt…pump` |
| PRIOR | Deer | ~$42k | 1.75 | 103 | 7.78 | pumpswap | `4tf5GEXU1dt7Vfj2…Deer` |
| NEW | Irene | ~$30k | 0.66 | 221 | 22.23 | pumpswap | `2xZjZSFkuFvTef55…ThJ3` |
| PRIOR | LULU | ~$24k | 2.39 | 1.43 | 0.53 | pumpfun | `8DQzWohFEMWruKUC…pump` |
| PRIOR | Chase | ~$20k | 0.77 | 395 | 29.35 | pumpfun | `YwCKitMEdf7nagej…pump` |
| PRIOR | TCAT | ~$18k | 3.79 | 36.98 | -19.29 | pumpfun | `34HExr1pEVFWkx99…pump` |
| PRIOR | YERN | ~$15k | 0.77 | 370 | 16.24 | pumpfun | `PdtREY9H6Fp9jVMp…yern` |
| PRIOR | BDOG | ~$13k | 1.83 | 24.25 | -0.06 | pumpfun | `G6NnKQTgN7Dmo9yr…pump` |
| PRIOR | GITPAID | ~$12k | 1.01 | 243 | 19.98 | pumpfun | `2MdBA1Yiy3oCFmwy…pump` |
| PRIOR | TCAT | ~$12k | 1.86 | 158 | -17.62 | pumpfun | `6ZDKgWopksQPMBPQ…pump` |
| PRIOR | EVERYTHING | ~$12k | 2.43 | 7.77 | -0.59 | pumpswap | `DZVADw7Qkfqg2mqQ…pump` |
| PRIOR | SocialFrnk | ~$12k | 1.9 | 2.2 | -11.55 | pumpfun | `62tKjqdvzKrNHb8K…pump` |
| NEW | PITBULL | ~$11k | 2.75 | 53.36 | 13 | pumpfun | `Gmh5hNtCycP6YSyU…pump` |

→ **16** in-window, **3** NEW, **0** autopsy-clean PASS (`inwindow-0613.json` / `new-0613.json` / `_prior-rejects-0613.json`)

## NEW autopsies
### BOUNCER `6X3cMFWWNQSV2pdK5nLyGfNvGUXV6oar45xusbSV3rmg` — **FAIL**
- BOUNCER — graduated PumpSwap (liq $0), ~$257k, 0.7h, h1 +2485 / m5 None.
- FAIL: post-grad blind chase (~$257k after h1 +2485)
- FAIL: top10ex ~89.4% (>30%)
- FAIL: creator holds 9.69% (>5% linked/dev)
- FAIL: single wallet Gw3MQNQE… holds 73.60%
- FAIL: RC risks: Top 10 holders high ownership, Single holder ownership, Low Liquidity, High ownership (score 20791)
- FAIL: no socials / no website
- creator `7atkTMsN…` age 0.68h, 96 tx, now 0.0015 SOL (funded ~95.6 SOL at launch).
- whale `Gw3MQNQE…` holds 73.60% with ~11.69 SOL.
- top10ex ~89.39%; RC score 20791; holders 2063.
- `autopsy-raw-BOUNCER-0613.json` / `autopsy-summary-BOUNCER-0613.json` / `funders-BOUNCER-0613.json` / `rc-BOUNCER-0613.json`

### Irene (2nd mint) `2xZjZSFkuFvTef55EWVrvapihgVwTgrfHFnAfU9aThJ3` — **FAIL**
- Irene The Orangutan — graduated PumpSwap (liq $33319.18), ~$30k, 0.71h, h1 +221 / m5 26.7.
- FAIL: creatorBal 0 (no visible dev bag / fee-share or dumped)
- FAIL: 8× wallets in 1–5% band
- FAIL: botty churn ~4051 tx/h on ~$30k mc (volh1 $128527.13)
- FAIL: no socials / no website
- FAIL: copycat of prior-FAIL Irene theme (different mint)
- top10ex ~13.04%; band_1_5 8; holders 2100; RC score 11400.
- `autopsy-raw-Irene2-0613.json` / `autopsy-summary-Irene2-0613.json` / `funders-Irene2-0613.json` / `rc-Irene2-0613.json`

### PITBULL `Gmh5hNtCycP6YSyU1Cd4Q77oDL9BdgoBoTWcSMvQpump` — **FAIL**
- Pitbull At Barber — pumpfun curve (curve/AMM+locker ~49.1%: Pump Fun:49.13%), ~$11.3k, 2.79h, h1 +53.36 / m5 13.
- FAIL: creatorBal 0 (no visible dev bag / fee-share or dumped)
- FAIL: 19× wallets in 1–5% band (sniper/distribution pattern) on 103 holders
- FAIL: graphInsiders 14
- FAIL: socials = X-community link only (https://x.com/i/communities/2022855185475764628)
- FAIL: shared funder 9iHgaD24… on 2 top holders (bundle signal)
- deployer `8NZkwtXm…` burner-ish (15 tx, 0.000650254 SOL, age 2.01h).
- top10ex ~24.84%; band_1_5 19; graphInsiders 14; holders 103.
- `autopsy-raw-PITBULL-0613.json` / `autopsy-summary-PITBULL-0613.json` / `funders-PITBULL-0613.json` / `rc-PITBULL-0613.json`

## Young watch (<30m) — `watch-extra-0613.json`
- **uıoɔ** `32yWxejbNvdX…` (~$32.8k, 0.06h, h1 +715, m5 715) — garbled ticker; skip
- **CHAIR** `3jWCPoGE8GBB…` (~$30.1k, 0.21h, h1 +608, m5 63.23) — too young (<30m)
- **CSF** `DDw2yrhhZNCp…` (~$10.2k, 0.26h, h1 +126, m5 -38.94) — twin-mint CSF still young/fading
- **Irene** `5j7gTphd94qD…` (~$63.1k, 0.29h, h1 +596, m5 36.7) — copycat of prior-FAIL Irene; do not buy
- **CSF** `6aNXLr6d9m2g…` (~$13.1k, 0.41h, h1 +225, m5 -11.74) — twin-mint CSF still young/fading

## Prior rechecks (light)
- No prior materially improved structurally:
  - ElonThrust ~$861k (still post-grad whale/botty; prior FAIL stands)
  - Irene `6Vdc…` ~$95k (m5 +39 bounce only; creatorBal 0 + insiders FAIL stands)
  - Chase `YwCK…` ~$20k (m5 +29 bounce; fresh 5.6% wallet + band FAIL stands)
  - YERN / TCAT×2 / Deer / LULU / BDOG / GITPAID / SocialFrnk / EVERYTHING / LOOM — prior FAILs stand
- LOOM re-entered in-window (~$130k, 3.35h) — prior FAIL (insiders/structure) unchanged; not re-autopsied.
- CCAT / ROADSTER / SOL / Womb / TRELLIS dropped out of in-window this pass.

## Decision
**NO-TRADE** — stay in SOL (~0.2976). All 3 NEW autopsies FAIL (BOUNCER post-grad 73.6% whale + 9.7% creator; Irene2 copycat + creatorBal 0 + botty; PITBULL creatorBal 0 + 19× band + graphInsiders 14 + shared funder). No clean PASS.

## Kraken
Watch-only. Last known USD cash ~$0.81 below min order — no proposal; no orders.


# ===== scout-0622.md =====

# Scout 0622 — 2026-10-16 06:22 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0622.json`); SPL: dust USDC only (0.000006) + 1 zero acct; Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0622.json` / `wallet-t22-0622.json`). Unchanged since 01:33 ET.
- SOL ~$105.97 (CoinGecko, `sol-price-0622.json`) → est. total ~$31.54.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0622.json` / `profiles-*-0622.json`
- pump.fun currently-live 50 → `pf-live-0622.json`; pump.fun sorted lists (mcap/last-trade/created) → `pf-sorted-0622.json`
- `lists.txt` rebuilt (4 lines)
- scan.py: **144 mints** → `scan-0622.out` / `cands-0622.json` (80 cands)
- expanded (lists + pf-live + pf-sorted + priors/watch + narrative searches, `expand0622.py`) → **442 mints / 422 pairs** (`expanded-0622.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | ElonThrust | ~$897k | 0.91 | 1934 | 2.38 | pumpswap | `pFibPnQk8ekCCtuB…pump` |
| PRIOR | BOUNCER | ~$257k | 0.78 | 2485 | — | pumpswap | `6X3cMFWWNQSV2pdK…3rmg` |
| PRIOR | LOOM | ~$170k | 3.48 | 98.83 | 8.15 | pumpswap | `7GCMYJcykHZ3qJH3…pump` |
| PRIOR | Irene | ~$159k | 0.98 | 296 | 58.76 | pumpswap | `6VdcMnBTCj4tJVwt…pump` |
| PRIOR | Deer | ~$58k | 1.89 | 88.14 | 47.96 | pumpswap | `4tf5GEXU1dt7Vfj2…Deer` |
| PRIOR | FSR | ~$35k | 1.67 | 20.23 | 9.71 | pumpswap | `HiKU8Lsa8aUFkhtC…pump` |
| PRIOR | Irene | ~$32k | 0.8 | 241 | 1.64 | pumpswap | `2xZjZSFkuFvTef55…ThJ3` |
| PRIOR | LULU | ~$25k | 2.52 | 8.51 | 6.93 | pumpfun | `8DQzWohFEMWruKUC…pump` |
| PRIOR | TCAT | ~$22k | 3.93 | 64.34 | 21.27 | pumpfun | `34HExr1pEVFWkx99…pump` |
| PRIOR | Chase | ~$21k | 0.91 | 413 | -14.44 | pumpfun | `YwCKitMEdf7nagej…pump` |
| PRIOR | YERN | ~$16k | 0.9 | 403 | 27.9 | pumpfun | `PdtREY9H6Fp9jVMp…yern` |
| PRIOR | BDOG | ~$13k | 1.96 | 2.65 | -1.29 | pumpfun | `G6NnKQTgN7Dmo9yr…pump` |
| PRIOR | PITBULL | ~$11k | 2.88 | 47.79 | 1.07 | pumpfun | `Gmh5hNtCycP6YSyU…pump` |
| PRIOR | Womb | ~$10k | 1.1 | 1.53 | 11.57 | pumpfun | `BxUHuVGyP9kKRoJZ…pump` |
| NEW | CSF | ~$10k | 0.54 | 152 | -31.28 | pumpfun | `6aNXLr6d9m2gAZKm…pump` |

→ **15** in-window, **1** NEW, **0** autopsy-clean PASS (`inwindow-0622.json` / `new-0622.json` / `_prior-rejects-0622.json`)

## NEW autopsies
### CSF `6aNXLr6d9m2gAZKmGn448f2PhuMeFqWhdDsnPs3Zpump` — **FAIL**
- Charles, Solomon & Francesca — pumpfun curve (curve/AMM+locker ~51.1%: Pump Fun:51.15%), ~$10.2k, 0.54h, h1 +152 / m5 −31.28.
- FAIL: creatorBal 0 (no visible dev bag / fee-share or dumped)
- FAIL: 12× wallets in 1–5% band (sniper/distribution pattern) on 898 holders
- FAIL: botty churn ~4242 tx/h on ~$10k mc (volh1 $148164.91)
- FAIL: no socials / no website
- FAIL: twin-mint CSF copycat (other mint `DDw2yrhh…pump` fading ~$6k)
- FAIL: m5 −31.28 hard fade just after aging into window
- FAIL: deployer burner-ish (wallet age ~0.41h, ≥1000 tx, 0.0059 SOL)
- creator `5EHkmYwU…` age 0.41h, ≥1000 tx, now 0.0059 SOL; pf `/coins/<mint>` 404.
- top10ex ~21.63%; band_1_5 12; graphInsiders 0; holders 898; RC score 1.
- funders: no shared 8+ same-funder bundle among sampled top holders (individual funders Biw4eeai… / 3Mbj13VT… / 5F1seMKU… when found).
- `autopsy-raw-CSF-0622.json` / `autopsy-summary-CSF-0622.json` / `funders-CSF-0622.json` / `rc-CSF-0622.json` / `dex-CSF-0622.json`

## Young watch (<30m) — `watch-extra-0622.json`
- **CHIPTO** `2paFXNaod76U…` (~$11.3k, 0.05h, h1 +71.77, m5 71.77) — too young (<30m)
- **USDC** `JCaa73V2VdbF…` (~$21.7k, 0.09h, h1 +472, m5 472) — spoof ticker; skip
- **ECONOMY** `HesfyHKTEu2V…` (~$11.7k, 0.22h, h1 +286, m5 45.35) — too young (<30m)
- **Irene** `5j7gTphd94qD…` (~$78.7k, 0.42h, h1 +769, m5 36.11) — copycat of prior-FAIL Irene; do not buy

## Prior rechecks (light)
- No prior materially improved structurally:
  - ElonThrust ~$897k (still post-grad whale/botty; prior FAIL stands)
  - BOUNCER ~$257k (73.6% whale + 9.7% creator; prior FAIL stands)
  - Irene `6Vdc…` ~$159k (m5 +59 bounce only; creatorBal 0 + insiders FAIL stands)
  - Irene2 `2xZj…` ~$32k (copycat + creatorBal 0 + botty; FAIL stands)
  - Deer / FSR / Chase / YERN / TCAT / LULU / BDOG / PITBULL / Womb / LOOM — prior FAILs stand
- GITPAID / SocialFrnk / EVERYTHING / TCAT2 / TRELLIS dropped out of in-window this pass (or below filters).

## Decision
**NO-TRADE** — stay in SOL (~0.2976). Only 1 NEW autopsy FAIL (CSF: creatorBal 0 + 12× band + ~4.2k tx/h botty + no socials + twin-mint + m5 −31). No clean PASS.

## Kraken
Watch-only. Last known USD cash ~$0.81 below min order — no proposal; no orders.


# ===== scout-0650.md =====

# Scout 0650 — 2026-10-16 06:50 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (297605540 lamports, `wallet-sol-0650.json`); SPL: dust USDC only (0.000006) + 1 zero USDT acct; Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0650.json` / `wallet-t22-0650.json`). Unchanged since 01:33 ET.
- SOL ~$106.46 (CoinGecko, `sol-price-0650.json`) → est. total ~$31.69.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0650.json` / `profiles-*-0650.json`
- pump.fun currently-live 44 → `pf-live-0650.json`; pump.fun sorted lists (mcap/last-trade/created) → `pf-sorted-0650.json`
- `lists.txt` rebuilt (4 lines; 60 unique solana)
- scan.py: **139 mints** → `scan-0650.out` / `cands-0650.json` (81 cands)
- expanded (lists + pf-live + pf-sorted + priors/watch + narrative searches, `expand0650.py`) → **454 mints / 436 pairs** (`expanded-0650.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | ELON | ~$1.19M | 0.81 | 2609 | 4.5 | pumpswap | `HGcVEA6uF6Ln…sobn` |
| PRIOR | ElonThrust | ~$1.04M | 1.40 | 44 | 2.07 | pumpswap | `pFibPnQk8ekC…pump` |
| PRIOR | BOUNCER | ~$257k | 1.27 | 78 | — | pumpswap | `6X3cMFWWNQSV…3rmg` |
| PRIOR | LOOM | ~$175k | 3.97 | 41 | 11.07 | pumpswap | `7GCMYJcykHZ3…pump` |
| PRIOR | Irene | ~$153k | 1.47 | 45 | 5.13 | pumpswap | `6VdcMnBTCj4t…pump` |
| PRIOR | Deer | ~$116k | 2.37 | 240 | 37.54 | pumpswap | `4tf5GEXU1dt7…Deer` |
| PRIOR | Irene | ~$73k | 0.90 | 703 | 61.33 | pumpswap | `5j7gTphd94qD…nEUY` |
| PRIOR | FSR | ~$46k | 2.16 | 30 | -5.46 | pumpswap | `HiKU8Lsa8aUF…pump` |
| PRIOR | LULU | ~$25k | 3.00 | 6.5 | -0.13 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | Chase | ~$19k | 1.39 | 31 | -14.36 | pumpfun | `YwCKitMEdf7n…pump` |
| PRIOR | YERN | ~$15k | 1.38 | 9.4 | 25.5 | pumpfun | `PdtREY9H6Fp9…yern` |
| PRIOR | PITBULL | ~$11k | 3.37 | 28 | -7.31 | pumpfun | `Gmh5hNtCycP6…pump` |
| PRIOR | Ira | ~$11k | 0.51 | 172 | -15.16 | pumpfun | `Aq8Jdz2m4Vda…pump` |

**NEW: 0** — no full pre-buy autopsy this cycle.

## Young watch (<30m) — light RC only
| symbol | mc | age_h | verdict | note |
|--------|-----|-------|---------|------|
| ROADSTER | ~$10.1k | 0.00 | FAIL_PRESCREEN | 19×1–5% band; creatorBal≈0 |
| normie | ~$21k | 0.05 | FAIL_PRESCREEN | creatorBal 0; 19× band |
| Chase | ~$3.3M | 0.06 | FAIL_PRESCREEN | RC 32839; single holder 99.2%; post-grad chase |
| Mika | ~$13k | 0.41 | FAIL_PRESCREEN | prior 0647 FAIL; graphInsiders 21 |
| Irene×2 / USDC | — | — | SKIP | copycat / impersonation |

## Decision
**NO-TRADE** — stay in SOL. 0 NEW in-window; all young pre-screens fail structural checks; priors unchanged.


# ===== scout-0703.md =====

# Scout 0703 — 2026-10-16 07:03 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (`wallet-sol-0703.json`); SPL: dust USDC only (0.000006); Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0703.json` / `wallet-t22-0703.json`). Unchanged.
- SOL ~1.76$106.73 (CoinGecko, `sol-price-0703.json`) → est. total ~1.76$31.76.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0703.json` / `profiles-*-0703.json`
- pump.fun currently-live 50 → `pf-live-0703.json`; pump.fun sorted lists → `pf-sorted-0703.json`
- `lists.txt` rebuilt (4 lines; 59 unique solana)
- scan.py: **145 mints** → `scan-0703.out` / `cands-0703.json` (81 cands)
- expanded (`expand0703.py`) → **474 mints / 450 pairs** (`expanded-0703.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | ELON | ~1.76$1,430,584 | 1.02 | 263 | 5.49 | pumpswap | `HGcVEA6uF6Ln…sobn` |
| PRIOR | ElonThrust | ~1.76$1,108,933 | 1.61 | 36.29 | 2.31 | pumpswap | `pFibPnQk8ekC…pump` |
| PRIOR | BOUNCER | ~1.76$257,054 | 1.48 | 17.05 | — | pumpswap | `6X3cMFWWNQSV…3rmg` |
| PRIOR | Irene | ~1.76$120,824 | 1.68 | 48.36 | -4 | pumpswap | `6VdcMnBTCj4t…pump` |
| PRIOR | Deer | ~1.76$104,134 | 2.58 | 207 | 15.74 | pumpswap | `4tf5GEXU1dt7…Deer` |
| PRIOR | Irene | ~1.76$65,628 | 1.11 | 148 | — | pumpswap | `5j7gTphd94qD…nEUY` |
| PRIOR | FSR | ~1.76$37,943 | 2.37 | 21.15 | -2.32 | pumpswap | `HiKU8Lsa8aUF…pump` |
| PRIOR | LULU | ~1.76$25,264 | 3.21 | 6.97 | 0.29 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | Irene | ~1.76$24,325 | 0.69 | 152 | 5.37 | pumpswap | `Aoh85TCPn6yY…J5rm` |
| PRIOR | Chase | ~1.76$16,887 | 1.6 | 30.3 | 3.46 | pumpfun | `YwCKitMEdf7n…pump` |
| PRIOR | HASHED | ~1.76$11,872 | 0.5 | 275 | 6.72 | pumpfun | `BMRjts1YYzGu…rSoL` |
| PRIOR | PITBULL | ~1.76$10,559 | 3.58 | 21.74 | -2.21 | pumpfun | `Gmh5hNtCycP6…pump` |

**NEW: 0** — no full pre-buy autopsy this cycle (no NEW mints in window).

### PRIOR notes (none materially improved)
- **HASHED** `BMRj…rSoL` aged into window (0.50h, ~1.76$11.9k, h1 +275) — **FAIL**: creatorBal **0**; 18×1–5% band (0655 holders); top10ex ~1.7626.5%; non-pump suffix; no socials. Fresh RC 0703 confirms creatorBal 0 (holders endpoint empty this run). `autopsy-summary-HASHED-0703.json` / `rc-HASHED-0703.json`
- **Deer** (~1.76$104k, m5 +15.7) — **FAIL/worse**: RC score **14432** (was ~1.761); LP unlocked 100% + liq ~1.76$68; creatorBal 0; prior band/cabal/social fails stand. `autopsy-summary-Deer-0703.json`
- **ELON** — FAIL stands: ~1.7647k tx/h on ~1.76$50k vol (~1.76$1.04/tx bot micro-churn); creatorBal 0; whale concentration; no socials.
- ELON-theme / BOUNCER / Irene×3 / FSR / LULU / Chase / PITBULL — prior FAILs stand (none materially improved).
- Dropped vs 0655: YERN / Ira (h1≤0 or out of window).

## Young watch (<30m) — light RC only (do NOT buy)
| symbol | mc | age_h | verdict | note |
|--------|-----|-------|---------|------|
| ROADSTER | ~1.76$10.1k | 0.00 | FAIL_PRESCREEN | creatorBal 0; RC 1001 Missing metadata; 19× band (0650); dead tape |
| normie | ~1.76$25.5k | 0.26 | FAIL_PRESCREEN | creatorBal 0; 19× band; thin X status social; h1 +610 but <30m |
| Chase | ~1.76$4.9M | 0.27 | FAIL_PRESCREEN | prior RC 32839 / 99.2% holder; post-grad chase |
| Irene `NqZa…` | ~1.76$83k | 0.29 | SKIP | Irene copycat |
| USDC | ~1.76$125k | 0.49 | SKIP | impersonation name; m5 −18.6 |

## Decision
**NO-TRADE** — stay in SOL (~0.2976 SOL / ~$31.76).
- In-window: **12** | NEW: **0** | autopsy-clean: **0**
- No buy candidates pass pre-buy autopsy.


# ===== scout-0710.md =====

# Scout 0710 — 2026-10-16 07:10 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (`wallet-sol-0710.json`); SPL: dust USDC only (0.000006); Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0710.json` / `wallet-t22-0710.json`). Unchanged.
- SOL ~$106.64 (CoinGecko, `sol-price-0710.json`) → est. total ~$31.74.

## Feeds
- DexScreener boosts latest/top (30+30), profiles latest (30), community-takeovers (8) → `boosts-*-0710.json` / `profiles-*-0710.json`
- pump.fun currently-live 50 → `pf-live-0710.json`; pump.fun sorted lists → `pf-sorted-0710.json`
- `lists.txt` rebuilt (4 lines; 60 unique solana)
- scan.py: **146 mints** → `scan-0710.out` / `cands-0710.json` (83 cands)
- expanded (`expand0710.py`) → **466 mints / 442 pairs** (`expanded-0710.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | ElonThrust | ~$1,147,272 | 1.73 | 35.11 | 2.06 | pumpswap | `pFibPnQk8ekC…pump` |
| PRIOR | Irene | ~$129,997 | 1.80 | 70.83 | 4.51 | pumpswap | `6VdcMnBTCj4t…pump` |
| NEW | USDC | ~$105,104 | 0.61 | 90.79 | -7.54 | pumpswap | `6We2unR6HXgE…pump` |
| PRIOR | Deer | ~$95,947 | 2.70 | 134 | 0.09 | pumpswap | `4tf5GEXU1dt7…Deer` |
| PRIOR | Irene | ~$65,628 | 1.23 | 5.23 | — | pumpswap | `5j7gTphd94qD…nEUY` |
| PRIOR | FSR | ~$35,450 | 2.49 | 12.13 | -5.39 | pumpswap | `HiKU8Lsa8aUF…pump` |
| PRIOR | LULU | ~$25,393 | 3.33 | 7.44 | 0.39 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | Irene | ~$21,638 | 0.80 | 124 | -7.51 | pumpswap | `Aoh85TCPn6yY…J5rm` |
| PRIOR | Chase | ~$19,942 | 1.72 | 21.31 | 19.65 | pumpfun | `YwCKitMEdf7n…pump` |
| PRIOR | YERN | ~$13,934 | 1.71 | 8.71 | -3.25 | pumpfun | `PdtREY9H6Fp9…yern` |
| PRIOR | SocialFrnk | ~$12,666 | 2.85 | 28.32 | 10.56 | pumpfun | `62tKjqdvzKrN…pump` |
| PRIOR | PITBULL | ~$10,559 | 3.69 | 10.8 | — | pumpfun | `Gmh5hNtCycP6…pump` |

**NEW: 1** — full pre-buy autopsy below.

### NEW autopsy
- **USDC** `6We2unR6HXgE…pump` (name "UpSide Down Cat", ~$105k PumpSwap, 0.61h, h1 +91 / m5 −7.5) — **FAIL**: USDC impersonation / RC Copycat of Circle mint; creatorBal **0**; **18×**1–5% band; social is coinbase status (stolen); post-grad chase. `autopsy-summary-USDC-0710.json` / `rc-USDC-0710.json`

### PRIOR notes (none materially improved)
- **Chase** `YwCK…pump` m5 +19.7 but structural FAIL stands (creatorBal 0 / band / botty tape from 0603) — not borderline; no re-autopsy.
- ElonThrust / Irene×3 / Deer / FSR / LULU / YERN / SocialFrnk / PITBULL — prior FAILs stand (copycats / creatorBal 0 / bands / whales / post-grad).
- Dropped vs 0703: ELON / BOUNCER / HASHED (h1≤0 or out of window / mc filter).

## Young watch (<30m) — light RC only (do NOT buy)
| symbol | mc | age_h | verdict | note |
|--------|-----|-------|---------|------|
| ONE | ~$12.7k | 0.12 | FAIL_PRESCREEN | creatorBal 0; 11× band; graphInsiders 4 |
| GRAB | ~$11.9k | 0.18 | FAIL_PRESCREEN | creatorBal≈0; **19×** band; low liq |
| TCAT | ~$12.5k | 0.03 | SKIP | TCAT copycat theme |
| normie | ~$17.2k | 0.38 | FAIL_PRESCREEN | prior (creatorBal 0; 19×); m5 −24 |
| Chase `9TXN…` | ~$5.7M | 0.39 | FAIL_PRESCREEN | prior RC 32839 / 99% holder; post-grad |
| Irene `NqZa…` | ~$86k | 0.41 | SKIP | Irene copycat |

## Decision
**NO-TRADE** — stay in SOL (~0.2976 SOL / ~$31.74).
- In-window: **12** | NEW: **1** | autopsy-clean: **0**
- No buy candidates pass pre-buy autopsy.


# ===== scout-0714.md =====

# Scout 0714 — 2026-10-16 07:14 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (`wallet-sol-0714.json`); SPL: dust USDC only (0.000006); Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0714.json` / `wallet-t22-0714.json`). Unchanged.
- SOL ~$107.02 (CoinGecko, `sol-price-0714.json`) → est. total ~$31.85.

## Feeds
- DexScreener boosts latest/top, profiles latest, community-takeovers → `boosts-*-0714.json` / `profiles-*-0714.json`
- pump.fun currently-live 50 → `pf-live-0714.json`; pump.fun sorted lists → `pf-sorted-0714.json`
- `lists.txt` rebuilt (4 lines; 60 unique solana)
- scan.py: **147 mints** → `scan-0714.out` / `cands-0714.json` (84 cands)
- expanded (`expand0714.py`, `expand-0714.out`) → **469 mints / 446 pairs** (`expanded-0714.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | ElonThrust | ~$1,167,456 | 1.77 | 35.23 | 2.39 | pumpswap | `pFibPnQk8ekC…pump` |
| PRIOR | Irene | ~$149,009 | 1.84 | 59.57 | 14.35 | pumpswap | `6VdcMnBTCj4t…pump` |
| PRIOR | Deer | ~$130,912 | 2.74 | 208 | 37.31 | pumpswap | `4tf5GEXU1dt7…Deer` |
| PRIOR | USDC | ~$120,059 | 0.66 | 118 | -3.37 | pumpswap | `6We2unR6HXgE…pump` |
| PRIOR | Irene | ~$65,628 | 1.28 | 12.98 | — | pumpswap | `5j7gTphd94qD…nEUY` |
| PRIOR | LULU | ~$25,478 | 3.38 | 7.59 | 0.73 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | Irene | ~$22,359 | 0.85 | 132 | -17.49 | pumpswap | `Aoh85TCPn6yY…J5rm` |
| PRIOR | YERN | ~$14,288 | 1.76 | 8.06 | -0.79 | pumpfun | `PdtREY9H6Fp9…yern` |
| PRIOR | PITBULL | ~$11,777 | 3.74 | 4.32 | 11.54 | pumpfun | `Gmh5hNtCycP6…pump` |

**NEW: 0** — no new in-window candidates.

### PRIOR notes
- **Deer** `4tf5…Deer` rechecked (RC improved vs 0703: score 1, liq ~$28.7k, h1 +208 / m5 +37) — **FAIL stands**: creatorBal 0; 19×1–5% band; top10 excl. pool ≈27%; post-grad chase. `autopsy-summary-Deer-0714.json` / `rc-Deer-0714.json`
- ElonThrust / Irene×3 / USDC / LULU / YERN / PITBULL — prior FAILs stand (copycats / impersonation / creatorBal 0 / bands / whales / post-grad; none materially improved).
- Dropped vs 0710: FSR / Chase `YwCK…` / SocialFrnk (out of window or filter).

## Young watch (<30m) — light RC only (do NOT buy)
| symbol | mc | age_h | verdict | note |
|--------|-----|-------|---------|------|
| CCAT (CyberCat) | ~$13.4k | 0.06 | FAIL_PRESCREEN | creatorBal 0; 15× band; non-pump mint; cat copycat wave (`rc-CCAT-0714.json`) |
| TCAT | ~$14.3k | 0.05 | SKIP | TCAT copycat theme |
| GRAB | ~$10.2k | 0.22 | FAIL_PRESCREEN | prior (19× band; creatorBal≈0); m5 −11.6 |
| normie | ~$17.3k | 0.42 | FAIL_PRESCREEN | prior (creatorBal 0; 19×); m5 −26.6 |
| Chase `9TXN…` | ~$6.1M | 0.43 | FAIL_PRESCREEN | prior RC 32839 / 99% holder; post-grad |
| Irene `NqZa…` | ~$89k | 0.46 | SKIP | Irene copycat |

## Decision
**NO-TRADE** — stay in SOL (~0.2976 SOL / ~$31.85).
- In-window: **9** | NEW: **0** | autopsy-clean: **0**
- No buy candidates pass pre-buy autopsy.


# ===== scout-0720.md =====

# Scout 0720 — 2026-10-16 07:20 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (`wallet-sol-0720.json`); SPL: dust USDC only (0.000006); Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0720.json` / `wallet-t22-0720.json`). Unchanged.
- SOL ~$106.86 (CoinGecko, `sol-price-0720.json`) → est. total ~$31.8.

## Feeds
- DexScreener boosts latest/top, profiles latest, community-takeovers → `boosts-*-0720.json` / `profiles-*-0720.json`
- pump.fun currently-live 50 → `pf-live-0720.json`; pump.fun sorted lists → `pf-sorted-0720.json` (via expand)
- `lists.txt` rebuilt (4 lines; 62 unique solana)
- scan.py: **147 mints** → `scan-0720.out` / `cands-0720.json` (86 cands)
- expanded (`expand0720.py`, `expand-0720.out`) → **477 mints / 456 pairs** (`expanded-0720.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | Chase | ~$7,003,960 | 0.55 | 32557 | 16.61 | pumpswap | `9TXNTWV5v7M3…SLEm` |
| PRIOR | ElonThrust | ~$1,203,980 | 1.89 | 35.03 | 2.26 | pumpswap | `pFibPnQk8ekC…pump` |
| PRIOR | Deer | ~$120,209 | 2.86 | 121 | -6.21 | pumpswap | `4tf5GEXU1dt7…Deer` |
| PRIOR | Irene | ~$90,083 | 0.57 | 75.41 | -1.69 | pumpswap | `NqZaNi1v6qjF…RWGU` |
| PRIOR | USDC | ~$86,696 | 0.77 | 57.38 | -26.55 | pumpswap | `6We2unR6HXgE…pump` |
| PRIOR | Irene | ~$25,924 | 0.96 | 169 | 5.92 | pumpswap | `Aoh85TCPn6yY…J5rm` |
| PRIOR | LULU | ~$25,515 | 3.49 | 0.93 | 0.15 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | normie | ~$20,499 | 0.54 | 470 | 4.35 | pumpfun | `4673spr9Zth4…pump` |
| PRIOR | PITBULL | ~$11,381 | 3.85 | 5.51 | -3.04 | pumpfun | `Gmh5hNtCycP6…pump` |
| PRIOR | SocialFrnk | ~$10,911 | 3.01 | 10.54 | 8.9 | pumpfun | `62tKjqdvzKrN…pump` |
| PRIOR | Ira | ~$10,155 | 1.00 | 153 | 4.77 | pumpfun | `Aq8Jdz2m4Vda…pump` |

**NEW: 0** — no new in-window candidates.

### PRIOR notes
- **Chase** `9TXN…SLEm` aged into window from young — **FAIL stands**: prior RC 32839 / single holder ~99%; post-grad chase at ~$7M.
- **Deer** `4tf5…Deer` — no material improvement (m5 −6.21 fading); prior FAIL stands (creatorBal 0; 19× band; post-grad).
- **normie** aged into window — FAIL stands (creatorBal 0; 19× band).
- ElonThrust / Irene×2 (copycats) / USDC (impersonation) / LULU / PITBULL / SocialFrnk / Ira — prior FAILs stand (none materially improved).
- Dropped vs 0714: Irene `6Vdc…` / Irene `5j7g…` / YERN (out of window or filter).

## Young watch (<30m) — light RC only (do NOT buy)
| symbol | mc | age_h | verdict | note |
|--------|-----|-------|---------|------|
| OPTIMA | ~$24.6k | 0.09 | FAIL_PRESCREEN | creatorBal 0; 13×1–5% band on 366 holders (`rc-OPTIMA-0720.json`) |
| FTR | ~$822k | 0.25 | FAIL_PRESCREEN | creatorBal 0; early post-grad chase ~$822k MC (`rc-FTR-0720.json`) |
| ONE | ~$10.6k | 0.28 | FAIL_PRESCREEN | prior (creatorBal 0; band; graphInsiders) |
| GRAB | ~$12.9k | 0.34 | FAIL_PRESCREEN | prior (19× band; creatorBal≈0) |

## Decision
**NO-TRADE** — stay in SOL (~0.2976 SOL / ~$31.8).
- In-window: **11** | NEW: **0** | autopsy-clean: **0**
- No buy candidates pass pre-buy autopsy.


# ===== scout-0725.md =====

# Scout 0725 — 2026-10-16 07:25 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (`wallet-sol-0725.json`); SPL: dust USDC only (0.000006); Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0725.json` / `wallet-t22-0725.json`). Unchanged.
- SOL ~$106.77 (CoinGecko, `sol-price-0725.json`) → est. total ~$31.8.

## Feeds
- DexScreener boosts latest/top, profiles latest, community-takeovers → `boosts-*-0725.json` / `profiles-*-0725.json`
- pump.fun currently-live 50 → `pf-live-0725.json`; pump.fun sorted lists → `pf-sorted-0725.json` (via expand)
- `lists.txt` rebuilt (4 lines; 60 unique solana)
- scan.py: **148 mints** → `scan-0725.out` / `cands-0725.json` (85 cands)
- expanded (`expand0725.py`, `expand-0725.out`) → **473 mints / 452 pairs** (`expanded-0725.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | Chase | ~$7,825,037 | 0.62 | 36386 | 9.6 | pumpswap | `9TXNTWV5v7M3…SLEm` |
| PRIOR | ElonThrust | ~$1,225,965 | 1.96 | 33.87 | 1.76 | pumpswap | `pFibPnQk8ekC…pump` |
| PRIOR | Irene | ~$152,059 | 2.03 | 9.39 | 14.15 | pumpswap | `6VdcMnBTCj4t…pump` |
| PRIOR | Deer | ~$115,175 | 2.93 | 78.72 | -3.29 | pumpswap | `4tf5GEXU1dt7…Deer` |
| PRIOR | Irene | ~$96,569 | 0.65 | 88.04 | 4.34 | pumpswap | `NqZaNi1v6qjF…RWGU` |
| PRIOR | USDC | ~$89,590 | 0.84 | 62.63 | 7.81 | pumpswap | `6We2unR6HXgE…pump` |
| PRIOR | Irene | ~$65,628 | 1.47 | 6.83 | — | pumpswap | `5j7gTphd94qD…nEUY` |
| PRIOR | Irene | ~$28,337 | 1.04 | 67.19 | -3.28 | pumpswap | `Aoh85TCPn6yY…J5rm` |
| PRIOR | LULU | ~$25,517 | 3.57 | 0.77 | 0.01 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | normie | ~$13,201 | 0.61 | 267 | -35.71 | pumpfun | `4673spr9Zth4…pump` |
| PRIOR | PITBULL | ~$11,381 | 3.93 | 5.51 | — | pumpfun | `Gmh5hNtCycP6…pump` |
| PRIOR | SocialFrnk | ~$10,788 | 3.09 | 7.27 | -1.13 | pumpfun | `62tKjqdvzKrN…pump` |
| PRIOR | Ira | ~$10,568 | 1.08 | 20.89 | 4.07 | pumpfun | `Aq8Jdz2m4Vda…pump` |
| PRIOR | TCAT | ~$10,208 | 3.04 | 12.28 | 10.96 | pumpfun | `6ZDKgWopksQP…pump` |

**NEW: 0** — no new in-window candidates.

### PRIOR notes
- **Chase** `9TXN…SLEm` — FAIL stands: prior RC 32839 / single holder ~99%; post-grad chase ~$7.8M.
- **Deer** `4tf5…Deer` — no material improvement (m5 −3.29 still fading); prior FAIL stands (creatorBal 0; 19× band; post-grad).
- **normie** — FAIL stands (creatorBal 0; 19× band); m5 −35.71 dumping.
- **Irene×4** (`6Vdc…` returned / `NqZa…` / `5j7g…` returned / `Aoh8…`) — copycat theme; FAIL stands.
- **TCAT** returned to window — copycat / prior FAIL stands.
- ElonThrust / USDC (impersonation) / LULU / PITBULL / SocialFrnk / Ira — prior FAILs stand (none materially improved).
- Dropped vs 0720: (none material; OPTIMA aged out of young into nowhere / filtered).

## Young watch (<30m) — light RC only (do NOT buy)
| symbol | mc | age_h | verdict | note |
|--------|-----|-------|---------|------|
| Jato | ~$16.8k | 0.09 | FAIL_PRESCREEN | creatorBal 0; 15×1–5% band on 421 holders (`rc-Jato-0725.json`) |
| FTR | ~$12.5k | 0.14 | FAIL_PRESCREEN | creatorBal 0; 19×1–5% band on 275 holders (`rc-FTR-0725.json`) mint `BPVUcKX5…pump` |
| FTR | ~$997k | 0.33 | FAIL_PRESCREEN_PRIOR | creatorBal 0; early post-grad chase (`rc-FTR2-0725.json`) mint `9sv13ToY…pump` |
| GRAB | ~$15.1k | 0.41 | FAIL_PRESCREEN_PRIOR | creatorBal≈0; 19× band (`rc-GRAB-0725.json`) |

## Decision
**NO-TRADE** — stay in SOL (~0.2976 SOL / ~$31.8).
- In-window: **14** | NEW: **0** | autopsy-clean: **0**
- No buy candidates pass pre-buy autopsy.


# ===== scout-0730.md =====

# Scout 0730 — 2026-10-16 07:30 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` RPC **0.29760554 SOL** (`wallet-sol-0730.json`); SPL: dust USDC only (0.000006); Token-2022: 12 accounts all zero → **no meme positions** (`wallet-spl-0730.json` / `wallet-t22-0730.json`). Unchanged.
- SOL ~$106.82 (CoinGecko, `sol-price-0730.json`) → est. total ~$31.8.

## Feeds
- DexScreener boosts latest/top, profiles latest, community-takeovers → `boosts-*-0730.json` / `profiles-*-0730.json`
- pump.fun currently-live 50 → `pf-live-0730.json`; pump.fun sorted lists → `pf-sorted-0730.json` (empty this run — API returned `[]`; expand still used live + Dex search)
- `lists.txt` rebuilt (4 lines; 60 unique solana)
- scan.py: **143 mints** → `scan-0730.out` / `cands-0730.json` (80 cands)
- expanded (`expand0730.py`, `expand-0730.out`) → **480 mints 457 pairs** (`expanded-0730.json`)

## In-window (age 0.5–4h, mc ≥$10k, h1>0, dex pump/pumpswap)
| tag | symbol | mc | age_h | h1 | m5 | dex | mint |
|-----|--------|-----|-------|-----|-----|-----|------|
| PRIOR | Chase | ~$9,056,665 | 0.74 | 42129 | 5.14 | pumpswap | `9TXNTWV5v7M3…SLEm` |
| PRIOR | ElonThrust | ~$1,266,144 | 2.08 | 32.9 | 1.77 | pumpswap | `pFibPnQk8ekC…pump` |
| PRIOR | Deer | ~$117,925 | 3.05 | 90.09 | -4.73 | pumpswap | `4tf5GEXU1dt7…Deer` |
| PRIOR | USDC | ~$113,599 | 0.96 | 106 | 1.41 | pumpswap | `6We2unR6HXgE…pump` |
| PRIOR | Irene | ~$104,903 | 0.77 | 104 | 4.34 | pumpswap | `NqZaNi1v6qjF…RWGU` |
| PRIOR | Irene | ~$65,628 | 1.59 | 59.69 | — | pumpswap | `5j7gTphd94qD…nEUY` |
| PRIOR | Irene | ~$42,239 | 1.16 | 112 | -4.54 | pumpswap | `Aoh85TCPn6yY…J5rm` |
| PRIOR | LULU | ~$25,549 | 3.69 | 2.19 | 0.13 | pumpfun | `8DQzWohFEMWr…pump` |
| PRIOR | GRAB | ~$18,253 | 0.53 | 479 | 13.5 | pumpfun | `5rB2Z8xPrUGX…pump` |
| PRIOR | normie | ~$14,358 | 0.73 | 299 | 6.78 | pumpfun | `4673spr9Zth4…pump` |
| PRIOR | BDOG | ~$11,175 | 3.13 | 10.44 | -1.13 | pumpfun | `G6NnKQTgN7Dm…pump` |
| PRIOR | TCAT | ~$10,117 | 3.16 | 11.73 | -0.76 | pumpfun | `6ZDKgWopksQP…pump` |

**NEW: 0** — no new in-window candidates.

### PRIOR notes
- **Chase** `9TXN…SLEm` — FAIL stands: prior RC 32839 / single holder ~99%; post-grad chase ~$9.1M.
- **Deer** `4tf5…Deer` — no material improvement (m5 −4.73 still fading); prior FAIL stands (creatorBal 0; 19× band; post-grad).
- **GRAB** aged into window — FAIL stands / reconfirmed: creatorBal **0**; RC score 2735 (Low Liquidity); prior 19× band (`rc-GRAB-0730.json` / `autopsy-summary-GRAB-0730.json`).
- **BDOG** returned — FAIL reconfirmed: creatorBal **0**; 19×1–5% band on 222 holders (`rc-BDOG-0730.json` / `autopsy-summary-BDOG-0730.json`); prior FAIL @0456.
- **Irene×3** (`NqZa…` / `5j7g…` / `Aoh8…`) — copycat theme; FAIL stands. (Irene `6Vdc…` dropped vs 0725.)
- **USDC** (impersonation) / **LULU** / **normie** / **TCAT** — prior FAILs stand (none materially improved).
- Dropped vs 0725: Irene `6Vdc…`, PITBULL, SocialFrnk, Ira (aged/filtered out).

## Young watch (<30m) — light RC only (do NOT buy)
| symbol | mc | age_h | verdict | note |
|--------|-----|-------|---------|------|
| Caramel | ~$13.8k | 0.07 | FAIL_PRESCREEN | creatorBal 0; 19×1–5% band on 283 holders (`rc-Caramel-0730.json`) |
| Irene | ~$12.7k | 0.14 | SKIP | copycat theme (`6N4B…XDbo`) |
| OPTIMA | ~$70.9k | 0.15 | FAIL_PRESCREEN_PRIOR | prior FAIL (creatorBal≈0; 13× band); now post-grad chase (`DdVX…pump`) |
| PAIRS | ~$13.5k | 0.16 | FAIL_PRESCREEN | creatorBal 0; 19×1–5% band on 293 holders (`rc-PAIRS-0730.json`) |
| Jato | ~$13.0k | 0.21 | FAIL_PRESCREEN_PRIOR | creatorBal 0; 15× band (`rc-Jato-0725.json`) |
| FTR | ~$11.2k | 0.26 | FAIL_PRESCREEN_PRIOR | creatorBal 0; 19× band (`rc-FTR-0725.json`) mint `BPVU…pump` |
| FTR | ~$1.01M | 0.45 | FAIL_PRESCREEN_PRIOR | creatorBal 0; early post-grad chase (`rc-FTR2-0725.json`) mint `9sv1…pump` |

## Decision
**NO-TRADE** — stay in SOL (~0.2976 SOL / ~$31.8).
- In-window: **12** | NEW: **0** | autopsy-clean: **0**
- No buy candidates pass pre-buy autopsy.


# ===== scout-0802.md =====

# Scout 0802 — 2026-10-16 08:02 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (~$31.71 @ $106.56)
- SPL: dust USDC only (6e-06); Token-2022: 12 accounts all zero
- Book: **ALL SOL — no meme positions**

## Scout counts
| Stage | Count |
|-------|------:|
| scan.py mints | 139 |
| cands | 77 |
| expanded mints | 481 |
| expanded pairs | 462 |
| strict in-window | 9 |
| NEW | 0 |
| young (<30m) | 7 |
| autopsy-clean buys | 0 |

## In-window (0.5–4h, mc≥$10k, h1>0, pumpfun|pumpswap)
- **PRIOR Chase** mc~$9,344,013 age=1.24h h1=97.94 m5=None pumpswap `9TXNTWV5v7M3…`
- **PRIOR ElonThrust** mc~$1,433,300 age=2.58h h1=29.89 m5=1.67 pumpswap `pFibPnQk8ekC…`
- **PRIOR Irene** mc~$124,986 age=1.27h h1=50.33 m5=0.37 pumpswap `NqZaNi1v6qjF…`
- **PRIOR OPTIMA** mc~$60,221 age=0.65h h1=40.82 m5=55.14 pumpswap `DdVXE425xZe2…`
- **PRIOR Irene** mc~$44,629 age=1.66h h1=110 m5=None pumpswap `Aoh85TCPn6yY…`
- **PRIOR Irene** mc~$35,809 age=0.64h h1=280 m5=24.93 pumpswap `6N4BHPN8rvN2…`
- **PRIOR YERN** mc~$16,584 age=2.56h h1=29.46 m5=-0.79 pumpfun `PdtREY9H6Fp9…`
- **PRIOR SocialFrnk** mc~$14,503 age=3.7h h1=52.87 m5=-1.11 pumpfun `62tKjqdvzKrN…`
- **PRIOR BDOG** mc~$11,614 age=3.63h h1=4.65 m5=8.99 pumpfun `G6NnKQTgN7Dm…`

### Recheck
- **OPTIMA** `DdVXE425…pump` — FAIL (rechecked). Price hot (h1 +41 / m5 was +55) + socials appeared, but 12×1–5% band, top wallets ~18%+10%, post-grad pumpswap; prior 0720 FAIL structure persists. `autopsy-summary-OPTIMA-0802.json` / `rc-OPTIMA-0802.json`
- Chase / ElonThrust / Irene×3 / YERN / SocialFrnk / BDOG — prior FAILs stand (structural: 99% holder, whales, copycats, creatorBal 0 / bands). Irene `6N4B…`+`NqZa…`+`Aoh8…` = copycat theme skip.

## Young pre-screen (<30m, no-buy)
- **17/10** mc~$10,328 age=0.04h h1=187 m5=187 pumpfun `AGEG7Top8SGq…`
- **FI** mc~$11,188 age=0.06h h1=113 m5=113 pumpfun `GjuiYGJi3QNt…`
- **Tesla** mc~$21,768 age=0.09h h1=627 m5=627 pumpfun `6KEm7GHTspmv…`
- **DTR** mc~$145,486 age=0.18h h1=222 m5=-17.41 pumpswap `4ti7DQpMPKHc…`
- **Jato** mc~$45,758 age=0.21h h1=0.6 m5=17.21 pumpswap `HtqVqejZuh9B…`
- **Caramel** mc~$199,589 age=0.25h h1=348 m5=41.01 pumpswap `63UjR7d4xfCD…`
- **Cub** mc~$14,706 age=0.27h h1=308 m5=24.48 pumpfun `DG5cR2W2Ms5Q…`

### Young RC
- **17/10** `AGEG7…pump` — FAIL: creatorBal 0; 0.04h; mc faded. `rc-1710-0802.json`
- **FI** `Gjui…pump` — FAIL: creatorBal 0; 13× band. `rc-FI-0802.json`
- **Tesla** `6KEm…pump` — FAIL: RC 6153; single holder 51%; 7 holders. `rc-Tesla-0802.json`
- **DTR** `4ti7…pump` ("Doge Tesla Roadster") — FAIL: 18× band; top10ex≈32%; post-grad ~$145k chase; m5 fading. `rc-DTR-0802.json`
- Jato / Caramel / Cub — prior FAILs stand.

## Decision
**NONE — stay in SOL.** No autopsy-clean buys.


# ===== scout-0808.md =====

# Scout 0808 — 2026-10-16 08:08 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (~$31.61 @ $106.21)
- SPL: dust USDC only (6e-06); Token-2022: 12 accounts all zero
- Book: **ALL SOL — no meme positions**

## Scout counts
| Stage | Count |
|-------|------:|
| scan.py mints | 137 |
| cands | 75 |
| expanded mints | 481 |
| expanded pairs | 460 |
| strict in-window | 9 |
| NEW | 0 |
| young (<30m) | 6 |
| autopsy-clean buys | 0 |

## In-window (0.5–4h, mc≥$10k, h1>0, pumpfun|pumpswap)
- **PRIOR Chase** mc~$9,344,013 age=1.35h h1=76.92 m5=None pumpswap `9TXNTWV5v7M3…`
- **PRIOR ElonThrust** mc~$1,468,753 age=2.69h h1=29.31 m5=1.75 pumpswap `pFibPnQk8ekC…`
- **PRIOR Deer** mc~$176,535 age=3.66h h1=82.88 m5=22.99 pumpswap `4tf5GEXU1dt7…`
- **PRIOR Irene** mc~$124,986 age=1.38h h1=46.96 m5=None pumpswap `NqZaNi1v6qjF…`
- **PRIOR OPTIMA** mc~$110,856 age=0.76h h1=159 m5=24.45 pumpswap `DdVXE425xZe2…`
- **PRIOR Irene** mc~$44,629 age=1.77h h1=64.69 m5=None pumpswap `Aoh85TCPn6yY…`
- **PRIOR Irene** mc~$35,892 age=0.75h h1=281 m5=1.96 pumpswap `6N4BHPN8rvN2…`
- **PRIOR SocialFrnk** mc~$13,601 age=3.82h h1=9.98 m5=-6.22 pumpfun `62tKjqdvzKrN…`
- **PRIOR BDOG** mc~$11,614 age=3.74h h1=4.65 m5=None pumpfun `G6NnKQTgN7Dm…`

### Recheck
- **Deer** `4tf5GEXU1dt7…Deer` — FAIL (rechecked). Hot rebound (h1 +83 / m5 +23, liq ~$36.7k) but creatorBal **0**; **19×** 1–5% band; top10ex≈27.5%; post-grad chase; prior 0714 FAIL stands. `autopsy-summary-Deer-0808.json` / `rc-Deer-0808.json`
- **OPTIMA** `DdVXE425…pump` — FAIL (rechecked). Still hot (h1 +159 / m5 +24, ~$111k) but **13×** band; top10ex≈27.8%; post-grad pumpswap; 0720/0802 structure persists. `autopsy-summary-OPTIMA-0808.json` / `rc-OPTIMA-0808.json`
- Chase / ElonThrust / Irene×3 (`NqZa…`/`Aoh8…`/`6N4B…` copycats) / SocialFrnk / BDOG — prior FAILs stand (none materially improved). YERN dropped vs 0802.

## Young pre-screen (<30m, no-buy)
- **FI** mc~$28,479 age=0.17h h1=441 m5=16.07 pumpfun `GjuiYGJi3QNt…`
- **Tesla** mc~$21,768 age=0.2h h1=627 m5=None pumpfun `6KEm7GHTspmv…`
- **DJT** mc~$19,957 age=0.21h h1=395 m5=120 pumpfun `5aGRLchKmNDv…`
- **DTR** mc~$164,819 age=0.29h h1=265 m5=2.89 pumpswap `4ti7DQpMPKHc…`
- **Caramel** mc~$63,432 age=0.36h h1=42.39 m5=-46.66 pumpswap `63UjR7d4xfCD…`
- **Cub** mc~$10,312 age=0.38h h1=186 m5=-7.52 pumpfun `DG5cR2W2Ms5Q…`

### Young RC
- **DJT** `5aGRL…TTLG` — FAIL (NEW young): RC Copycat of DJTu7…; creatorBal 0; 19× band. `rc-DJT-0808.json` / `autopsy-summary-DJT-0808.json`
- **FI** `Gjui…pump` — FAIL: creatorBal 0; 14× band. `rc-FI-0808.json`
- **Tesla** `6KEm…pump` — FAIL: RC 6153; single holder 51%; 7 holders. `rc-Tesla-0808.json`
- **DTR** `4ti7…pump` — FAIL stands: young post-grad chase ~$165k; prior band/copycat narrative. `rc-DTR-0808.json`
- Caramel / Cub — prior FAILs stand (m5 fading on Caramel −47).

## Decision
**NONE — stay in SOL.** No autopsy-clean buys. 0 NEW in-window; Deer+OPTIMA rechecks still FAIL.



# ===== scout-0832.md =====

# Scout 0832 — 2026-10-16 08:32 ET

## Wallet
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.29760554** (~$31.66 @ $106.37)
- SPL: dust USDC only (6e-06); Token-2022: 12 accounts all zero
- Book: **ALL SOL — no meme positions**

## Scout counts
| Stage | Count |
|-------|------:|
| scan.py mints | 149 |
| cands | 83 |
| expanded mints | 549 |
| expanded pairs | 493 |
| strict in-window | 8 |
| NEW | 0 |
| young (<30m) | 4 |
| autopsy-clean buys | 0 |

## In-window (0.5–4h, mc≥$10k, h1>0, pumpfun|pumpswap)
- **PRIOR ElonThrust** mc~$1,603,624 age=3.09h h1=25.6 m5=0.35 pumpswap `pFibPnQk8ekC…`
- **PRIOR Irene** mc~$124,986 age=1.78h h1=14.41 m5=None pumpswap `NqZaNi1v6qjF…`
- **PRIOR Caramel** mc~$116,349 age=0.76h h1=170 m5=-13.26 pumpswap `63UjR7d4xfCD…`
- **PRIOR OPTIMA** mc~$108,405 age=1.16h h1=57.92 m5=-3.14 pumpswap `DdVXE425xZe2…`
- **PRIOR $1** mc~$78,346 age=1.24h h1=225 m5=23.94 pumpswap `5qjzEB3bUBax…`
- **PRIOR Irene** mc~$51,225 age=1.15h h1=285 m5=3.88 pumpswap `6N4BHPN8rvN2…`
- **PRIOR Tesla** mc~$21,768 age=0.6h h1=627 m5=None pumpfun `6KEm7GHTspmv…`
- **PRIOR YERN** mc~$14,732 age=3.08h h1=14.6 m5=-4.33 pumpfun `PdtREY9H6Fp9…`

### Recheck
- **Tesla** `6KEm7GHTspmv…pump` — FAIL (PRIOR recheck; aged into window). RC score **114153**; Creator history of rugged tokens; single holder **51.39%**; only **4** holders; creatorBal **0**; Tesla copycat skip. `autopsy-summary-Tesla-0832.json` / `rc-Tesla-0832.json`
- ElonThrust / Irene×2 (`NqZa…`/`6N4B…` copycats) / Caramel (m5 −13 dumping) / OPTIMA / $1 / YERN — prior FAILs stand (structural; none materially improved). Chase / Deer dropped vs 0826.

## Young pre-screen (<30m, no-buy)
- **VP** mc~$48,190 age=0.15h h1=8.33 m5=-36.4 pumpswap `3rSfVix6BUoP…`
- **CAT** mc~$10,340 age=0.16h h1=142 m5=-15.44 pumpfun `9nQNALg2SqBC…`
- **TripleT** mc~$18,908 age=0.17h h1=424 m5=1.27 pumpfun `8TB7iWUaUrtf…`
- **FI** mc~$52,257 age=0.39h h1=19.89 m5=-6.51 pumpswap `GjuiYGJi3QNt…`

### Young RC
- **CAT** `9nQNALg2SqBC…pump` — FAIL (NEW young): creatorBal **0**; **19×** 1–5% band on 359 holders; top10ex≈25.2%; age 0.16h. `rc-CAT-0832.json` / `autopsy-summary-CAT-0832.json`
- **TripleT** `8TB7iWUaUrtf…pump` — FAIL (NEW young): RC Copycat; creatorBal **0**; **19×** band + tight ~2.1–2.3% cluster; age 0.17h. `rc-TripleT-0832.json` / `autopsy-summary-TripleT-0832.json`
- VP / FI — prior FAILs stand (VP m5 −36 dumping; FI m5 −6.5 fading).

## Decision
**NONE — stay in SOL.** No autopsy-clean buys. 0 NEW in-window; Tesla recheck + CAT/TripleT young all FAIL.


# ===== scout-0849.md =====

# Scout 0849 — 2026-10-16 08:49 ET

## Wallet
- `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- RPC **0.29760554 SOL** (297605540 lamports) — `wallet-sol-0849.json`
- SPL: dust USDC 6e-06 + zero USDT; Token-2022 12 accounts all zero
- **No meme positions**
- SOL ~$105.76 → est. total ~$31.47

## Universe
- DexScreener: boosts-latest (30), boosts-top (30), profiles-latest (30), CTOs (7) → `lists.txt` rebuilt
- pf-live-0849.json: 50 currently-live
- scan0849.py: **146 mints** → `cands-0849.json` (83 pairs passing v24/age filter) / `scan-0849.out`
- expand0849.py: **607 mints / 538 pairs** → `expanded-0849.json` / `expand-0849.out`

## In-window (0.5–4h, mc≥$10k, h1>0, pumpfun/pumpswap)
**11** strict in-window → **0 NEW** → **0** autopsy-clean buys

| tag | sym | mc | age_h | h1 | m5 | dex | mint |
|-----|-----|----|-------|----|----|-----|------|
| PRIOR | ElonThrust | 1698886 | 3.38 | 24.18 | -0.08 | pumpswap | `pFibPnQk…` |
| PRIOR | $1 | 162485 | 1.53 | 323 | 15.53 | pumpswap | `5qjzEB3b…` |
| PRIOR | OPTIMA | 147215 | 1.45 | 186 | 13.22 | pumpswap | `DdVXE425…` |
| PRIOR | Caramel | 129758 | 1.05 | 112 | 18.78 | pumpswap | `63UjR7d4…` |
| PRIOR | Irene | 124986 | 2.07 | 4.48 | None | pumpswap | `NqZaNi1v…` |
| PRIOR | Irene | 114243 | 3.45 | 39.78 | -0.89 | pumpswap | `6VdcMnBT…` |
| PRIOR | Irene | 64036 | 1.44 | 154 | 15.87 | pumpswap | `6N4BHPN8…` |
| PRIOR | FI | 43316 | 0.68 | 2.77 | -11.01 | pumpswap | `GjuiYGJi…` |
| PRIOR | Tesla | 21768 | 0.89 | 627 | None | pumpfun | `6KEm7GHT…` |
| PRIOR | DJT | 16375 | 0.9 | 306 | -9.96 | pumpfun | `5aGRLchK…` |
| PRIOR | YERN | 13559 | 3.37 | 27.33 | 16.86 | pumpfun | `PdtREY9H…` |

### Prior FAILs (stand — no material structure improvement)
- ElonThrust `pFib…pump` (~$1.7M, 3.38h) — clone theme / prior structural FAIL
- $1 `5qjz…pump` (~$162k, h1 +323) — RC rugged creator history; creator ~5.7%; LP unlocked — do not chase flagged-creator pump
- OPTIMA `DdVX…pump` (~$147k, h1 +186) — holder-band / sniper structure from 0720/0802
- Caramel `63Uj…pump` (~$130k, m5 +18) — prior FAIL
- Irene×3 `NqZa…` / `6Vdc…` / `6N4B…` — copycats; skip
- FI `Gjui…pump` (m5 −11 fading) — prior FAIL
- Tesla `6KEm…pump` — RC rugged creator; 51% holder
- DJT `5aGR…` (m5 −10) — Copycat / creatorBal 0 / band
- YERN `PdtR…yern` — prior FAIL

## Young pre-screen (<30m, no-buy by narrative-age)
- **TCAT** `AD7Wvdut…` (0.03h, ~$51032, h1 19.59, pumpswap)
- **JOE** `6yfQL6Fq…` (0.09h, ~$16751, h1 367, pumpfun)
- **pump** `6nN3B3jP…` (0.13h, ~$15069, h1 275, pumpfun)

### Autopsies
- **JOE** "EmotiGuy" `6yfQL6Fqfe9SnhLVxZxjGaWAQboBb8YYqZBYceP4pump` (0.09h, ~$16.8k, on curve) — **FAIL**: creatorBal **0**; **18×** 1–5% band on 703 holders; top non-curve wallets clustered ~1.9–2.9%; has X link but structure dead. `rc-JOE-0849.json` / `autopsy-summary-JOE-0849.json`
- **TCAT** "Tesla Cat" `AD7WvdutwV3XyJypm5VrDG7bbtxLFgdqMLkMKndLpump` (0.03h, ~$51k, post-grad) — **FAIL** stands (0844): creatorBal **0**; **15×** band; Tesla Cat copycat theme. `rc-TCAT-0849.json`
- **pump** `6nN3…pump` (0.13h, ~$15k) — too young; not re-autopsied (0846 note stands)

## Action
**NO_BUY — stay in SOL.** 0 NEW in-window; young JOE/TCAT both FAIL structure. Prefer cash over borderline.

Kraken: watch-only; no proposal.


# ===== scout-0928.md =====

# Scout 0928 — 2026-10-16 09:28 ET

## Wallet
- SOL: **0.29760554** (`wallet-sol-0928.json`)
- SOL/USD: **~$105.48** → est. **~$31.39**
- SPL: USDC dust 6e-06 only; Token-2022 all zero — **no meme positions**

## Scout counts
- lists: boosts latest/top + profiles + CTOs → `lists.txt`
- pf-live: 50 (`pf-live-0928.json`)
- scan: 142 mints → `cands-0928.json` / `scan-0928.out`
- expand: **638 mints / 561 pairs** → `expand-0928.out`
- strict in-window (0.5–4h, mc≥$10k, h1>0, pumpfun|pumpswap): **6**
- NEW: **2** (SOCKSS, EI)
- young (<0.5h): **4** (Scud, INU, RIBBIT, ELON)

## Autopsies
| Sym | Mint | Role | Verdict | One-line |
|-----|------|------|---------|----------|
| SOCKSS | Egk3…pump | NEW | **FAIL** | creatorBal 0; 11× 1.0–1.1% sniper band; fresh post-grad |
| EI | 8qGJ…pump | NEW | **FAIL** | creatorBal 0; 19× 1–5% band; top10ex≈26.6%; insiderNetworks |
| RIBBIT | 78ZB…pump | YOUNG | **FAIL** | too young + creatorBal 0 |
| Scud | 74St…pump | YOUNG | **FAIL** | too young + creatorBal 0 + tight bands |
| INU | 5xri…pump | YOUNG | **FAIL** | too young + creatorBal 0 + 19× band |
| $1 / OPTIMA / Irene / pump | — | PRIOR | prior FAIL stands | structural; not re-autopsied |

## Decision
**NO_BUY** — stay in SOL. Prefer cash over any borderline; zero autopsy-clean candidates.

## Artifacts
- `wallet-sol-0928.json`, `wallet-spl-0928.json`, `wallet-t22-0928.json`, `sol-price-0928.json`
- `lists.txt`, `boosts-*-0928.json`, `profiles-latest-0928.json`, `ctos-latest-0928.json`, `pf-live-0928.json`
- `scan0928.py`, `scan-0928.out`, `cands-0928.json`
- `expand0928.py`, `expand-0928.out`, `expanded-0928.json`, `inwindow-0928.json`, `new-0928.json`, `watch-extra-0928.json`
- `rc-{SOCKSS,EI,RIBBIT,Scud,INU}-0928.json`, `autopsy-summary-*-0928.json`
- `trade-log.md` appended


# ===== scout-0946.md =====

# Scout 0946 — 2026-10-16 09:46 ET

## Wallet
- SOL: **0.29760554** (`wallet-sol-0946.json`)
- SOL/USD: **~$105.32** → est. **~$31.34**
- SPL: USDC dust 6e-06 only; Token-2022 12 accounts all zero — **no meme positions**

## Scout counts
- lists: boosts latest/top + profiles + CTOs → `lists.txt`
- pf-live: 50 (`pf-live-0946.json`)
- scan: **143 mints** → 71 cands → `cands-0946.json` / `scan-0946.out`
- expand: **650 mints / 573 pairs** → `expand-0946.out`
- strict in-window (0.5–4h, mc≥$10k, h1>0, pumpfun|pumpswap): **2**
- NEW: **0**
- young (<0.5h): **11** (Audaster, ETR, BROG×2, RIBBIT, Twin, AI, UMBRA, Konasu, Halloween, OHM)

## Autopsies
| Sym | Mint | Role | Verdict | One-line |
|-----|------|------|---------|----------|
| $1 | 5qjz…pump | PRIOR | prior FAIL stands | rugged creator / structural |
| OPTIMA | DdVX…pump | PRIOR | prior FAIL stands | creatorBal≈0 + sniper bands (0720/0802/0808) |
| Audaster | 3xmz…pump | YOUNG | **FAIL** | creatorBal 0; ~$928k / 0.30h — sold-out deployer |
| ETR | BALf…pump | YOUNG | **FAIL** | still <30m; top10ex 28.7%; **14×** 2.3–2.5% sniper band |
| BROG | CUfB…pump | YOUNG | **FAIL** | creatorBal 0; ~$216k post-grad |
| RIBBIT | 78ZB…pump | YOUNG | **FAIL** | creatorBal 0 + graphInsiders=9 |
| Twin | 7Jai…pump | YOUNG | **FAIL** | creatorBal 0 |
| UMBRA | Axbj…pump | YOUNG | **FAIL** | Copycat (RC 2001); creatorBal≈0; top10ex 25.4% |
| AI | GX1J…pump | YOUNG | **FAIL** | creatorBal 0 + graphInsiders=4 |
| Konasu | 93RF…pump | YOUNG | **FAIL** | creatorBal 0 |
| OHM | 5SQv…pump | YOUNG | **FAIL** | creatorBal 0 |
| Halloween | 8y4b…pump | YOUNG | **WATCH** | too young; creator still holds; thin 124 holders / ~$10k — recheck ≥30m |

## Decision
**NO_BUY** — stay in SOL. Zero NEW in-window; every notable young fails structural vetting (or is still <30m WATCH). Prefer cash.

## Artifacts
- `wallet-sol-0946.json`, `wallet-spl-0946.json`, `wallet-t22-0946.json`, `sol-price-0946.json`
- `lists.txt`, `boosts-*-0946.json`, `profiles-latest-0946.json`, `ctos-latest-0946.json`, `pf-live-0946.json`
- `scan0946.py`, `scan-0946.out`, `cands-0946.json`
- `expand0946.py`, `expand-0946.out`, `expanded-0946.json`, `inwindow-0946.json`, `new-0946.json`, `watch-extra-0946.json`
- `rc-{Audaster,ETR,BROG,RIBBIT,Twin,UMBRA,OHM,AI,Halloween,Konasu}-0946.json`, `autopsy-summary-*-0946.json`
- `_prior-rejects-0946.json`, `trade-log.md` appended


# ===== scout-0959.md =====

# Scout 0959 — 2026-10-16 09:59 ET

Wallet **0.29760554 SOL** (~$31.44 at SOL $105.63). SPL USDC dust only; Token-2022 none. **No meme positions.**

## Pipeline
- Refreshed Dexscreener boosts latest/top + profiles + CTOs → `lists.txt`
- `pf-live-0959.json` (50)
- `scan0959.py` → 145 mints / 79 cands (`scan-0959.out` / `cands-0959.json`)
- `expand0959.py` → 655 mints / 575 pairs → **5** strict in-window, **0** NEW, **7** young

## In-window (0.5–4h, mc≥$10k, h1>0, pumpfun/pumpswap)
- **PRIOR** Audaster `3xmzHi86…` mc~$1,608,001 age 0.51h h1 2672 m5 80.53 pumpswap
- **PRIOR** ETR `BALftXRK…` mc~$257,949 age 0.58h h1 485 m5 -23.8 pumpswap
- **PRIOR** OPTIMA `DdVXE425…` mc~$153,816 age 2.6h h1 33.75 m5 -6.83 pumpswap
- **PRIOR** RIBBIT `78ZBbCJk…` mc~$58,943 age 0.65h h1 35.42 m5 72.17 pumpswap
- **PRIOR** INU `5xri1bAx…` mc~$12,412 age 0.65h h1 162 m5 57.33 pumpfun

## Autopsy (aged-into-window recheck + young pre-screen)
- **Audaster** [inwindow_recheck] **FAIL**: creatorBal 0 (dev sold out early)
- **BFRG** [too_young] **FAIL**: age 0.37h <30m — no-buy by narrative-age; RC Low Liquidity (score 2884); creatorBal 0 (dev sold out early); 19× 1–5% holder band
- **ETR** [inwindow_recheck] **FAIL**: top10ex 26.7% elevated >25%; 9× tight 2.0–2.2% sniper band; 18× 1–5% holder band
- **INU** [inwindow_recheck] **FAIL**: creatorBal 0 (dev sold out early); 19× 1–5% holder band
- **Konasu** [too_young] **FAIL**: age 0.37h <30m — no-buy by narrative-age; creatorBal 0 (dev sold out early); 16× 1–5% holder band
- **OPTIMA** [inwindow_recheck] **FAIL**: top10ex 37.1%>30%; 16× 1–5% holder band
- **RIBBIT** [inwindow_recheck] **FAIL**: creatorBal 0 (dev sold out early); 15× 1–5% holder band
- **SKILL** [too_young] **FAIL**: age 0.2h <30m — no-buy by narrative-age; creatorBal 0 (dev sold out early); 18× 1–5% holder band
- **Scud** [too_young] **FAIL**: age 0.29h <30m — no-buy by narrative-age; RC Low Liquidity (score 2864); creatorBal 0 (dev sold out early)
- **Twin** [too_young] **FAIL**: age 0.39h <30m — no-buy by narrative-age; creatorBal 0 (dev sold out early); top10ex 31.0%>30%; 19× 1–5% holder band
- **UMBRA** [too_young] **FAIL**: age 0.36h <30m — no-buy by narrative-age; RC Copycat; top10ex 28.8% elevated >25%; 18× 1–5% holder band
- **catJAM** [too_young] **FAIL**: age 0.26h <30m — no-buy by narrative-age; RC Low Liquidity (score 2699); creatorBal 0 (dev sold out early); 19× 1–5% holder band

## Devil's advocate
No coin clears structural bars. Audaster/RIBBIT/INU creatorBal=0; ETR still shows ~9× 2.0–2.2% sniper band + top10ex~27%; OPTIMA top10ex~37% + bands. Momentum (Audaster m5 +80, RIBBIT +72, INU +57) does not fix sold-out creator / sniper bands. Would not put most of the SOL into any of these.

## Decision
**Action: none — stay in SOL.** 0 autopsy-clean buys.


# ===== scout-1003.md =====

# Scout 1003 — 2026-10-16 10:03 ET

## Wallet
- RPC **0.29760554 SOL** (`wallet-sol-1003.json`); SPL dust USDC only (6e-06); Token-2022 12 accounts all zero; **no meme positions**.
- SOL ~$105.58. Est. total ~$31.42.

## Pipeline
- DexScreener boosts latest/top + profiles + CTOs (5 sol) + pf-live 50 → `lists.txt`
- `scan1003.py` → 147 mints / 79 cands (`scan-1003.out` / `cands-1003.json`)
- `expand1003.py` → **657 mints / 578 pairs** (`expand-1003.out`)
- Strict in-window (0.5–4h, mc≥10k, h1>0, pumpfun/pumpswap): **5** (NEW 0 / PRIOR 5)
- Young (<30m): **4**
- Autopsy-clean buys: **0**

## In-window
| tag | symbol | mint | mc | age_h | h1 | m5 | dex |
|-----|--------|------|----|-------|----|----|-----|
| PRIOR | Audaster | `3xmzHi86…` | 1435908 | 0.6 | 2376 | -6.65 | pumpswap |
| PRIOR | ETR | `BALftXRK…` | 240111 | 0.67 | 449 | -26.39 | pumpswap |
| PRIOR | RIBBIT | `78ZBbCJk…` | 99592 | 0.74 | 129 | 12.83 | pumpswap |
| PRIOR | Irene | `6N4BHPN8…` | 52380 | 2.68 | 4.32 | None | pumpswap |
| PRIOR | INU | `5xri1bAx…` | 14978 | 0.75 | 217 | 19.65 | pumpfun |

## Young (<30m)
| symbol | mint | mc | age_h | h1 | m5 |
|--------|------|----|-------|----|----|
| UMBRA | `Axbj7Jdz…` | 37180 | 0.45 | 979 | 60.89 |
| Konasu | `93RFugk8…` | 16388 | 0.47 | 311 | 34.87 |
| BFRG | `FMwuYPDg…` | 13936 | 0.47 | 282 | 53.91 |
| Twin | `7Jain9Ef…` | 147533 | 0.48 | 225 | 27.39 |

## Autopsy verdicts
- **Audaster** [inwindow_recheck] **FAIL**: creatorBal 0 (dev sold out early)
  - `rc-Audaster-1003.json` / `autopsy-summary-Audaster-1003.json` (top10ex=3.48, band_1_5=1, creatorBal=0, rc_score=1)
- **ETR** [inwindow_recheck] **FAIL**: 18× 1–5% holder band; 8× tight 1.8–2.0% sniper band
  - `rc-ETR-1003.json` / `autopsy-summary-ETR-1003.json` (top10ex=19.1, band_1_5=18, creatorBal=14849142185973, rc_score=1)
- **RIBBIT** [inwindow_recheck] **FAIL**: creatorBal 0 (dev sold out early); 16× 1–5% holder band; 6× tight 1.1–1.3% sniper band; 9 graph insiders
  - `rc-RIBBIT-1003.json` / `autopsy-summary-RIBBIT-1003.json` (top10ex=18.91, band_1_5=16, creatorBal=0, rc_score=1)
- **Irene** [inwindow_recheck] **FAIL**: creator 42.2%>5%; top10ex 50.74%>30%; 9× identical ~0.9% holdings; RC Low Liquidity
  - `rc-Irene-1003.json` / `autopsy-summary-Irene-1003.json` (top10ex=50.74, band_1_5=0, creatorBal=422156439268901, rc_score=8228)
- **INU** [inwindow_recheck] **FAIL**: creatorBal 0 (dev sold out early); top10ex 27.51% elevated >25%; 18× 1–5% holder band
  - `rc-INU-1003.json` / `autopsy-summary-INU-1003.json` (top10ex=27.51, band_1_5=18, creatorBal=0, rc_score=1)
- **UMBRA** [too_young] **FAIL**: age 0.45h <30m — no-buy by narrative-age; RC Copycat token; top10ex 27.97% elevated >25%; 18× 1–5% holder band; 7× tight 1.2–1.4% sniper band
  - `rc-UMBRA-1003.json` / `autopsy-summary-UMBRA-1003.json` (top10ex=27.97, band_1_5=18, creatorBal=1, rc_score=2001)
- **Konasu** [too_young] **FAIL**: age 0.47h <30m — no-buy by narrative-age; creatorBal 0 (dev sold out early); 19× 1–5% holder band; 5× tight 1.1–1.3% sniper band
  - `rc-Konasu-1003.json` / `autopsy-summary-Konasu-1003.json` (top10ex=19.88, band_1_5=19, creatorBal=0, rc_score=1)
- **BFRG** [too_young] **FAIL**: age 0.47h <30m — no-buy by narrative-age; creatorBal 0 (dev sold out early); top10ex 25.14% elevated >25%; 19× 1–5% holder band; 7× tight 1.1–1.3% sniper band; RC Low Liquidity
  - `rc-BFRG-1003.json` / `autopsy-summary-BFRG-1003.json` (top10ex=25.14, band_1_5=19, creatorBal=0, rc_score=2811)
- **Twin** [too_young] **FAIL**: age 0.48h <30m — no-buy by narrative-age; creatorBal 0 (dev sold out early); 19× 1–5% holder band; 7× tight 1.0–1.2% sniper band; 5 graph insiders
  - `rc-Twin-1003.json` / `autopsy-summary-Twin-1003.json` (top10ex=19.13, band_1_5=19, creatorBal=0, rc_score=1)

## Devil's advocate
No coin clears structural bars. Audaster/RIBBIT/INU/Konasu/BFRG/Twin creatorBal=0; ETR still shows heavy 1–5% + tight sniper bands; Irene creator ~42% + top10ex~51%; UMBRA Copycat + bands. Momentum (RIBBIT m5 +13, INU +20, young UMBRA/Konasu/BFRG/Twin m5 +27–61) does not fix sold-out creator / sniper bands / copycats / whale creator. Would **not** put most of ~0.30 SOL into any of these.

## Decision
**Stay in SOL.** Zero PASS. Kraken watch-only — no proposal.


# ===== scout-2026-10-15-2048.md =====

# pump.fun scout — 2026-10-15 ~20:51 ET
Data: DexScreener (UA), public Solana RPC, RugCheck. **Report only — no trades.**

## Wallet snapshot `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
| Asset | Amount | ~USD |
|-------|--------|------|
| SOL | 0.346122757 | ~$36.50 @ $105.43 |
| SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump` | 19,904.206434 (Token-2022 ATA) | ~$5.12 @ $0.0002571 |
| Other *pump ATAs | NULLCASH / SPOOKY / Macca / etc. | **0** (exited) |
| USDC/USDT dust | ~0 | negligible |

RPC confirms sole non-zero meme position is SYCAMORE.

## SYCAMORE status (PumpSwap primary)
| Field | Value |
|-------|-------|
| price | $0.0002571 |
| mcap | **$249.3k** (entry ~$300k → **~−17%**) |
| liq | $47.7k |
| m5 / h1 / h6 / h24 | **+1.5% / −21.5% / −10.1% / +407%** |
| m5 tx | 24B / 13S |
| h1 tx | 301B / 248S (buys still > sells) |
| vol h1 | ~$67k |
| age | **~17.0h** (past 30m–3h prefer window; “leaders only”) |
| boosts | 100 (still on DexScreener top boosts) |
| RugCheck | score 1, rugged=false, mint/freeze **revoked**, risks=[], graphInsiders=0, ~3317 holders; top10 ex-#1 ≈ **~13%** (healthy); LP mostly locked on summary |

Position is small (~$5). Dry powder is mostly SOL.

## Rotate scout
Universe: DexScreener boosts latest/top + token profiles + multi-query search (`pump`, `solana`, `meme`, `bonk`, `pepe`, `cat`, `ai`, `cto`) → **~99** unique Solana `*pump` mints; pair stats fetched for **~64**.

### Numeric filter (mc $50–450k, liq≥$15k, age≥1h, h1≥+20%, buys>sells h1, not botty)
**Passers: 0**

### Notable rejects (closest)
| Token | mint (short) | Why rejected |
|-------|--------------|--------------|
| Starman | H2pkm…pump | h1 +22%, buys>>sells, but **mc $815k** (>450k); age 4.6h |
| OWLDACITY | D61pT…pump | mc $745k; h1 flat; **6908 buys/h** botty risk |
| DICKBUTTIFIER | — | h1 +19.6% (shy of 20), mc $25k, liq $12k |
| STREAM | Diy4Q… | mc $157k in band but **h1 −0.8%**, sells>buys |
| VICE | 2uwxx… | mc $77k, h1 −8.4% |
| PONK | 4jjQj… | h1 −21% |
| DIKSHIT | AMQ8B… | h1 −12% |
| CBUCKS / SI276 | — | mc >450k / old |
| Most boosts | — | wrong mc band, red h1, thin liq, or sub-1h |

No numeric passer → **no RugCheck buy-vetting required** this cycle. Spot-checked summaries on SYCAMORE + a few boost names: low scores / LP locked; not actionable without momentum filter pass.

## Recommendation: **HOLD**
1. **No BUY** — zero candidates clear the desk filters; chasing Starman at $815k or red/flat midcaps is outside rules.
2. **No SELL SYCAMORE** (devil’s advocate below) — bag is ~$5; realizing −17% adds pennies of SOL and exits a still-buy-biased tape (301/248 h1) with clean RugCheck and active boosts. Better keep the lottery stub while hunting a real rotate.
3. **Park dry powder in SOL** — 0.346 SOL (~$36.5) stays dry until a passer appears.

### Devil’s advocate — why one *might* sell SYCAMORE
- h1 **−21%** / h6 **−10%** after a +400% day = distribution risk.
- Age **17h** ≫ preferred narrative window; “leaders only” bar is higher and mc is sliding from entry.
- Tiny size means opportunity cost of attention, not capital — if desk wants a clean slate for the next scout, sell is low-regret in USD terms.

**Counter:** sells would not fund a better name tonight (none passed). m5 still green; buys>sells; structure clean. Default = **HOLD**.

## Kraken /markets (watch-only)
Latest snapshot 2026-10-15 09:50 ET: total **~$103**, USD cash **$0.81** (below actionable min), action=none. Spot bags BTC/ETH/SOL only. **No proposal** — cash not actionable; pump.fun desk SOL is separate.

## Action for desk
**HOLD** — no trade. Re-scout when a *pump* clears mc/liq/age/h1/flow filters.


# ===== scout-20261015-1553.md =====

# pump.fun scout — Oct 15 2026 ~4:00 PM ET (data from DexScreener + RugCheck, SOL ~$105.87)
## Wallet BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF (public RPC)
- SOL: 0.002163681 (~$0.23) — NOT $19.54
- Token: 6,446,857.69 of EBgMjwNFEVEMJcsamJWEW65tBcjLnqncnxtEQU6dpump (no DexScreener pair, pump.fun API returns no coin -> likely dead/unpriced)
- 2 empty Token-2022 accounts (pumpCmXq..., NFLX7q...)
## Picks (top10 excl. #1 holder assumed pool/curve)
1. Macca — AKotzk1dhcNangAJBtvNKtT9bhbSVZc2mMhRFgkFpump — PumpSwap, mc $249k, liq $48k, 1h +96%, 24h +502%, vol24 $1.33M, 1h buys 806/sells 604, 4,102 holders, top10 38.5% incl pool (~24% excl), creator 0, mint/freeze revoked. Size $7
2. SYCAMORE — 3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump — PumpSwap, mc $291k, liq $51k, 1h +9.9%, 24h +492%, vol24 $3.72M, buys 257/sells 187, 3,261 holders, top10 22.1% (~13% excl pool), creator ~0.1%, revoked. Size $6
3. NULLCASH — 31GYUbJW5vjF1o7VM5SGP9Emj5WDBHb1cdcR8BM6pump — still on bonding curve, mc $22.4k, 1h +43%, 24h +636%, vol24 $212k, buys 176/sells 95, 712 holders, top10 57% incl curve (~25% excl), creator ~0, revoked. Lottery ticket. Size $4
## Rejected
STREAM (top10 ex-pool ~41%, 133 insiders, creator ~6.5%), PONK (~42% ex-pool, 58 insiders), p0f (~33%), CBUCKS (creator 1%, ~31%), GROKBOT (7065 buys vs 839 sells in 1h = bot pattern), NODF (two mints same ticker, absurd mc), DacityCoin (sells 2x buys), sub-1h coins.


# ===== scout-2113.md =====

# pump.fun scout 2113 ET — watch-only
Generated: 2026-10-15 21:17:19 ET

## Wallet (RPC mainnet-beta)
- Address: BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF
- SOL: 0.346122758 (~$36.55 @ $105.6/SOL)
- Tokens with balance>0:
  - SYCAMORE 3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump: 19,904.206434 tok (~$6.44)
  - USDC dust: 6e-06 (ignore)
- Surprise positions: NONE (Token + Token2022 scanned; only SYCAMORE + dust USDC)
- Est. total portfolio: ~$42.99

## SYCAMORE
- mc: $313,850 | liq: $53,862 | dex: pumpswap
- priceUsd: 0.0003236
- m5: 6% | h1: 31.28% | h6: 9.88% | h24: 538%
- h1 buys/sells: 430/199 | m5 buys/sells: 72/17
- h1 vol: $96,814
- age: ~17.4h | entry mcap was ~$300k → now ~$313,850 (slightly above entry)
- RugCheck: score 1/100-scale-ish (raw score 1), risks=[], graphInsiders=0, mintAuth=None, freezeAuth=None, LP locked ~100% (summary), top10 ex-pool ~13.0%
- **Recommendation: HOLD**
- Devil's advocate (if dumping): age 17h is past the ideal 0.5–3h meme window; a sudden buy/sell flip + drawdown would justify exit — but right now buys≃2.2× sells and h1 +31% with solid liq, so hold.

## Numeric passers (strict filter)
Count: **1** (excluding SYCAMORE itself)

### 1) XTV — 6MBf1XdZNSAaDKcxxbnCAngRUxBmwbHS5Ybe2rLRpump
- mc $132,332 | h1 +28.87% | m5 +2.55% | liq $33,974 | age **75.4h** | h1 b/s 41/29 | vol_h1 ~$4.5k
- RugCheck summary: score 1, risks=[], lpLockedPct=0
- Full: mint/freeze auth None, graphInsidersDetected=**8**, top10 ex-pool ~26.2%, creator ANDiQ6L6…, creatorTokens empty
- **Autopsy: FAIL** — graph-insiders=8 (threshold ~handful); top10-ex-pool~26.2%>25%; age 75h past narrative; thin h1 flow 41/29 not a clear leader vs parking SOL; lpLockedPct=0
- Does NOT beat parking SOL + holding SYCAMORE (thin flow, late, insider graph).

## Near-misses in 0.5–3.5h (not passers)
- GCLASS mc~$232k h1+247 but liq only ~$2.1k → FAIL liq
- DRAINLOVE mc~$43k age 0.6h → FAIL mc+age
- AKITA / MOO undersized; saluteface & Motion = prior rejects / botty

## Prior rejects
Not re-recommended (no new evidence): STREAM, DacityCoin, Nihilism, saluteface, VICE, Motion, OWLDACITY, Starman, CRS, TrumpCoin, Macca.

## ACTION
**none** — hold SYCAMORE; keep ~0.35 SOL dry powder. No buy / no rotate. Only numeric passer (XTV) fails pre-buy autopsy.

## Key files
- /workspace/pumpfun/wallet-sol-2113.json
- /workspace/pumpfun/wallet-tokens-2113.json
- /workspace/pumpfun/wallet-tokens2022-2113.json
- /workspace/pumpfun/sycamore-pairs-2113.json
- /workspace/pumpfun/boosts-latest-2113.json
- /workspace/pumpfun/boosts-top-2113.json
- /workspace/pumpfun/profiles-2113.json
- /workspace/pumpfun/dex-search-*-2113.json
- /workspace/pumpfun/pairs-by-mint-2113.json
- /workspace/pumpfun/scan-2113.txt
- /workspace/pumpfun/cands-2113.json
- /workspace/pumpfun/cands-filter-2113.json
- /workspace/pumpfun/rc-sum-6MBf1XdZ-2113.json / rc-full-6MBf1XdZ-2113.json
- /workspace/pumpfun/rc-sum-3EC7gRDG-2113.json / rc-full-3EC7gRDG-2113.json
- /workspace/pumpfun/pf-2113-*.json
- /workspace/pumpfun/scout-2113.md (this file)


# ===== scout-2141.md =====

# pump.fun scout 2141 ET — watch-only
Generated: 2026-10-15 21:44 ET

## Wallet (RPC mainnet-beta)
- Address: BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF
- SOL: 0.346122758 (~$36.40 @ $105.16/SOL)
- Tokens with balance>0:
  - SYCAMORE 3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump: 19,904.206434 tok (~$6.29)
  - USDC dust: 6e-06 (ignore)
- Surprise positions: NONE (Token + Token2022 scanned; only SYCAMORE + dust USDC)
- Est. total portfolio: ~$42.69

## SYCAMORE
- mc: $306,328 | liq: $53,273 | dex: pumpswap
- priceUsd: 0.0003159
- m5: +20.32% | h1: +24.8% | h6: +5.65% | h24: +523%
- h1 buys/sells: 665/302 | m5 buys/sells: 48/16
- h1 vol: $139,404
- age: ~17.9h | entry mcap ~$300k → now ~$306k (**~+2.1%**)
- RugCheck summary: score 14401 / normalised 55; **new** risk flag vs 21:13 (was score 1, risks=[]): "Creator history of rugged tokens" (danger). Full: graphInsiders=0, mint/freeze auth None, lpLockedPct~100%, top10 ex-LP ~14%, creator 4ksbmVvz… has 6 other same-day tokens stuck ~$2.9k mc. Token itself not marked rugged.
- Dump gate: **NOT met** — mc well above $180–200k; m5/h1 buys ≫ sells; price bouncing (was ~$199k at 21:29, now $306k).
- **Recommendation: HOLD**
- Note: creator-rug history flag is a vigilance item, not a dump trigger while flow stays buy-heavy and mc holds. Revisit if mc breaks <$180–200k with sells ≥ buys.

## Numeric filter
Universe: DexScreener boosts latest/top + profiles + searches (pump/pumpswap/pumpfun/meme/new solana meme/graduated pump) + frontend-api-v3 currently-live / last_trade / market_cap / created (+ scan.py lists).
- Unique Solana `*pump` pairs evaluated: **208**
- Numeric passers (mc $50–450k or strong curve $15–80k, liq≥$15k or active curve, age 0.5–3.5h or clear late leader, h1≥+20%, buys>sells, non-botty, not prior reject): **0**

### Near misses (not passers — no autopsy)
- $OTCOIN / SPACEMAN / CatTok / AKITA — age <0.5h (CatTok also botty 2481 buys/h)
- GTA `6S7jwQuVipHu…pump` — curve mc~$30k, age 3.7h (just past 3.5h), h1 +22%, 202b/82s — late / not clear leader (needs h1≥40)
- UNBUY / Whaleoween — late age 7–9h, thin curve, not leaders
- Prior rejects excluded without re-run: STREAM, VICE, Nihilism, Motion, saluteface, PONK, DIKSHIT, grokazon, BOT, FTR, Macca, CRS, DEXTERM, XTV, OWLDACITY, Starman, Quentra, etc.

## Autopsy
**Skipped** — 0 numeric passers (per run rules).

## ACTION
**none** — hold SYCAMORE; keep ~0.35 SOL dry powder. Nothing beats parking SOL + SYCAMORE bag this cycle.

## Key files
- /workspace/pumpfun/wallet-sol-2141.json
- /workspace/pumpfun/wallet-tokens-2141.json
- /workspace/pumpfun/wallet-tokens2022-2141.json
- /workspace/pumpfun/sycamore-pairs-2141.json
- /workspace/pumpfun/sol-price-2141.json
- /workspace/pumpfun/boosts-latest-2141.json / boosts-top-2141.json / profiles-2141.json
- /workspace/pumpfun/dex-search-*-2141.json
- /workspace/pumpfun/pf-2141-*.json
- /workspace/pumpfun/scan-2141.txt / cands.json / pairs-all-2141.json
- /workspace/pumpfun/cands-filter-2141.json / cands-near-2141.json
- /workspace/pumpfun/rc-sum-3EC7gRDG-2141.json / rc-full-3EC7gRDG-2141.json
- /workspace/pumpfun/scout-2141.md (this file)


# ===== scout-2146.md =====

# pump.fun scout 2146 ET — watch-only
Generated: 2026-10-15 21:48 ET

## Wallet (RPC mainnet-beta)
- Address: BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF
- SOL: 0.346122758 (~$36.38 @ $105.11/SOL)
- Tokens with balance>0:
  - SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump`: 19,904.206434 tok (~$7.11 @ $0.0003572)
  - USDC dust: 6e-06 (ignore)
- Surprise positions: NONE (Token + Token2022 scanned; only SYCAMORE + dust)
- Est. total portfolio: ~$43.49

## SYCAMORE
- mc: $346,415 | liq: $56,776 | dex: pumpswap
- priceUsd: 0.0003572
- m5: +21.66% | h1: +38.36% | h6: +17.55% | h24: +604%
- h1 buys/sells: 676/302 | m5 buys/sells: 44/13
- h1 vol: $140,958
- age: ~18.0h | entry mcap ~$300k → now ~$346k (**~+15.5%**)
- RugCheck summary: score 14401 / normalised 55; risk "Creator history of rugged tokens" (danger). Token itself rugged=false. mint/freeze auth None, lpLockedPct~100%, graphInsiders=0. Top holder is LP (~10.5%); next holders ~1–2.5% each (top10 ex-LP well under 25%). Creator `4ksbmVvz…` has 6 other same-day tokens stuck ~$2.9k mc.
- Dump gate: **NOT met** — mc well above $180–200k; m5/h1 buys ≫ sells; momentum strengthening vs 21:41 ($306k → $346k).
- **Recommendation: HOLD**
- Vigilance: creator-rug history flag unchanged; not a dump trigger while flow stays buy-heavy and mc holds. Revisit if mc breaks <$180–200k with sells ≥ buys sustained.

## Numeric filter
Universe: DexScreener boosts latest/top + profiles + searches (pump/pumpswap/pumpfun/meme/new solana meme/graduated pump) + frontend-api-v3 currently-live / last_trade / market_cap / created (+ mint merge).
- Unique Solana `*pump` best-pairs: **212**
- Evaluated after exclude own/prior rejects: **183**
- Numeric passers: **0**

### Near misses / close calls (not passers — no autopsy)
- `1` Gn8Xti76…pump — mc~$291k liq~$46k age 0.58h h1 +529% — **botty** (9259 h1 buys)
- dih / ROGCAN / $DEAD — age <0.5h (curve)
- GTA `6S7jwQuVipHu…pump` — curve mc~$30k, age 3.76h, h1 +16% (cooled; fails mom + late)
- Prior rejects still hot but excluded: STREAM (live), VICE, PONK, FTR (botty), grokazon (botty), BOT, QUENTRA

## Autopsy
**Skipped** — 0 numeric passers (per run rules).

## ACTION
**none** — hold SYCAMORE; keep ~0.35 SOL dry powder. Nothing beats parking SOL + SYCAMORE bag this cycle.

## Key files
- /workspace/pumpfun/wallet-sol-2146.json
- /workspace/pumpfun/wallet-tokens-2146.json / wallet-tokens2022-2146.json
- /workspace/pumpfun/sycamore-pairs-2146.json
- /workspace/pumpfun/sol-price-2146.json / sol-price-2146-meta.json
- /workspace/pumpfun/boosts-latest-2146.json / boosts-top-2146.json / profiles-2146.json
- /workspace/pumpfun/dex-search-*-2146.json
- /workspace/pumpfun/pf-2146-*.json
- /workspace/pumpfun/pairs-all-2146.json / cands-filter-2146.json / cands-near-2146.json / cands-meta-2146.json
- /workspace/pumpfun/rc-sum-3EC7gRDG-2146.json / rc-full-3EC7gRDG-2146.json
- /workspace/pumpfun/scout-2146.md (this file)


# ===== scout-2156.md =====


## 2026-10-15 21:58 ET — position watch (no trade)
SOL ~$105. Wallet SOL 0.346122758 (~$36.35, unchanged since 20:42 exit). Prices via DexScreener + RPC.
- SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump`: 19,904.21 tok @ $0.0002756, mcap $267.3k vs entry ~$300k (**~−10.9%**, ~$5.49). m5 −6.1% (47b/39s) · h1 +7.6% (728b/351s) · liq $49.7k. Buyers ~2:1 on h1 — dump gate not met; hold. RC creator-rug flag = vigilance only.
- Est. total ~$41.84 (incl. SOL).
Scout: 167 Solana `*pump` mints (boosts latest/top + profiles + pf live/last_trade/mc) → 147 pairs → **2** numeric passers, **0** rotate targets.
- VICE `2uwxxiD1PshoPrrSoNvttRD8Aa1nwxVDTFf4JK36pump` (mc $128k, h1 +67%, liq $35k, age 9.4h) — FAIL: past 3h narrative window; thin h1 flow (43/41); prior concentration reject.
- PONK `4jjQjDRYd7xLcFMViRsz4GvtgU6gPZgbVaxN3Rq9pump` (mc $114k, h1 +55%, age 24.8h) — FAIL: far past narrative window; prior concentration reject.
- Near rejects: Holdoween/CatTok/`1`/FTR (age <1h + botty 5k–11k buys/h); STREAM (sells≥buys + prior concentration).
Nothing beats parking ~0.35 SOL + SYCAMORE bag. Kraken: watch-only; no proposal.
Action: none.


# ===== scout-2203.md =====

# pump.fun scout 2203/2204 ET — watch-only
Generated: 2026-10-15 22:06 ET

## Wallet (RPC mainnet-beta)
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.346122758** (~$36.35 @ $105.03/SOL)
- Tokens with balance>0:
  - SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump`: **19,904.206434** tok (~$6.86 @ $0.0003445)
  - USDC dust: 6e-06 (ignore)
- Surprise positions: NONE (Token + Token2022 scanned)
- Est. total portfolio: **~$43.21**

## SYCAMORE
- mc: **$334,137** | liq: **$55,854** | dex: pumpswap
- priceUsd: 0.0003445
- m5: **+6.06%** | h1: **+41.5%** | h6: +16% | h24: +579%
- h1 buys/sells: **747/392** | m5 buys/sells: **60/38**
- h1 vol: ~$173k
- age: ~18.3h | entry mcap ~$300k → now ~$334k (**~+11.4%**)
- RugCheck (22:05 ET): score 1 / normalised 1; risks=[]; rugged=false; mint/freeze auth None; lpLockedPct~100%; graphInsidersDetected=0. Top holder is LP (~8.7%); next ~1–2.5% each (top10 ex-LP well under 25%). Creator `4ksbmVvz…` — prior runs flagged creator-rug history; current summary empty (still vigilance-only, not a dump trigger).
- Dump gate: **NOT met** — mc well above $180–200k; m5/h1 buys ≫ sells; h1 momentum strong (+41%).
- **Recommendation: HOLD**

### Devil's advocate (sell case — rejected)
Could argue taking profit into strength: bag is only ~$6.86 (~16% of book), creator previously showed multi-token same-day rugs, and 18h age is past the 0.5–3h narrative window so mean-reversion risk rises. Counter: dump gate requires breakdown below ~$180–200k with sells≥buys on m5/h1 — none of that is present (mc $334k, 747/392 h1, 60/38 m5). On-chain concentration is healthy (LP-led, no graph insiders, mint/freeze revoked, LP ~100% locked). Selling here would crystallize a small win and forfeit the run while flow remains buy-heavy. **Do not sell.**

## Scout / numeric filter
Universe: DexScreener boosts latest/top + profiles + searches (pump/pumpswap/pumpfun/meme/new solana meme/graduated pump) + frontend-api-v3 currently-live / last_trade / market_cap / created (+ lists.txt merge).
- Unique Solana `*pump` mints: **243**
- Best-pairs resolved: **168**
- Numeric passers (mc $15k–$450k, liq≥$15k, age≥1h, h1≥+20%, buys>sells, not botty): **0**
- Autopsy: **skipped** (0 passers)

### Near rejects (not passers — no autopsy)
- `1` `Gn8Xti76…pump` — mc~$319k liq~$49k age **0.88h** h1 +603% — **YOUNG + botty** (12,959 h1 buys)
- CatTok `A5YQxuXB…pump` — mc~$213k liq~$39k age **0.70h** h1 +368% — **YOUNG + botty** (6,423 h1 buys)
- FTR `Afkbv7ea…pump` — mc~$58k age 1.0h h1 +41% — **botty** (12,237 h1 buys on small mc; m5 −41%)
- PONK `4jjQjDRY…pump` — mc~$96k h1 +35% age 24.9h — **prior reject + past narrative**
- VICE `2uwxxiD1…pump` — mc~$116k h1 **−18%** age 9.6h sells>buys — cooled; prior reject
- STREAM `Diy4Q5ai…pump` — mc~$188k h1 +8.6% sells≥buys — fails mom + flow
- grokazon / KWIF / Motion — weak or botty / negative h1

## ACTION
**none** — hold SYCAMORE; keep ~0.35 SOL dry powder. Nothing beats parking SOL + SYCAMORE bag this cycle. No BUY, no SELL.

## Key files
- /workspace/pumpfun/wallet-sol-2204.json / wallet-tokens-2204.json / wallet-tokens2022-2204.json
- /workspace/pumpfun/sycamore-2204.json / sycamore-2204-final.json / sol-price-2204.json
- /workspace/pumpfun/boosts-latest-2204.json / boosts-top-2204.json / profiles-latest-2204.json
- /workspace/pumpfun/dex-search-*-2204.json / pf-2204-*.json
- /workspace/pumpfun/mints-2204.txt / pairs-all-2204.json
- /workspace/pumpfun/cands-filter-2204.json / cands-near-2204.json / cands-meta-2204.json
- /workspace/pumpfun/rc-sum-3EC7gRDG-2204.json / rc-full-3EC7gRDG-2204.json
- /workspace/pumpfun/scout-2203.md (this file)

---
## Append-ready log block
```
## 2026-10-15 22:06 ET — position watch (no trade)
SOL ~$105.03. Wallet SOL 0.346122758 (~$36.35). Prices via DexScreener + RPC.
- SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump`: 19,904.21 tok @ $0.0003445, mcap $334.1k vs entry ~$300k (**~+11.4%**, ~$6.86). m5 +6.1% (60b/38s) · h1 +41.5% (747b/392s) · liq $55.9k. Buyers ~1.9:1 on h1 — dump gate not met; hold.
- Est. total ~$43.21 (incl. SOL).
Scout: 243 Solana `*pump` mints → 168 pairs → **0** numeric passers, **0** rotate targets.
- Near: `1`/CatTok (age <1h + botty 6k–13k buys/h); FTR (botty); PONK/VICE (prior/cooled); STREAM (sells≥buys).
Nothing beats parking ~0.35 SOL + SYCAMORE bag. Action: none.
```


# ===== scout-2204.md =====

# pump.fun scout 2203/2204 ET — watch-only
Generated: 2026-10-15 22:06 ET

## Wallet (RPC mainnet-beta)
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.346122758** (~$36.35 @ $105.03/SOL)
- Tokens with balance>0:
  - SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump`: **19,904.206434** tok (~$6.86 @ $0.0003445)
  - USDC dust: 6e-06 (ignore)
- Surprise positions: NONE (Token + Token2022 scanned)
- Est. total portfolio: **~$43.21**

## SYCAMORE
- mc: **$334,137** | liq: **$55,854** | dex: pumpswap
- priceUsd: 0.0003445
- m5: **+6.06%** | h1: **+41.5%** | h6: +16% | h24: +579%
- h1 buys/sells: **747/392** | m5 buys/sells: **60/38**
- h1 vol: ~$173k
- age: ~18.3h | entry mcap ~$300k → now ~$334k (**~+11.4%**)
- RugCheck (22:05 ET): score 1 / normalised 1; risks=[]; rugged=false; mint/freeze auth None; lpLockedPct~100%; graphInsidersDetected=0. Top holder is LP (~8.7%); next ~1–2.5% each (top10 ex-LP well under 25%). Creator `4ksbmVvz…` — prior runs flagged creator-rug history; current summary empty (still vigilance-only, not a dump trigger).
- Dump gate: **NOT met** — mc well above $180–200k; m5/h1 buys ≫ sells; h1 momentum strong (+41%).
- **Recommendation: HOLD**

### Devil's advocate (sell case — rejected)
Could argue taking profit into strength: bag is only ~$6.86 (~16% of book), creator previously showed multi-token same-day rugs, and 18h age is past the 0.5–3h narrative window so mean-reversion risk rises. Counter: dump gate requires breakdown below ~$180–200k with sells≥buys on m5/h1 — none of that is present (mc $334k, 747/392 h1, 60/38 m5). On-chain concentration is healthy (LP-led, no graph insiders, mint/freeze revoked, LP ~100% locked). Selling here would crystallize a small win and forfeit the run while flow remains buy-heavy. **Do not sell.**

## Scout / numeric filter
Universe: DexScreener boosts latest/top + profiles + searches (pump/pumpswap/pumpfun/meme/new solana meme/graduated pump) + frontend-api-v3 currently-live / last_trade / market_cap / created (+ lists.txt merge).
- Unique Solana `*pump` mints: **243**
- Best-pairs resolved: **168**
- Numeric passers (mc $15k–$450k, liq≥$15k, age≥1h, h1≥+20%, buys>sells, not botty): **0**
- Autopsy: **skipped** (0 passers)

### Near rejects (not passers — no autopsy)
- `1` `Gn8Xti76…pump` — mc~$319k liq~$49k age **0.88h** h1 +603% — **YOUNG + botty** (12,959 h1 buys)
- CatTok `A5YQxuXB…pump` — mc~$213k liq~$39k age **0.70h** h1 +368% — **YOUNG + botty** (6,423 h1 buys)
- FTR `Afkbv7ea…pump` — mc~$58k age 1.0h h1 +41% — **botty** (12,237 h1 buys on small mc; m5 −41%)
- PONK `4jjQjDRY…pump` — mc~$96k h1 +35% age 24.9h — **prior reject + past narrative**
- VICE `2uwxxiD1…pump` — mc~$116k h1 **−18%** age 9.6h sells>buys — cooled; prior reject
- STREAM `Diy4Q5ai…pump` — mc~$188k h1 +8.6% sells≥buys — fails mom + flow
- grokazon / KWIF / Motion — weak or botty / negative h1

## ACTION
**none** — hold SYCAMORE; keep ~0.35 SOL dry powder. Nothing beats parking SOL + SYCAMORE bag this cycle. No BUY, no SELL.

## Key files
- /workspace/pumpfun/wallet-sol-2204.json / wallet-tokens-2204.json / wallet-tokens2022-2204.json
- /workspace/pumpfun/sycamore-2204.json / sycamore-2204-final.json / sol-price-2204.json
- /workspace/pumpfun/boosts-latest-2204.json / boosts-top-2204.json / profiles-latest-2204.json
- /workspace/pumpfun/dex-search-*-2204.json / pf-2204-*.json
- /workspace/pumpfun/mints-2204.txt / pairs-all-2204.json
- /workspace/pumpfun/cands-filter-2204.json / cands-near-2204.json / cands-meta-2204.json
- /workspace/pumpfun/rc-sum-3EC7gRDG-2204.json / rc-full-3EC7gRDG-2204.json
- /workspace/pumpfun/scout-2203.md (this file)

---
## Append-ready log block
```
## 2026-10-15 22:06 ET — position watch (no trade)
SOL ~$105.03. Wallet SOL 0.346122758 (~$36.35). Prices via DexScreener + RPC.
- SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump`: 19,904.21 tok @ $0.0003445, mcap $334.1k vs entry ~$300k (**~+11.4%**, ~$6.86). m5 +6.1% (60b/38s) · h1 +41.5% (747b/392s) · liq $55.9k. Buyers ~1.9:1 on h1 — dump gate not met; hold.
- Est. total ~$43.21 (incl. SOL).
Scout: 243 Solana `*pump` mints → 168 pairs → **0** numeric passers, **0** rotate targets.
- Near: `1`/CatTok (age <1h + botty 6k–13k buys/h); FTR (botty); PONK/VICE (prior/cooled); STREAM (sells≥buys).
Nothing beats parking ~0.35 SOL + SYCAMORE bag. Action: none.
```


# ===== scout-2209.md =====

# pump.fun scout 2209 ET — watch-only
Generated: 2026-10-15 22:14 ET

## Wallet (RPC mainnet-beta)
- Address: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF`
- SOL: **0.346122758** (~$36.35 @ $105.01/SOL)
- Tokens with balance>0:
  - SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump`: **19,904.206434** tok (~$6.52 @ $0.0003276)
  - USDC dust: 6e-06 (ignore)
- Surprise positions: NONE (Token + Token2022 scanned)
- Est. total portfolio: **~$42.87**

## SYCAMORE
- mc: **$317,754** | liq: **$54,495** | dex: pumpswap
- priceUsd: 0.0003276
- m5: **−3.64%** | h1: **+9.01%** | h6: +7.35% | h24: +546%
- h1 buys/sells: **746/423** | m5 buys/sells: **72/52**
- h1 vol: ~$186k
- age: ~18.4h | entry mcap ~$300k → now ~$318k (**~+5.9%**)
- RugCheck (22:13 ET): score 1 / normalised 1; risks=[]; rugged=false; mint/freeze auth None; lpLockedPct~100%; graphInsidersDetected=0. Top holder LP (~8.7%); top10 ex-LP ~16.6% (under 25%). Creator `4ksbmVvz…` balance ~0.13% supply (not a dump trigger). Prior runs flagged creator-rug history elsewhere — vigilance-only.
- Dump gate: **NOT met** — mc well above $180–200k; m5/h1 buys ≫ sells; h1 still green (+9%).
- **Recommendation: HOLD**

### Devil's advocate (sell case — rejected)
Could argue trimming into a cool-down: h1 momentum faded from ~+41% (22:06 scout) to +9%, m5 is lightly red (−3.6%), bag is only ~$6.52 (~15% of book), age ~18h is past the 0.5–3h narrative window, and creator still holds a token balance (albeit ~0.13%). Counter: dump gate requires breakdown below ~$180–200k **with** sells≥buys on m5/h1 — none of that is present (mc $318k, 746/423 h1, 72/52 m5). On-chain concentration remains healthy (LP-led, 0 graph insiders, mint/freeze revoked, LP ~100% locked). Selling now crystallizes a small paper win and forfeits residual upside while flow is still buy-heavy. **Do not sell.**

## Scout / numeric filter
Universe: DexScreener boosts latest/top + profiles + searches (pump/pumpswap/pumpfun/meme/new solana meme/graduated pump) + frontend-api-v3 currently-live / last_trade / market_cap / created (+ lists.txt merge).
- Unique Solana `*pump` mints: **241**
- Best-pairs resolved: **228**
- Numeric passers (mc $15k–$450k, liq≥$15k, age≥1h, h1≥+20%, buys>sells, not botty; age>3h needs h1≥+40%): **1**
- Autopsy clean: **0**

### Numeric passer → autopsy
- PONK `4jjQjDRYd7xLcFMViRsz4GvtgU6gPZgbVaxN3Rq9pump` — mc~$98k liq~$27k age **25.0h** h1 +62% (801/537) — **REJECT**
  - Holders: top10 ex-curve/LP **36.2%** (FAIL >30%)
  - Insiders: graphInsidersDetected=**61**; 6 transfer nets ~10.8% supply (FAIL)
  - Dev hold: creatorBalance=0 (PASS)
  - Deployer history: no creatorTokens in RugCheck / empty creator coins list (INCONCLUSIVE; prior reject)
  - Bundle (early/block-0): recent swap-api sample only (100 trades ~6m window) — no 8+ identical SOL cluster; residual insider graph used as proxy (FAIL soft)
  - Socials: X @PEPEBONKK joined 2026-10-07, 374 foll / 218 tweets (not empty — soft PASS)
  - Narrative: **25h** ≫ 0.5–3h preferred window (FAIL)
  - Prior scouts (2156/2203/2204): concentration / past-narrative reject — confirmed

### Near rejects (not passers — no autopsy)
- `1` `Gn8Xti76…pump` — mc~$404k liq~$55k age **0.97h** h1 +790% — **YOUNG + botty** (15,662 h1 buys)
- CatTok `A5YQxuXB…pump` — mc~$157k liq~$33k age **0.79h** h1 +245% — **YOUNG + botty** (7,383 h1 buys)
- NVIDIA `Bjr6DbMs…pump` — mc~$450k age **0.12h** h1 +930% — **YOUNG**
- Before GTA `Ewzy4cxD…pump` — mc~$61k age **0.20h** h1 +34% — **YOUNG**
- Holdoween `3UYqfnBm…pump` — mc~$905k (over MC cap) + age 0.69h + botty
- STREAM `Diy4Q5ai…pump` — mc~$180k h1 +5% sells>buys — fails mom + flow
- FTR / EI / DJT — over MC and/or botty

## ACTION
**none** — hold SYCAMORE; keep ~0.35 SOL dry powder. Sole numeric passer (PONK) failed autopsy (holders + insiders + age). Nothing beats parking SOL + SYCAMORE bag this cycle. No BUY, no SELL.

## Key files
- /workspace/pumpfun/wallet-sol-2209.json / wallet-tokens-2209.json / wallet-tokens2022-2209.json
- /workspace/pumpfun/sycamore-2209.json / sycamore-2209-final.json / sol-price-2209.json / sol-price-2209-meta.json
- /workspace/pumpfun/boosts-latest-2209.json / boosts-top-2209.json / profiles-latest-2209.json
- /workspace/pumpfun/dex-search-*-2209.json / pf-2209-*.json
- /workspace/pumpfun/mints-2209.txt / pairs-all-2209.json
- /workspace/pumpfun/cands-filter-2209.json / cands-near-2209.json / cands-meta-2209.json
- /workspace/pumpfun/autopsy-PONK-2209.json / rc-sum-PONK-2209.json / rc-full-PONK-2209.json
- /workspace/pumpfun/rc-sum-3EC7gRDG-2209.json / rc-full-3EC7gRDG-2209.json
- /workspace/pumpfun/scout-2209.md (this file)

---
## Append-ready log block
```
## 2026-10-15 22:14 ET — position watch (no trade)
SOL ~$105.01. Wallet SOL 0.346122758 (~$36.35). Prices via DexScreener + RPC.
- SYCAMORE `3EC7gRDGKgqPHc9ipJxxChoeyseE2xAbQHZUSSTfpump`: 19,904.21 tok @ $0.0003276, mcap $317.8k vs entry ~$300k (**~+5.9%**, ~$6.52). m5 −3.6% (72b/52s) · h1 +9.0% (746b/423s) · liq $54.5k. Buyers ~1.8:1 on h1 — dump gate not met; hold.
- Est. total ~$42.87 (incl. SOL).
Scout: 241 Solana `*pump` mints → 228 pairs → **1** numeric passer (PONK) → **0** autopsy-clean. PONK REJECT: top10 ex-LP 36% + 61 graph-insiders + age 25h.
- Near: `1`/CatTok/NVIDIA (age <1h ± botty); STREAM (sells≥buys); Holdoween over MC.
Nothing beats parking ~0.35 SOL + SYCAMORE bag. Action: none.
```


# ===== scout-2322.md =====

# Scout 23:22 ET Oct 15 2026 — all-SOL book, hunt for clean buy

Wallet: BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF — **0.378250232 SOL** (RPC confirmed, unchanged since SYCAMORE dump). SOL ~$105.45 → ~$39.90.

## Scan
- Fresh boosts/profiles + Dex search + pf live → scan.py **140 mints** → `scan-2322.out` / `cands.json`
- Broader sweep **173 mints** → in-window 10k–500k / 0.4–4h listed in `cands-window-2322.json`
- **0** autopsy-clean buy candidates

## Autopsies (FAIL any = skip)

### GTA `6S7jwQuVipHuEaASAZ9Kn7r3Zy3jkebhAMFxnuWnpump` (only numeric passer at scan time)
- Dex: pumpswap mc ~$38–40k, age ~1.15h, then **m5/h1 −17 to −22%** (440b/350s) — momentum broke
- RC score 1 / mint+freeze none / creatorTokens 0 — else clean
- **FAIL holders:** #1 whale **GyYkhdyJ… 22.96%**; #2 is pump AMM LP N34x… 20%. Top10 ex-LP ≫30% (~45%+)
- **FAIL:** graphInsidersDetected **14**
- Socials: own X @grandtheftcoi + gtacoin.tech + discord (OK) — still skip on holders/insiders/dump

### ETERNAL `4XUmT22L7LN2e1us3bLHpPFKtkGUk9cAKQXEr3wXpump` (pf live curve)
- mc ~$13.8k (<$15k pref), age ~0.8h, h1 +314% 210b/49s
- **FAIL:** creator still holds **~6.63%** (>~5%)
- **FAIL socials:** empty Dex socials / no own X
- top10 ex-curve ~22% OK-ish; RC score 1

### Before GTA `Ewzy4cxD7LsB86pUziRZrAXar6z8KWyNNg4WYEJspump`
- **FAIL holders:** top10 ex-#1 ~64%; #2 alone ~40%; 4 graph insiders; borrowed Dexerto tweet; dumping

### Prior rejects still in window (not re-bought)
- STARMAN DiveEY… — RC score_norm 55, LP 100% unlocked danger, borrowed X status
- BANANA 6vs4… — botty 12k buys/h, age <1h, concentration
- MENTOR 7XoH… — prior top10 ex-curve ~37%
- FSD CgbB… — dumping −70%+ h1, concentrated, age 0.5h
- TESLON / DarkStar / GPU / `1` / STREAM / PONK / Nihilism / DEXTERM — prior rejects or past window

## Verdict
**NO BUY.** Stay all SOL (~0.3783). No autopsy-clean setup in the 0.5–3h / $15–450k / real-flow window.


# ===== scout-2346.md =====

# Scout 23:46 ET Oct 15 2026 — all-SOL book, hunt for clean buy

Wallet: `BXc3ju3mY68Kx9bM5f7akE2urdsNe7SiSpMmxzsVjyNF` — **0.378250232 SOL** (RPC `getBalance` confirmed).  
Token accounts: dust USDC `0.000006` + USDT 0; all Token-2022 meme ATAs **0** (empty SYCAMORE / prior bags). Book = **all SOL**.  
SOL USD used: **~$105.02** (DexScreener SOL pairs) → book ≈ **$39.72**.

## Scan
- Refreshed `lists.txt` (boosts latest/top + profiles latest) + `pf-live.json` (50 live)
- `python3 scan.py` → **143 mints** → `scan-2346.out` / `cands.json` (83 vol/age rows)
- Broader Dex token fetch + search → `all-scout-pairs-2346.json` / `cands-window-2346.json`
- **Strict numeric passers** (mc $15–450k, age 0.5–3.5h, h1 ≥+20%, buys>sells, not botty, pump mint, not prior-reject): **0**
- **Autopsy-clean buys: 0**

## Autopsies (FAIL any = skip)

### IKE `FZ9jKav6BAEEaBZtq6RPpMnVupQdopvvMiocZMEVpump` (best near-miss)
- Dex: pumpfun bonding, mc ~$15.9k, liq n/a (curve), age **~4.1h** (past 3.5h narrative window), m5 −3%, h1 +27–31%, **47b/39s** (thin), m5 1b/3s
- RC: score 1 / mint+freeze none / graphInsiders **0** / creatorBalance **0** / bonding LP locked 100% on curve reserves
- Holders: #1 unlabeled ~38% (bonding curve) → **top9 ex-curve ~28.2%** (at 25–30% fail band; #2–#6 each ~3.1–3.7%)
- Socials: Dex = X **community** link only (`x.com/i/communities/...`); no own account / no site
- **FAIL:** age past window + thin flow + top10 ex-curve ~28% + weak socials. Not a leader.

### ETERNAL `4XUmT22L7LN2e1us3bLHpPFKtkGUk9cAKQXEr3wXpump` (prior reject — re-check)
- Dex/pf: still bonding, mc ~$14.6–14.7k (**under $15k floor**), age ~1.2h, h1 +133–138%, 122b/43s, m5 +1–2%
- RC: score 1 / 0 insiders / top9 ex-curve ~**18.8%** OK / mint+freeze none
- Creator: balance now **0** (was ~6.6% at 23:22) → **early dump** red flag
- Socials: pf shows `@MinesCryptoZNFT` + minescrypto.space; Dex socials still empty/null
- **FAIL:** prior reject; creator dumped; mc under floor. Do not chase.

### ONE / `1` `FSJbL5UjbZkkMWNeKnUgjG6PHQKdbhhycugDo1LCpump` (new mint, not Gn8)
- Dex: **graduated** pumpswap, mc ~$90–95k, liq ~$24–25k, age **~0.5h**, h1 +93–102%, **~4500–4700b / ~420s** (!), m5 −6 to −14% with 675b/68s
- RC: score 1 / 0 insiders / creatorBalance 0 / LP locked 100%; top10 ~29% (ex-#1 ~16% if #1 is AMM)
- Socials: own X `@inu1coin` + inu1coin.lol (OK on paper)
- **FAIL botty:** ≳4.5k buys/h on modest mc + brand-new graduation spike (expect 30–60% dip). Symbol/`1` adjacency to prior `1` reject. Skip.

### SUPERCYCLE `84AaE16zkQ97UqeRsbZwkkDQJn9L3v4nUqrMMZ3Xpump`
- Dex: pumpswap, mc ~$8.7–9.0k (**under floor**), liq ~$6.7–6.9k (**<$15k**), age ~1.5h, h1 +48%, 110b/83s
- RC: score_norm **18**, risk **Low Liquidity $2.3k**; holder table messy (top10 sum >100%); concentration extreme even ex-#1
- Socials: **borrowed tweet-only** (`x.com/gettindevvy/status/...`) — fail
- **FAIL:** mc/liq floors + borrowed socials + low liq warn.

### UNBUY `2XJTEyYAtrU4K4UBAzJY2cjr4BM29WWaofmPMjPbpump` (optional age-check)
- Age **~11.2h** (far outside window); top9 ex-curve ~**47%**; creator still ~1.6% supply
- **FAIL:** age + concentration. Not a buy.

## Prior rejects still in tape (not re-bought)
BANANA (botty 10k+/h), TESLON (creator rug history), GTA (whale+insiders), ROADSTER/RDSTR (revived/borrowed), DEXTERM, MENTOR (concentration), STARMAN, NINNY (insiders+creator sold+mc floor), BOT, DarkStar, STREAM, PONK, Nihilism, GPU, `1` Gn8, FSD, ETERNAL, Macca.

## Verdict
**HOLD SOL** — no autopsy-clean setup in the preferred 0.5–3.5h / $15–450k / real-flow window.  
Best near-miss IKE fails age + concentration + thin tape; only hot prints are botty graduation (`1` FSJb…) or prior rejects.  
Suggested size: n/a (no buy). Keep ≥0.02 SOL fee buffer; next entry still prefer ~0.08–0.15 SOL when a clean passer appears.


# ===== scout-2355.md =====


## 2026-10-15 23:57 ET — position watch (no trade)
SOL ~$105.25. Wallet SOL **0.378250232** (RPC; unchanged since SYCAMORE dump ~23:19). Book: **all SOL**, no meme positions. Est. total ~$39.81.
Scout: refreshed boosts/profiles + pf-live + Dex search → scan.py **146 mints** → 7 loose in-window → **0** autopsy-clean buys (`scan-2355.out` / `interesting-2355.json`).
- `123456` `hps4Xy4…pump` (was mc ~$43k / h1 +1276% on curve) — FAIL: top10 ex-curve ~35%; by autopsy time already graduated and crashed to mc ~$2.1k (−95% h1). Dead.
- roadster `CbAeScGT…pump` (curve mc ~$15.7k, age 1.9h, h1 +120%, 303b/212s) — FAIL: top10 ex-curve ~28.5%; **5 graph insiders**; socials = borrowed tweet only (`CoachPatNFT/status/…`); OTC-desk website; crowded ROADSTER copycat narrative.
- GPU `DBbBt37U…pump` (curve ~$15.8k, age 3.6h, h1 +45%) — FAIL: past narrative window; top10 ex-curve ~43%; 4 insiders; m5 sells>buys.
- Priors stand / not rebuy: ETERNAL (creator dumped), GTA (whale+insiders), BANANA/`1` (botty), ROADSTER Eizz/RDSTR (revived/borrowed), MENTOR/TESLON/BOT/IKE/DEXTERM/STREAM/PONK/Nihilism.
Action: **none — stay in SOL**. Kraken: watch-only; prior USD cash ~$0.81 below min; no proposal.
