# MAILO Legal AI Engine

[Public repository](https://github.com/vrkkao-eng/mailo-legal-ai-engine)

## Research and engineering goal

MAILO Legal AI Engine is an auditable workflow prototype for regulated-AI work. It turns reviewed regulatory-change information into traceable obligation, control, evidence, review, and audit workflows.

It is deliberately designed around a bounded claim: structured workflow support and inspectable evidence, not autonomous legal interpretation or a declaration of compliance.

## Public technical evidence

The repository documents and implements:

- a Python/FastAPI application layer with typed interfaces;
- deterministic workflow logic for reviewed regulatory changes, applicability gates, evidence gaps, review routing, and audit events;
- transactional persistence, idempotency, explicit failure semantics, and reproducible tests;
- RDF/JSON-LD export, SPARQL execution, and SHACL validation; and
- a minimal local operator interface for reviewing changes, queues, and case traces.

The canonical legal knowledge model and substantive SHACL constraints remain in the separate [MAILO ontology repository](https://github.com/vrkkao-eng/Mailo-ontology). This separation preserves a clear boundary between legal knowledge modelling and operational application state.

## Research relevance

The project provides public evidence of how knowledge-engineering methods can be connected to reliable operational workflows while retaining provenance, review points, and testable failure boundaries.

## Scope note

This is an engineering prototype. Its deterministic checks and validation outputs do not establish legal correctness or regulatory compliance. The public repository is the source of record for implementation, tests, and documented limitations.
