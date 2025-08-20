# Non-Functional Requirements (NFRs)

> Track the qualities that drive architecture.

* **Availability:** target 99.9% (three-nines) for UI and API.
* **Performance:** P95 UI latency < 300 ms; API < 200 ms (intra-DC).
* **Scalability:** horizontal for API/workers; BI queries via columnar store.
* **Security:** OIDC/OAuth2; role-based auth; audit for data mutations.
* **Observability:** logs, metrics, traces; SLOs for core endpoints.
* **Data:** GDPR/PII tagging; lineage (ELT jobs), retention classes.
* **Reliability:** idempotent workers; DLQ on bus; at-least-once processing.
