# Ethics — SEAMLY2D

**Project:** SEAMLY2D  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/FashionFreedom/Seamly2D.git  
**Pinned commit:** `0627ac315f7b9aae6109e0961a59b98852e7aae0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `01c34990d489776e77d977aaa0b0d7d6ec958706002222243ce72396eba45aa3`  
**Date:** October 2026

## Position

SEAMLY2D is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
