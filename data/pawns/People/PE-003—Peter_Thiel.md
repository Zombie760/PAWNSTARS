# PE-003 — Peter Thiel

PEOPLE ID: PE-003
NAME: Peter Thiel
ROLE: The Puppeteer / Dark Money Architect
DESCRIPTION: Co-founder of PayPal (1998) and Palantir Technologies (2003). Managing partner of Founders Fund. Co-founder of Mithril Capital and Narya Capital. Character bible entry: "The Puppeteer" archetype; "Narya Capital, 'zero to one' as extraction ideology, Palantir as surveillance capitalism."
DESCRIPTION-CLAIM: Thiel's Founders Fund held $1.2B in Palantir stock as of 2023 Q1 (SEC Form 13F-HR). Claim published as falsifiable in character_bible.md. Substrate: efta_live_2026-07-21.jsonl row "Peter Thiel" with file_id ec3d9ff1c6745876f1cfc1d470bb3790 (EFTA02457661.pdf) — i.e. Thiel appears in the DOJ-disclosed Epstein set.
VOICE: Ellis (clinical precision) + Thompson (nihilist fury)
EVIDENCE:
  - efta_live_2026-07-21.jsonl: entity "Peter Thiel" with file_id ec3d9ff1c6745876f1cfc1d470bb3790 (EFTA02457661.pdf).
  - vance_thiel_palantir_claims.jsonl row 0: "Thiel funded Vance's Senate campaign ($15M, 2022)" with source FEC.gov C00789339-2022 — establishes the money conduit.
  - vance_thiel_palantir_claims.jsonl row 1: "Vance lobbied for Palantir's $10B Pentagon AI contract (2025)" with falsifier and source.
  - newsom_donors.jsonl: Hoffman (row 0), Andreessen (row 2), Horowitz (row 3) all have intelligence_links to Palantir — Thiel's downstream influence network.
SOURCES:
  - https://www.sec.gov/Archives/edgar/data/1321655/000132165523000008/xslForm13F_X01/primary_doc.xml
  - https://epsteinfta.com/document/ec3d9ff1c6745876f1cfc1d470bb3790
  - receipt:efta_live_2026-07-21.jsonl#file:ec3d9ff1c6745876f1cfc1d470bb3790
  - receipt:vance_thiel_palantir_claims.jsonl#row0
  - receipt:vance_thiel_palantir_claims.jsonl#row1
LINKS: [MO-001]—Thiel-Influence-Model, [CL-001]—Vance-Thiel-Funding, [PE-001]—JD_Vance, [PE-005]—Kamala_Harris
FALSIFIER: If SEC Form 13F-HR (Q1 2023) for Founders Fund does not list Palantir (PLTR) shares with market value ≈ $1.2B, this claim is false. Test: hit the SEC URL above, grep for "PLTR" in the holdings table.
