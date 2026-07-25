# SO-001 — Receipts-First Pipeline

SOLUTION ID: SO-001
NAME: Receipts-First Pipeline
DESCRIPTION: Every claim in the pawns/ subgraph is paired with a JSONL receipt ID (`receipt:<filename>.jsonl#row|file|bates:<id>`). The pipeline is: (1) identify a public claim, (2) find the primary-source receipt, (3) write the pawns/ entry with a SOURCES: line that names the receipt, (4) write a FALSIFIER: line that names the test that would disprove the claim. If a claim has no receipt, it does not ship.
APPLIES-TO: [PR-001]—Money-Laundering-Through-Donor-Nets, [PR-003]—Mechanism-Opacity, [PR-004]—Donor-Vote-Alignment-Beyond-Constituency, [PR-005]—Manufactured-Authenticity
EVIDENCE:
  - All 30 entries in /home/gringo/Substrate/pawns/ carry SOURCES: and FALSIFIER: lines.
  - Validator output (planned): `grep -rE '^SOURCES:' /home/gringo/Substrate/pawns/ | wc -l` >= 30.
  - vance_thiel_palantir_claims.jsonl and vance_rogan_crossref.jsonl already implement the pipeline at the receipt level (each row carries source + falsifier).
LINKS: [SO-002]—Source-Trace-Validator, [VA-001]—Receipts-First-Principle, [PL-001]—Three-Deliverable-Plan
SOURCES:
  - receipt:vance_thiel_palantir_claims.jsonl#row0
  - receipt:vance_rogan_crossref.jsonl#row0
  - receipt:newsom_donors.jsonl#row0
FALSIFIER: If a pawns/ entry is published without a SOURCES: or FALSIFIER: line, the pipeline has failed. Test: `grep -rL '^SOURCES:' /home/gringo/Substrate/pawns/*/*.md | grep -v README | grep -v INDEX` should return empty.
