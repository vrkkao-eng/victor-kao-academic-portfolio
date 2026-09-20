# MAILO — Medical AI Legal Ontology

[Public repository](https://github.com/vrkkao-eng/Mailo-ontology)

## Research goal

MAILO investigates how legal and regulatory knowledge relevant to medical artificial intelligence can be represented in a structured, machine-readable form while keeping source material, interpretation, and modelling choices distinguishable.

The project brings together legal doctrine, ontology engineering, RDF/OWL modelling, SPARQL querying, and SHACL validation.

## Role

Victor Kao developed the MAILO thesis artifact and maintains the public ontology repository. The public repository remains the source of record for implementation history, releases, encoded legal sources, and validation scope.

## Research contribution and technical evidence

The public repository provides verifiable evidence of work involving:

- ontology modelling for a multi-framework EU legal and regulatory domain;
- RDF/OWL knowledge representation;
- SPARQL querying;
- SHACL constraints for machine-executable validation;
- legal-source annotation and provenance;
- explicit separation between court holdings and designer operationalisations; and
- documented limits on what has and has not been formalised.

## Why it matters

Legal and regulatory texts are not naturally executable specifications. MAILO explores how parts of that information can be made explicit and testable without implying that legal interpretation has been eliminated.

This makes the project relevant to broader research questions about:

- formalisation difficulty and open texture;
- provenance-aware AI;
- neuro-symbolic legal-AI systems;
- human review and expert disagreement; and
- the role of knowledge graphs in LLM grounding and explanation.

## Companion engine

The application and validation layer is maintained separately in:

[MAILO Legal AI Engine](https://github.com/vrkkao-eng/mailo-legal-ai-engine)

The separation is deliberate:

- **Mailo-ontology** owns the canonical knowledge model and substantive SHACL artefacts.
- **mailo-legal-ai-engine** owns the Python pipeline, graph export, query execution, validation reports, and tests.

## Related public paper

**Kao, Chang-Hua. “MAILO: An OWL/SHACL Resource for Machine-Executable Conformance Checking of EU Medical-AI Regulatory Obligations.”** SSRN, 17 September 2026.

[SSRN abstract 7476078](https://ssrn.com/abstract=7476078)

## Scope note

MAILO is a research artifact. SHACL conformance does not by itself establish legal correctness or regulatory compliance. The ontology and engine repositories document their own modelling assumptions and validation boundaries.

## Project links

- [MAILO ontology](https://github.com/vrkkao-eng/Mailo-ontology)
- [MAILO Legal AI Engine](https://github.com/vrkkao-eng/mailo-legal-ai-engine)
- [SSRN resource paper](https://ssrn.com/abstract=7476078)
