# Students — HUGIN

**Project:** HUGIN  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `5658f26d4c176e3b6052dc0a6f400f5a45a6ec83`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a59cccea3b638027380b5d319dacadcf0d01aec128abc18556e12ee08de2c179`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `5658f26d4c176e3b6052dc0a6f400f5a45a6ec83`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `a59cccea3b638027380b5d319dacadcf0d01aec128abc18556e12ee08de2c179`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
