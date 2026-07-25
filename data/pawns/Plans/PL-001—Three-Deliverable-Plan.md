# PL-001 — Three-Deliverable Plan

PLAN ID: PL-001
NAME: Three-Deliverable Plan (Book + Substrate + Pipeline)
SCOPE: The Pawns-of-the-Mechanism book project, the substrate that feeds it, and the pipeline that produces both.
CHALLENGES:
  1. Substrate is 79MB of JSONL; the writer cannot hold it in context.
  2. Public persona and substrate reality are deliberately decoupled (PR-005).
  3. Sourcing coverage is asymmetric: Vance has crossref, Newsom does not (RI-005).
  4. Operator is one person with a 1-year-old; lead time is hours, not weeks.
MISSION: Ship three artifacts in 90 days: (D1) a 47k-word manuscript of *Pawns of the Mechanism* Book 1, (D2) a verified pawns/ subgraph with ≥30 entries and a passing substrate validator, (D3) a receipts-first pipeline that any operator can fork and run.
STRATEGIES:
  - D1 — Manuscript: Thompson cold opens + Ellis clinical precision voice, character-by-character from character_bible.md, each chapter anchored to a substrate entry.
  - D2 — Substrate: 30 entries across 8 categories (this integration run), each with SOURCES: + FALSIFIER: lines and ≥1 receipt per People/Claim/Risk/Solution/Problem entry.
  - D3 — Pipeline: Source-Trace-Validator (SO-002) + MOA Voice Lock (SO-003) + Blockchain Anchor (SO-004) packaged as a single botwave skill.
IDEAL WORLD: A reader can pick up the book, follow the receipt pointers to the substrate, follow the substrate pointers to the JSONL receipts, follow the JSONL pointers to the primary sources (FEC.gov, SEC EDGAR, epsteinfta.com), and reproduce every claim. The book is undeniable; the operator is paid.
LINKS: [PL-002]—Substrate-Gathering-Plan, [VA-001]—Receipts-First-Principle, [MO-001]—Thiel-Influence-Model, [SO-001]—Receipts-First-Pipeline
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - receipt:character_bible.md#section:Vance
  - receipt:character_bible.md#section:Newsom
  - receipt:vance_thiel_palantir_claims.jsonl#row0
FALSIFIER: If 90 days pass without (D1) ≥30k words shipped, (D2) ≥30 pawns/ entries passing the validator, and (D3) a runnable receipts-first pipeline, the plan has failed. Test: snapshot /home/gringo/Substrate/pawns/ and /home/gringo/botwave/journalism/pawns/substrate/ on day 90 and compare to day 0.
