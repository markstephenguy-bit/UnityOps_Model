# ADR 0001: Adopt Architecture as Code (AaC)

* **Date:** 2025-08-20
* **Status:** Accepted

## Context

Architecture drifts without source control and repeatable rendering.

## Decision

Use Git as the **single source of truth** for architecture (diagrams + docs).
Store diagrams as **Mermaid** text; docs as **Markdown**; track decisions as **ADRs**.

## Consequences

* ✔ Reviewable diffs, reproducible diagrams, CI rendering
* ✖ Requires minimal tooling (Mermaid CLI in CI)

## Alternatives

* Static images (no diffs)
* Wiki-only documentation (not reviewable as code)
