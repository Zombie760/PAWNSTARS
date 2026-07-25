# PR-002 — Regulatory Capture Through Tech Donor Networks

PROBLEM ID: PR-002
NAME: Regulatory Capture
GEOGRAPHIC REGION(S): US, CA
POTENTIAL PROBLEM: Tech oligarch donors simultaneously fund elected officials AND hold state contracts with those same officials' jurisdictions, creating a closed loop where the regulator depends on the regulated for both campaign survival and budget.
PROBLEM DESCRIPTION: The substrate's extraction_math field on newsom_donors.jsonl shows the pattern explicitly: Hoffman donates $5.2M → Greylock portfolio companies receive $47M in CA state contracts (2020-2023). Andreessen donates $2.5M → a16z portfolio receives $30M in CA state contracts. Palantir (Thiel-adjacent) holds $1.2B in CA state contracts. Marc Andreessen is on the CA AI Task Force (Executive Order N-12-23, 2023) — i.e. he is both donor and regulator. The pattern repeats at scale: per-entity rows in newsom_donors.jsonl show the same donor→contract loop for Hoffman, Andreessen, Horowitz, Khosla, Doerr, Botha, Leone, Altman, Bezos, Gates, Ellison, Schmidt, Cohn.
EVIDENCE:
  - newsom_donors.jsonl row 0 (Hoffman): extraction_math shows $47M in CA state contracts to Greylock portfolio companies (source ftb.ca.gov).
  - newsom_donors.jsonl row 2 (Andreessen): a16z portfolio companies received $30M in CA state contracts; Andreessen appointed to CA AI Task Force.
  - newsom_donors.jsonl row 14 (Gates) and row 12 (Altman) and row 15 (Ballmer) and row 16 (Ellison) all carry the same extraction_math field.
  - newsom_donors.md line 60-69: "Andreessen donated $2.5M to Newsom's 2022 campaign... Andreessen appointed to CA AI Task Force (Executive Order N-12-23, 2023). a16z portfolio companies received $30M in CA state contracts (2020-2023)."
LINKS: solved by [SO-002]—Source-Trace-Validator; informs [MO-001]—Thiel-Influence-Model; risks [RI-001]—Legal-Exposure.
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://www.ftb.ca.gov/file/business/california-taxpayers-report.html
  - receipt:newsom_donors.jsonl#row0
  - receipt:newsom_donors.jsonl#row2
  - receipt:newsom_donors.md#line:60
FALSIFIER: If newsom_donors.jsonl rows 0 and 2 (Hoffman, Andreessen) are removed, or if ftb.ca.gov's California Taxpayers Report does not list Greylock and a16z portfolio companies among the top CA state vendors, this problem description is not supported.
