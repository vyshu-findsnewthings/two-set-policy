# Two-Set Policy v0.1.0

## Overview

This is the initial public research release of Two-Set Policy.

Two-Set Policy is an open research framework exploring whether policies written primarily for human interpretation require a second, explicit operational policy layer before they can be safely implemented, monitored, or enforced by software systems and AI agents.

## Origin of the hypothesis

The idea emerged from work on a paper prepared for the International Sociological Association.

While attempting to screen Instagram Reels using vision models and frontier AI models, substantial gaps were observed between the content present in the source material and the way models interpreted, classified, or contextualised it.

That observation led to a broader hypothesis:

> Policies intended for human interpretation may be insufficient for direct implementation, monitoring, or enforcement by software systems and AI agents unless an additional operational policy layer makes permissions, prohibitions, evidence requirements, authority boundaries, escalation paths, monitoring conditions, and redressal mechanisms explicit.

This release presents that proposition as a research hypothesis, not as a validated conclusion.

## This release includes

- the core Two-Set Policy concept
- the origin and motivation of the hypothesis
- a current-context explanation covering agentic systems, robotics, automated vehicles, surgical assistants, agricultural robots, and other action-capable systems
- the immediate research and functional scope
- a 6-to-12-month development roadmap
- a generic framework overview
- a provisional source-policy model
- a provisional operational-policy model
- an initial worked case based on the National Digital Health Blueprint
- related-work positioning
- explicit research limitations
- a disclaimer
- content licensing
- citation metadata
- Mermaid diagrams for conceptual, technical, and case-level explanation

## Mermaid diagrams included

This release includes diagrams covering:

- the current system context and interpretation risk
- the Two-Set Policy architecture
- the generic framework workflow
- the NDHB case workflow
- the relationship to adjacent research fields

## Repository artefacts

### Concept

- `concept/two-set-policy.md`
- `concept/immediate-scope.md`

### Framework

- `framework/framework-overview.md`
- `framework/provisional-policy-model.json`
- `framework/provisional-operational-policy-model.json`

### Case study

- `cases/case-001-ndhb/README.md`

### Research

- `research/related-work.md`
- `research/limitations.md`

### Project governance

- `ROADMAP.md`
- `CHANGELOG.md`
- `DISCLAIMER.md`
- `LICENSE-CONTENT`
- `CITATION.cff`

## What this release does not claim

This release does not claim:

- that the framework has been comprehensively validated
- that the proposed terminology is final
- that the JSON models are complete or implementation-ready
- that the NDHB analysis is authoritative
- that the framework constitutes a legal standard
- that the repository provides certified regulatory compliance
- that the framework applies universally across policy domains
- that the repository is ready for production enforcement
- that all policy provisions should be machine-executable

## Known limitations

The main limitations include:

- novelty has not yet been fully established
- the related-work review is preliminary
- the first case is selective and exploratory
- independent expert review has not yet been completed
- statistical and empirical validation remain future work
- cross-domain generalisation is unproven
- institutional participation is not yet built into the method
- runtime policy enforcement is outside the current release

See:

- `research/limitations.md`

## Release status

Version: `v0.1.0`

Status: Initial public research framework release

Validation status: Not independently validated

Deployment status: Not suitable for production enforcement

## Licence

Original documentation, diagrams, schemas, research notes, and case-study materials are licensed under the Creative Commons Attribution 4.0 International Licence unless otherwise stated.

See:

- `LICENSE-CONTENT`

## Citation

Citation metadata is available in:

- `CITATION.cff`

A DOI will be added after this GitHub release is archived through Zenodo.

## Author

Vani Vyshnavi Jupudi

## Next steps

Planned next steps include:

- deeper NDHB analysis
- clause-to-rule traceability
- operational sequence diagrams
- direct machine-interpretation vulnerability registers
- monitoring-system vulnerability registers
- redressal modelling
- expert review
- a second policy-domain case
- framework refinement
- early tooling for structured policy analysis
