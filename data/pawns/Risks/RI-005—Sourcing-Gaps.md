# RI-005 — Sourcing Gaps

RISK ID: RI-005
NAME: Sourcing Gaps
DESCRIPTION: The substrate is comprehensive but not exhaustive. vance_rogan_crossref.jsonl is structured, but the operator has not built a corresponding "Newsom-Crossref" or "Hoffman-Crossref" — i.e. the OMISSION/CONTRADICTION/CONSISTENT analysis that Vance got has not been done for other principals. vance_all_claims.jsonl has 139 rows, but the corresponding newsom_all_claims.jsonl does not exist.
PROBABILITY: high (the gaps are real and visible)
IMPACT: medium (a book that dissects Vance's public persona but not Newsom's loses force; a reader notes the asymmetry)
MITIGATION: Three-Deliverable-Plan (PL-001) — one of the three deliverables is to expand the crossref coverage to all named principals. Substrate-Gathering-Plan (PL-002) includes running a per-principal claim crossref script.
EVIDENCE:
  - vance_rogan_crossref.jsonl: 8 rows, all Vance-specific.
  - vance_all_claims.jsonl: 139 rows of Vance-related claims.
  - newsom_donors.jsonl: 25 donor rows but no public-utterance crossref.
  - character_bible.md §Netanyahu, §Barak, §Kushner, §Adelson, §Mossad, §CIA, §MI6, §Black Cube — all have falsifiable claims but no corresponding crossref.
LINKS: [PL-001]—Three-Deliverable-Plan, [PL-002]—Substrate-Gathering-Plan, [SO-001]—Receipts-First-Pipeline
SOURCES:
  - receipt:vance_rogan_crossref.jsonl#row0
  - receipt:vance_rogan_crossref.jsonl#row7
  - receipt:vance_all_claims.jsonl#row0
FALSIFIER: If a per-principal crossref already exists in the substrate (e.g. newsom_rogan_crossref.jsonl), the gap is closed. Test: list `/home/gringo/botwave/journalism/pawns/substrate/ | grep crossref`.
