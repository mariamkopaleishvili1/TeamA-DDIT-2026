# Framework: Responsible AI and Governance

## Sources
EU AI Act (2024)
OECD AI Principles
Westerman, Bonnet, and McAfee, *Leading Digital*

---

## Why AI governance differs from IT governance

IT governance manages systems. AI governance manages decisions.

| Dimension | IT governance | AI governance |
|---|---|---|
| What is governed | Access to systems, data, and infrastructure | Decisions that affect individuals |
| Failure mode | Bounded, auditable error | Millions of flawed decisions before detection |
| Accountability | Assigned to system owner | Contested: developer, deployer, or board? |
| Explainability | Not required | Required by regulation for high-stakes decisions |
| Liability | Product liability | Individual rights, discrimination law, sector regulation |

---

## EU AI Act: four risk tiers

| Tier | Examples | Obligations |
|---|---|---|
| Unacceptable risk | Social scoring by governments, real-time biometric surveillance in public spaces | Prohibited. No deployment permitted. |
| High risk | AI in credit decisions, AI in hiring, AI in critical infrastructure, AI in educational assessment | Mandatory conformity assessment, transparency obligations, human oversight required, audit trail compulsory. |
| Limited risk | Chatbots, AI-generated content, emotion recognition outside high-risk contexts | Transparency obligations only. Users must be informed they are interacting with AI. |
| Minimal risk | AI route optimisation, spam filters, content recommendation engines | No specific obligations under the Act. Standard product liability applies. |

Georgian context: Georgian regulation follows EU trajectory. High-risk AI use cases in banking (AI credit decisions) require human oversight and explainability documentation before deployment.

---

## Three-tier AI governance architecture

### Tier 1: Model governance

Controls how AI models are built, tested, validated, and retired.

Required elements:
- Model versioning and registry.
- Performance monitoring for accuracy, fairness, and drift.
- Review cadence before and after deployment.
- Rollback protocol when performance degrades.
- Named owner: typically a data science lead or model risk officer.

In regulated industries: independent model validation team required before production deployment.

### Tier 2: Data governance

Controls which data enters AI training and inference pipelines.

Required elements:
- Named data owner for every dataset.
- Quality thresholds that must be met before training.
- Consent requirements for personal data.
- Lineage tracking: every model must be traceable to its training data.
- Access audit trail.

### Tier 3: Decision governance

Controls how AI decisions are made, communicated to affected individuals, and challenged.

Required elements:
- Human override protocol: who can override an AI decision, under what conditions, with what documentation.
- Explainability mechanism: how can an affected individual receive a plain-language explanation of an automated decision affecting them?
- Appeal process.
- Adverse action notice for denied applications.
- Named accountable owner: when an AI denies credit to a qualified applicant, who is accountable?

---

## Six Responsible AI principles

Each principle requires a named implementation mechanism. A principle without a mechanism is a statement of intent, not a governance plan.

### Fairness

What it requires: AI decisions must not systematically disadvantage protected groups based on race, gender, age, or socioeconomic status.

Implementation mechanisms:
- Bias testing before deployment: measure accuracy disaggregated by demographic group.
- Ongoing fairness audit: quarterly review of decision outcomes by demographic segment.
- Alert threshold: if disparity exceeds a defined percentage, escalate to the model review board.

### Transparency

What it requires: affected individuals must know when a decision affecting them is made by AI and must be able to receive a plain-language explanation.

Implementation mechanisms:
- Adverse action notice for every AI-denied application, including the three primary factors used in the decision.
- Explanation system that logs the top contributing factors for each decision.
- Public disclosure that AI is used in the decision process.

### Accountability

What it requires: a named human is accountable for every category of AI decision. There is no accountability gap.

Implementation mechanisms:
- Decision accountability matrix: every AI use case mapped to a named accountable owner by function.
- Board-level model risk committee for high-stakes AI.
- Clear escalation path when the model produces an unexpected outcome.

### Reliability

What it requires: AI systems must perform consistently and predictably over time. Model drift must be detected and addressed before it affects customer outcomes.

Implementation mechanisms:
- Continuous performance monitoring against defined accuracy and fairness thresholds.
- Automatic alert system when performance drops below threshold.
- Scheduled retraining protocol.
- Rollback capability to a prior validated version.

### Privacy

What it requires: personal data used in AI training and inference must be handled in compliance with GDPR and Georgian data protection law.

Implementation mechanisms:
- Data minimisation: collect only what is needed for the specific use case.
- Consent audit trail: document consent for every personal data use in AI.
- Right to erasure protocol: mechanism to remove an individual's data from training sets when requested.

### Inclusion

What it requires: AI systems must not exclude or disadvantage users based on limited digital access, language, or disability.

Implementation mechanisms:
- Accessibility audit before deployment.
- Human fallback channel for users who cannot or choose not to interact with AI.
- Multi-language support where the customer population requires it.

---

## Application to Weekend 3

In your governance plan section:
- Classify each of your recommended AI use cases by EU AI Act risk tier.
- Design the three-tier governance architecture for your most important high-risk use case.
- Name a specific implementation mechanism for each of the six principles. Do not list principles without mechanisms.
- Connect every governance element to a named roadmap initiative in H1.
