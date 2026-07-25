# PE-005 — Kamala Harris

PEOPLE ID: PE-005
NAME: Kamala Harris
ROLE: The Alibi / Corporate Democrat
DESCRIPTION: Vice President of the United States (2021-2025). 2020 presidential candidate. Former U.S. Senator (CA) and California Attorney General. Character bible entry: "The Alibi" archetype; "Newsom's protégé, extraction math, 'I'm with the people' as brand cover."
DESCRIPTION-CLAIM: Harris's 2020 presidential campaign received $1.8M from Reid Hoffman's "Win the Future" PAC (FEC #C00694455-2020). Claim published as falsifiable in character_bible.md. Substrate: newsom_donors.jsonl row 21 (Kamala Harris, total_donated=1800000, "VP, Former CA AG"); efta_live_2026-07-21.jsonl has her as entity with file_id 4bc2b2fe46f4e5dee0335b206e626c34 (EFTA00175169.pdf).
VOICE: Ellis (brand precision) + Palahniuk (reader complicity)
EVIDENCE:
  - character_bible.md §Harris: "Harris's 2020 presidential campaign received $1.8M from Reid Hoffman's 'Win the Future' PAC (FEC #C00694455-2020)."
  - newsom_donors.jsonl row 21: donor=Kamala Harris, total_donated=1800000, affiliation="VP, Former CA AG".
  - efta_live_2026-07-21.jsonl: entity "Kamala Harris" with file_id 4bc2b2fe46f4e5dee0335b206e626c34 (EFTA00175169.pdf).
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00694455&two_year_transaction_period=2020
  - https://epsteinfta.com/document/4bc2b2fe46f4e5dee0335b206e626c34
  - receipt:newsom_donors.jsonl#row21
  - receipt:efta_live_2026-07-21.jsonl#file:4bc2b2fe46f4e5dee0335b206e626c34
  - receipt:character_bible.md#section:Harris
LINKS: [PE-002]—Gavin_Newsom, [PE-004]—Reid_Hoffman, [CL-003]—Dark-Money-Flows
FALSIFIER: If FEC filing C00694455-2020 does not show $1.8M from Reid Hoffman / Win the Future to Harris for President, this claim is false. Test: hit the FEC URL, filter by contributor "Reid Hoffman" or committee "Win the Future", confirm ≈ $1.8M.
