# Independent Insurance — HUGIN

**Project:** HUGIN  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `5658f26d4c176e3b6052dc0a6f400f5a45a6ec83`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a59cccea3b638027380b5d319dacadcf0d01aec128abc18556e12ee08de2c179`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | HUGIN with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `a59cccea3b638027380b5d319dacadcf0d01aec128abc18556e12ee08de2c179`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
