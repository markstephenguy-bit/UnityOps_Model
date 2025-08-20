# ADR 0002: Choose C4 + Mermaid for modeling

* **Date:** 2025-08-20
* **Status:** Accepted

## Context

We need layered views and portable, text-first diagrams.

## Decision

Adopt **C4 views** (L1–L3) rendered with **Mermaid** (broad tool support).

## Consequences

* ✔ Team can edit in any editor; CI renders previews
* ✖ Mermaid C4 extension varies by renderer; we maintain compatibility via flowcharts

## Alternatives

* PlantUML C4 (excellent, JVM requirement)
* UML-only (loses pragmatic C4 views)
