# Related Work

## Purpose

Two-Set Policy is not being developed in an empty field.

Several established and emerging areas already address parts of the broader problem of translating policy, law, standards, and governance requirements into structured or operational forms.

This file records the main areas of related work that should inform the development of the framework.

The purpose is not to claim that Two-Set Policy replaces these fields. It is to clarify where the project overlaps with them and where its current research hypothesis may differ.

## Rules as Code

Rules as Code explores how legislation, regulation, and public rules can be represented in machine-consumable forms.

Related work in this area includes:

- machine-readable legislation
- computable rules
- digital-ready legislation
- public-rule modelling
- administrative rule engines
- open-source legal calculation systems

Two-Set Policy overlaps with Rules as Code in its interest in structured policy representation.

Its current distinction is that it focuses on the interpretive stage before operationalisation, including:

- ambiguity detection
- authority assignment
- evidence requirements
- redressal
- monitoring interpretation
- non-automatable provisions
- unresolved policy dependencies

## Policy as Code

Policy as Code commonly refers to the representation of operational rules in formats that can be evaluated by software systems.

Examples include:

- access-control policies
- infrastructure rules
- compliance checks
- deployment controls
- security constraints
- automated governance checks

Two-Set Policy may eventually use Policy as Code technologies, but the project is not currently proposing a specific rule engine.

The framework first asks:

- Which policy interpretation is authorised?
- Which assumptions were introduced?
- Who owns the action?
- Who can approve or override it?
- What evidence is required?
- What redressal is available?
- Which actions must remain prohibited?

## Computational Law and Legal Informatics

Computational law and legal informatics examine how legal rules, legal reasoning, legal documents, and legal processes can be represented or supported through computation.

Relevant topics include:

- legal knowledge representation
- legal ontologies
- legal reasoning systems
- automated legal document analysis
- machine-readable contracts
- decision modelling
- legal information retrieval
- regulatory technology

Two-Set Policy should learn from these fields, particularly their treatment of legal interpretation, formal representation, and the limits of automation.

## Requirements Engineering

Requirements engineering studies how human goals, business needs, regulations, risks, and stakeholder expectations are translated into system requirements.

This is closely related to the Two-Set Policy problem.

Relevant practices include:

- stakeholder analysis
- requirements elicitation
- ambiguity detection
- traceability
- acceptance criteria
- conflict resolution
- change control
- verification and validation

Two-Set Policy differs mainly in its emphasis on public policy, institutional authority, rights, redressal, and democratic oversight.

## Business Rules and Decision Modelling

Business-rule systems and decision-modelling methods translate organisational policies into structured decision logic.

Relevant approaches include:

- decision tables
- decision trees
- business rules management systems
- Decision Model and Notation
- workflow engines
- rule-based automation

These methods may help represent parts of operational policy.

However, they do not by themselves establish whether the underlying interpretation is legally or institutionally authorised.

## AI Governance and Responsible AI

AI governance frameworks address:

- risk management
- transparency
- accountability
- human oversight
- documentation
- testing
- monitoring
- incident management
- impact assessment
- lifecycle governance

Two-Set Policy may complement these frameworks by focusing on how broad governance requirements become operational constraints for software systems and AI agents.

## AI Agents and Agent Governance

Agentic AI systems can plan, use tools, interact with external systems, and take actions.

Emerging work in this area addresses:

- agent permissions
- tool-use controls
- identity
- delegation
- audit
- sandboxing
- runtime constraints
- human approval
- multi-agent coordination
- agent security

Two-Set Policy is interested in the upstream governance question:

> Which operational policy should an agent follow, and who was authorised to define it?

## Robotics and Autonomous Systems Governance

Robotics and autonomous-systems research addresses physical safety, operating boundaries, human control, monitoring, and failure handling.

Relevant domains include:

- industrial robots
- collaborative robots
- service robots
- humanoid robots
- automated driving systems
- surgical robotic systems
- agricultural robotics
- autonomous inspection systems

These fields already contain mature safety standards and engineering controls.

Two-Set Policy does not seek to replace them.

Its hypothesis is that policies governing these systems may require a traceable operational interpretation layer in addition to existing technical controls.

## Administrative Discretion

Public administration and legal scholarship have long examined how broad policy and law are interpreted during implementation.

Relevant concepts include:

- administrative discretion
- street-level bureaucracy
- delegated authority
- implementation gaps
- professional judgement
- procedural fairness
- accountability
- appeals

This literature is important because operationalisation is not only a technical activity. It can redistribute decision-making authority.

## Sociotechnical Systems

Sociotechnical research examines how technologies, institutions, people, rules, incentives, and social contexts interact.

Two-Set Policy is fundamentally a sociotechnical proposition because the operational meaning of policy cannot be understood only through code or schemas.

The framework must consider:

- institutional structures
- power
- incentives
- professional practice
- social context
- affected groups
- governance processes
- technical systems

## Deliberative and Democratic Governance

Some policy terms involve normative choices that cannot be resolved through technical optimisation alone.

Relevant concepts include:

- public deliberation
- representation
- participation
- reason-giving
- contestability
- legitimacy
- dissent
- revision

Two-Set Policy may eventually explore how value-laden operational decisions should be authored and reviewed.

## Provenance and Auditability

Provenance research addresses how data, decisions, models, and transformations can be traced.

Relevant practices include:

- source attribution
- version history
- decision logs
- audit trails
- change records
- evidence chains
- responsibility assignment

Traceability is central to Two-Set Policy, but traceability alone does not establish legitimacy or correctness.

## Current differentiation hypothesis

The current working hypothesis is that many existing approaches focus on one or more of the following:

- representation
- execution
- compliance checking
- system control
- risk management
- documentation
- technical safety

Two-Set Policy focuses on the prior and surrounding interpretive process through which human-readable policy becomes operational authority.

Its proposed contribution is the combined treatment of:

- policy interpretation
- actor and authority assignment
- machine-interpretation vulnerability
- monitoring-system vulnerability
- explicit prohibitions
- non-automatable provisions
- redressal
- unresolved deployment-critical questions
- source traceability
- change control

## Important limitation

This differentiation is provisional.

A comprehensive literature review may identify substantial overlap, prior formulations, or stronger existing methods.

The project should therefore avoid claims such as:

- first framework
- unique global standard
- complete solution
- universal policy model
- proof of novelty

The related-work analysis will be updated as the repository grows.

## Preliminary references

The following public sources provide an initial foundation for the related-work map.

### Rules as Code

- OECD Observatory of Public Sector Innovation. *Cracking the Code: Rulemaking for Humans and Machines*. 2020.
  https://oecd-opsi.org/publications/cracking-the-code/

- OECD. *Cracking the Code*. 2020.
  https://www.oecd.org/en/publications/cracking-the-code_3afe6ba5-en.html

### AI governance and agent systems

- National Institute of Standards and Technology. *Artificial Intelligence Risk Management Framework, AI RMF 1.0*. 2023.
  https://www.nist.gov/itl/ai-risk-management-framework

- National Institute of Standards and Technology. *CAISI Issues Request for Information About Securing AI Agent Systems*. 2026.
  https://www.nist.gov/news-events/news/2026/01/caisi-issues-request-information-about-securing-ai-agent-systems

### Decision modelling

- Object Management Group. *Decision Model and Notation*.
  https://www.omg.org/dmn/

### Robotics and autonomous systems

- International Organization for Standardization. *Robotics Standards*.
  https://www.iso.org/sectors/engineering/robotics

- National Highway Traffic Safety Administration. *Automated Vehicle Safety*.
  https://www.nhtsa.gov/vehicle-safety/automated-vehicles-safety

- U.S. Food and Drug Administration. *Computer-Assisted Surgical Systems*.
  https://www.fda.gov/medical-devices/surgery-devices/computer-assisted-surgical-systems

### Agriculture and field robotics

- EU CAP Network. *Robotics and Artificial Intelligence in Farming and Forestry*. 2025.
  https://eu-cap-network.ec.europa.eu/publications/eu-cap-network-seminar-robotics-and-artificial-intelligence-farming-and-forestry_en

- European Commission. *Digitalising the EU Agricultural Sector*.
  https://digital-strategy.ec.europa.eu/en/policies/digitalisation-agriculture

## Reference-development note

This is an initial reference list rather than a comprehensive systematic literature review.

Future versions will add peer-reviewed and foundational literature on:

- computational law
- requirements engineering
- administrative discretion
- street-level bureaucracy
- sociotechnical systems
- deliberative governance
- provenance
- auditability
- policy implementation
- human-automation interaction

The references will be expanded, classified, and reviewed as the research develops.
