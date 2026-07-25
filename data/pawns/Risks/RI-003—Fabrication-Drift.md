# RI-003 — Fabrication Drift

RISK ID: RI-003
NAME: Fabrication Drift
DESCRIPTION: When the agent writes a chapter or a substrate entry, the path of least resistance is to invent plausible detail. The substrate is dense, the receipts are real, but a single fabricated line — a date, a dollar figure, a name — destroys the operator's "undeniable" bar.
PROBABILITY: high (the temptation is always present; the cost of one slip is total)
IMPACT: catastrophic (the book becomes another "fabricated spaghetti code" project, and the operator's reputation is the cost)
MITIGATION: (a) Every pawns/ entry carries SOURCES: and FALSIFIER: lines. (b) Every quantitative claim is testable against the JSONL. (c) The MOA Voice Lock (SO-003) requires the agent to cite the receipt in the same paragraph as the claim. (d) The operator's prime directive ("no fabrication") is enforced in OPERATIONAL_RULES.md LAW 2.
EVIDENCE:
  - character_bible.md §Trump cites a $30M Adelson figure; vance_thiel_palantir_claims.jsonl row 0 cites a $15M Thiel figure; newsom_donors.jsonl row 0 cites $5.2M Hoffman — each is a quantitative claim that a fabricator might "round" or "estimate." The substrate does not round.
  - OPERATIONAL_RULES.md LAW 2: "No fabrication / no sycophancy / undeniable — Every factual claim must trace to a verified primary source (command + output, or a cited source I actually read). No invented codes, fees, stats, or 'remembered' facts."
LINKS: [VA-001]—Receipts-First-Principle, [SO-001]—Receipts-First-Pipeline, [SO-003]—MOA-Voice-Lock
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - receipt:vance_thiel_palantir_claims.jsonl#row0
  - receipt:newsom_donors.jsonl#row0
FALSIFIER: If any pawns/ entry's quantitative claim (e.g. $15M, $5.2M, $30M) does not match its cited receipt, fabrication has occurred. Test: spot-check any cited dollar figure against the cited JSONL row.
