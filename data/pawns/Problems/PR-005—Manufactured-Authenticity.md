# PR-005 — Manufactured Authenticity (Brand-Cover Extraction)

PROBLEM ID: PR-005
NAME: Manufactured Authenticity
GEOGRAPHIC REGION(S): US, CA, global
POTENTIAL PROBLEM: Public figures deploy carefully constructed "authentic" identities (Hillbilly, Golden Boy, Alibi, Brand) as cover for an underlying extraction model that enriches their patrons and weakens their nominal constituency.
PROBLEM DESCRIPTION: Character_bible.md articulates the brand-cover extraction pattern: Newsom's "California Dream" as cover for PG&E ties and tech-PAC extraction; Vance's "Hillbilly Elegy" as cover for Thiel funding and book-tour money-laundering; Harris's "I'm with the people" as cover for Hoffman money; Trump as "The Brand" covering Adelson / Kushner dark money. The substrate confirms each cover story with FEC receipts underneath. The book project calls this "manufactured authenticity": the public-facing narrative and the substrate-traceable reality are deliberately decoupled.
EVIDENCE:
  - character_bible.md §Newsom: "California Dream as brand cover" + falsifiable claim.
  - character_bible.md §Vance: "hillbilly elegy as grift mythology" + falsifiable claim.
  - character_bible.md §Harris: "I'm with the people as brand cover" + falsifiable claim.
  - character_bible.md §Trump: "reality distortion field as asset" + falsifiable claim.
  - newsom_donors.jsonl rows 0-24: every donor → CA state contracts (the extraction math that the brand covers).
LINKS: solved by [SO-001]—Receipts-First-Pipeline, [SO-003]—MOA-Voice-Lock; risks [RI-003]—Fabrication-Drift.
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00694455&two_year_transaction_period=2020
  - https://www.fec.gov/data/receipts/?committee_id=C00580100&cycle=2016
  - receipt:character_bible.md#section:Newsom
  - receipt:character_bible.md#section:Vance
  - receipt:character_bible.md#section:Harris
  - receipt:character_bible.md#section:Trump
FALSIFIER: If character_bible.md §Newsom/§Vance/§Harris/§Trump are removed, or any of the four FEC committee IDs (C00789338, C00789339, C00694455, C00580100) does not show the cited contribution, this problem is not supported.
