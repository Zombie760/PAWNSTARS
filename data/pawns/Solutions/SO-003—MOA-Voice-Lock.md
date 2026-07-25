# SO-003 — MOA Voice Lock

SOLUTION ID: SO-003
NAME: MOA Voice Lock (Multi-Output / Multi-Author)
DESCRIPTION: The book voice (Thompson rage + Ellis hyper-precision) is fragile to the agent's natural drift toward AI-smoothing. The MOA Voice Lock enforces that the writer model (1) cites the receipt in the same paragraph as the claim, (2) names the source class (doj_release, fec_filing, news) explicitly, and (3) refuses to assert any quantitative claim without a receipt ID.
APPLIES-TO: [PR-005]—Manufactured-Authenticity, [RI-003]—Fabrication-Drift
EVIDENCE:
  - character_bible.md supplies per-character voice profiles (Voice: Ellis + Thompson for Newsom; Voice: Palahniuk + Child for Vance; etc.).
  - newsom_donors.md and vance_thiel_palantir_claims.jsonl demonstrate the operator's house style: claim + receipt + falsifier, no smoothing.
  - BUQP voice rules (BUQP Voice Rules Validator) are the upstream enforcement mechanism.
LINKS: [VA-001]—Receipts-First-Principle, [SO-001]—Receipts-First-Pipeline, [PL-001]—Three-Deliverable-Plan
SOURCES:
  - receipt:character_bible.md#section:Vance
  - receipt:character_bible.md#section:Newsom
  - receipt:vance_thiel_palantir_claims.jsonl#row0
FALSIFIER: If a book chapter ships with an unsourced quantitative claim (e.g. "$15M" without a citation), the voice lock has failed. Test: run BUQP voice validator on each chapter draft.
