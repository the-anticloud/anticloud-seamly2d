# Students — SEAMLY2D

**Project:** SEAMLY2D  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/FashionFreedom/Seamly2D.git  
**Pinned commit:** `0627ac315f7b9aae6109e0961a59b98852e7aae0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `01c34990d489776e77d977aaa0b0d7d6ec958706002222243ce72396eba45aa3`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `0627ac315f7b9aae6109e0961a59b98852e7aae0`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `01c34990d489776e77d977aaa0b0d7d6ec958706002222243ce72396eba45aa3`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
