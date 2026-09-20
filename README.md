# Chang-Hua Kao (Victor) — Research Portfolio

**Legal AI · Knowledge Representation · Knowledge Graphs · Neuro-Symbolic AI · AI & Law**

My research sits at the intersection of **law, knowledge representation, and artificial intelligence**. I am particularly interested in how legal and regulatory knowledge can be represented in machine-readable form, where formalisation reaches its limits, and how knowledge graphs can be combined with language models while preserving traceability, verification, and meaningful human review.

This repository is the **academic-facing** counterpart to my engineering-oriented GitHub profile. It highlights research questions, public research artifacts, methods, and academic development rather than general software-project breadth.

## Research profile

My current research interests include:

- **Legal knowledge representation** using RDF, OWL, SHACL, and SPARQL
- **Knowledge graph + LLM integration** and neuro-symbolic approaches
- **Explainability and verification** for AI-supported legal reasoning
- **Open texture / interpretive openness** as a boundary condition for legal formalisation
- **Machine-executable regulatory constraints** and provenance
- **AI governance and EU digital regulation**, including data protection and medical AI
- **Human-centred evaluation** of explanations, verification behaviour, metacognition, and cognitive load

## Current research direction

My current Master of Artificial Intelligence research direction investigates how structured legal knowledge can support language-model systems without treating formalisation as a substitute for legal interpretation.

The working agenda has three connected strands:

1. **Knowledge-graph-guided LLM use**  
   Compare structured grounding with less structured LLM approaches for traceability, verification, and explanation.

2. **Interpretive openness / formalisation difficulty**  
   Study where legal concepts resist deterministic representation and where human review or expert disagreement should remain explicit.

3. **Human-centred explainability**  
   Examine whether knowledge-grounded explanations affect users' verification behaviour, metacognition, and cognitive load in an educational setting.

These are ongoing research questions, not claims of completed empirical results.

## Selected public research artifacts

### [MAILO — Medical AI Legal Ontology](https://github.com/vrkkao-eng/Mailo-ontology)

MAILO is an OWL/SHACL knowledge graph for EU medical-AI regulation. It represents legal sources, obligations, regulatory relationships, and selected case-law principles in a machine-readable form while distinguishing source material from modelling and operationalisation choices.

**Research methods and technologies:** OWL 2 · RDF · SHACL · SPARQL · ontology engineering · legal doctrinal analysis · provenance-aware modelling

[Project note](projects/mailo.md)

### [MAILO Legal AI Engine](https://github.com/vrkkao-eng/mailo-legal-ai-engine)

A companion Python research prototype separated from the ontology repository. It provides an inspectable application layer for structured findings, RDF/JSON-LD export, SPARQL execution, SHACL validation, reproducible reports, and testing.

For academic purposes, the engine serves as an **experimental and reproducibility layer** rather than as a claim of automated legal compliance.

**Methods and technologies:** Python · RDFLib · pySHACL · SPARQL · JSON-LD · pytest · GitHub Actions

### SSRN research resource

**“MAILO: An OWL/SHACL Resource for Machine-Executable Conformance Checking of EU Medical-AI Regulatory Obligations.”**  
SSRN, 17 September 2026.  
[SSRN abstract 7476078](https://ssrn.com/abstract=7476078)

This paper documents MAILO as a research resource and explains its use of OWL/SHACL for machine-executable regulatory constraints.

### [AI & Data Protection — Advanced Master thesis visualisation](https://github.com/vrkkao-eng/IpIct_MANAMA_Thesis_AI_Data_protection)

Interactive presentation of research on foundation models, generative AI, data protection, and the EU regulatory framework.

### [Kelsen — Authority visualisation](https://github.com/vrkkao-eng/Kelsen-authority-visualization)

Bilingual interactive visualisation based on earlier jurisprudential research on Hans Kelsen's concept of authority. It reflects the legal-theory foundation that informs my later work on formalisation and legal knowledge representation.

## Research questions connecting the portfolio

A recurring question across these projects is:

> **What should be made machine-readable, what can be made machine-executable, and what should remain explicitly open to interpretation and human judgment?**

This leads to several linked research problems:

- How should legal holdings be separated from engineering operationalisations?
- How can a system expose provenance and validation boundaries rather than collapse them into a single “compliance” answer?
- When does a knowledge graph improve an LLM's grounding or explainability?
- Can interpretive openness or formalisation difficulty be detected or represented in ways that meaningfully guide human review?
- How should empirical user studies evaluate explanation quality beyond simple answer accuracy?

## Methodological toolkit

### Legal and regulatory analysis
- EU digital and data regulation
- data protection and AI governance
- medical-AI regulation
- doctrinal case-law analysis
- distinction between legal source, interpretation, and system operationalisation

### Knowledge representation
- RDF / OWL
- SHACL
- SPARQL
- ontology engineering
- competency questions
- provenance and traceability

### Computational methods
- Python
- RDFLib / pySHACL
- structured graph export
- validation pipelines
- LLM-assisted research workflows
- reproducible testing and documentation

### Human-centred evaluation
- qualitative study design
- explanation and verification behaviour
- metacognition
- cognitive load
- educational framing

## Academic trajectory

My academic development combines four complementary layers:

- **Philosophy** — conceptual analysis and legal philosophy
- **LL.M. / legal research** — jurisprudence and legal authority
- **Advanced Master in IP & ICT Law, KU Leuven** — data protection, AI regulation, copyright, telecom, competition, and digital regulation
- **Master of Digital Humanities, KU Leuven** — semantic technologies, knowledge graphs, and the MAILO thesis artifact
- **Master of Artificial Intelligence, KU Leuven (Speech & Language Technology)** — current work on KG–LLM integration, explainability, and human-centred evaluation

## Research-to-engineering boundary

The research portfolio intentionally distinguishes between:

**Legal / research layer**  
sources → interpretation → ontology → explicit constraints → research questions

and

**Engineering layer**  
Python pipeline → graph export → query execution → validation → testing

This separation is important to the research agenda: executable constraints can support analysis and verification, but they do not eliminate legal interpretation.

## For industry-oriented reviewers

My engineering and applied-AI projects are presented separately on my main GitHub profile:

**[github.com/vrkkao-eng](https://github.com/vrkkao-eng)**

That profile foregrounds AI engineering, API integration, deployment-oriented work, and applied system building.

## Links

- [MAILO ontology](https://github.com/vrkkao-eng/Mailo-ontology)
- [MAILO Legal AI Engine](https://github.com/vrkkao-eng/mailo-legal-ai-engine)
- [SSRN — MAILO resource paper](https://ssrn.com/abstract=7476078)
- [Main GitHub profile](https://github.com/vrkkao-eng)
- [LinkedIn](https://www.linkedin.com/in/victor-changhua-kao/)

---

*Ongoing research directions are labelled as such. Public repositories and papers are the source of record for implemented artifacts and published claims.*
