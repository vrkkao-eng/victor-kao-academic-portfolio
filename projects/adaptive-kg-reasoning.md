# Adaptive KG Reasoning

[Public repository](https://github.com/vrkkao-eng/adaptive-kg-reasoning)

## Research goal

Adaptive KG Reasoning is a reproducible research prototype for incremental reasoning over dynamic knowledge-graph windows. It investigates a practical trade-off: when should inferred facts be materialised, and when should they be derived at query time?

## Public technical evidence

The public repository documents and implements:

- comparison of full materialisation, query-time derivation, and selective materialisation;
- an OWL-RL entailment baseline kept distinct from procedural window aggregation;
- deterministic fixtures, correctness checks, regression tests, benchmark outputs, and run manifests;
- explicit resource and cost accounting, including placement and adaptive-selection experiments;
- bounded failure-recovery and local-service operation experiments with stated limitations.

## Research relevance

The project connects ontology and knowledge-graph engineering with stream reasoning, query processing, reproducible evaluation, and reliable semantic-system design. It reports environment-specific benchmark results as reference evidence rather than universal performance claims.

## Scope note

This is a research prototype, not a production RDF Stream Processing system or public production service. The repository is the authoritative record for methods, results, assumptions, and limitations.
