# Polymarket Mechanism — Substrate Index

**Provenance:** Whitney Webb & Mark Goodwin, *The Secret History of Polymarket — Part 1*, Unlimited Hangout, June 30, 2026 (55 min read).

**Source:** `/home/gringo/Downloads/The-Secret-History-of-Polymarket-Part-1.txt` (1,883 lines, ~120K chars, fully read in 500-line chunks per active rules).

**Methodology:** Miessler Substrate format — each entry has `ID:`, `DESCRIPTION:`, `SOURCES:`, `FALSIFIER:`, `CROSS-REFERENCES:`. Every claim traces to a real receipt. No fabrication.

---

## Counts

| Category | Count |
|----------|-------|
| Claims (CL-*) | 10 |
| People (PE-*) | 9 (so far) |
| Programs (PR-*) | 5 |
| Companies (CO-*) | 11 |
| Evidence artifacts (EV-*) | 6 |
| **Total entries** | **41** |

## Master Claim List

| ID | Claim | Status |
|----|-------|--------|
| CL-001 | PAM is direct ancestor of Polymarket | substantiated |
| CL-002 | TIA privatized into Palantir by Thiel | substantiated |
| CL-003 | LifeLog launched as Facebook same day (Feb 4 2004) | substantiated |
| CL-004 | TokenUnion partnered with Bancor (Netanyahu family) | substantiated |
| CL-005 | CFTC captured: Selig/Quintenz/a16z | substantiated |
| CL-006 | Augur → Polymarket "Napsterization" via Krug | substantiated |
| CL-007 | Sean Parker intelligence lineage (FBI/CIA/MK-ULTRA) | substantiated |
| CL-008 | "Napsterization" model as Thiel disruption pattern | substantiated |
| CL-009 | IARPA ACE parallel to Augur (2011-2015) | substantiated |
| CL-010 | "House always wins" — Polymarket + Trump + futarchy | substantiated |

## Master Node List

### People (9)
- PE-001 Robin Hanson (PAM architect, futarchy)
- PE-002 Shayne Coplan (Polymarket founder)
- PE-003 John Poindexter (Iran-Contra, IAO, TIA)
- PE-004 Peter Thiel (PayPal, Palantir, Facebook, Founders Fund, Vance)
- PE-008 Sean Parker (Napster, Facebook, Founders Fund, MK-ULTRA lineage)
- PE-011 Benjamin Netanyahu (Bibi, Benartzi uncle)
- PE-016 Donald Trump Jr. (Polymarket + Kalshi advisor/investor)
- PE-017 Joey Krug (Augur co-founder, Founders Fund crypto)
- PE-026 JD Vance (VP, Thiel $15M)

### Programs (5)
- PR-001 PAM (Policy Analysis Market, 2003)
- PR-002 TIA (Total Information Awareness, 2003)
- PR-003 LifeLog (2004)
- PR-004 IARPA ACE (2011-2015)
- PR-005 IAO (Information Awareness Office)

### Companies (11)
- CO-001 Polymarket
- CO-002 Augur
- CO-003 Palantir
- CO-004 Facebook (referenced)
- CO-005 Bancor (referenced)
- CO-006 TokenUnion (Coplan predecessor)
- CO-007 Kalshi
- CO-008 5c(c) Capital (Coplan+Mansour)
- CO-009 1789 Capital (Don Jr)
- CO-010 Andreessen Horowitz (referenced)
- CO-011 Founders Fund

### Evidence Artifacts (6)
- EV-001 PAM Logo (pyramid in A)
- EV-002 Augur Logo (pyramid)
- EV-003 TokenUnion/Bancor 2018 archive
- EV-004 Coplan deleted bio
- EV-005 Parker Forbes 2011 profile
- EV-006 Palantir/TIA quote stack

## Missing Entries (Part 2 not yet published)

Per Webb/Goodwin: "As will be explored in Part II of this series, an ulterior motive directly linked to Coplan's efforts aims to advance an extremely dystopian governance model that is of great interest to the Big Tech billionaires now closely linked to Coplan and the dominant prediction market companies, such as Peter Thiel and Marc Andreessen."

Part 2 (per Part 1's own forward references):
- **Futarchy** governance model — to be detailed
- **Musk-Hanson relationship** (via Kimbal Musk, Wyly son-in-law)
- **Oracle problem** for Polymarket legal standing + centralization
- **Internal Polymarket architecture / UMA oracle**

**Action:** Subscribe to Unlimited Hangout newsletter. When Part 2 publishes, add new claims PE-018, PE-024, etc.

## To Do

1. Add more people (PE-005 Karp, PE-006 Wade, PE-007 Gage, PE-009/010 Benartzi, PE-012 Selig, PE-013 Quintenz, PE-014 Andreessen, PE-015 Mansour, PE-018 Buterin, PE-019/020/021/022 Parker family + Jones/Conover, PE-023 Matheny, PE-024 Moskovitz, PE-025 Gardner)
2. Add remaining companies (CO-004 Facebook, CO-005 Bancor, CO-009 1789 Capital, CO-010 a16z, CO-012 Pantera Capital, CO-013 Edge Foundation, CO-014 Project Medea, CO-015 Napster, CO-016 Spotify, CO-017 Uber, CO-018 CSET, CO-019 Open Philanthropy, CO-020 Thiel Fellowship, CO-021 Narya Capital, CO-022 Anduril)
3. Add CLAIM CL-011: 1789 Capital + Don Jr. as family capture vehicle
4. Add CLAIM CL-012: Futarchy implementation in current administration
5. Build Maltego-style graph rendering (use mcp__mcphub__filesystem for write_file or write Python script that reads this substrate and emits a Maltego-compatible .mtz file)
6. Cross-validate against Unwarranted Influence manuscript (already in book/) — the Thiel-Palantir-Vance axis intersects

## Links to Botwave substrate

This `polymarket_mechanism` directory is the **first thematic subgraph** under the master `~/Substrate/`. It follows the same format as the existing `pawns/` subgraph.

Compatible with:
- `pawns_substrate.py` (loader)
- `pawns_validate.py` (4-check validator)
- The botwave-journalism `substrate` directory

## Key Insight: The "Napsterization" Pattern

Webb's central thesis: a documented Thiel-network disruption pattern.

| Iteration | Step 1: Illegal | Step 2: Raid/Fine | Step 3: De-facto capture | Step 4: Legitimacy |
|----------|----------------|-------------------|------------------------|-------------------|
| Napster | P2P music | Sued out of biz | — | Spotify (Parker/Founders Fund) |
| Facebook | Harvard dorm | Various | — | World's largest social network |
| Uber | Illegal taxis | Raided | Lobbying state-by-state | De facto monopoly |
| Augur | First on Ethereum | Failed | — | Polymarket (Krug/Founders Fund) |
| Polymarket | Offshore, broke CFTC rules | Fined/blocked | CFTC Selig chair | "Tell us to police ourselves" |
| TIA/LifeLog | DARPA programs | Congress defunded | — | Palantir/Facebook |
| Facebook Libra | Stablecoin attempt | Killed | — | Now? (per "Chain of Command" 2024) |

**This is the user's book thesis operationalized as a substrate:** "we don't hold elections, we hold auctions" — the Napsterization model is *the* mechanism. Polymarket's prediction markets are the *financialization* of this same pattern.

## What the book will need

- 6-8 chapters minimum following the cold-open doc pattern
- Each chapter open with a real document/filing
- The three DARPAs (PAM, TIA, LifeLog) → three privatizations (Polymarket, Palantir, Facebook)
- The political capture: 1789 Capital + Don Jr. + Vance + Thiel
- The visual map as appendix or chapter opening
- Each claim = substrate entry with FALSIFIER

The substrate is now usable. Next step: write the book, using the buqp_humanizer project profile.
