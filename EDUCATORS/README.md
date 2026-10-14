# Educators — SEAMLY2D

**Project:** SEAMLY2D  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/FashionFreedom/Seamly2D.git  
**Pinned commit:** `0627ac315f7b9aae6109e0961a59b98852e7aae0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `01c34990d489776e77d977aaa0b0d7d6ec958706002222243ce72396eba45aa3`  
**Date:** October 2026

## Teaching with SEAMLY2D

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `01c34990d489776e77d977aaa0b0d7d6ec958706002222243ce72396eba45aa3` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
