# Governance and Change Management Draft

## Purpose

This document sets out the AI governance plan for the recommended transformation: a Georgian, bank-backed prediction-market platform launched through a regulatory-first pathway.

The recommended strategic option is:

> **Regulatory Sandbox Pathway, with responsible-use controls embedded from day one.**

The preferred route is a GEL-settled, bank-backed platform tested through NBG sandbox / pre-consultation first. A VASP / USDC route remains a fallback or niche crypto-native option, not the default mass-market model.

This governance plan covers:

1. EU AI Act-style risk classification of the recommended AI use cases.
2. A three-tier governance architecture for the most important high-risk use case.
3. Responsible AI principles with named implementation mechanisms.
4. Governance integration with the roadmap.

---

## Source Note

The repository identifies the following AI use cases:

- Loan A/R Collections Optimization
- Real-Time Payment Fraud Detection
- Customer Service Automation
- Wealth Management Robo-Advisory
- Prediction Market Platform
- Open Banking-Powered Personalization
- SME Credit Scoring
- Regulatory Compliance Automation

The repository classifies the prediction-market platform as an **Invest to Enable** opportunity because the legal category, payment-rail access, and market-integrity requirements remain unresolved. The roadmap treats the prediction-market platform as a **Horizon 2 / Horizon 3 bridge**, where regulatory work can begin immediately but full public launch depends on sandbox testing, legal classification, payment-partner approval, and market-integrity controls.

This document uses the EU AI Act as a governance benchmark. It does not claim that EU AI Act rules directly apply to Georgia in the same way they apply inside the EU. For this project, the EU AI Act is used as a best-practice risk framework because the client is operating in a regulated financial industry and the product could affect users’ financial behavior, access, payments, and dispute outcomes.

---

# Part 1. EU AI Act Risk Classification

## Classification approach

The EU AI Act follows a risk-based structure:

- **Unacceptable risk:** banned AI practices.
- **High risk:** AI systems that can materially affect health, safety, fundamental rights, financial access, employment, education, essential services, or democratic processes.
- **Limited risk:** AI systems requiring transparency, such as chatbots or AI-generated content.
- **Minimal risk:** low-impact AI tools with no meaningful adverse decision effect.

For this project, several AI systems are treated conservatively as **High Risk** even when the strict EU legal classification may be debatable. This is because the client is a bank-backed regulated platform and the AI systems may affect user access, trading restrictions, payment flows, financial recommendations, account freezes, or payout timing.

---

## AI use case classification table

| AI use case | Risk tier | Tier rationale | Primary regulatory obligation |
|---|---|---|---|
| Loan A/R Collections Optimization | High | The model predicts default probability, contact timing, and repayment risk. It can influence credit treatment, collection escalation, repayment negotiation, and customer outcomes in an essential financial service. | Conformity-style internal assessment before deployment; human oversight for collection decisions; adverse-action logging; explainability for escalation; audit trail for every AI-driven recommendation. |
| Real-Time Payment Fraud Detection | High | The model may block payments, trigger step-up authentication, freeze transactions, or restrict user access to payment services. Even if designed for fraud prevention, it can create adverse user impact. | Human-review pathway for blocked transactions; clear user notice for payment holds; audit trail for alert, block, override, and release; false-positive monitoring. |
| Customer Service Automation for Digital Banking | Limited | The system interacts directly with users and provides information, routing, and support. It should not make final financial, legal, or account-blocking decisions. | Users must know they are interacting with AI; chatbot must provide human escalation; generated answers must be logged and quality-reviewed. |
| Wealth Management Robo-Advisory MVP | Limited, upgraded to High if automated suitability decisions are added | If the tool only explains portfolios and provides educational summaries, it is limited-risk. If it recommends specific products, portfolio reallocations, or risk classifications used for suitability decisions, it becomes high-risk under internal governance. | AI disclosure; human/advisor review for regulated investment recommendations; suitability explanation; audit trail for recommendation logic and user-facing output. |
| AI-Assisted Event Risk Scoring for Prediction Markets | Limited, upgraded to High for market approval automation | The model scores proposed event contracts and routes them for review. If it only assists humans, risk is limited. If it automatically approves or rejects markets, it becomes high-risk because it affects market access and regulatory exposure. | Human approval required before market listing; event-risk score logged; prohibited-market classifier reviewed; override log maintained. |
| AI Market Surveillance for Prediction Markets | High | The model detects manipulation, suspicious trading, price jumps, concentrated positions, and related-account activity. It may trigger market pauses, account reviews, or trading restrictions. | Human oversight for account freezes and market pauses; surveillance alerts logged; appeal pathway for affected users; model performance monitoring. |
| Responsible-Use Scoring for Prediction Markets | High | The model assesses user risk based on losses, deposit frequency, trading intensity, cooling-off history, and failed risk checks. It may restrict trading access or impose limits. | Clear user notice; human review for restrictions beyond automatic sandbox limits; appeal process; audit trail; bias and disparate-impact monitoring. |
| Outcome Resolution and Payout Automation | High | The system extracts official results and drafts settlement decisions. A wrong resolution affects payouts and user trust. | Human approval before final payout; official-source registry; resolution memo; dispute process; full audit trail for every resolved market. |
| Open Banking-Powered Personalization | High if used for affordability, credit, or product eligibility; Limited if used only for generic insights | The system processes sensitive financial behavior and may shape product offers, affordability warnings, or access to financial features. | Explicit consent; purpose limitation; data minimization; explainable personalization; user opt-out; access logs and data lineage. |
| AI-Powered SME Credit Scoring | High | The model affects access to credit for SMEs and may influence loan pricing, approval, or rejection. | Conformity-style assessment; high-quality training data; explainability; adverse action notice; human credit officer review; appeal process. |
| Regulatory Compliance Automation | Limited, upgraded to High if filings or controls execute automatically | If the tool drafts filings, monitors regulatory changes, or prepares compliance summaries, it is limited-risk. If it automatically submits reports or changes compliance controls, it becomes high-risk internally. | Human sign-off before filing or control changes; version history; source traceability; compliance calendar audit log. |

---

## Highest-risk AI use case selected for detailed governance

The most important high-risk use case is:

> **AI Market Surveillance and Responsible-Use Scoring for the Prediction-Market Platform**

This is selected because it directly affects:

- user trading access,
- possible account restrictions,
- market pauses,
- responsible-use interventions,
- market-integrity investigations,
- payment-partner confidence,
- NBG confidence,
- and the platform’s reputation.

The system should never be allowed to permanently suspend a user, freeze payout, approve final dispute outcome, or approve public market listing without human review during the sandbox phase.

---

# Part 2. Three-Tier Governance Architecture

## High-risk use case governed

**AI Market Surveillance and Responsible-Use Scoring for Prediction Markets**

This system monitors:

- price jumps,
- bid-ask spreads,
- account concentration,
- related-account clusters,
- unusual deposit behavior,
- rapid trading frequency,
- user loss patterns,
- market-maker behavior,
- possible manipulation,
- and user harm indicators.

The system produces risk scores and alerts. It does not make final adverse decisions without human review.

---

## Tier 1: Model Governance

| Element | Your entry |
|---|---|
| Named oversight body | **Market Governance and AI Risk Committee** |
| Review cadence | Monthly during H1 build; bi-weekly during H2 sandbox; emergency review within 24 hours after any severe incident |
| What is reviewed | Model purpose, training data, feature list, performance metrics, false positives, false negatives, drift, override history, bias indicators, incident reports, user complaints, and regulatory feedback |
| Who can approve deployment | Market Governance and AI Risk Committee, with sign-off from Head of Data & AI, Compliance Lead, Responsible Use Lead, and Prediction Market General Manager |
| Who can trigger rollback | Compliance Lead, Chief Risk Officer delegate, Head of Data & AI, Responsible Use Lead, or Market Integrity Lead |
| Performance monitoring mechanism | **AI Model Performance Dashboard** tracking precision/recall, alert volumes, false-positive rate, missed-risk incidents, override rate, drift, subgroup impact, and SLA compliance |

### Model governance rules

1. No model moves from test to sandbox without committee approval.
2. No model output can automatically impose permanent user restriction.
3. No model output can automatically approve final market resolution.
4. No model output can automatically approve a new market listing.
5. Every model version must be registered in the **AI Model Registry**.
6. Every override must be recorded in the **Human Override Log**.
7. Every severe incident must trigger a post-incident model review.

### Minimum deployment conditions

Before sandbox deployment, the model must have:

- documented purpose,
- approved feature list,
- training and validation dataset description,
- known limitations,
- escalation thresholds,
- rollback protocol,
- test results,
- named human owner,
- and approved monitoring dashboard.

---

## Tier 2: Data Governance

| Element | Your entry |
|---|---|
| Named data owner | **Head of Data, AI & Market Integrity** |
| Quality threshold for training data | 95% completeness for required fields; 98% timestamp accuracy for trading events; 100% official-source mapping for market resolution data; missing critical fields must block model training |
| Consent requirement | Explicit user consent for use of personal financial behavior in personalization or responsible-use scoring; separate notice for trading surveillance and fraud monitoring as platform safety controls |
| Access audit mechanism | Role-based access control, monthly access review, privileged-access log, and automated alerts for unauthorized data export |
| Data lineage documentation | **Event Source Registry**, **Feature Store Lineage Log**, **Model Training Dataset Register**, and **Resolution Evidence Archive** |

### Data governed by this tier

| Dataset | Owner | Purpose | Key control |
|---|---|---|---|
| User KYC dataset | Payments, KYC & Settlement | Identity, AML, account verification | Access limited to KYC/AML and compliance users |
| Wallet and payment ledger | Payments, KYC & Settlement | Deposits, withdrawals, settlement | Immutable transaction logs |
| Order-book and trade dataset | Market Operations & Liquidity | Trading surveillance, liquidity monitoring | Timestamp accuracy and tamper-resistant audit trail |
| Event-source registry | Data, AI & Market Integrity | Official event resolution | Only approved official sources used |
| Responsible-use dataset | Responsible Use & Customer Trust | Loss limits, deposit alerts, cooling-off triggers | Purpose limitation and human review |
| Market-maker performance dataset | Market Operations & Liquidity | Spread, depth, quote obligations | Daily liquidity-quality review |
| Complaint and dispute dataset | Customer Trust + Resolution Committee | Complaint handling and resolution quality | Case-level audit trail |
| AI model registry | Data, AI & Market Integrity | Model governance | Version control and approval history |

### Data governance thresholds

| Condition | Required action |
|---|---|
| Source-confidence score below 95% | Market cannot be listed until source is approved |
| AI extraction confidence below 98% for official result | Human verification required before payout |
| Missing KYC or duplicate account signal | Account blocked from sandbox trading until reviewed |
| Incomplete timestamp, trade ID, or user ID in order-book data | Data excluded from model training and flagged for engineering fix |
| Unauthorized access to user-risk dataset | Immediate security review and access suspension |
| More than 5% missing values in required surveillance features | Model retraining blocked until data issue resolved |

---

## Tier 3: Decision Governance

| Element | Your entry |
|---|---|
| Named accountable owner for adverse AI decisions | **Responsible Use Lead** for user restrictions; **Market Integrity Lead** for surveillance actions; **Resolution Committee Chair** for payout or dispute decisions |
| Human override protocol | AI produces alert or recommendation; human reviewer must approve, reject, or modify action; override reason must be logged; repeated overrides trigger model review |
| Explainability mechanism | User-facing reason codes, internal feature-contribution summary, market-event timeline, and official-source evidence pack |
| Appeal process for affected individuals | User may appeal account restriction, market settlement, or payout decision through Customer Trust team; appeal reviewed by Resolution Committee or Responsible Use Lead within defined SLA |
| Adverse action notice requirement | Users must receive notice when AI-supported review leads to trading restriction, deposit limit, cooling-off period, account freeze, or delayed payout |

### Human override protocol

The platform must use a **human-in-the-loop** model for all adverse decisions.

```text
AI alert
→ human review queue
→ reviewer decision
→ logged rationale
→ user notice if adverse
→ appeal path if user affected
→ model monitoring update
