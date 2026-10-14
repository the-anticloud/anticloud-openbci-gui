# Educators — OPENBCI_GUI

**Project:** OPENBCI_GUI  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/OpenBCI/OpenBCI_GUI.git  
**Pinned commit:** `e23869e7b5cc621e733d8fa0d81f05d477264306`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `878f09218446ea52a3fc0efac919fcf0aff290edf8a0feadec497064191c7f8f`  
**Date:** October 2026

## Teaching with OPENBCI_GUI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `878f09218446ea52a3fc0efac919fcf0aff290edf8a0feadec497064191c7f8f` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
