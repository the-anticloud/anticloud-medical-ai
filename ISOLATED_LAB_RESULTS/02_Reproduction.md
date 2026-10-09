# Reproduction — MEDICAL_AI

1. Environment: Windows, Python 3.12.10, runner version 1.0.0
2. `cd anticloud/`
3. `python tools\run_bench.py --quiet`  (exit 0 = all 16 PASS)
4. Compare `anticloud/BENCH.json` SHA3-256: `ecc3d369a9cd995bd5fd62a751be3876182a156858a9454697f0ae8606e52862`

The `anticloud/` overlay is a standalone copy of the anticloud_reference tree; the 16 checks run against it via `tools/run_bench.py`.
