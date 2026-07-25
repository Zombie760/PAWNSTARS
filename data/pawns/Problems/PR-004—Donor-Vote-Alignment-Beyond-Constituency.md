# PR-004 — Donor-Vote Alignment Beyond Constituency

PROBLEM ID: PR-004
NAME: Donor-Vote Alignment Beyond Constituency Interest
GEOGRAPHIC REGION(S): US
POTENTIAL PROBLEM: Elected officials vote on issues (H-1B visas, AI contracts, ICE surveillance, regulatory carve-outs) that align with the financial interests of a small donor class but cut against the interests of their stated constituency.
PROBLEM DESCRIPTION: The Vance case (character_bible.md, vance_rogan_crossref.jsonl) is the cleanest documented example. Vance publicly attacks H-1B visas while his own VC firms (Narya, Mithril) invest in H-1B-dependent companies. Vance promotes *Communion* as a faith journey on the Rogan podcast while vance_rogan_crossref.jsonl row 1 marks the conversion claim as CONTRADICTION (he can't recite the Hail Mary). Vance secured $10B in Pentagon AI contracts for Palantir (vance_thiel_palantir_claims.jsonl row 1). Vance, as VP, oversees ICE while ICE killed 11+ people in 2025 shootings and detained 170+ US citizens (vance_all_claims.jsonl rows + vance_rogan_crossref.jsonl row 5 = OMISSION on Rogan). On the largest podcast in the world, none of this was discussed.
EVIDENCE:
  - vance_rogan_crossref.jsonl row 3: "Vance's VC firms (Narya, Mithril) invest in H-1B-dependent companies while he publicly attacks H-1B visas" — Rogan interview = OMISSION.
  - vance_rogan_crossref.jsonl row 4: "Palantir's AI is embedded in ICE for predictive deportations; Vance secured $10B Pentagon contract for Palantir" — Rogan interview = OMISSION.
  - vance_rogan_crossref.jsonl row 5: "ICE killed 11+ people in 2025 shootings; 170+ US citizens wrongfully detained" — Rogan interview = OMISSION.
  - vance_rogan_crossref.jsonl row 1: conversion claim is CONTRADICTION (Rogan audio shows performative Christianity).
LINKS: solved by [SO-001]—Receipts-First-Pipeline; risks [RI-005]—Sourcing-Gaps; informs [PL-001]—Three-Deliverable-Plan.
SOURCES:
  - receipt:vance_rogan_crossref.jsonl#row1
  - receipt:vance_rogan_crossref.jsonl#row3
  - receipt:vance_rogan_crossref.jsonl#row4
  - receipt:vance_rogan_crossref.jsonl#row5
  - receipt:vance_thiel_palantir_claims.jsonl#row1
  - receipt:vance_thiel_palantir_claims.jsonl#row2
FALSIFIER: If vance_rogan_crossref.jsonl is missing rows 1, 3, 4, or 5, or if those rows are not labeled OMISSION/CONTRADICTION, this problem is not supported by the substrate. Independent test: listen to the Rogan audio (video_id vtxyvD58eDg) and confirm Vance never says "Thiel", "H-1B", "Palantir", or "ICE killings".
