# MO-001 — Thiel-Influence Model

MODEL ID: MO-001
NAME: Thiel-Influence Model
DESCRIPTION: A causal model of how Peter Thiel and his downstream network influence U.S. politics. The model has three layers: (1) Capital layer — Thiel's Narya Capital and Founders Fund deploy capital into Thiel-aligned companies (Palantir, Anduril, Vance's VC firms) and into political campaigns (Vance Senate run, Vance VP selection). (2) Personnel layer — Thiel alumni move into executive-branch positions (Vance → VP; multiple Thiel founders → DOD contracts; Palantir → ICE contracts). (3) Narrative layer — the "Hillbilly Elegy" cover story, the performative-Catholic conversion, the "anti-establishment" framing on Rogan — all decouple the public persona from the substrate reality. The model predicts that any Thiel-backed political candidate will follow the same three-layer pattern; the operator's job is to read the substrate for which layer the candidate is on.
EVIDENCE:
  - vance_thiel_palantir_claims.jsonl row 0: Thiel funded Vance's Senate campaign ($15M, 2022), FEC C00789339-2022.
  - vance_thiel_palantir_claims.jsonl row 1: Vance lobbied for Palantir's $10B Pentagon AI contract (2025).
  - vance_thiel_palantir_claims.jsonl row 2: 41 ICE shootings in 2025 (11 deaths), source Wikipedia list of shootings by U.S. immigration agents in the second Trump administration.
  - vance_rogan_crossref.jsonl row 2: Vance.txt claim "Thiel funded Vance's Senate campaign" → Rogan interview = OMISSION.
  - vance_rogan_crossref.jsonl row 4: Vance.txt claim "Vance secured $10B Pentagon contract for Palantir" → Rogan interview = OMISSION.
  - newsom_donors.jsonl rows 0, 2, 3: Hoffman, Andreessen, Horowitz (all Thiel-network) → CA contracts.
PREDICTIONS:
  - If a Thiel-backed candidate takes executive office, expect a Thiel-aligned Pentagon contract within 12 months.
  - Expect the candidate to perform "anti-establishment" identity work that the substrate will contradict.
  - Expect the candidate's largest media appearances to omit the Thiel / Palantir / contract layer.
LINKS: [CL-001]—Vance-Thiel-Funding, [PE-001]—JD_Vance, [PE-003]—Peter_Thiel, [PR-001]—Money-Laundering-Through-Donor-Nets
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - https://www.sec.gov/Archives/edgar/data/1321655/000132165523000008/xslForm13F_X01/primary_doc.xml
  - receipt:vance_thiel_palantir_claims.jsonl#row0
  - receipt:vance_thiel_palantir_claims.jsonl#row1
  - receipt:vance_thiel_palantir_claims.jsonl#row2
  - receipt:vance_rogan_crossref.jsonl#row2
  - receipt:vance_rogan_crossref.jsonl#row4
FALSIFIER: If a Thiel-backed candidate takes executive office and does NOT receive a Thiel-aligned Pentagon contract within 12 months, the model's personnel layer fails. If the candidate names Thiel on a major media appearance, the narrative layer is no longer applicable. Track per-quarter.
