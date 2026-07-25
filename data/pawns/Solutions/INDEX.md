# Solutions — Index

| ID | Name | One-line | Links |
|----|------|----------|-------|
| [SO-001](./SO-001—Receipts-First-Pipeline.md) | Receipts-First Pipeline | Every claim is paired with a JSONL receipt ID; if a claim has no receipt, it does not ship | [SO-002]—Source-Trace-Validator, [VA-001]—Receipts-First-Principle, [PL-001]—Three-Deliverable-Plan |
| [SO-002](./SO-002—Source-Trace-Validator.md) | Source-Trace Validator | CLI that walks a pawns/ entry's SOURCES: block, resolves each URL/receipt pointer to a row in the substrate, and reports resolved/unresolvable; substrate's CHECK 4 enforcer | [SO-001]—Receipts-First-Pipeline, [SO-004]—Blockchain-Anchor, [VA-001]—Receipts-First-Principle |
| [SO-003](./SO-003—MOA-Voice-Lock.md) | MOA Voice Lock | Writer model must cite receipt in same paragraph as claim, name source class explicitly, refuse unsourced quantitative claims | [VA-001]—Receipts-First-Principle, [SO-001]—Receipts-First-Pipeline, [PL-001]—Three-Deliverable-Plan |
| [SO-004](./SO-004—Blockchain-Anchor.md) | Blockchain Anchor | Hash every receipt and submit to a public chain (Telos or Bitcoin) at load time; tamper-evident timestamp for every claim | [SO-002]—Source-Trace-Validator, [VA-001]—Receipts-First-Principle, [PR-003]—Mechanism-Opacity |
