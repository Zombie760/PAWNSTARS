# SO-002 — Source-Trace Validator

SOLUTION ID: SO-002
NAME: Source-Trace Validator
DESCRIPTION: A small CLI / library that, given a pawns/ entry, walks the SOURCES: block, resolves each URL or receipt pointer to a row in the botwave journalism substrate, and reports (a) resolved, (b) unresolvable (no matching row), (c) URL not in canonical SOURCES.md list. The validator is the substrate's CHECK 4 enforcer.
APPLIES-TO: [PR-001]—Money-Laundering-Through-Donor-Nets, [PR-002]—Regulatory-Capture, [RI-002]—Source-Contamination
EVIDENCE:
  - The pawns/SOURCES.md file lists every URL referenced by any entry (validator CHECK 4 demand).
  - receipt:<filename>.jsonl#row|file|bates:<id> pointers use the canonical row/file/bates IDs present in the JSONL.
  - vance_rogan_crossref.jsonl row 4 carries a source URL + a falsifier — i.e. the operator has already demonstrated the pattern at receipt level.
LINKS: [SO-001]—Receipts-First-Pipeline, [SO-004]—Blockchain-Anchor, [VA-001]—Receipts-First-Principle
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://epsteinfta.com/document/ddde6f756d6aa4fdba8369e0dadc5511
  - receipt:newsom_donors.jsonl#row0
  - receipt:vance_rogan_crossref.jsonl#row4
FALSIFIER: If a SOURCES: line points at a URL that is not in pawns/SOURCES.md, or at a receipt pointer that does not resolve to a row in the substrate, the validator should fail. Test: write the validator, run it on the existing 30 entries, confirm 0 failures.
