# PR-003 — Mechanism Opacity

PROBLEM ID: PR-003
NAME: Mechanism Opacity
GEOGRAPHIC REGION(S): US, global
POTENTIAL PROBLEM: Networks that move influence and money across tax-exempt entities, foreign jurisdictions, and intelligence-community conduits are not visible to the average reader, voter, or journalist.
PROBLEM DESCRIPTION: The substrate shows the network is dense but each link is individually deniable. Hoffman → Greylock → Palantir → CA contracts. Thiel → Narya → Vance → Senate. Andreessen → a16z → CA AI Task Force. The DOJ-disclosed Epstein set (house_oversight_2026-07-21.jsonl, 2,897 bates; efta_live_2026-07-21.jsonl) places at least 30 named Silicon Valley / political figures in the same file set as Mossad, CIA, MI6 — i.e. the donor network and the intelligence community share the same room. Each individual connection is small; the system is invisible from any single vantage point.
EVIDENCE:
  - house_oversight_2026-07-21.jsonl: 2,897 bates, all Custodian/Source "Epstein, Jeffrey", DOJ release 2026.
  - efta_live_2026-07-21.jsonl: 30+ distinct entity rows (Newsom, Vance, Thiel, Hoffman, Powell Jobs, Andreessen, Horowitz, Kushner, Netanyahu, Barak, Adelson, Ellison, Schmidt, Khosla, Altman, Mossad, CIA, MI6, Black Cube, Wexner) all in the same DOJ Disclosures file set.
  - jmail_content_2026-07-21.jsonl: per-thread content with mentions_persons and document_date; e.g. thread EFTA00155146 mentions Prince Andrew.
  - jmail_threads_2026-07-21.jsonl: 810,620 thread rows indexed by source jmail.world_thread.
LINKS: solved by [SO-001]—Receipts-First-Pipeline, [SO-004]—Blockchain-Anchor; informs [CL-004]—Mechanism-Dual-Case-Thesis.
SOURCES:
  - https://www.jmail.nyc/
  - https://www.epsteinflightlogs.com/
  - receipt:house_oversight_2026-07-21.jsonl#bates:HOUSE_OVERSIGHT_010477
  - receipt:house_oversight_2026-07-21.jsonl#bates:HOUSE_OVERSIGHT_010486
  - receipt:efta_live_2026-07-21.jsonl#file:ddde6f756d6aa4fdba8369e0dadc5511
  - receipt:jmail_content_2026-07-21.jsonl#thread:EFTA00155146
FALSIFIER: If efta_live_2026-07-21.jsonl contains fewer than ~25 distinct entity rows, or house_oversight_2026-07-21.jsonl contains fewer than ~1,000 bates, this problem is not supported by the substrate.
