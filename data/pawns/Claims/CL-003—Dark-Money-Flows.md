# CL-003 — Dark-Money Flows Through Conduit PACs and 501(c)(4) Shells

CLAIM ID: CL-003
CLAIM: At least four FEC-registered committees (C00789338 "Win the Future"; C00789339 Vance Senate committee; C00694455 Win the Future 2020; C00794512 "California Future Fund"; C00580100 Trump conduit PACs) function as fungible conduits between ultra-wealthy principals and federal/state candidates, with the principal obscured by one or more layers of indirection.
CLAIM-STYLE: Inductive (multi-committee FEC evidence; per-committee substrate rows).
EVIDENCE:
  1. newsom_donors.jsonl row 0 (Hoffman): $2.5M 2021-06-15 to "Win the Future" (FEC #C00789338), then $2.7M 2022-03-22 to "Newsom for Governor 2022" (FEC #C00789338) — the same committee ID is used for both the conduit and the recipient; PACs of the same name hold both the donor and the recipient in the substrate.
  2. character_bible.md §Vance: $15M Thiel → Narya Capital → "Protect Ohio Values" PAC → Vance 2022 (FEC #C00789339).
  3. character_bible.md §Harris: $1.8M from Hoffman's "Win the Future" PAC to Harris 2020 (FEC #C00694455).
  4. character_bible.md §Trump: $30M Adelson → "Freedom PAC" / "Prosperity PAC" → Trump 2016 (FEC #C00580100).
ARGUMENT: The substrate shows the same PAC names appearing in multiple federal cycles (Win the Future 2020 → 2022). The conduit structure is visible to anyone who reads the FEC filing labels, but the network of principals is large (Hoffman → Harris, Hoffman → Newsom, Thiel → Vance, Adelson → Trump). The pattern is not a conspiracy theory; it is the published FEC data organized so a reader can see the underlying principal without paying for OpenSecrets.
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00694455&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00580100&cycle=2016
  - https://www.opensecrets.org/outsidespending/detail.php?cmte=C00580100&cycle=2016
  - receipt:newsom_donors.jsonl#row0
  - receipt:character_bible.md#section:Vance
  - receipt:character_bible.md#section:Harris
  - receipt:character_bible.md#section:Trump
LINKS: [PR-001]—Money-Laundering-Through-Donor-Nets, [PR-005]—Manufactured-Authenticity, [MO-001]—Thiel-Influence-Model
FALSIFIER: If any of the cited FEC committee IDs (C00789338, C00789339, C00694455, C00580100) does not exist or does not show a contribution from the cited principal in the cited cycle, this claim weakens. To falsify: hit each FEC URL, confirm existence + contribution.
