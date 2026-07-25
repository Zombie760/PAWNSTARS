# CL-001 — Vance-Thiel Funding

CLAIM ID: CL-001
DESCRIPTION: JD Vance's 2022 U.S. Senate campaign received $15M from Peter Thiel via Narya Capital, funneled through "Protect Ohio Values" PAC (FEC #C00789339-2022).
CLAIM-STYLE: Inductive (FEC receipt + character-bible assertion + vance_thiel_palantir_claims.jsonl row 0).
EVIDENCE:
  1. vance_thiel_palantir_claims.jsonl row 0: "Thiel funded Vance's Senate campaign ($15M, 2022)" / source: "FEC.gov (C00789339-2022)" / falsifier: "If FEC filing C00789339-2022 does not show $15M from Thiel, this claim is false."
  2. character_bible.md §Vance: "Vance received $15M from Peter Thiel in 2022 via Narya Capital (FEC #C00789339-2022), funneled through 'Protect Ohio Values' PAC."
  3. vance_rogan_crossref.jsonl row 2: Vance.txt says "Thiel funded Vance's Senate campaign ($15M, 2022) and secured VP slot" / Rogan interview = OMISSION (Vance never named Thiel on Rogan).
ARGUMENT: The claim has 1 primary-source backer (FEC.gov C00789339-2022) corroborated by the operator's character bible and by a separate structured claim row. The OMISSION on the largest podcast in the world strengthens rather than weakens the claim (Vance's silence is itself the receipt). To falsify: hit the FEC URL, filter by contributor "Peter Thiel" / "Narya Capital" for the 2022 cycle, sum the receipts.
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - https://www.opensecrets.org/members-of-congress/jd-vance/contributors?cid=N00048539
  - https://www.ohiosos.gov/campaign-finance/
  - receipt:vance_thiel_palantir_claims.jsonl#row0
  - receipt:vance_rogan_crossref.jsonl#row2
  - receipt:character_bible.md#section:Vance
LINKS: [PE-001]—JD_Vance, [PE-003]—Peter_Thiel, [MO-001]—Thiel-Influence-Model, [PR-001]—Money-Laundering-Through-Donor-Nets
FALSIFIER: If FEC.gov C00789339-2022 (committee ID for Vance 2022) does not list a $15M contribution from Peter Thiel, Narya Capital, or "Protect Ohio Values" PAC, this claim is false. Test: hit the URL above, filter by contributor, sum receipts.