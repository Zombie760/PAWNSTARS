# PR-001 — Money-Laundering-Through-Donor-Nets

PROBLEM ID: PR-001
NAME: Money Laundering Through Donor Networks
GEOGRAPHIC REGION(S): US, CA, OH, NY, NV
POTENTIAL PROBLEM: Donor PACs and 501(c)(4) shells act as fungible conduits between ultra-wealthy patrons and elected officials, making the origin of campaign funds untraceable to the underlying principal.
PROBLEM DESCRIPTION: The substrate shows that 25+ tech oligarchs each donated $1M-$5.2M to a single California gubernatorial campaign (Newsom 2022), totaling tens of millions from a small group with shared downstream interests in Palantir/CA state contracts. The same pattern is visible in the Vance 2022 Senate run (Thiel $15M via Narya Capital). The mechanism is: a donor gives to a PAC, the PAC gives to a campaign, the campaign supports policies that favor the donor's portfolio companies. The receipt ledger is real (FEC.gov) but the underlying principal is washed through two-to-three degrees of separation.
EVIDENCE:
  - newsom_donors.jsonl rows 0..24: 25 Silicon Valley donor lines with total_donated, FEC committee IDs, and extraction_math showing CA state contracts to portfolio companies.
  - vance_thiel_palantir_claims.jsonl row 0: "Thiel funded Vance's Senate campaign ($15M, 2022)" with source FEC.gov C00789339-2022.
  - character_bible.md §Vance: "Vance received $15M from Peter Thiel in 2022 via Narya Capital (FEC #C00789339-2022), funneled through 'Protect Ohio Values' PAC."
LINKS: solved by [SO-001]—Receipts-First-Pipeline, [SO-002]—Source-Trace-Validator; informs [PL-001]—Three-Deliverable-Plan.
SOURCES:
  - https://www.fec.gov/data/receipts/?committee_id=C00789338&two_year_transaction_period=2022
  - https://www.fec.gov/data/receipts/?committee_id=C00789339&two_year_transaction_period=2022
  - https://www.opensecrets.org/members-of-congress/jd-vance/contributors?cid=N00048539
  - receipt:newsom_donors.jsonl#row0
  - receipt:vance_thiel_palantir_claims.jsonl#row0
FALSIFIER: If newsom_donors.jsonl row 0 (Hoffman) shows total_donated != 5200000, or vance_thiel_palantir_claims.jsonl row 0 is removed/relabeled, this problem description is not supported. Independent check: OpenSecrets "Top Contributors" for Newsom 2022 and Vance 2022 should name Hoffman, Andreessen, Thiel.
