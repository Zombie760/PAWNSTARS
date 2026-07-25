# SO-004 — Blockchain Anchor for Substrate Receipts

SOLUTION ID: SO-004
NAME: Blockchain Anchor
DESCRIPTION: Hash every receipt in the substrate and submit the hash to a public chain (e.g. Telos or Bitcoin) at the time the receipt is loaded. This gives the operator a tamper-evident timestamp for every claim: "as of block N, this JSONL row existed." A reader can verify the substrate was not edited after publication.
APPLIES-TO: [PR-003]—Mechanism-Opacity, [RI-002]—Source-Contamination
EVIDENCE:
  - house_oversight_2026-07-21.jsonl carries MD5 Hash + Bates Begin per row (sample row 0: HOUSE_OVERSIGHT_010477 / Bates Begin HOUSE_OVERSIGHT_010477).
  - efta_live_2026-07-21.jsonl carries file_id (32-char hex) per row.
  - The operator's substrate already uses file_id as a natural unique key (e.g. ddde6f756d6aa4fdba8369e0dadc5511 = Newsom's DOJ-disclosed PDF).
LINKS: [SO-002]—Source-Trace-Validator, [VA-001]—Receipts-First-Principle, [PR-003]—Mechanism-Opacity
SOURCES:
  - receipt:house_oversight_2026-07-21.jsonl#bates:HOUSE_OVERSIGHT_010477
  - receipt:efta_live_2026-07-21.jsonl#file:ddde6f756d6aa4fdba8369e0dadc5511
  - https://epsteinfta.com/document/ddde6f756d6aa4fdba8369e0dadc5511
FALSIFIER: If a JSONL row's MD5 Hash (where present) does not match the actual file bytes, the anchor is broken. Test: recompute MD5 of a sample DOJ-disclosed PDF and compare.
