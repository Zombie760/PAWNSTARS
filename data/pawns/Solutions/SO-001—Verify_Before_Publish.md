# [SO-001] — Verify Before Publish
ID: SO-001

DESCRIPTION: Every claim in this subgraph must trace to a primary source. The loader enforces this by matching `SOURCES:` lines to the receipts JSONL.

SOURCES:
  - botwave_substrate.py (existing loader)
  - botwave-substrate/SKILL.md (validator CHECK 4)

LINKS: [CL-001]—Mechanism_Falsifiers
