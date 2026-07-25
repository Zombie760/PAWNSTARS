# VA-001 — Receipts-First Principle

VALUE ID: VA-001
NAME: Receipts-First Principle
DESCRIPTION: Every claim that ships in the operator's work traces to a verified primary source. A "receipt" is a JSONL row, a SEC filing, a FEC receipt, a DOJ-disclosed PDF, a JMail thread, or a verbatim quoted passage from a primary source. The bar is "undeniable" — a third party can reproduce the claim from the cited receipt alone, without trusting the operator.
STATEMENT: If a claim has no receipt, it does not ship. If a claim has a receipt, the claim is published with the receipt ID. If a claim is challenged, the falsifier named in the entry is the test.
EVIDENCE:
  - OPERATIONAL_RULES.md LAW 2: "No fabrication / no sycophancy / undeniable — Every factual claim must trace to a verified primary source (command + output, or a cited source I actually read). No invented codes, fees, stats, or 'remembered' facts."
  - SETTLED.md: "Undeniable path: when a dilemma appears, take the undeniable action; do not re-engage with rhetorical clarify menus."
  - PRINCIPAL_TELOS.md: "Evidence beats assertion — 'undeniable' (command + output) is the bar."
  - botwave ISA.md Principles: "Undeniable — every claim backed by a command run + its output. No 'should be,' no 'done' without evidence."
  - All 30 entries in /home/gringo/Substrate/pawns/ carry SOURCES: and FALSIFIER: lines.
LINKS: [SO-001]—Receipts-First-Pipeline, [SO-002]—Source-Trace-Validator, [MO-001]—Thiel-Influence-Model
SOURCES:
  - receipt:vance_thiel_palantir_claims.jsonl#row0
  - receipt:newsom_donors.jsonl#row0
  - receipt:efta_live_2026-07-21.jsonl#file:ddde6f756d6aa4fdba8369e0dadc5511
FALSIFIER: If a pawns/ entry ships with a quantitative claim that does not match its cited JSONL receipt (e.g. claimed $5.2M but receipt says $5.1M, or claimed FEC ID C00789338 but receipt has a different ID), the principle has been violated. Test: spot-check every dollar figure and every committee ID against the cited row.
