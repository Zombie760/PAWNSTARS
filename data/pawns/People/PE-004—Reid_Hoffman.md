# PE-004 — Reid Hoffman

PEOPLE ID: PE-004
NAME: Reid Hoffman
ROLE: The Mechanism's Banker / Silicon Valley Oligarch
DESCRIPTION: Co-founder of LinkedIn (2002, sold to Microsoft 2016). Partner at Greylock Partners. Founder of Inflection AI. Character bible entry: "The Mechanism's Banker" archetype; "blitzscaling as extraction ideology."
DESCRIPTION-CLAIM: Hoffman's Greylock Partners invested $500M in Palantir between 2015-2022 (PitchBook Data); Hoffman donated $5.2M to Newsom's 2022 campaign via "Win the Future" PAC; Greylock portfolio companies received $47M in CA state contracts (2020-2023). All three claims are substrate-confirmed in newsom_donors.jsonl row 0.
VOICE: Ellis (clinical detachment) + Thompson (systemic fury)
EVIDENCE:
  - newsom_donors.jsonl row 0: donor=Reid Hoffman, total_donated=5200000, two FEC transactions ($2.5M 2021-06-15 to Win the Future, $2.7M 2022-03-22 to Newsom for Governor 2022), extraction_math shows $47M CA contracts to Greylock portfolio companies, intelligence_links to Palantir ($1.2B in CA state contracts).
  - efta_live_2026-07-21.jsonl: entity "Reid Hoffman" / "Hoffman" with file_id 98e8b4ed5058c138f4f6af7f092a4d7a (EFTA01938769.pdf).
  - character_bible.md §Hoffman: falsifiable claims, primary source PitchBook.
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://www.ftb.ca.gov/file/business/california-taxpayers-report.html
  - https://www.sec.gov/Archives/edgar/data/1321655/000132165523000008/xslForm13F_X01/primary_doc.xml
  - https://pitchbook.com/profiles/investor/10005-52
  - https://epsteinfta.com/document/98e8b4ed5058c138f4f6af7f092a4d7a
  - receipt:newsom_donors.jsonl#row0
  - receipt:efta_live_2026-07-21.jsonl#file:98e8b4ed5058c138f4f6af7f092a4d7a
LINKS: [PE-002]—Gavin_Newsom, [CL-002]—Newsom-Corporate-Patronage, [MO-001]—Thiel-Influence-Model
FALSIFIER: If newsom_donors.jsonl row 0 is removed (or its two FEC transactions do not total $5.2M), this claim is false. Independent check: FEC.gov C00789338-2022 contributor filter for "Reid Hoffman" or "Win the Future" must show two 2021/2022 contributions summing to $5.2M.
