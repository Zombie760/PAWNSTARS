# pawns — Pawns-of-the-Mechanism subgraph

Truth-telling knowledge graph for the **botwavebomba / Pawns-of-the-Mechanism**
book project, in Miessler Substrate format
(`[CATEGORY-ID]—Name.md`, field-keyed bodies, `LINKS` cross-references). The
operator's DA loads these entries as memory so it reasons FROM the evidence,
not from thin air — every People / Claim / Risk / Solution / Problem entry
cites at least one receipt from the botwave journalism substrate on disk
(10,322 receipts in `/home/gringo/botwave/journalism/pawns/substrate/`).

## Compliance anchors (every claim traces to a fetched source)

- **EFTA / DOJ Epstein release (2026-07-21)** — 2,897 bates in
  `house_oversight_2026-07-21.jsonl`; per-entity `efta_live_2026-07-21.jsonl`
  rows with PDF id + doc_url.
- **Newsom donor matrix** — `newsom_donors.jsonl` (25 rows) with FEC committee
  IDs, dates, and amounts; 1:1 mirror in `newsom_donors.md`.
- **Vance-Rogan claim crossref** — `vance_rogan_crossref.jsonl` (8 rows) marks
  every Vance.txt claim CONSISTENT / CONTRADICTION / OMISSION vs. the Rogan
  interview transcript (`vance_rogan_vance_utterances.jsonl`).
- **JMail / JMail.world thread index** — 810K+ thread records
  (`jmail_threads_2026-07-21.jsonl`) plus per-thread content
  (`jmail_content_2026-07-21.jsonl`).
- **DOJ Federal Register (2026-07-21)** — `doj_fedregister_2026-07-21.jsonl`
  with publication_date + document_number + agency_names.
- **Vance all-claims** — `vance_all_claims.jsonl` (139 rows) each carrying
  source URL + falsifier.
- **Master substrate thesis** — `master_substrate.json` (project thesis +
  components); `mechanism_substrate.jsonl` (79MB evidence).
- **Multi-source** — `multi_source_2026-07-21.jsonl` with entity + file_id
  + filename + doc_url (DOJ Disclosures).

## Categories (each has an INDEX.md)

| Category | Entries | Index |
|----------|---------|-------|
| People | PE-001..008 | People/INDEX.md |
| Problems | PR-001..005 | Problems/INDEX.md |
| Claims | CL-001..004 | Claims/INDEX.md |
| Risks | RI-001..005 | Risks/INDEX.md |
| Solutions | SO-001..004 | Solutions/INDEX.md |
| Plans | PL-001..002 | Plans/INDEX.md |
| Models | MO-001 | (single entry) |
| Values | VA-001 | (single entry) |

## Governing frames

- MO-001 Thiel-Influence-Model — the bridge between Silicon Valley donor
  networks and elected officials.
- VA-001 Receipts-First-Principle — every claim must trace to a JSONL
  receipt; fabricated prose is not a receipt.
- FR-001 Tool Not Magic (carried from cannabis-delivery) — the substrate
  is a memory graph for the agent, not a court of law. It states
  confidence and cites the receipt, then defers to the operator's
  judgment on the call.
