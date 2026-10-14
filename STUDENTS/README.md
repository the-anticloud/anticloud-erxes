# Students — ERXES

**Project:** ERXES  
**Category:** MARKETING_TOOLS  
**Upstream:** see BENCH.json  
**Pinned commit:** `see BENCH.json`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ce634191ff3f7c90d54d233dff93f87dae17cb3268fe7474678297ccfdadc5fd`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `see BENCH.json`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `ce634191ff3f7c90d54d233dff93f87dae17cb3268fe7474678297ccfdadc5fd`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
