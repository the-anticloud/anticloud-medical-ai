# Ethics — MEDICAL_AI

**Project:** MEDICAL_AI  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/Project-MONAI/MONAI.git  
**Pinned commit:** `a7904ae138c01cc90ad9c3bdf52c10218bde315f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `01fb83bf4aef8a091bdeba9d1208f380f5b68ee043ee2209aaeb42b6207de963`  
**Date:** October 2026

## Position

MEDICAL_AI is packaged for offline deployment with a verifiable audit trail. The
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
