1) Context-first: no runtime/infra work until the readiness checklist is green.
2) Small, strict model later: one DSL, versioned, codegen drives UI/API/DB.
3) Grain discipline: every future entity declares grain & units.
4) Azure managed-first; defer “nice-to-haves” (APIM, ClickHouse) until events flow.
5) Monolith-module: one deployable, contracts enforce module boundaries.
