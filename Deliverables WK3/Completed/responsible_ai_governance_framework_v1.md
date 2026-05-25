# Responsible AI and Governance Framework v1

## Project

Team A — Georgian Prediction-Market Platform  
Industry: Fintech  
Market: Republic of Georgia  
Recommended strategic option: Regulatory Sandbox Pathway with responsible-use controls embedded from day one

---

## Purpose

This document defines the Responsible AI and governance framework for the proposed Georgian prediction-market platform.

It is a separate supporting file for the final report. It can be referenced from the governance and implementation sections, but it should not replace the main `governance_cm_draft.md`.

The framework is based on:

- EU AI Act risk-tier logic,
- OECD Responsible AI principles,
- Westerman, Bonnet, and McAfee’s digital transformation governance logic,
- and the project’s recommended strategy: a bank-backed, GEL-settled, sandbox-first prediction-market platform.

The core idea is:

> AI governance is not only about controlling technology. It is about controlling decisions that affect users, markets, regulators, and the bank’s reputation.

---

# 1. Why AI Governance Is Different from IT Governance

Traditional IT governance manages systems. AI governance manages decisions.

For a prediction-market platform, this distinction matters because AI systems may influence:

- whether a market is listed,
- whether a user is restricted,
- whether a trade is flagged,
- whether a market is paused,
- whether a payout is delayed,
- whether a user receives a warning,
- whether a regulator receives an incident report.

These are not ordinary system-management decisions. They affect user rights, financial behavior, market trust, and regulatory exposure.

| Dimension | IT governance | AI governance | Relevance to this project |
|---|---|---|---|
| What is governed | Access to systems, data, and infrastructure | Decisions that affect individuals and markets | AI may affect user access, market status, and payout timing |
| Main failure mode | Bounded technical error | Scaled decision error before detection | A flawed model could wrongly flag many users or markets |
| Accountability | Usually assigned to system owner | Often contested between developer, deployer, product owner, and board | The bank must name accountable human owners |
| Explainability | Usually not required | Required for high-stakes decisions | Users need reason codes for restrictions or delayed payouts |
| Liability | Product or operational liability | Individual rights, discrimination, financial regulation, consumer protection | Errors could create legal, reputational, and regulatory risk |

---

# 2. EU AI Act Risk-Tier Logic

The EU AI Act uses a risk-based approach. This framework applies that logic as a benchmark for the Georgian prediction-market platform.

This does not mean EU AI Act rules automatically apply in Georgia exactly as they apply in the EU. However, Georgia’s financial regulation and banking sector are increasingly influenced by EU-style regulatory expectations, so this is a useful best-practice benchmark.

| Tier | Examples | Obligations | Project interpretation |
|---|---|---|---|
| Unacceptable risk | Social scoring, real-time biometric surveillance in public spaces | Prohibited; no deployment permitted | The platform should prohibit any AI that ranks users by social worth or uses biometric surveillance |
| High risk | AI credit decisions, hiring AI, critical infrastructure AI, education assessment AI | Conformity-style assessment, transparency, human oversight, audit trail | Any AI that restricts trading, freezes accounts, delays payouts, affects credit, or influences high-impact decisions should be treated as high risk |
| Limited risk | Chatbots, AI-generated content, automated explanations | Users must be informed they are interacting with AI | Chatbot support and AI-generated market explanations require AI disclosure |
| Minimal risk | Route optimization, spam filters, content recommendations | No specific AI Act obligations beyond standard product controls | Low-impact internal workflow optimization may be minimal risk |

---

# 3. Recommended AI Use Cases and Risk Classification

## 3.1 Risk-classification table

| AI use case | Risk tier | Rationale | Required governance mechanism |
|---|---|---|---|
| AI-assisted event risk scoring | Limited, upgraded to High if it approves or rejects markets automatically | If used only to support human review, risk is limited. If it approves listings, it directly affects market availability and regulatory exposure. | Market Governance Committee approval before listing; event-risk score logged; human override log |
| AI market surveillance | High | May trigger trading reviews, account restrictions, market pauses, or manipulation investigations. | Human-in-the-loop market integrity review; surveillance alert log; model performance dashboard |
| Responsible-use scoring | High | May lead to deposit limits, cooling-off periods, trading restrictions, or account review. | Adverse action notice, user appeal process, responsible-use intervention log |
| Outcome-resolution support | High | Wrong extraction or interpretation of official results could affect payouts. | Resolution Committee sign-off; official-source registry; resolution memo for every settled market |
| Payment fraud detection | High | May block deposits, withdrawals, or user access to funds. | Fraud review queue; payment hold notice; false-positive monitoring |
| KYC / AML risk scoring | High | May affect onboarding, continued access, or account restrictions. | Compliance review, audit trail, appeal route where applicable |
| Customer service chatbot | Limited | Users interact with AI, but it should not make final financial or legal decisions. | AI disclosure, escalation to human support, answer-quality review |
| AI-generated market explanations | Limited | Helps explain contracts, probabilities, and risk warnings. It should not recommend trades. | AI-generated content label; compliance-approved templates; human review for new market categories |
| Regulatory and payment-partner reporting automation | Limited, upgraded to High if it submits filings or changes controls automatically | Drafting reports is lower risk; automatic filing or control execution is higher risk. | Compliance sign-off before filing; version history; source traceability |

---

## 3.2 Highest-risk use case

The most important high-risk AI use case for this project is:

> **AI Market Surveillance and Responsible-Use Scoring**

This is the priority because it can affect:

- user trading access,
- market pauses,
- deposit limits,
- account reviews,
- responsible-use interventions,
- payment-partner confidence,
- NBG confidence,
- and public trust.

This system must never make final adverse decisions without human review during the sandbox phase.

---

# 4. Three-Tier AI Governance Architecture

The project should use a three-tier governance model:

1. Model governance
2. Data governance
3. Decision governance

---

## 4.1 Tier 1: Model Governance

Model governance controls how AI models are built, tested, validated, deployed, monitored, and retired.

| Element | Project design |
|---|---|
| Named oversight body | Market Governance and AI Risk Committee |
| Named model owner | Head of Data, AI & Market Integrity |
| Review cadence | Monthly during H1 build; bi-weekly during H2 sandbox; emergency review within 24 hours after severe incident |
| What is reviewed | Model purpose, risk tier, training data, feature list, accuracy, fairness, drift, false positives, false negatives, override rate, incident history |
| Who approves deployment | Market Governance and AI Risk Committee, with sign-off from Compliance Lead, Head of Data & AI, Responsible Use Lead, and Prediction Market General Manager |
| Who can trigger rollback | Compliance Lead, Chief Risk Officer delegate, Head of Data & AI, Responsible Use Lead, or Market Integrity Lead |
| Performance monitoring mechanism | AI Model Performance Dashboard |
| Required artifact | AI Model Registry entry for every model |

### Model governance mechanisms

| Mechanism | Purpose |
|---|---|
| AI Model Registry | Records every AI model, version, owner, risk tier, approval status, and deployment date |
| Model Validation Checklist | Confirms testing, limitations, thresholds, and rollback protocol before deployment |
| Drift Monitoring Dashboard | Tracks whether model performance changes over time |
| Human Override Log | Records when humans reject, modify, or approve AI recommendations |
| Rollback Protocol | Defines when the model must be disabled or reverted to a prior validated version |
| Post-Incident Review | Reviews severe model failures and updates controls |

### Model rollback triggers

Rollback is required if:

- a Level 4 incident occurs,
- false-positive rate doubles for two consecutive review periods,
- model drift exceeds approved threshold,
- more than 5% of high-impact AI alerts are overturned by human reviewers,
- regulator or payment partner raises a formal concern,
- the model uses unauthorized data,
- audit trail is incomplete for high-risk decisions.

---

## 4.2 Tier 2: Data Governance

Data governance controls which data enters AI training and inference pipelines.

| Element | Project design |
|---|---|
| Named data owner | Head of Data, AI & Market Integrity |
| Quality threshold for training data | 95% completeness for required fields; 98% timestamp accuracy for trading events; 100% official-source mapping for market-resolution data |
| Consent requirement | Explicit consent for personal financial behavior used beyond platform safety, compliance, or responsible-use scoring purposes |
| Access audit mechanism | Role-based access control, monthly access review, privileged-access logs, and unauthorized export alerts |
| Data lineage documentation | Event Source Registry, Feature Store Lineage Log, Model Training Dataset Register, Resolution Evidence Archive |

### Core datasets

| Dataset | Owner function | Use | Key control |
|---|---|---|---|
| KYC dataset | Payments, KYC & Settlement | Identity verification and AML | Restricted access and audit trail |
| Wallet and payment ledger | Payments, KYC & Settlement | Deposits, withdrawals, settlement | Immutable transaction log |
| Order-book and trade dataset | Market Operations & Liquidity | Surveillance, liquidity monitoring, market quality | Timestamp accuracy and tamper-resistant logs |
| Event-source registry | Data, AI & Market Integrity | Official outcome resolution | Approved sources only |
| Responsible-use dataset | Responsible Use & Customer Trust | Loss limits, deposit alerts, cooling-off triggers | Purpose limitation and human review |
| Market-maker performance dataset | Market Operations & Liquidity | Spread, depth, quote obligations | Daily market-quality review |
| Complaint and dispute dataset | Customer Trust + Resolution Committee | User disputes and complaint handling | Case-level audit trail |
| Model registry | Data, AI & Market Integrity | Model governance and approvals | Version control |

### Data-quality thresholds

| Condition | Required action |
|---|---|
| Official source-confidence score below 95% | Market cannot be listed |
| AI extraction confidence below 98% for official result | Human verification required |
| More than 5% missing values in required surveillance features | Model retraining blocked |
| Missing KYC or duplicate account signal | Account blocked from sandbox trading pending review |
| Unauthorized access to user-risk dataset | Immediate security review |
| Incomplete timestamp, trade ID, or user ID in order-book data | Exclude from training and flag engineering fix |

---

## 4.3 Tier 3: Decision Governance

Decision governance controls how AI-supported decisions are made, communicated, challenged, and corrected.

| Element | Project design |
|---|---|
| Named accountable owner for user restrictions | Responsible Use Lead |
| Named accountable owner for market surveillance actions | Market Integrity Lead |
| Named accountable owner for payout or dispute decisions | Resolution Committee Chair |
| Human override protocol | AI alert enters human review queue; reviewer approves, rejects, or modifies action; rationale is logged |
| Explainability mechanism | User-facing reason codes, internal feature-contribution summary, market-event timeline, official-source evidence pack |
| Appeal process | Users can appeal restrictions, payment holds, account freezes, payout delays, or settlement disputes |
| Adverse action notice requirement | Required for trading restrictions, deposit limits, cooling-off periods, account freezes, and delayed payouts |

### Human override workflow

```text
AI alert
→ human review queue
→ reviewer decision
→ rationale logged
→ user notice if adverse
→ appeal path opened if affected
→ model monitoring dashboard updated
```

### Specific decision rules

| AI-triggered condition | Automatic action allowed? | Human approval required? | Owner |
|---|---:|---:|---|
| User reaches GEL 100 sandbox daily loss limit | Yes, same-day stop | No, if pre-disclosed | Responsible Use System |
| User deposits more than GEL 500 in 24 hours | No | Yes, for restriction beyond warning | Responsible Use Lead |
| User makes more than 20 trades in one hour | Yes, friction warning | Yes, for trading restriction | Responsible Use Lead |
| User hits loss limit 3 times in 7 days | Yes, 48-hour cooling-off | Human review after cooling-off starts | Responsible Use Lead |
| One account cluster holds more than 25% of one side of market | No | Yes | Market Integrity Lead |
| Price moves more than 20 percentage points in 15 minutes without public news | Temporary 30-minute pause allowed | Yes, for extended pause | Market Integrity Lead |
| AI flags multi-accounting | Temporary withdrawal hold allowed | Yes, for account suspension | Fraud / KYC Lead |
| AI extracts official market result | No final payout | Yes | Resolution Committee |
| More than 10 disputes filed on one market | No automated final decision | Yes | Resolution Committee |

---

# 5. Responsible AI Principles and Mechanisms

A Responsible AI principle without a named mechanism is only a statement of intent. This project needs named controls, owners, and evidence.

| Principle | What it requires in this context | Named implementation mechanism | Owner |
|---|---|---|---|
| Fairness | AI systems must not unfairly restrict users based on age proxy, location, language, device type, income proxy, or banking relationship. | Fairness and Disparate Impact Dashboard | Market Governance and AI Risk Committee |
| Transparency | Users must know when AI is used in chatbot support, market explanations, risk warnings, restrictions, or payment/security reviews. | AI Disclosure Banner and Adverse Action Notice System | Product + Compliance |
| Accountability | Every AI-supported decision must have a named human owner. | AI Decision Register and Human Override Log | Data, AI & Market Integrity |
| Reliability | Models must perform consistently and must not drift silently. | Model Performance and Drift Dashboard with rollback triggers | Head of Data & AI |
| Privacy | User financial, trading, KYC, and responsible-use data must be processed only for approved purposes. | Role-Based Access Control, Consent Register, and Data Lineage Log | Payments/KYC + Data Governance |
| Inclusion | Georgian retail users must understand the product regardless of financial literacy level. | Plain-Language Georgian UX Review and Risk-Literacy Testing | Product + Responsible Use |
| Human oversight | Humans must review high-impact AI outputs before final adverse action. | Human-in-the-Loop Review Queue | Relevant accountable owner |
| Contestability | Users must be able to challenge AI-supported restrictions or settlement decisions. | User Appeal and Dispute Workflow | Customer Trust + Resolution Committee |
| Market integrity | AI must detect manipulation without creating unchecked automated enforcement. | Market Integrity Alert System | Market Integrity Lead |
| Regulatory readiness | The platform must prove decisions are traceable and controlled. | Regulator-Ready Audit Pack | Regulatory & Platform Governance |

---

# 6. Adverse Action Notice System

## Purpose

The adverse action notice system ensures users receive a plain-language explanation when AI-supported review leads to a restriction or delayed outcome.

## When notice is required

A notice is required when AI-supported review contributes to:

- trading restriction,
- deposit limit,
- cooling-off period,
- account freeze,
- payment hold,
- payout delay,
- rejected onboarding,
- market dispute decision.

## Notice contents

Each notice should include:

1. action taken,
2. whether AI-supported review was used,
3. main reason code,
4. data category considered,
5. duration of restriction,
6. appeal channel,
7. expected review timeline,
8. human owner responsible for review.

## Example notice language

```text
Your trading access has been temporarily limited because your account reached the sandbox daily loss limit. This limit is part of the platform’s responsible-use controls. AI-supported monitoring detected the threshold, but the rule was pre-disclosed and applies automatically to all sandbox users. You may continue to view markets, but trading will reopen after the daily cooling period. If you believe this action was applied incorrectly, you may request a review through Customer Support.
```

---

# 7. Stakeholder Resistance

## Role most likely to resist

The role most likely to resist the recommended transformation is:

> **Compliance Lead / MLRO assigned to the prediction-market pilot**

## Specific source of resistance

The Compliance Lead is likely to resist because the prediction-market platform increases personal and professional downside risk without automatically increasing upside.

In the current bank operating model, the Compliance Lead’s status comes from:

- preventing regulatory breaches,
- avoiding audit findings,
- reducing reputational incidents,
- stopping products with unclear legal classification,
- protecting the bank from NBG concern or payment-partner rejection.

A prediction-market platform is legally and reputationally uncomfortable because it sits between:

- financial markets,
- gambling-like speculation,
- virtual assets,
- payment services,
- consumer protection,
- and responsible-use regulation.

The specific threat is:

> The Compliance Lead may become accountable for a legally ambiguous product where the upside belongs to product and innovation teams, but the downside of NBG concern, gambling classification, user harm, payment-partner rejection, or media criticism falls heavily on compliance.

This creates a rational incentive to slow down or block the project.

## Resistance pattern

| Source of resistance | How it appears |
|---|---|
| Personal accountability risk | Compliance may hesitate to sign off before NBG classification is clear |
| Reputational risk | The product may be perceived as gambling under bank branding |
| Regulatory uncertainty | Sandbox, VASP, financial-market, and gambling classifications are not interchangeable |
| Workload increase | Compliance must review event categories, KYC/AML, responsible-use rules, disputes, and reporting |
| Weak upside participation | Compliance is rewarded for avoiding incidents, not for enabling controlled innovation |

## Change-management response

The project should not ask compliance to “be less conservative.” It should change the operating model so compliance has formal authority, better evidence, and a positive incentive for controlled experimentation.

Required mechanisms:

- permanent compliance seat on the Market Governance and AI Risk Committee,
- no public launch before NBG pre-consultation,
- written regulatory decision log,
- adverse action notice system before sandbox,
- compliance sign-off at board gates,
- compliance metric tied to approval-pack quality, not only incident avoidance.

---

# 8. Incentive Change

## Resistant role

**Compliance Lead / MLRO assigned to the prediction-market pilot**

| | Old metric | New metric |
|---|---|---|
| Metric | Zero regulatory breaches and minimum number of compliance exceptions | Controlled Market Approval Quality Rate |
| Measurement frequency | Quarterly or annual compliance review | Monthly during sandbox; reviewed at each board gate |
| Who measures | Chief Compliance Officer / Risk Committee | Market Governance and AI Risk Committee, with Chief Compliance Officer sign-off |
| Link to compensation | Bonus tied mainly to avoiding incidents, audit findings, and regulatory breaches | Bonus partly tied to safe innovation enablement: complete review packs, SLA-based approvals, timely NBG reporting, and zero unresolved high-risk exceptions |

## New metric definition

```text
Controlled Market Approval Quality Rate =
Number of listed sandbox markets with complete approval pack, source registry match, responsible-use controls, and audit trail
÷
Total listed sandbox markets
```

## Target

```text
95%+ during H2 sandbox
```

## What counts as a complete approval pack

A market approval pack is complete only if it includes:

- event category,
- legal / compliance review note,
- official data source,
- backup source if needed,
- source-confidence score,
- event-risk score,
- contract wording,
- payout rule,
- responsible-use warning,
- market exposure cap,
- liquidity plan,
- human approval record,
- dispute pathway,
- NBG / payment-partner reporting status if applicable.

## Why this aligns incentives

The old metric encourages compliance to block uncertain innovation.

The new metric encourages compliance to make uncertainty manageable through evidence, controls, escalation, and auditability.

It still protects the bank, but it allows the prediction-market pilot to proceed under controlled conditions.

---

# 9. Governance Roadmap Integration

| Governance element | Roadmap initiative | Horizon | Why it must precede AI deployment |
|---|---|---|---|
| Market Governance and AI Risk Committee | Initiative 06: Market Governance and AI Risk Function | H1 | AI systems need deployment approval, rollback authority, and accountable owners before sandbox |
| Data governance framework | Initiative 07: Data Governance and Official Event-Source Registry | H1 | AI scoring and resolution require clean official sources, lineage, and audit logs |
| Adverse action notice system | Initiative 09: Responsible-Use and Customer Protection Framework | H1 | Users must be informed when AI-supported review leads to restrictions |
| Human override protocol | Initiative 06: Market Governance and AI Risk Function | H1 | AI cannot autonomously approve listings, freeze accounts, or resolve payouts |
| AI event-risk prototype | Initiative 12: AI-Assisted Event Risk Scoring Prototype | H1 | Market approval AI must remain decision-support only before sandbox |
| Bias monitoring dashboard | Initiative 16: AI Market Surveillance and Responsible-Use Scoring | H2 | Live user data is needed to measure subgroup impact |
| Regular audit process | Initiative 17: Outcome Resolution and Regulator Reporting Automation | H2 | Regulators and payment partners need recurring evidence that AI decisions are traceable |
| Public launch governance gate | Initiative 19: Unit Economics and Public Launch Gate | H2 | Board should approve launch only after AI governance, liquidity, responsible-use, and economics are validated |

---

# 10. AI Incident Management

## Severity levels

| Severity | Definition | Example | Response |
|---|---|---|---|
| Level 1: Low | AI output is wrong but no user harm occurs | Chatbot gives incomplete FAQ answer | Correct content and log issue |
| Level 2: Medium | AI creates operational rework or user confusion | Event-risk model misclassifies market category | Human review, correction, committee note |
| Level 3: High | AI-supported action affects user access, payout, or market operation | False fraud alert causes payment hold | Human review within SLA, user notice, incident report |
| Level 4: Critical | AI failure creates regulatory, financial, or reputational harm | Incorrect outcome resolution triggers wrong payout | Immediate rollback, freeze affected workflow, board and regulator notification if required |

## Incident response workflow

```text
Incident detected
→ severity classification
→ workflow paused if Level 3 or Level 4
→ human review
→ user notification if affected
→ correction or rollback
→ root-cause analysis
→ model / data update
→ governance committee review
```

---

# 11. Governance KPIs

| Governance area | KPI | Target |
|---|---|---:|
| Model governance | AI models registered | 100% |
| Model governance | High-risk models reviewed on schedule | 100% |
| Human oversight | High-risk AI alerts reviewed within SLA | 95%+ |
| Transparency | AI-supported adverse decisions with user notice | 100% |
| Data governance | Critical datasets with named owner | 100% |
| Data governance | Market contracts with approved official source | 100% |
| Reliability | Severe model incidents unresolved beyond SLA | 0 |
| Privacy | Unauthorized access incidents | 0 |
| Accountability | Human overrides with documented reason | 100% |
| Responsible use | High-risk user interventions logged | 100% |
| Market integrity | Abnormal price moves reviewed within SLA | 100% |
| Dispute handling | Market disputes resolved within SLA | 90%+ |
| Regulatory readiness | Monthly governance report delivered on time | 100% |

---

# 12. Quality Check

- **The governance mechanism is specific enough to assign a budget line and an owner.**  
  Yes. The main mechanism is the Market Governance and AI Risk Committee, supported by the AI Model Registry, Human Override Log, Adverse Action Notice System, Model Performance Dashboard, and Regulator-Ready Audit Pack.

- **The stakeholder resistance names a role, not a department.**  
  Yes. The role is Compliance Lead / MLRO assigned to the prediction-market pilot.

- **The metric change names the old metric and the new metric.**  
  Yes. The old metric is zero regulatory breaches / minimum exceptions. The new metric is Controlled Market Approval Quality Rate.

- **Every item connects to a named H1 or H2 initiative on the roadmap.**  
  Yes. The main roadmap links are Initiatives 06, 07, 09, 12, 16, 17, and 19.

- **Every Responsible AI principle has a named mechanism.**  
  Yes.

- **High-risk AI use cases have explicit human override protocols.**  
  Yes.

---

# 13. References

European Union. (2024). *Artificial Intelligence Act*.

Organisation for Economic Co-operation and Development. (2019). *OECD principles on artificial intelligence*.

Westerman, G., Bonnet, D., & McAfee, A. (2014). *Leading digital: Turning technology into business transformation*. Harvard Business Review Press.

National Bank of Georgia. (2025). *Financial Innovation Office*. https://www.nbg.gov.ge/en/pages/financial-innovation-office

National Bank of Georgia. (2025). *Financial Literacy Survey 2024*. https://www.nbg.gov.ge/uploads/pressreleases/2025/Financial_Literacy_Survey_2024.pdf

Georgian Foundation for Strategic and International Studies. (2024). *Georgia’s cryptocurrency regulation landscape*. https://www.gfsis.org.ge/publications/georgia-s-cryptocurrency-regulation-landscape

TBC Bank. (2024). *TBC Capital individual brokerage services*. https://www.tbcbank.ge/en/corporate/tbc-capital/tbc-capital-individuals
