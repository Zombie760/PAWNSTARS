# PE-001 — JD Vance

PEOPLE ID: PE-001
NAME: JD Vance (James David Vance)
ROLE: The Hillbilly Grift / Distraction Asset
DESCRIPTION: U.S. Vice President. Senator from Ohio (2023-2025). Yale Law, Mithril Capital / Narya Capital. Peter Thiel–backed Senate run. Author of *Hillbilly Elegy* (2016) and *Communion* (2026). Character bible entry (character_bible.md §Vance): "The Hillbilly Grift" archetype; "book tour as money laundering."
DESCRIPTION-CLAIM: Vance's 2022 Senate campaign received $15M from Peter Thiel via Narya Capital, funneled through "Protect Ohio Values" PAC. Claim published as falsifiable in character_bible.md and corroborated in vance_thiel_palantir_claims.jsonl row 0.
VOICE: Palahniuk (isolated fragments) + Child (chapter-ending compression)
EVIDENCE:
  - vance_thiel_palantir_claims.jsonl row 0: "Thiel funded Vance's Senate campaign ($15M, 2022)" with source FEC.gov (C00789339-2022) and falsifier already in the receipt.
  - efta_live_2026-07-21.jsonl: entity "JD Vance" / "James David Vance" with file_id e274223ee2d13fbe833fac28d82d02e8 (EFTA01654144.pdf) and 7909e4c9ca4b7d778ff1673e5d0ccc62 (EFTA02407603.pdf).
  - vance_rogan_crossref.jsonl row 2: "Thiel funded Vance's Senate campaign ($15M, 2022) and secured VP slot" → Rogan interview = OMISSION. Vance on the biggest podcast on earth did not name Thiel.
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - https://www.opensecrets.org/members-of-congress/jd-vance/contributors?cid=N00048539
  - https://epsteinfta.com/document/e274223ee2d13fbe833fac28d82d02e8
  - https://epsteinfta.com/document/7909e4c9ca4b7d778ff1673e5d0ccc62
  - receipt:vance_thiel_palantir_claims.jsonl#row0
  - receipt:vance_rogan_crossref.jsonl#row2
  - receipt:efta_live_2026-07-21.jsonl#file:e274223ee2d13fbe833fac28d82d02e8
LINKS: [MO-001]—Thiel-Influence-Model, [CL-001]—Vance-Thiel-Funding, [PR-001]—Money-Laundering-Through-Donor-Nets
FALSIFIER: If FEC filing C00789339-2022 does not show $15M from Thiel to Vance's 2022 Senate committee (or the Narya / Protect Ohio Values conduit), this claim is false. Test: query https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022 by contributor and confirm.
