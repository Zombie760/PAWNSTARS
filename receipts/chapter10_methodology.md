# Chapter 10 Methodology Sources

This file provides source pointers for the methodology and claims in Chapter 10 (Falsifier Registry & Red Team Results).

## Core Sources

### Thesis Claims (TC-1 through TC-10)
- **R-TC-001**: TC-1 - Palantir incorporated May 2003 (same month TIA defunding debated)
  - Sources: Delaware Corp #3759318, Congressional Record TIA defunding
- **R-TC-002**: TC-2 - LifeLog cancelled Feb 4 2004 = Facebook launch Feb 4 2004
  - Sources: Wired 2004-02-04, Facebook incorporation records
- **R-TC-003**: TC-3 - PAM architect = Hanson; Augur co-founder = Krug (Thiel Fellow); Coplan TokenUnion→Bancor→Netanyahu; CFTC capture chain
  - Sources: Hanson papers, Thiefellowship.org, Bancor team, CFTC dockets
- **R-TC-004**: TC-4 - Mike Griffin = In-Q-Tel Pres 2000-05 → NASA Admin 2005-09 → SpaceX COTS/CRS/Starshield
  - Sources: In-Q-Tel leadership, NASA bio, SpaceX contracts
- **R-TC-005**: TC-5 - Eric Schmidt = NSCAI Chair + Bilderberg (with Thiel) + Narya Capital (Vance) + Newsom donor
  - Sources: NSCAI.gov, Bilderberg lists, Narya SEC, Newsom disclosures
- **R-TC-006**: TC-6 - Epstein archive contains Griffin, Wexner, Acosta, Clinton, Trump, Dershowitz, Vance Jr., Bannon, Carlson
  - Sources: epstein-docs.github.io deduplicated entities
- **R-TC-007**: TC-7 - DOGE CIOs = Palantir/SpaceX alumni (Barbaccia, Hogan, Riedel, Graber, Minor)
  - Sources: WIRED/NYT/Guardian 2025
- **R-TC-008**: TC-8 - Palantir $113M+ DOGE contracts first months; stock +90% post-election
  - Sources: Guardian Mar 2026, Bloomberg Feb 2025
- **R-TC-009**: TC-9 - Tesla 2020 profit 100% ZEV-credit dependent ($1.58B credits vs $721M income)
  - Sources: Tesla 10-K 2020, E&E News 2024
- **R-TC-010**: TC-10 - NRO Starshield $1.8B classified contract 2021
  - Sources: Reuters 2024-03-16 (5 sources)

### Red Team Methodology
- **R-REDTEAM-001**: Red team attack vectors per claim
  - Timeline divergence attacks
  - Entity misidentification attacks
  - Source corruption attacks
  - Logical gap attacks
- **R-REDTEAM-002**: Red team execution logs
  - Per-claim attack attempts
  - Results: UNTRIGGERED / TRIGGERED
  - Evidence for each result

### BUQP Gate Results
- **R-BUQP-001 through R-BUQP-012**: Chapter 1-12 BUQP gate results
  - gate_paper.py --strict output per chapter
  - MISMATCH/CANNOT-VERIFY counts
  - Pass/fail status

## Cross-References
- Substrate entries: `/home/gringo/Substrate/pawns/Claims/CL-001` through `CL-020`, `PE-001` through `PE-030`
- Epstein archive cross-ref: All falsifier entities verified in epstein-docs.github.io