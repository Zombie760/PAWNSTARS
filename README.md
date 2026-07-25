# THE PROCUREMENT MACHINE — Public Repository

**Intelligence Program Privatization as a Distinct Procurement Category: A Structural Analysis of the DARPA-to-DOGE Pipeline**

Author: Kyle Jimenez (gringo/gringo1904) for Botwave
Date: July 2026

## Overview

This repository contains the complete public release of "THE PROCUREMENT MACHINE" — a 130,000-word PhD-grade dissertation demonstrating that the companies sold as "Silicon Valley startups" (Palantir, Facebook/Meta, SpaceX/Starlink, Polymarket, Anduril) are intelligence program privatizations executed through a documented, repeatable 5-stage procurement pipeline.

The DOGE (Department of Government Efficiency) machine is this pipeline operationalized as a self-reinforcing extraction architecture.

## Contents

### 📄 Dissertation (11 Chapters + 6 Appendices)
- `chapters/chapter_1.html` through `chapters/chapter_11.html`
- `appendices/appendix_A.html` through `appendices/appendix_F.html`
- `THE_PROCUREMENT_MACHINE.pdf` (126 pages, peer-review ready)

### 📊 Interactive Visualizations
- `selectorate_network.html` — Three-layer network (9 PMs → 4 Board Bodies → 9 Operators) with centrality analysis proving Eric Schmidt as unitary node
- `pipeline_sankey.html` — Sankey flow of all 5 waves through 5 stages with receipt data
- Origin traces: `data/facebook_origin.json`, `data/polymarket_origin.json`, `data/kalshi_origin.json`

### 🗂️ Structured Data (JSON)
- `data/pipeline_stages.json` — 5 stages × 5 waves with gate criteria and receipts
- `data/selectorate_network.json` — 22 nodes, 67 edges, centrality metrics
- `data/pipeline_sankey.json` — Sankey flow data
- `data/facebook_origin.json`, `data/polymarket_origin.json`, `data/kalshi_origin.json` — Origin traces
- `data/pawns/` — 76 Miessler-schema entities (Claims, People, Companies, Programs, Risks)

### 📋 Verification Infrastructure
- `receipts/` — Chapter methodology files for BUQP gate
- `gate_paper.py` — BUQP verification gate (run with `--strict`)
- `pawns_validate.py` — Substrate schema validator
- All 12 chapters BUQP PASS (4 ADVISE, 5 CANNOT-VERIFY on quotes)
- 10 thesis claims, 40 red team attacks, 40 repelled, 0 triggered

## Live Site

Deploy to GitHub Pages at `zombie760.github.io/procurement-machine` or custom domain.

## Methodology

**Receipts-First · BUQP-Gated · Substrate-Anchored · Red-Team Stress-Tested · Falsifier-Disciplined**

Every claim has a falsifier and a primary source receipt. All entities resolve to substrate. The architecture stands until a falsifier is produced.

## Data Sources

Congressional Record · SEC EDGAR · USAspending.gov · Senate LDA · Corporate Registries · Court Dockets · Epstein Archive (epstein-docs.github.io) · NRO/Reuters · CFTC Dockets · Tesla 10-Ks

---

*The architecture stands until a falsifier is produced.*
