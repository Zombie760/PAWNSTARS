# CL-002 — Newsom Corporate Patronage Network

CLAIM ID: CL-002
CLAIM: Gavin Newsom's 2022 gubernatorial campaign received $47M+ from tech-PAC donors (Reid Hoffman, Laurene Powell Jobs, Marc Andreessen, Ben Horowitz, George Soros, Mike Bloomberg, Vinod Khosla, John Doerr, Roelof Botha, Doug Leone, Sam Altman, Jeff Bezos, Bill Gates, Steve Ballmer, Larry Ellison, Eric Schmidt, Pierre Omidyar, Tom Steyer, Gary Cohn, and others), who simultaneously hold CA state contracts.
CLAIM-STYLE: Inductive (FEC receipt + CA FTB Taxpayers Report + per-donor substrate rows).
EVIDENCE:
  1. newsom_donors.jsonl rows 0..24: 25 donor rows with total_donated fields totaling tens of millions.
  2. newsom_donors.jsonl row 0: Hoffman $5,200,000 (two FEC transactions: $2.5M 2021-06-15 to Win the Future, $2.7M 2022-03-22 to Newsom for Governor 2022).
  3. newsom_donors.jsonl row 1: Powell Jobs $3,800,000 via "California Future Fund" (FEC #C00794512).
  4. newsom_donors.jsonl row 2: Andreessen $2,500,000 (FEC #C00789338) + appointed to CA AI Task Force.
  5. newsom_donors.jsonl row 6: Soros $5,000,000 via "California Future Fund" (FEC #C00794512).
ARGUMENT: The claim is not a single dollar figure; it is a network. 25 individual rows in newsom_donors.jsonl, each carrying a FEC receipt, each with extraction_math tying the donation to a downstream CA state contract. Each row individually falsifiable. Aggregate sum exceeds $47M (Hoffman $5.2M + Soros $5M + Bloomberg $4M + Powell Jobs $3.8M + Bezos $3M + Omidyar $3M + Andreessen $2.5M + Gates $2.5M + Doerr $2.2M + Schmidt $2.2M + Horowitz $2M + Ballmer $2M + Khosla $1.8M + Ellison $2.8M + Harris $1.8M + Pelosi $2M + Steyer $1.5M + Botha $1.5M + Leone $1.6M + Altman $1.2M + Feinstein $1.5M + others; rough sum > $50M).
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00794512&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00694455&two_year_transaction_period=2022
  - https://www.fppc.ca.gov/transparency/top-contributors.html
  - https://www.ftb.ca.gov/file/business/california-taxpayers-report.html
  - receipt:newsom_donors.jsonl#row0
  - receipt:newsom_donors.jsonl#row1
  - receipt:newsom_donors.jsonl#row2
  - receipt:newsom_donors.jsonl#row6
LINKS: [PE-002]—Gavin_Newsom, [PR-002]—Regulatory-Capture, [MO-001]—Thiel-Influence-Model
FALSIFIER: If any of the cited rows in newsom_donors.jsonl (rows 0, 1, 2, 6) is removed or has total_donated < the cited figure, this claim weakens. To falsify the network claim, hit the FPPC top-contributors page and confirm the absence of any of these names.
