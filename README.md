# Two-Set Policy

An open research framework for creating a traceable operational policy layer for software systems and AI agents while preserving human policy, institutional authority, redressal, and democratic oversight.

## Origin of the idea

The idea for Two-Set Policy emerged while I was working on a paper for the International Sociological Association.

As part of that work, I attempted to screen Instagram Reels using vision models and frontier AI models. The models could detect and describe many visible features, but I noticed substantial gaps between what was present in the content and how the models interpreted, classified, or contextualised it.

That observation led to a broader question:

> What happens when policies written primarily for human interpretation are read, interpreted, monitored, or enforced by agentic AI systems?

A policy may appear clear to a policymaker, regulator, administrator, or legal professional because humans bring contextual knowledge, institutional understanding, professional judgement, and social awareness to the text.

An AI agent or software system does not automatically possess that context.

It may convert broad policy language into actions, classifications, thresholds, or enforcement decisions that were never explicitly authorised.

This raised the possibility that a policy written for human consumption may require a second, complementary operational policy before it can be safely implemented by software systems or AI agents.

## Why now?

This question is becoming more important as AI moves from generating information to selecting actions and interacting with physical and institutional environments.

Agentic AI systems can plan, use tools, communicate with other systems, and take actions on behalf of users or organisations. As their autonomy increases, an incorrect interpretation may no longer remain only an inaccurate answer. It may become a workflow decision, an access decision, a transaction, an alert, an instruction to another system, or an action in the physical world.

The same governance challenge appears across different levels of autonomy and human control.

Examples include:

- AI agents that retrieve information, call software tools, approve workflow steps, or initiate transactions
- humanoid and service robots operating near people
- industrial and collaborative robots acting within factories and warehouses
- advanced driver-assistance and automated driving systems
- robotically assisted surgical systems
- agricultural robots performing navigation, spraying, harvesting, monitoring, or other field operations
- healthcare, welfare, education, finance, and public-service decision-support systems
- monitoring systems that classify behaviour, detect anomalies, or trigger escalation

These systems are not equivalent. Some act autonomously, some operate within constrained environments, some provide recommendations, and some remain under direct human control.

However, they share a governance problem:

> A system must convert policy language, safety requirements, operating procedures, and institutional expectations into specific actions or constraints.

Human-facing policies may use terms such as:

- appropriate
- safe
- reasonable
- meaningful oversight
- authorised
- minimum necessary
- high risk
- emergency
- proportionate
- fair
- timely
- when required

Humans often interpret such terms using professional training, legal context, organisational knowledge, social expectations, and situational judgement.

A software system or AI agent requires a more explicit operational account of:

- what event activates a rule
- what evidence is sufficient
- who owns the action
- who has final authority
- which action is permitted
- which action is prohibited
- when human review is mandatory
- how uncertainty should be handled
- how an affected person can challenge the outcome
- how the rule is monitored, revised, or withdrawn

The need is especially significant when digital interpretation can lead to physical action or high-impact consequences.

For example:

- an automated driving system must translate road rules, safety requirements, operating boundaries, and fallback expectations into driving behaviour
- an industrial robot must operate within defined safety controls and human-interaction limits
- a surgical robotic system must preserve the authority and control of qualified clinical professionals
- an agricultural robot may convert prescription maps and decision-support outputs into navigation, spraying, or other field actions
- an AI agent may interpret organisational policy while accessing data, communicating externally, or invoking software tools

Standards, regulation, technical controls, and safety engineering already address parts of these problems. Two-Set Policy does not seek to replace them.

The hypothesis explored here is that an additional governance artefact may be required between human-facing policy and machine action: a traceable operational policy that makes interpretation, authority, prohibitions, escalation, monitoring, and redressal explicit.

The urgency therefore does not arise only because AI systems are becoming more capable.

It arises because systems are increasingly being permitted to act, while many of the policies intended to govern those actions were written primarily for human interpretation.

## Research hypothesis

Two-Set Policy currently begins as a hypothesis.

The hypothesis is:

> Policies intended for human interpretation may be insufficient for direct implementation, monitoring, or enforcement by software systems and AI agents unless an additional operational policy layer makes permissions, prohibitions, evidence requirements, authority boundaries, escalation paths, monitoring conditions, and redressal mechanisms explicit.

This proposition has not yet been comprehensively validated.

It is expected to require:

- literature review
- policy case studies
- data collection
- statistical analysis
- expert review
- cross-domain comparison
- empirical observation
- technical experimentation
- institutional participation

The concepts, models, classifications, and schemas in this repository should therefore be treated as provisional research artefacts rather than established conclusions.

## The Two-Set Policy proposition

Two-Set Policy proposes two complementary policy sets.

### Set 1: Human-readable policy

The first policy set is intended for:

- democratic deliberation
- public communication
- legal interpretation
- institutional guidance
- contextual judgement
- expression of rights and values
- professional and administrative decision-making

It may contain principles such as fairness, meaningful oversight, proportionality, inclusion, accountability, dignity, public interest, and citizen control.

### Set 2: Operational policy

The second policy set is intended to guide and constrain:

- software systems
- digital workflows
- monitoring systems
- decision-support systems
- autonomous or semi-autonomous AI agents
- agentic AI systems
- policy-enforcement mechanisms

It should define:

- permitted actions
- required actions
- prohibited actions
- action triggers
- required evidence
- action owners
- decision authorities
- human-review conditions
- exceptions
- escalation paths
- monitoring requirements
- notification duties
- redressal mechanisms
- audit evidence
- expiry and review conditions
- change-control authority
- unresolved policy dependencies

## Relationship between the two sets

The operational policy does not replace the human-readable policy.

It must remain:

- traceable to the source policy
- subordinate to authorised policy intent
- reviewable by accountable humans
- attributable to identified decision-makers
- explicit about uncertainty
- open to challenge and correction
- subject to formal change control
- blocked from deployment where critical questions remain unresolved

In some cases, the correct operational policy may state that automation is prohibited and authorised human judgement is required.

## Central research question

Who is authorised to convert human-readable policy into operational instructions for software systems and AI agents, and how can those choices be made visible, traceable, contestable, and reviewable?

## Immediate scope

The first phase of the project focuses on:

1. extracting policy structure
2. identifying actors and authorities
3. identifying obligations, permissions, and prohibitions
4. detecting direct machine-interpretation vulnerabilities
5. detecting monitoring-system interpretation vulnerabilities
6. modelling implementation sequences
7. identifying redressal gaps
8. drafting provisional operational policy
9. tracing operational rules to source policy
10. recording unresolved policy dependencies
11. defining change-control requirements
12. identifying provisions that should not be automated

The detailed immediate scope is available in:

- [Immediate Scope](concept/immediate-scope.md)

## Generic framework

The evolving framework currently includes:

- policy ingestion
- policy decomposition
- structured interrogation
- interpretation validation
- operational policy translation
- action-owner mapping
- authority mapping
- redressal modelling
- monitoring-risk analysis
- source traceability
- unresolved TODO management
- deployment blocking
- policy change control

See:

- [Two-Set Policy concept](concept/two-set-policy.md)
- [Framework overview](framework/framework-overview.md)
- [Provisional source policy model](framework/provisional-policy-model.json)
- [Provisional operational policy model](framework/provisional-operational-policy-model.json)

## Case 001

The National Digital Health Blueprint of India is being used as the first exploratory case.

The initial analysis focuses on selected areas such as:

- consented health-record sharing
- consent withdrawal
- emergency access
- identity uncertainty
- research and analytics access
- monitoring
- correction
- grievance and redressal

See:

- [Case 001: National Digital Health Blueprint](cases/case-001-ndhb/README.md)

## Development roadmap

The repository is intended to grow through progressive framework, functional, technical, and operational enhancements.

The current roadmap covers:

- framework foundation
- second-domain testing
- independent reviewer evaluation
- a human-in-the-loop policy analysis workbench
- an operational policy registry
- a basic rule-evaluation service
- monitoring and change-control prototypes

See:

- [Roadmap](ROADMAP.md)

## Current status

Status: Early research framework

Version: 0.1.0

Validation status: Not yet independently validated

This repository does not currently provide:

- automatic legal interpretation
- certified regulatory compliance
- production policy enforcement
- automated resolution of normative questions
- automated redressal decisions
- a universal policy ontology
- an official interpretation of any policy
- proof that the framework applies to every domain

## Responsible use

The repository should not be used for production enforcement, automated decision-making, legal certification, or regulatory compliance without appropriate legal, technical, institutional, and domain review.

Please read:

- [Disclaimer](DISCLAIMER.md)

## Licence

Original documentation, framework material, schemas, diagrams, and case-study content are made available under the Creative Commons Attribution 4.0 International Licence unless otherwise stated.

See:

- [Content licence](LICENSE-CONTENT)

## Citation

Citation metadata is available through:

- [CITATION.cff](CITATION.cff)

A DOI-backed release is planned for version 0.1.0.

## Background references

The initial “Why now?” framing is informed by active work on AI agents, automated systems, robotics, and safety governance, including:

- NIST work on AI agent systems capable of planning and autonomous action
- NIST AI Risk Management Framework
- ISO safety standards for industrial and service robots
- NHTSA guidance on automated driving systems
- FDA guidance on computer-assisted surgical systems
- European work on robotics and AI in agriculture and forestry

These references establish the growing operational context. They do not establish or validate the Two-Set Policy hypothesis.

## Author

Vani Vyshnavi Jupudi

## Invitation for critique

This repository is intended as a humble and evolving research effort.

Critique is particularly welcome on:

- the core hypothesis
- overlap with existing research
- interpretation-vulnerability categories
- authority modelling
- redressal requirements
- monitoring risks
- non-automatable provisions
- schema design
- empirical validation methods
