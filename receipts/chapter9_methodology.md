# Chapter 9 Methodology Sources

This file provides source pointers for the methodology and claims in Chapter 9 (Epstein-DOGE Continuity).

## Core Sources

### Epstein Archive Cross-References
- **R-EPSTEIN-ARCHIVE-001**: epstein-docs.github.io deduplicated entities (29,525 processed)
  - persons_registry.json: canonical person entities with aliases
  - knowledge_graph.db: entity relationships
  - document_entities.db.gz: per-document entity mentions
  - external_mentions.db.gz: cross-document references
  - concordance_complete.db.gz: DOJ production metadata (bates, custodians, dates)
  - redaction_analysis_v2.db.gz: detected redactions + OCR of text underneath
  - deposition_transcripts.db.gz: transcribed depositions

### 11 Falsifier Entities Verified in Archive
- **R-EPSTEIN-WEXNER-001**: Leslie Wexner (CargoMetrics → Paxos → TokenUnion)
- **R-EPSTEIN-ACOSTA-001**: Alexander Acosta (US Atty → Trump Labor Sec)
- **R-EPSTEIN-GRIFFIN-001**: Mike Griffin (In-Q-Tel → NASA → SpaceX)
- **R-EPSTEIN-CLINTON-001**: Bill Clinton (Foundation, flights)
- **R-EPSTEIN-TRUMP-001**: Donald Trump (Mar-a-Lago, Acosta)
- **R-EPSTEIN-DERSHOWITZ-001**: Alan Dershowitz (Harvard Law, legal shield)
- **R-EPSTEIN-VANCE-001**: JD Vance Jr. (Thiel/Schmidt/Musk network)
- **R-EPSTEIN-BANNON-001**: Steve Bannon (Breitbart, Trump admin)
- **R-EPSTEIN-CARLSON-001**: Tucker Carlson (Fox, amplification)
- **R-EPSTEIN-MAXWELL-001**: Ghislaine Maxwell (intelligence bridge)
- **R-EPSTEIN-BARR-001**: William Barr (AG, MCC oversight)

### Isomorphism Components (8)
1. **Patron/Funder**: Wexner → Thiel/Musk/Schmidt
   - **R-ISO-PATRON-001**: Wexner Limited Brands, New Albany/Technate Ohio
   - **R-ISO-PATRON-002**: Thiel Founders Fund, Musk SpaceX/Tesla, Schmidt Google/NSCAI

2. **Legal Shield**: Acosta/Dershowitz/Barr → Barr/DOGE capture
   - **R-ISO-LEGAL-001**: Acosta non-prosecution agreement 2008
   - **R-ISO-LEGAL-002**: Dershowitz Harvard Law defense
   - **R-ISO-LEGAL-003**: Barr AG oversight of MCC

3. **Political Cutouts**: Clinton/Trump → Newsom/Vance (Schmidt unitary)
   - **R-ISO-POLITICAL-001**: Clinton Foundation, Trump Mar-a-Lago
   - **R-ISO-POLITICAL-002**: Newsom (Hoffman/Powell Jobs), Vance (Thiel/Schmidt/Musk)

4. **Intelligence Bridge**: Maxwell/Borgerson/Paxos → Parker/Founders Fund
   - **R-ISO-INTEL-001**: Maxwell → Scott Borgerson (CargoMetrics) → Paxos
   - **R-ISO-INTEL-002**: Parker (CIA 16) → Founders Fund → Palantir/SpaceX/Polymarket

5. **Israeli Channel**: Barak/Wexner/Maxwell → Netanyahu/Benartzi/Bancor/Polymarket
   - **R-ISO-ISRAEL-001**: Ehud Barak association with Epstein
   - **R-ISO-ISRAEL-002**: Netanyahu family → Benartzi → Bancor → TokenUnion → Polymarket

6. **Science/Tech Pipeline**: MIT Media Lab (Ito/Epstein) → Stanford Review/Thiel Fellowship/NSCAI/In-Q-Tel
   - **R-ISO-TECH-001**: MIT Media Lab Ito/Epstein funds
   - **R-ISO-TECH-002**: Stanford Review → Thiel Fellowship → NSCAI → In-Q-Tel

7. **Media Control**: Blackmail/leverage (ABC spiked story 2015) → Platform ownership (Musk/X) + Amplification (Carlson)
   - **R-ISO-MEDIA-001**: ABC News spiked Epstein story 2015 (Robach hot mic)
   - **R-ISO-MEDIA-002**: Musk X ownership, Carlson amplification

8. **Financial Infrastructure**: JPMorgan/Bear Stearns → Stripe/Plaid (Thiel) → Paxos/PYUSD (CargoMetrics) → Polymarket/Kalshi (futarchy)
   - **R-ISO-FIN-001**: JPMorgan Epstein accounts, Bear Stearns Cayman funds
   - **R-ISO-FIN-002**: Stripe/Plaid Thiel investments
   - **R-ISO-FIN-003**: Paxos/PYUSD CargoMetrics connection
   - **R-ISO-FIN-004**: Polymarket/Kalshi futarchy implementation

### Disposal Mechanism Contrast
- **R-ISO-DISPOSAL-001**: Suicide in MCC (Acosta/Barr oversight)
- **R-ISO-DISPOSAL-002**: DOGE machine self-reinforces (no disposal needed)

## Cross-References
- Substrate entries: `/home/gringo/Substrate/pawns/Claims/CL-001` through `CL-020`, `PE-001` through `PE-025`
- Epstein archive queries: `/home/gringo/Epstein-research-data/` (7 SQLite DBs)
- DOGE evidence: `/home/gringo/botwave/osint/expansion/` (contracts, lobbying, CIO installs)