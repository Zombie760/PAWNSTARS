# PE-002 — Gavin Newsom

PEOPLE ID: PE-002
NAME: Gavin Newsom
ROLE: The Golden Boy / Tech Oligarch Puppet
DESCRIPTION: Governor of California (2019-present). Former SF Mayor (2004-2011). Lt. Governor (2011-2019). Character bible entry: "The Golden Boy" archetype; "charisma as camouflage, PG&E ties, extraction math."
DESCRIPTION-CLAIM: Newsom's 2022 gubernatorial campaign received $47M from tech PACs, including $5.2M from Reid Hoffman's "Win the Future" and $3.8M from Laurene Powell Jobs' Emerson Collective. Claim published as falsifiable in character_bible.md. Substrate: newsom_donors.jsonl rows 0 (Hoffman $5.2M), 1 (Powell Jobs $3.8M), 6 (Soros $5M) and 24 donors total.
VOICE: Ellis (clinical detachment) + Thompson (systemic fury)
EVIDENCE:
  - newsom_donors.jsonl row 0 (Reid Hoffman): total_donated=5200000, FEC #C00789338, two 2021/2022 transactions.
  - newsom_donors.jsonl row 1 (Laurene Powell Jobs): total_donated=3800000, FEC #C00794512, "California Future Fund".
  - efta_live_2026-07-21.jsonl: entity "Gavin Newsom" with file_id ddde6f756d6aa4fdba8369e0dadc5511 (EFTA01192508.pdf, 2014-06-19, 3 pages) — an early document from the Epstein disclosure set placing Newsom adjacent to the network.
  - newsom_donors.md lines 1-100: thesis (line 3) "The intelligence communities work for a small group of people who have been ruling for centuries — the Zionist class and Silicon Valley oligarchs. Newsom is their California avatar."
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00794512&two_year_transaction_period=2022
  - https://www.fppc.ca.gov/transparency/top-contributors.html
  - https://epsteinfta.com/document/ddde6f756d6aa4fdba8369e0dadc5511
  - receipt:newsom_donors.jsonl#row0
  - receipt:newsom_donors.jsonl#row1
  - receipt:efta_live_2026-07-21.jsonl#file:ddde6f756d6aa4fdba8369e0dadc5511
  - receipt:newsom_donors.md#line:1
LINKS: [MO-001]—Thiel-Influence-Model, [CL-002]—Newsom-Corporate-Patronage, [PR-002]—Regulatory-Capture
FALSIFIER: If FEC filing C00789338-2022 does not show the $5.2M Hoffman conduit, this claim is false. Test: hit the FEC URL, filter by contributor "Reid Hoffman" / "Win the Future" and confirm two-line contribution total ≈ $5.2M. If C00794512-2022 has no $3.8M from Emerson Collective, the Powell Jobs leg fails.
