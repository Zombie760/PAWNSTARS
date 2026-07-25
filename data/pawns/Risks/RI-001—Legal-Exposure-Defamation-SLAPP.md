# RI-001 — Legal Exposure (Defamation / SLAPP)

RISK ID: RI-001
NAME: Legal Exposure (Defamation / SLAPP)
DESCRIPTION: The book and the substrate name living public figures (Newsom, Vance, Hoffman, Thiel, Powell Jobs, Andreessen, Trump, etc.) with quantified claims against them. Each is a potential defendant in a defamation or Strategic Lawsuit Against Public Participation (SLAPP) action. The book operates without a publisher's legal team.
PROBABILITY: medium
IMPACT: catastrophic (a single successful SLAPP could end the book project and create financial liability for the operator).
MITIGATION: Every claim traces to a FEC, SEC, or DOJ-disclosed source. The substrate is the only ledger. Every entry in pawns/ carries a SOURCES: line and a FALSIFIER: line so the claim is testable, not rhetorical. The Receipts-First-Principle (VA-001) is the legal defense: "I asserted X because receipts X.1, X.2, X.3 say X, and they are falsifiable."
EVIDENCE:
  - newsom_donors.jsonl (25 rows) all carry FEC.gov URLs as sources.
  - character_bible.md is the operator's own claim ledger; its Falsifiable Claims sections are the test surface.
  - vance_thiel_palantir_claims.jsonl row 1 carries a separate falsifier for the White House visitor-logs claim — i.e. the operator has internalized "claims must be testable."
LINKS: [VA-001]—Receipts-First-Principle, [SO-001]—Receipts-First-Pipeline, [SO-002]—Source-Trace-Validator
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - receipt:newsom_donors.jsonl#row0
  - receipt:vance_thiel_palantir_claims.jsonl#row1
FALSIFIER: If any of the named public figures' FEC committee IDs does not in fact show the cited contribution, the risk is moot (because the claim is wrong, not because the risk is gone). Real risk realization test: a court would ask "did the operator know the claim was false?" The substrate proves the operator had receipts.
