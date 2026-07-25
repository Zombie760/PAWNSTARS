# RI-002 — Source Contamination

RISK ID: RI-002
NAME: Source Contamination
DESCRIPTION: The substrate is built from DOJ-disclosed documents (Epstein FTA, House Oversight release, Federal Register, JMail), FEC filings, and news reporting. Each source has a different contamination profile: the Epstein set is voluminous and partially redacted, the JMail index is third-party-curated, FEC filings are authoritative for amounts but not for intent, and news reporting is editorial. Mixing these without per-source class rules can produce false convergences.
PROBABILITY: medium-high
IMPACT: medium (contaminated entries degrade the substrate's integrity and weaken the entire chain).
MITIGATION: Every source in the substrate carries a `source_class` field (e.g. doj_release, jmail_index, news). The Source-Trace-Validator (SO-002) enforces that each claim's evidence citations resolve to a specific source class, not a generic "the substrate." Future: a per-claim contamination score (0-1) based on source-class entropy.
EVIDENCE:
  - house_oversight_2026-07-21.jsonl: every row carries source_class="doj_release" (verified by sample read of row 0).
  - efta_live_2026-07-21.jsonl: rows carry source_class="epsteinfta.com_live".
  - jmail_threads_2026-07-21.jsonl: source_class="jmail_index".
  - doj_fedregister_2026-07-21.jsonl: source_class="doj_release".
LINKS: [SO-002]—Source-Trace-Validator, [VA-001]—Receipts-First-Principle
SOURCES:
  - receipt:house_oversight_2026-07-21.jsonl#bates:HOUSE_OVERSIGHT_010477
  - receipt:efta_live_2026-07-21.jsonl#file:ddde6f756d6aa4fdba8369e0dadc5511
  - receipt:jmail_threads_2026-07-21.jsonl#row0
  - receipt:doj_fedregister_2026-07-21.jsonl#row0
FALSIFIER: If source_class fields in any of the cited JSONL files are missing or all set to the same value (no class variance), the contamination model is unverified.
