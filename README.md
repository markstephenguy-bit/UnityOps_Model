# UnityOps Model – Architecture as Code

This repo stores the **official software architecture** for UnityOps using **Architecture as Code (AaC)**.

## What’s here
- **C4 diagrams** (Mermaid) in `docs/c4`
- **Architecture Decision Records (ADRs)** in `docs/adr`
- **Non‑functional requirements** in `docs/non-functional-requirements.md`
- **Glossary** in `docs/glossary.md`
- **CI** renders diagrams on every push and uploads them as build artifacts

## Edit flow
1) Propose changes in a branch.
2) Update C4 Mermaid files and/or ADRs.
3) Run PR; CI will render and attach **PNG/SVG** of every diagram.
4) Review diffs (text + rendered diagrams). Merge when approved.

## Local preview (optional)
```bash
# Requires Node 18+
npm -g install @mermaid-js/mermaid-cli
mmdc -i docs/c4/01-context.mmd -o docs/c4/01-context.png
```

## Files of interest

* `docs/c4/01-context.mmd` – System Context (L1)
* `docs/c4/02-container.mmd` – Containers (L2)
* `docs/c4/03-component-example.mmd` – Component example (L3)
* `docs/adr/0000-template.md` – ADR template
* `docs/adr/0001-adopt-architecture-as-code.md`
* `docs/adr/0002-choose-c4-mermaid.md`
