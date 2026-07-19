# Roadmap

## Roadmap purpose

This roadmap describes the planned development of Two-Set Policy over the next 6 to 12 months.

The framework and the supporting technology stack will evolve together. The governance framework will define the method, while the technology stack will support analysis, validation, traceability, review, and future operational use.

The roadmap is intentionally staged. Early work will focus on research structure and human-reviewed policy modelling before any attempt is made to support runtime policy enforcement.

## Months 0 to 3: Foundation

### Framework development

- define the Two-Set Policy concept
- define the relationship between human-readable and operational policy
- establish provisional terminology
- define a generic policy context model
- define a provisional operational policy model
- define interpretation-vulnerability categories
- define monitoring-vulnerability categories
- define redressal and escalation requirements
- define non-automatable policy provisions
- define source traceability requirements
- define unresolved-policy dependency handling

### Case development

Case 001 will use selected workflows from the National Digital Health Blueprint of India.

The initial workflows will include:

- consented health-record sharing
- consent withdrawal
- emergency access
- identity uncertainty
- research and analytics access
- monitoring
- correction and redressal

### Technology development

- Markdown-based framework documentation
- JSON policy models
- JSON Schema validation
- Mermaid sequence diagrams
- CSV vulnerability registers
- traceability tables
- lightweight validation scripts
- Git-based version history

### Expected outputs

- version 0.1 framework release
- first DOI-backed archive
- concept note
- immediate scope
- provisional schemas
- NDHB Case 001 preview
- first vulnerability register
- initial implementation diagrams
- research limitations

## Months 3 to 6: Generalisation

### Framework development

- apply the framework to a second policy domain
- compare stable and domain-specific framework elements
- refine actor and authority modelling
- refine evidence and exception modelling
- refine monitoring and redressal structures
- refine change-control requirements
- improve the provisional gap taxonomy

### Technology development

Develop a small human-in-the-loop policy analysis workbench capable of:

- accepting policy documents
- reviewing extracted clauses
- identifying actors and authorities
- classifying interpretation gaps
- generating operational policy drafts
- generating sequence diagrams
- linking rules to source clauses
- flagging unresolved fields
- exporting JSON and Markdown artefacts

### Expected outputs

- framework version 0.3
- second policy case
- cross-case comparison
- revised schemas
- prototype analysis workbench
- concept or working paper
- external feedback record

## Months 6 to 9: Evaluation

### Framework evaluation

- involve independent reviewers
- compare reviewer findings
- measure agreement and disagreement
- test authority assignments
- test non-automatable classifications
- assess redressal modelling
- assess traceability usefulness
- document unresolved disagreements

### Functional development

Add support for:

- reviewer roles
- decision attribution
- comment history
- approval states
- structured TODO management
- source-clause linking
- version comparison
- dissent recording
- change proposals

### Expected outputs

- pilot evaluation report
- framework version 0.5
- inter-reviewer comparison
- revised terminology
- improved workbench
- case-study paper draft

## Months 9 to 12: Operational prototype

### Operational policy registry

Create a prototype registry containing:

- approved policy versions
- jurisdiction
- scope
- operational rules
- prohibitions
- exceptions
- human-review conditions
- redressal routes
- monitoring requirements
- expiry
- change authority
- source provenance

### Rule-evaluation prototype

Build a basic reference service capable of answering:

- Is this action permitted?
- Is human review required?
- Which authority must approve?
- What evidence is missing?
- Which prohibition applies?
- What redressal route must be offered?
- Which policy version governed the decision?

### Monitoring and change control

Introduce prototype monitoring for:

- policy conformance
- authority misuse
- unresolved TODOs
- policy-version drift
- unapproved changes

### Expected outputs

- three policy cases
- stable generic schema
- operational policy registry
- basic rule-evaluation API
- monitoring and change-control prototype
- human-reviewed workbench
- public methodology
- working paper or conference submission

## Year-one objective

The year-one objective is:

> A validated generic framework, demonstrated across several policy domains, supported by an open-source human-in-the-loop workbench and a prototype operational-policy registry.

The year-one objective is not a production-grade legal compliance or policy-enforcement platform.

## Beyond 12 months

Possible later directions include:

- runtime policy enforcement
- AI-agent guardrails
- policy-decision services
- monitoring-system integrations
- legal and policy drift detection
- cross-jurisdiction comparison
- policy simulation
- public consultation support
- redressal workflow integration
- open schema governance
- standards development

These directions will depend on research validation, institutional participation, and demonstrated need.
