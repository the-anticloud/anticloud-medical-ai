# Students — MEDICAL_AI

**Project:** MEDICAL_AI  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/Project-MONAI/MONAI.git  
**Pinned commit:** `a7904ae138c01cc90ad9c3bdf52c10218bde315f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `01fb83bf4aef8a091bdeba9d1208f380f5b68ee043ee2209aaeb42b6207de963`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `a7904ae138c01cc90ad9c3bdf52c10218bde315f`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `01fb83bf4aef8a091bdeba9d1208f380f5b68ee043ee2209aaeb42b6207de963`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
