# PL-002 — Substrate-Gathering Plan

PLAN ID: PL-002
NAME: Substrate-Gathering Plan
SCOPE: The continuous ingestion of primary-source receipts into /home/gringo/botwave/journalism/pawns/substrate/ — DOJ disclosures, FEC filings, SEC EDGAR, JMail index, news coverage, interview transcripts, and per-principal claim crossrefs.
CHALLENGES:
  1. Each source has a different contamination profile and rate limit.
  2. Some sources (e.g. White House visitor logs) require FOIA; lead time is months.
  3. The substrate is already 79MB+ and growing; the loader cannot read it all in one pass.
  4. The operator's RECONCILER must surface new receipts without manual scanning.
MISSION: Stand up a daily substrate-gathering routine that grows the JSONL store by ≥100 new receipts per week, each tagged with source_class, source_hash (where available), and a one-line human-readable title.
STRATEGIES:
  - Stream 1 — DOJ releases: monitor House Oversight / DOJ press page; ingest new bates into house_oversight_*.jsonl.
  - Stream 2 — FEC filings: re-fetch the top-100 donors for each named principal every 30 days; diff against newsom_donors.jsonl and write new rows.
  - Stream 3 — JMail: poll jmail.world for new threads; ingest into jmail_threads_*.jsonl.
  - Stream 4 — Interview crossref: for every named principal who goes on a major podcast, run vance_rogan_crossref-style analysis (claim × public-utterance = CONSISTENT | CONTRADICTION | OMISSION).
  - Stream 5 — News / multi-source: weekly news scrape of the top 20 outlets for the named principals.
IDEAL WORLD: Every claim in every pawns/ entry can be traced to a JSONL row ingested within the last 30 days. The substrate is the operator's living memory of the network.
LINKS: [PL-001]—Three-Deliverable-Plan, [SO-001]—Receipts-First-Pipeline, [SO-002]—Source-Trace-Validator
SOURCES:
  - https://epsteinfta.com/document/ddde6f756d6aa4fdba8369e0dadc5511
  - https://jmail.world/thread/EFTA00155146
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - receipt:house_oversight_2026-07-21.jsonl#bates:HOUSE_OVERSIGHT_010477
  - receipt:jmail_content_2026-07-21.jsonl#thread:EFTA00155146
FALSIFIER: If after 30 days the substrate has not grown by ≥100 new rows, the plan has failed. Test: wc -l on each JSONL in /home/gringo/botwave/journalism/pawns/substrate/ and compare to the day-0 baseline.
