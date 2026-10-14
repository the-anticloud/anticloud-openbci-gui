# Students — OPENBCI_GUI

**Project:** OPENBCI_GUI  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/OpenBCI/OpenBCI_GUI.git  
**Pinned commit:** `e23869e7b5cc621e733d8fa0d81f05d477264306`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `878f09218446ea52a3fc0efac919fcf0aff290edf8a0feadec497064191c7f8f`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e23869e7b5cc621e733d8fa0d81f05d477264306`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `878f09218446ea52a3fc0efac919fcf0aff290edf8a0feadec497064191c7f8f`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
