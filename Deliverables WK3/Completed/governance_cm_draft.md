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
- **Limited / transparency risk:** AI systems requiring transparency, such as chatbots or AI-generated content.
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
| More than 5% missing values in required surveillance features | Model retraining blocked until data issue is resolved |

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
```

### Specific adverse decision rules

| AI-triggered condition | Automatic action allowed? | Human approval required? | Owner |
|---|---:|---:|---|
| User reaches GEL 100 sandbox daily loss limit | Yes, temporary same-day stop | No, if rule is pre-disclosed | Responsible Use System |
| User deposits more than GEL 500 in 24 hours | No | Yes, for further restriction | Responsible Use Lead |
| User makes more than 20 trades in one hour | Yes, friction warning | Yes, for trading restriction | Responsible Use Lead |
| User hits loss limit 3 times in 7 days | Yes, 48-hour cooling-off if pre-disclosed | Human review after cooling-off starts | Responsible Use Lead |
| One account cluster holds more than 25% of one side of market | No | Yes | Market Integrity Lead |
| Price moves more than 20 percentage points in 15 minutes without public news | Temporary market pause allowed for 30 minutes | Yes, for extended pause | Market Integrity Lead |
| AI flags multi-accounting | Temporary withdrawal hold allowed | Yes, for account suspension | Fraud / KYC Lead |
| AI extracts official outcome result | No final payout without human confirmation | Yes | Resolution Committee |
| More than 10 disputes filed on one market | No automated final decision | Yes | Resolution Committee |

### User appeal process

Affected users must have access to an appeal process when AI-supported decisions affect them.

| Decision type | Appeal owner | SLA |
|---|---|---:|
| Deposit restriction | Responsible Use Lead | 2 business days |
| Trading restriction | Responsible Use Lead + Compliance | 3 business days |
| Account freeze | Fraud / KYC Lead + Compliance | 3 business days |
| Market payout dispute | Resolution Committee | 5 business days |
| Permanent user restriction | Responsible Use Lead + Compliance + General Manager | 5 business days |

### Adverse action notice template

Every adverse user-facing AI-supported decision should include:

- what action was taken,
- whether AI was used in the review,
- the main reason code,
- what data category was considered,
- how long the restriction lasts,
- how the user can appeal,
- and when the case will be reviewed.

---

# Part 3. Responsible AI Principles with Implementation Mechanisms

| Principle | What it requires in this context | Named implementation mechanism |
|---|---|---|
| Fairness | AI systems must not unfairly restrict users based on age proxy, location, language, device type, income proxy, or banking relationship. Responsible-use and fraud models must be checked for disproportionate impact. | **Fairness and Disparate Impact Dashboard** reviewed monthly by Market Governance and AI Risk Committee |
| Transparency | Users must know when AI is used in chatbot support, market explanations, risk warnings, responsible-use restrictions, or payment/security reviews. | **AI Disclosure Banner and Adverse Action Notice System** embedded in app and support workflows |
| Accountability | Every AI-supported decision must have a named human owner. No model can approve final adverse action without accountable human review during sandbox. | **AI Decision Register and Human Override Log** owned by Data, AI & Market Integrity |
| Reliability | Models must perform consistently under live-market conditions and must not drift silently. Market surveillance and responsible-use models need threshold monitoring and rollback rules. | **Model Performance and Drift Dashboard** with rollback trigger owned by Head of Data & AI |
| Privacy | User financial, trading, KYC, and responsible-use data must be processed only for approved purposes, with access limits and audit logs. | **Role-Based Access Control, Consent Register, and Data Lineage Log** owned by Payments/KYC and Data Governance |
| Inclusion | The platform must be understandable for Georgian retail users and should not rely on complex financial language that excludes entry-level users. | **Plain-Language Georgian UX Review and Risk-Literacy Testing** before sandbox launch |
| Human oversight | Humans must be able to review, override, pause, or roll back AI outputs affecting users, markets, or payouts. | **Human-in-the-Loop Review Queue** for surveillance, responsible-use, and resolution decisions |
| Contestability | Users must have a way to challenge AI-supported restrictions, settlement decisions, or payout delays. | **User Appeal and Dispute Workflow** owned by Customer Trust and Resolution Committee |
| Market integrity | AI must help detect manipulation, suspicious timing, concentrated positions, and related-account behavior without creating unchecked automated enforcement. | **Market Integrity Alert System** with human approval for account sanctions and extended market pauses |
| Regulatory readiness | The platform must be able to show regulators and payment partners how AI decisions were made, reviewed, challenged, and corrected. | **Regulator-Ready Audit Pack** generated monthly during sandbox |

---

# Part 4. Governance Roadmap Integration

## Governance-roadmap connection table

| Governance element | Roadmap initiative | Horizon | Why it must precede AI deployment |
|---|---|---|---|
| Data governance framework | Initiative 07: Data Governance and Official Event-Source Registry | H1 | AI event scoring, outcome resolution, and market surveillance require clean official sources, lineage, and audit logs before deployment |
| Model review board | Initiative 06: Market Governance and AI Risk Function | H1 | High-risk AI systems need named human oversight, deployment approval, rollback authority, and accountability before sandbox use |
| Adverse action notice system | Initiative 09: Responsible-Use and Customer Protection Framework | H1 | Users must be informed when AI-supported review leads to limits, cooling-off, payment holds, account restrictions, or payout delays |
| Human override protocol | Initiative 06: Market Governance and AI Risk Function | H1 | AI cannot autonomously approve market listings, freeze accounts, or resolve payouts during sandbox |
| Consent and data-use register | Initiative 13: Open Banking Personalization and Consent Foundation | H2 | Personalization and responsible-use scoring require clear consent, data-use boundaries, and revocation logic |
| Bias monitoring dashboard | Initiative 16: AI Market Surveillance and Responsible-Use Scoring | H2 | Once live user data exists, the platform must check whether alerts or restrictions disproportionately affect specific user groups |
| Regular audit process | Initiative 17: Outcome Resolution and Regulator Reporting Automation | H2 | Regulators and payment partners need recurring evidence that decisions, outcomes, disputes, and AI interventions are traceable |
| Model performance monitoring | Initiative 16: AI Market Surveillance and Responsible-Use Scoring | H2 | Live-market AI tools require drift monitoring, false-positive tracking, and rollback thresholds |
| Appeal and dispute workflow | Initiative 09: Responsible-Use and Customer Protection Framework; Initiative 17: Reporting Automation | H1 / H2 | User restrictions and payout disputes must be contestable before public launch |
| Regulator-ready reporting | Initiative 17: Outcome Resolution and Regulator Reporting Automation | H2 | NBG and payment partners need audit evidence before the platform can scale beyond sandbox |
| Public launch governance gate | Initiative 19: Unit Economics and Public Launch Gate | H2 | Board should approve public launch only after AI governance, data quality, liquidity, responsible-use, and unit economics are validated |

---

## Detailed governance sequencing

### H1: Governance before AI deployment

H1 must establish the minimum safe governance foundation before any AI system affects users or markets.

| H1 governance item | Owner | Output |
|---|---|---|
| Market Governance and AI Risk Committee | Regulatory & Platform Governance | Committee charter, decision rights, review cadence |
| AI Model Registry | Data, AI & Market Integrity | Inventory of AI models, owners, versions, risk tier |
| Event Source Registry | Data Governance Lead | Official sources, backup sources, source-confidence rules |
| Human Override Protocol | Market Governance and AI Risk Committee | Required human review rules and override log |
| Responsible-Use Policy | Responsible Use & Customer Trust | Loss limits, cooling-off rules, deposit alerts, appeal rights |
| AI Disclosure and User Notice Rules | Product + Compliance | Chatbot notices, adverse action notice templates |
| NBG Pre-Consultation Package | Regulatory & Platform Governance | Sandbox scope, sample contracts, risk-control documentation |

### H2: Governance during sandbox

H2 tests whether governance works under live conditions.

| H2 governance item | Owner | Output |
|---|---|---|
| Live Model Performance Dashboard | Data, AI & Market Integrity | Alert quality, drift, false positives, override rate |
| Bias Monitoring Dashboard | Data, AI & Market Integrity + Responsible Use | Subgroup impact and fairness review |
| Market Integrity Review Process | Market Integrity Lead | Investigation log and escalation record |
| Outcome Resolution Audit Trail | Resolution Committee + Data Governance | Official source evidence and payout decision record |
| Regulator Reporting Automation | Regulatory & Platform Governance | Monthly NBG / payment-partner reports |
| User Appeal Workflow | Customer Trust | Appeal SLA tracking and resolution outcomes |

### H3: Governance before public launch

H3 governance must be stricter than sandbox governance because the platform becomes more visible and higher-risk.

| H3 governance item | Owner | Output |
|---|---|---|
| External AI / model audit | Board + Chief Risk Officer | Independent model and governance review |
| Public launch governance pack | Executive Steering Committee | Board-ready evidence on risk, compliance, liquidity, and unit economics |
| Advanced market-integrity graph | Data, AI & Market Integrity | Related-account detection and insider-risk monitoring |
| AI-first regulatory compliance automation | Regulatory & Platform Governance | Automated filing drafts and regulatory change monitoring |
| Scaled responsible-use governance | Responsible Use & Customer Trust | Expanded limits, user protection, and harm monitoring |

---
---

# Part 5. Activity Insert: Governance and Change Management Draft

## Recommended AI use case selected

The recommended AI use case for this activity is:

> **AI Market Surveillance and Responsible-Use Scoring for the Georgian Prediction-Market Platform**

This use case is the most important governance priority because it directly affects user trading access, account restrictions, market pauses, responsible-use interventions, payment-partner confidence, and regulator trust.

It connects to the roadmap through:

- **Initiative 06: Market Governance and AI Risk Function**
- **Initiative 09: Responsible-Use and Customer Protection Framework**
- **Initiative 16: AI Market Surveillance and Responsible-Use Scoring**
- **Initiative 17: Outcome Resolution and Regulator Reporting Automation**

---

## Part 5.1 Governance plan

### EU AI Act-style risk tier

| AI use case | Risk tier | Rationale |
|---|---|---|
| AI Market Surveillance and Responsible-Use Scoring | High Risk | The system may trigger trading restrictions, deposit limits, cooling-off periods, account reviews, market pauses, or payout delays. These decisions affect users’ financial activity and access to the platform, so the model should be governed as high-risk even if final decisions remain human-approved. |

### Specific obligation created for the client

The client must implement an **Adverse Action Notice and Human Review Mechanism** for every AI-supported user restriction.

This means:

> If AI-supported surveillance or responsible-use scoring leads to a trading restriction, deposit limit, cooling-off period, account freeze, or delayed payout, the user must receive a notice explaining the action, the main reason code, whether AI was used, the duration of the restriction, and the appeal channel.

This is more specific than simply saying “transparency.” The mechanism must be built into the product and support workflow.

### Named governance mechanism

| Governance question | Entry |
|---|---|
| Oversight body | **Market Governance and AI Risk Committee** |
| Review cadence | Monthly during H1 build; bi-weekly during H2 sandbox; emergency review within 24 hours for severe incidents |
| Who holds the human override protocol? | **Responsible Use Lead** for user restrictions, **Market Integrity Lead** for trading surveillance actions, and **Resolution Committee Chair** for payout or dispute decisions |
| Who can approve deployment? | Market Governance and AI Risk Committee, with sign-off from Head of Data & AI, Compliance Lead, Responsible Use Lead, and Prediction Market General Manager |
| Who can trigger rollback? | Compliance Lead, Chief Risk Officer delegate, Head of Data & AI, Responsible Use Lead, or Market Integrity Lead |
| Required evidence | AI model registry entry, training data description, escalation thresholds, human override log, adverse action notice template, model performance dashboard, and incident rollback protocol |

### Human override protocol

```text
AI alert
→ human review queue
→ reviewer approves, rejects, or modifies action
→ rationale logged
→ user notice sent if adverse
→ appeal path opened if user is affected
→ model monitoring dashboard updated

# Governance Mechanisms by AI Use Case

| AI use case | Minimum governance mechanism | Human owner | Evidence required |
|---|---|---|---|
| Loan A/R Collections Optimization | Human-in-the-loop collections review | Head of Collections | Contact recommendation log, escalation record, customer complaint log |
| Payment Fraud Detection | Payment hold review queue | Fraud Risk Lead | Alert log, false-positive rate, release/hold decision record |
| Customer Service Automation | Chatbot disclosure and escalation button | Customer Experience Lead | Conversation logs, escalation rate, CSAT |
| Robo-Advisory MVP | Investment explanation review and suitability boundary | TBC Capital / Brokerage Lead | User disclosure, advisor review sample, recommendation logs |
| Event Risk Scoring | Market approval committee review | Market Governance Committee | Event-risk score, source-confidence score, approval memo |
| Market Surveillance | Market integrity alert workflow | Market Integrity Lead | Price-move alert, investigation memo, action taken |
| Responsible-Use Scoring | Responsible-use intervention workflow | Responsible Use Lead | Loss/deposit trigger log, notice, appeal result |
| Outcome Resolution | Resolution Committee sign-off | Resolution Committee Chair | Official-source evidence, resolution memo, dispute log |
| Open Banking Personalization | Consent and purpose-limitation register | Open Banking Lead | Consent record, data-use log, opt-out tracking |
| SME Credit Scoring | Credit officer review and adverse action notice | Credit Risk Lead | Explainability report, decision log, appeal record |
| Regulatory Compliance Automation | Compliance sign-off before filing | Compliance Lead | Draft history, source citations, filing approval |

---

# High-Risk AI Controls

## Required controls for high-risk use cases

Every high-risk AI use case must have:

1. named business owner,
2. named model owner,
3. model registry entry,
4. data owner,
5. approved training dataset,
6. documented limitations,
7. human override process,
8. user notice where applicable,
9. appeal or dispute process where applicable,
10. monitoring dashboard,
11. audit trail,
12. rollback procedure,
13. monthly governance review.

## High-risk use cases in this project

| Use case | Why high-risk | Required additional control |
|---|---|---|
| Loan A/R Collections Optimization | Affects credit collection treatment | Human collections officer approves escalation |
| Payment Fraud Detection | Can block payments or freeze transactions | Human review for prolonged holds |
| Market Surveillance | Can trigger account or market restrictions | Human approval for sanctions or extended market pause |
| Responsible-Use Scoring | Can restrict user trading access | User notice and appeal pathway |
| Outcome Resolution | Affects payout and user trust | Resolution Committee sign-off before payout |
| SME Credit Scoring | Affects loan approval or pricing | Credit officer review and adverse action notice |

---

# AI Incident Management

## Incident severity levels

| Severity | Definition | Example | Response |
|---|---|---|---|
| Level 1: Low | AI output is wrong but no user harm or market impact occurs | Chatbot gives incomplete FAQ answer | Correct content and log issue |
| Level 2: Medium | AI creates operational rework or user confusion | Event-risk model misclassifies market category | Human review, model correction, committee note |
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

## Rollback triggers

AI system rollback is required if:

- false-positive rate doubles for two consecutive review periods,
- model drift exceeds approved threshold,
- more than 5% of alerts are overturned by humans in high-impact cases,
- a model causes a Level 4 incident,
- regulator or payment partner raises formal concern,
- audit trail is incomplete for high-risk decisions,
- or the model uses unauthorized data.

---

# Governance KPIs

| Governance area | KPI | Target |
|---|---|---:|
| Model governance | Percentage of AI models registered | 100% |
| Model governance | High-risk models reviewed on schedule | 100% |
| Human oversight | High-risk AI alerts reviewed within SLA | 95%+ |
| Transparency | AI-supported adverse decisions with user notice | 100% |
| Data governance | Critical datasets with named owner | 100% |
| Data governance | Market contracts with approved source | 100% |
| Reliability | Severe model incidents unresolved beyond SLA | 0 |
| Privacy | Unauthorized access incidents | 0 |
| Accountability | Overrides with documented reason | 100% |
| Responsible use | High-risk user interventions logged | 100% |
| Market integrity | Abnormal price moves reviewed within SLA | 100% |
| Dispute handling | Market disputes resolved within SLA | 90%+ |
| Regulatory readiness | Monthly governance report delivered on time | 100% |

---

# Quality Check

Before finalising:

- **Every AI use case has a named EU AI Act risk tier with rationale.**  
  Yes.

- **Every tier in the three-tier architecture has a named owner function.**  
  Yes.

- **Every Responsible AI principle has a named mechanism, not just a definition.**  
  Yes.

- **Every governance element is connected to a named roadmap initiative.**  
  Yes.

- **High-risk use cases have human override protocols stated explicitly.**  
  Yes.

---

# References

European Commission. (2026). *AI Act*. Shaping Europe’s Digital Future. https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai

Christensen, C. M. (1997). *The innovator’s dilemma: When new technologies cause great firms to fail*. Harvard Business School Press.

Rogers, D. L. (2023). *The digital transformation roadmap: Rebuild your organization for continuous change*. Columbia Business School Publishing.

National Bank of Georgia. (2025). *Financial Innovation Office*. https://www.nbg.gov.ge/en/pages/financial-innovation-office

National Bank of Georgia. (2025). *Financial Literacy Survey 2024*. https://www.nbg.gov.ge/uploads/pressreleases/2025/Financial_Literacy_Survey_2024.pdf

National Bank of Georgia. (2025). *Amendments to the Law on Operating of the Virtual Assets*. https://www.nbg.gov.ge/uploads/pressreleases/2025/Amendments_to_the_Law_on_Operating_of_the_Virtual_Assets.pdf

Georgian Foundation for Strategic and International Studies. (2024). *Georgia’s cryptocurrency regulation landscape*. https://www.gfsis.org.ge/publications/georgia-s-cryptocurrency-regulation-landscape

TBC Bank. (2024). *TBC Capital individual brokerage services*. https://www.tbcbank.ge/en/corporate/tbc-capital/tbc-capital-individuals

CoinDesk. (2024, November 12). *Polymarket crypto prediction market hits $1B in monthly volume for first time*. https://www.coindesk.com/markets/2024/11/12/polymarket-crypto-prediction-market-hits-1b-in-monthly-volume-for-first-time/
