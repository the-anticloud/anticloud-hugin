# Educators — HUGIN

**Project:** HUGIN  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `5658f26d4c176e3b6052dc0a6f400f5a45a6ec83`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a59cccea3b638027380b5d319dacadcf0d01aec128abc18556e12ee08de2c179`  
**Date:** October 2026

## Teaching with HUGIN

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `a59cccea3b638027380b5d319dacadcf0d01aec128abc18556e12ee08de2c179` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
