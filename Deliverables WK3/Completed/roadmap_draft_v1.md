# Roadmap Draft v1

## Purpose

This document builds the 18-month transformation roadmap for a Georgian, bank-backed prediction-market platform. It becomes Section 7 of the final project report.

The roadmap pulls from:

- Three Horizons Portfolio v1,
- AI Opportunity Map v1,
- Operating Model v1,
- ROI and unit-economics model,
- and the recommended strategic option from the midterm.

The recommended strategic option is:

> **Regulatory Sandbox Pathway, with responsible-use controls embedded from day one.**

The preferred path is a GEL-settled, bank-backed platform launched through NBG sandbox / pre-consultation first. A VASP / USDC route remains a fallback or niche crypto-native option, not the default mass-market model.

---

# 1. Roadmap Logic Summary

The roadmap is built around one sequencing principle:

> **H1 funds and prepares H2; H2 validates and de-risks H3.**

In the repository’s Three Horizons portfolio, several H1 initiatives are already high-readiness AI use cases: loan collections optimization, payment fraud detection, customer service automation, and wealth-management robo-advisory. These are not the final prediction-market product, but they matter because they create cash flow, data governance maturity, AI operating experience, and regulatory credibility.

The prediction-market platform itself is treated as a **Horizon 2 / Horizon 3 bridge**. Regulatory work can begin immediately, and a controlled pilot may be possible within 12 to 18 months, but full public launch should only happen after sandbox testing, legal classification, payment-partner approval, and market-integrity controls are proven.

The logic is:

```text
H1: strengthen existing bank capabilities and build the operating foundation
→ H2: invest in data, governance, sandbox pilot, liquidity, and reporting
→ H3: scale prediction markets only if regulation, liquidity, and unit economics are validated
```

---

# 2. Initiative Table

| # | Initiative name | Horizon | Timeline (months) | Owner function | Budget estimate | Dependency | Success metric |
|---|---|---|---:|---|---:|---|---|
| 01 | Loan A/R Collections Optimization | H1 | Months 1–6 | Credit Risk + Collections + Data/AI | $500K | None | 30DPD-to-90DPD roll-rate reduced by at least 15% in pilot portfolio; human-in-the-loop escalation active |
| 02 | Real-Time Payment Fraud Detection Upgrade | H1 | Months 1–6 | Payments + Fraud Risk + Data/AI | $500K | None | 95% of high-risk payment alerts reviewed within SLA; false-positive rate tracked weekly |
| 03 | Customer Service Automation for Digital Banking | H1 | Months 1–6 | Customer Experience + Product + Data/AI | $100K | None | 30% of routine service requests handled by chatbot with human escalation; CSAT remains above baseline |
| 04 | Wealth Management Robo-Advisory MVP | H1 | Months 2–6 | TBC Capital / Brokerage + Product + Data/AI | $500K | None | 10,000 users receive AI-generated portfolio explanations; advisor workload per micro-account reduced by 25% |
| 05 | Change Management Programme | H1 | Months 1–18 | Transformation Office / PMO | 20–30% of total transformation cost | None | 90% of impacted staff complete training; monthly adoption score above 75%; resistance log reviewed monthly |
| 06 | Market Governance and AI Risk Function | H1 | Months 1–3 | Regulatory & Platform Governance | $100K | None | Committee charter, AI override policy, escalation thresholds, and decision rights approved by month 3 |
| 07 | Data Governance and Official Event-Source Registry | H1 | Months 1–4 | Data, AI & Market Integrity | $500K | 06 | Source registry covers NBG, Geostat, CEC, FX backup feeds, and at least 5 approved official sources; source-confidence rule defined |
| 08 | NBG Pre-Consultation and Legal Classification Package | H1 | Months 2–5 | Regulatory & Platform Governance + Legal | $100K | 06 | NBG meeting completed or written feedback obtained; legal memo defines sandbox, financial-instrument, VASP, and gambling-risk paths |
| 09 | Responsible-Use and Customer Protection Framework | H1 | Months 2–5 | Responsible Use & Customer Trust | $100K | 06 | Daily loss limit, deposit alerts, cooling-off rules, risk quiz, complaint workflow, and vulnerable-user policy approved |
| 10 | KYC, AML, and GEL Payment-Rail Design | H1 | Months 3–6 | Payments, KYC & Settlement | $500K | 02, 06, 07 | Payment architecture approved; at least two PSP / bank-rail quotes collected; sandbox onboarding flow documented |
| 11 | MVP Market Listing Workflow and Contract Templates | H1 | Months 4–6 | Product, Engineering & UX + Market Operations | $500K | 06, 07, 08, 09 | 10 test contracts drafted; 100% include source, payout rule, risk warning, resolution rule, and escalation owner |
| 12 | AI-Assisted Event Risk Scoring Prototype | H1 | Months 4–6 | Data, AI & Market Integrity | $500K | 06, 07, 11 | AI scores 100% of proposed pilot markets; all scores reviewed by humans; false escalation and missed-risk rates measured |
| 13 | Open Banking Personalization and Consent Foundation | H2 | Months 7–14 | Open Banking / Digital Banking + Data/AI | $1M | 01, 02, 04, 07 | Consent model designed; customer data available through governed APIs; at least 3 personalization use cases tested |
| 14 | Controlled Prediction-Market Sandbox Pilot | H2 | Months 7–12 | Prediction Market General Manager | $1M | 08, 09, 10, 11, 12 | Pilot launches with capped users and approved markets; dispute rate below 1% of active traders per market |
| 15 | Liquidity and Market-Maker Programme | H2 | Months 7–13 | Market Operations & Liquidity | $500K | 11, 14 | Top pilot markets maintain bid-ask spread below 8% for 80% of trading hours; monthly market-maker scorecard produced |
| 16 | AI Market Surveillance and Responsible-Use Scoring | H2 | Months 8–14 | Data, AI & Market Integrity + Responsible Use | $1M | 09, 12, 14 | 100% of abnormal price moves above 20 percentage points in 15 minutes reviewed within SLA; high-risk user interventions logged |
| 17 | Outcome Resolution and Regulator Reporting Automation | H2 | Months 10–15 | Regulatory & Platform Governance + Data/AI | $500K | 07, 14, 16 | Monthly NBG / payment-partner report generated on time; 100% of resolved markets have audit trail and resolution memo |
| 18 | SME Credit Scoring Alternative Data Pilot | H2 | Months 12–18 | SME Banking + Credit Risk + Data/AI | $1M | 01, 13 | Alternative-data score tested on SME pilot segment; model explanation report approved by Credit Risk |
| 19 | Unit Economics and Public Launch Gate | H2 | Months 15–18 | Board / Executive Steering Committee | $100K | 14, 15, 16, 17 | Go / no-go pack completed with CAC, payment cost, active users, volume per user, contribution margin, liquidity cost, and regulatory status |
| 20 | Public GEL-Settled Prediction-Market Launch Option | H3 | Post-18 months | Board + Prediction Market General Manager | $5M+ | 19 | Trigger only if NBG path, payment rails, responsible-use controls, liquidity, and base-case economics are validated |
| 21 | VASP / USDC Fallback Option | H3 | Post-18 months | Strategy + Regulatory + Payments | $1M | 19 | Trigger only if GEL-settled route is blocked but VASP / crypto-native route is legally viable |
| 22 | AI-First Regulatory Compliance Automation | H3 | Post-18 months | Regulatory & Platform Governance + Data/AI | $1M+ | 17, 19 | Automated regulatory-monitoring and filing-draft workflow ready for scaled platform |
| 23 | Advanced Market-Integrity and Account-Linkage Graph | H3 | Post-18 months | Data, AI & Market Integrity | $1M+ | 16, 17, 20 | Manipulation detection, related-account graph, and insider-risk monitoring ready for scaled public launch |

---

# 3. Horizon Definitions

## Horizon 1: Months 1 to 6

H1 initiatives are deployable with current capabilities. They either create near-term ROI or build the minimum safe operating foundation for the prediction-market platform.

H1 includes two types of initiatives:

1. **Bank-side AI quick wins**  
   These include collections optimization, payment fraud detection, customer-service automation, and robo-advisory. They create internal AI readiness, cash-flow logic, and operational credibility.

2. **Prediction-market foundation**  
   These include market governance, event-source registry, NBG pre-consultation, responsible-use rules, payment-rail design, contract templates, and AI event-risk scoring.

H1 should not be judged by prediction-market profit. It should be judged by readiness, risk reduction, and evidence creation.

---

## Horizon 2: Months 7 to 18

H2 initiatives require investment before value is visible. This is the platform-building and validation phase.

H2 includes:

- open banking personalization foundation,
- controlled sandbox pilot,
- liquidity and market-maker programme,
- AI market surveillance,
- responsible-use scoring,
- outcome-resolution automation,
- regulator reporting,
- SME credit scoring pilot,
- and the public-launch gate.

H2 should be judged by:

- regulatory comfort,
- payment-partner acceptance,
- user retention,
- liquidity quality,
- dispute rate,
- responsible-use effectiveness,
- and contribution-margin evidence.

---

## Horizon 3: Post-18-month option space

H3 initiatives are not full commitments during the first 18 months. They are strategic options activated only after H2 evidence is strong enough.

H3 includes:

- public GEL-settled prediction-market launch,
- VASP / USDC fallback route,
- AI-first regulatory compliance automation,
- advanced market-integrity and account-linkage infrastructure.

H3 should be triggered only if the platform passes the regulatory, liquidity, responsible-use, and unit-economics gates.

---

# 4. Detailed Initiative Profiles

## 01. Loan A/R Collections Optimization

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 1–6 |
| Owner function | Credit Risk + Collections + Data/AI |
| Budget estimate | $500K |
| Dependency | None |
| Success metric | 30DPD-to-90DPD roll-rate reduced by at least 15% in pilot portfolio; human-in-the-loop escalation active |

### Description

This initiative deploys AI prediction models for early warning, optimal contact timing, and propensity-to-pay scoring. The repository’s AI Opportunity Map classifies loan collections optimization as a Deploy Now initiative with high value potential because banks lose portfolio value to delayed collections and relationship-based SME lending lacks early warning before serious delinquency.

### Why it belongs in the roadmap

Collections optimization is not the final prediction-market product, but it matters because it is an H1 cash-flow and capability source. It gives the bank practical experience with AI decision support, escalation thresholds, model monitoring, and human-in-the-loop workflows.

### Deliverables

- early-warning model,
- customer segmentation rules,
- contact-priority queue,
- human escalation thresholds,
- collections dashboard,
- model-monitoring report,
- compliance review of AI-supported collection actions.

### Link to prediction-market strategy

This builds AI governance maturity and can help fund H2 platform infrastructure. The Three Horizons portfolio states that H1 efficiency initiatives fund H2 platform investment.

---

## 02. Real-Time Payment Fraud Detection Upgrade

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 1–6 |
| Owner function | Payments + Fraud Risk + Data/AI |
| Budget estimate | $500K |
| Dependency | None |
| Success metric | 95% of high-risk payment alerts reviewed within SLA; false-positive rate tracked weekly |

### Description

This initiative upgrades fraud monitoring for cards, wallets, and digital payments. The AI Opportunity Map classifies payment fraud detection as a Quick Win because payment infrastructure already exists and cards dominate online purchases.

### Why it belongs in the roadmap

A prediction-market platform depends on trusted payment rails. Before launching any micro-stakes trading product, the client needs strong fraud detection, account-linkage logic, suspicious-payment monitoring, and step-up authentication.

### Deliverables

- real-time anomaly detection model,
- device fingerprinting rules,
- account-linkage features,
- automated block / step-up authentication workflow,
- fraud analyst dashboard,
- weekly false-positive report.

### Link to prediction-market strategy

The same fraud capabilities will later support:

- multi-account detection,
- suspicious deposit monitoring,
- payment-partner confidence,
- responsible-use enforcement,
- and market-integrity monitoring.

---

## 03. Customer Service Automation for Digital Banking

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 1–6 |
| Owner function | Customer Experience + Product + Data/AI |
| Budget estimate | $100K |
| Dependency | None |
| Success metric | 30% of routine service requests handled by chatbot with human escalation; CSAT remains above baseline |

### Description

This initiative improves digital customer service using Georgian-language conversational AI, intent classification, knowledge-base retrieval, and human escalation.

### Why it belongs in the roadmap

Prediction markets will generate user questions about contracts, risk warnings, deposits, settlements, disputes, and outcome resolution. Customer-service automation creates a reusable support capability before the platform pilot begins.

### Deliverables

- FAQ knowledge base,
- Georgian-language chatbot flows,
- escalation rules,
- human support dashboard,
- complaint tagging taxonomy,
- customer-satisfaction tracking.

### Link to prediction-market strategy

This initiative becomes the support foundation for:

- user education,
- dispute triage,
- responsible-use messages,
- settlement questions,
- and market-explanation workflows.

---

## 04. Wealth Management Robo-Advisory MVP

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 2–6 |
| Owner function | TBC Capital / Brokerage + Product + Data/AI |
| Budget estimate | $500K |
| Dependency | None |
| Success metric | 10,000 users receive AI-generated portfolio explanations; advisor workload per micro-account reduced by 25% |

### Description

This initiative uses generative AI for portfolio explanations, risk profiling, market summaries, and investment education. The repository classifies wealth-management robo-advisory as a Deploy Now opportunity because existing brokerage infrastructure and KYC pipelines already exist.

### Why it belongs in the roadmap

The prediction-market thesis depends on the idea that many users find traditional brokerage too complex. Robo-advisory helps the bank learn how users respond to simplified financial explanations before launching event contracts.

### Deliverables

- portfolio explanation engine,
- risk-profile summary,
- investment education content,
- human-advisor escalation rules,
- usage and activation dashboard.

### Link to prediction-market strategy

This creates:

- financial education capability,
- customer engagement data,
- user segmentation,
- and a natural funnel toward later event-contract products.

---

## 05. Change Management Programme

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 1–18 |
| Owner function | Transformation Office / PMO |
| Budget estimate | 20–30% of total transformation cost |
| Dependency | None |
| Success metric | 90% of impacted staff complete training; monthly adoption score above 75%; resistance log reviewed monthly |

### Description

This initiative manages adoption across risk, compliance, product, engineering, customer support, data, and executive stakeholders.

### Why it belongs in the roadmap

The project changes how the client governs markets, users, AI recommendations, disputes, and regulatory reporting. Without change management, employees may work around new workflows or treat the platform as a normal app rather than a supervised market.

### Deliverables

- stakeholder map,
- training plan,
- operating-model playbooks,
- escalation playbooks,
- communication plan,
- monthly adoption survey,
- resistance log,
- board update template.

### Link to prediction-market strategy

The platform cannot pass regulatory or payment-partner scrutiny if internal teams do not understand the new operating model.

---

## 06. Market Governance and AI Risk Function

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 1–3 |
| Owner function | Regulatory & Platform Governance |
| Budget estimate | $100K |
| Dependency | None |
| Success metric | Committee charter, AI override policy, escalation thresholds, and decision rights approved by month 3 |

### Description

This initiative creates the governance structure for event-market approval, AI oversight, responsible-use escalation, and high-risk decision-making.

### Why it belongs in the roadmap

The prediction-market platform cannot safely list markets without a governance body that owns event taxonomy, escalation thresholds, dispute rules, and AI override accountability.

### Deliverables

- Market Governance Committee charter,
- AI model approval policy,
- escalation matrix,
- human override log,
- approved decision rights,
- policy-exception process.

### Link to prediction-market strategy

The strategic recommendation is sandbox-first with responsible-use controls embedded from day one. This governance function is required to make that recommendation executable.

---

## 07. Data Governance and Official Event-Source Registry

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 1–4 |
| Owner function | Data, AI & Market Integrity |
| Budget estimate | $500K |
| Dependency | 06 |
| Success metric | Source registry covers NBG, Geostat, CEC, FX backup feeds, and at least 5 approved official sources; source-confidence rule defined |

### Description

This initiative creates the official data foundation for prediction-market operations.

### Why it belongs in the roadmap

Prediction markets cannot be trusted unless every contract has a clear source, publication time, backup source, and resolution rule.

### Deliverables

- official source registry,
- data owner list,
- source-confidence scoring rule,
- backup-source protocol,
- event data ingestion design,
- audit-log structure,
- data retention policy.

### Examples of sources

| Source | Potential event use |
|---|---|
| NBG | policy rate, GEL exchange-rate reference data, monetary indicators |
| Geostat | inflation, GDP, unemployment, macro releases |
| CEC | election results and turnout |
| FX data provider | backup market reference for GEL/USD or global FX |
| Government portals | public official announcements where appropriate |

### Link to prediction-market strategy

This initiative is a prerequisite for AI-assisted outcome resolution, market surveillance, and regulator-ready reporting.

---

## 08. NBG Pre-Consultation and Legal Classification Package

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 2–5 |
| Owner function | Regulatory & Platform Governance + Legal |
| Budget estimate | $100K |
| Dependency | 06 |
| Success metric | NBG meeting completed or written feedback obtained; legal memo defines sandbox, financial-instrument, VASP, and gambling-risk paths |

### Description

This initiative prepares the formal engagement package for NBG and external legal counsel.

### Why it belongs in the roadmap

Regulatory classification is the gating issue. The platform should not launch publicly before it knows whether event contracts can be tested as financial innovation or whether they risk being treated as gambling.

### Deliverables

- legal classification memo,
- NBG pre-consultation deck,
- proposed sandbox scope,
- sample event contracts,
- responsible-use policy,
- AML/KYC summary,
- payment-rail explanation,
- risk and control register.

### Link to prediction-market strategy

This initiative determines whether the GEL-settled route remains feasible or whether the project must pivot to a VASP / USDC fallback or stop.

---

## 09. Responsible-Use and Customer Protection Framework

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 2–5 |
| Owner function | Responsible Use & Customer Trust |
| Budget estimate | $100K |
| Dependency | 06 |
| Success metric | Daily loss limit, deposit alerts, cooling-off rules, risk quiz, complaint workflow, and vulnerable-user policy approved |

### Description

This initiative designs the consumer-protection layer required for a regulated prediction-market platform.

### Why it belongs in the roadmap

The platform must avoid looking like a gambling substitute. Responsible-use controls are therefore not optional product features. They are part of regulatory trust, payment-partner confidence, and reputational protection.

### Deliverables

- GEL 100 daily loss limit for sandbox,
- GEL 500 daily deposit alert during sandbox,
- cooling-off rules,
- user risk quiz,
- risk warnings,
- vulnerable-user policy,
- complaint and dispute workflow,
- responsible-use intervention dashboard.

### Link to prediction-market strategy

Responsible-use controls are the embedded layer inside the sandbox-first strategy, not a standalone legal strategy.

---

## 10. KYC, AML, and GEL Payment-Rail Design

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 3–6 |
| Owner function | Payments, KYC & Settlement |
| Budget estimate | $500K |
| Dependency | 02, 06, 07 |
| Success metric | Payment architecture approved; at least two PSP / bank-rail quotes collected; sandbox onboarding flow documented |

### Description

This initiative defines how users will deposit, trade, withdraw, and settle in GEL during the sandbox.

### Why it belongs in the roadmap

The ROI model depends heavily on payment cost. The platform is only economically attractive if bank-backed rails reduce external PSP dependence and lower friction.

### Deliverables

- KYC flow,
- AML screening design,
- wallet ledger design,
- deposit and withdrawal workflow,
- payment-partner quote pack,
- reconciliation process,
- chargeback / failed-payment handling,
- payment-risk controls.

### Link to prediction-market strategy

A GEL-settled route supports mass-market trust. A VASP / USDC route should only be used as fallback if GEL settlement is blocked.

---

## 11. MVP Market Listing Workflow and Contract Templates

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 4–6 |
| Owner function | Product, Engineering & UX + Market Operations |
| Budget estimate | $500K |
| Dependency | 06, 07, 08, 09 |
| Success metric | 10 test contracts drafted; 100% include source, payout rule, risk warning, resolution rule, and escalation owner |

### Description

This initiative creates the operating workflow for turning a market idea into a controlled, approved event contract.

### Why it belongs in the roadmap

Without standardized templates, each market becomes a legal, operational, and dispute risk.

### Deliverables

- contract template,
- market listing checklist,
- event category selector,
- user-facing explanation template,
- risk-warning template,
- resolution-rule template,
- admin approval workflow,
- test-market library.

### Initial market categories

Start with verifiable, lower-risk markets:

- inflation releases,
- GEL/USD exchange-rate bands,
- NBG policy-rate decisions,
- public macro indicators,
- election turnout,
- clearly resolvable civic outcomes.

Avoid in first phase:

- sports,
- war outcomes,
- individual criminal cases,
- medical outcomes,
- private-person markets,
- ambiguous political claims,
- events without official sources.

---

## 12. AI-Assisted Event Risk Scoring Prototype

| Element | Detail |
|---|---|
| Horizon | H1 |
| Timeline | Months 4–6 |
| Owner function | Data, AI & Market Integrity |
| Budget estimate | $500K |
| Dependency | 06, 07, 11 |
| Success metric | AI scores 100% of proposed pilot markets; all scores reviewed by humans; false escalation and missed-risk rates measured |

### Description

This initiative builds a decision-support model that screens proposed markets before human approval.

### Why it belongs in the roadmap

AI can help route and flag risk, but it should not autonomously approve markets during the sandbox.

### Deliverables

- event-risk scoring model,
- prohibited-topic classifier,
- source-confidence model,
- explanation generator,
- human review dashboard,
- model performance log,
- override log.

### Escalation thresholds

Escalate to human review if:

- event-risk score is above 30 / 100,
- source-confidence score is below 95%,
- market references sports, war, medical, or criminal outcomes,
- projected user exposure exceeds sandbox cap,
- event involves NBG, elections, or sensitive political outcomes.

---

## 13. Open Banking Personalization and Consent Foundation

| Element | Detail |
|---|---|
| Horizon | H2 |
| Timeline | Months 7–14 |
| Owner function | Open Banking / Digital Banking + Data/AI |
| Budget estimate | $1M |
| Dependency | 01, 02, 04, 07 |
| Success metric | Consent model designed; customer data available through governed APIs; at least 3 personalization use cases tested |

### Description

This initiative develops the governed customer-data and consent layer needed for future personalization, affordability checks, and responsible-use analytics.

### Why it belongs in the roadmap

The Three Horizons file identifies open banking personalization as a critical H2 platform capability and a prerequisite for future prediction-market infrastructure.

### Deliverables

- consent management model,
- API access framework,
- customer data mart,
- affordability indicator design,
- personalization use cases,
- privacy and compliance review.

### Link to prediction-market strategy

This supports:

- safer onboarding,
- affordability checks,
- responsible-use limits,
- user education,
- and segmentation for event-market recommendations.

---

## 14. Controlled Prediction-Market Sandbox Pilot

| Element | Detail |
|---|---|
| Horizon | H2 |
| Timeline | Months 7–12 |
| Owner function | Prediction Market General Manager |
| Budget estimate | $1M |
| Dependency | 08, 09, 10, 11, 12 |
| Success metric | Pilot launches with capped users and approved markets; dispute rate below 1% of active traders per market |

### Description

This initiative tests the platform under controlled conditions with limited users, limited event categories, exposure caps, and full audit logging.

### Why it belongs in the roadmap

The sandbox pilot converts the strategy from concept into evidence.

### Pilot design

| Design item | Pilot rule |
|---|---|
| User access | Invite-only or limited cohort |
| Settlement | GEL preferred |
| Markets | Macro, civic, and financial-public-data events |
| Daily loss limit | GEL 100 |
| Deposit alert | GEL 500 within 24 hours |
| Market exposure cap | GEL 50,000 per market during sandbox |
| Resolution | Official sources only |
| AI approval | No autonomous listing; human approval required |
| Reporting | Monthly NBG / partner evidence pack |

### Deliverables

- sandbox pilot plan,
- user cohort design,
- market list,
- trading interface,
- payment flow,
- responsible-use dashboard,
- reporting pack,
- pilot review memo.

---

## 15. Liquidity and Market-Maker Programme

| Element | Detail |
|---|---|
| Horizon | H2 |
| Timeline | Months 7–13 |
| Owner function | Market Operations & Liquidity |
| Budget estimate | $500K |
| Dependency | 11, 14 |
| Success metric | Top pilot markets maintain bid-ask spread below 8% for 80% of trading hours; monthly market-maker scorecard produced |

### Description

This initiative ensures that pilot markets are actually tradable. Without liquidity, users cannot enter and exit positions at fair prices.

### Why it belongs in the roadmap

The ROI model shows liquidity subsidy as a major fixed cost. The platform must test whether market-maker support can keep spreads tight enough before public launch.

### Deliverables

- market-maker agreement,
- spread targets,
- depth targets,
- quote obligations,
- market-maker dashboard,
- liquidity subsidy tracking,
- monthly market-quality report.

### Key metrics

- bid-ask spread,
- order-book depth,
- market-maker uptime,
- failed quote intervals,
- open interest,
- trade completion rate,
- user abandonment after viewing spread.

---

## 16. AI Market Surveillance and Responsible-Use Scoring

| Element | Detail |
|---|---|
| Horizon | H2 |
| Timeline | Months 8–14 |
| Owner function | Data, AI & Market Integrity + Responsible Use |
| Budget estimate | $1M |
| Dependency | 09, 12, 14 |
| Success metric | 100% of abnormal price moves above 20 percentage points in 15 minutes reviewed within SLA; high-risk user interventions logged |

### Description

This initiative builds the AI-assisted risk layer for live markets and users.

### Why it belongs in the roadmap

Prediction markets are exposed to manipulation, insider information, multi-accounting, and harmful user behavior. These risks increase once real trading begins.

### Deliverables

- suspicious price-move alerts,
- account-concentration alerts,
- related-account detection,
- user risk score,
- responsible-use intervention workflow,
- market integrity dashboard,
- model audit logs.

### Escalation examples

| Trigger | Action |
|---|---|
| Price moves more than 20 percentage points in 15 minutes without public news | Market integrity review |
| One account cluster holds more than 25% of one side | Concentration review |
| User reaches GEL 100 daily loss limit | Automatic stop |
| User hits loss limit 3 times in 7 days | 48-hour cooling-off |
| More than 20 trades in one hour | Friction warning |

---

## 17. Outcome Resolution and Regulator Reporting Automation

| Element | Detail |
|---|---|
| Horizon | H2 |
| Timeline | Months 10–15 |
| Owner function | Regulatory & Platform Governance + Data/AI |
| Budget estimate | $500K |
| Dependency | 07, 14, 16 |
| Success metric | Monthly NBG / payment-partner report generated on time; 100% of resolved markets have audit trail and resolution memo |

### Description

This initiative automates resolution evidence gathering and regulator / payment-partner reporting.

### Why it belongs in the roadmap

Outcome disputes are one of the most important trust risks in prediction markets. Regulators and payment partners need evidence that markets are resolved fairly and consistently.

### Deliverables

- resolution memo generator,
- official result extraction,
- dispute summary report,
- regulator report template,
- payment-partner report template,
- monthly compliance dashboard,
- audit trail export.

### Key metrics

- time from event result to payout,
- percentage of markets resolved without dispute,
- number of disputes per market,
- report submission timeliness,
- audit trail completeness.

---

## 18. SME Credit Scoring Alternative Data Pilot

| Element | Detail |
|---|---|
| Horizon | H2 |
| Timeline | Months 12–18 |
| Owner function | SME Banking + Credit Risk + Data/AI |
| Budget estimate | $1M |
| Dependency | 01, 13 |
| Success metric | Alternative-data score tested on SME pilot segment; model explanation report approved by Credit Risk |

### Description

This initiative uses alternative data to support SME credit scoring. It is included because the AI Opportunity Map identifies SME credit scoring as a Future Option that becomes more feasible after open banking and data infrastructure improve.

### Why it belongs in the roadmap

It is not directly required for the prediction-market pilot, but it strengthens the broader bank transformation portfolio and helps justify the H2 data infrastructure investment.

### Deliverables

- alternative-data feature set,
- SME pilot model,
- explainability report,
- credit-risk review,
- model validation plan.

### Link to prediction-market strategy

The same data governance, explainability, and AI risk-management capabilities support future prediction-market personalization and responsible-use controls.

---

## 19. Unit Economics and Public Launch Gate

| Element | Detail |
|---|---|
| Horizon | H2 |
| Timeline | Months 15–18 |
| Owner function | Board / Executive Steering Committee |
| Budget estimate | $100K |
| Dependency | 14, 15, 16, 17 |
| Success metric | Go / no-go pack completed with CAC, payment cost, active users, volume per user, contribution margin, liquidity cost, and regulatory status |

### Description

This initiative turns pilot evidence into a board decision.

### Why it belongs in the roadmap

The platform should not proceed to public launch simply because the pilot worked technically. It must pass economic, regulatory, liquidity, and responsible-use gates.

### Required evidence

| Gate | Required evidence |
|---|---|
| Regulatory gate | NBG feedback, legal classification, approved restrictions |
| Payment gate | PSP / bank-rail pricing, payment success rate, AML/KYC performance |
| User gate | active users, repeat usage, retention, complaint rate |
| Liquidity gate | spread, depth, market-maker subsidy |
| Economics gate | CAC, ARPU, contribution margin, breakeven active users |
| Risk gate | dispute rate, responsible-use interventions, market-integrity incidents |

### Decision options

1. proceed to public GEL-settled launch,
2. continue sandbox,
3. pivot to VASP / USDC route,
4. pause the project.

---

## 20. Public GEL-Settled Prediction-Market Launch Option

| Element | Detail |
|---|---|
| Horizon | H3 |
| Timeline | Post-18 months |
| Owner function | Board + Prediction Market General Manager |
| Budget estimate | $5M+ |
| Dependency | 19 |
| Success metric | Trigger only if NBG path, payment rails, responsible-use controls, liquidity, and base-case economics are validated |

### Description

This is the preferred H3 option if H2 evidence supports scaling.

### Why it remains H3

The public launch requires board commitment, broader market exposure, expanded compliance operations, stronger engineering, higher liquidity subsidy, and market-integrity automation.

### Trigger conditions

- NBG path confirmed,
- payment rails approved,
- legal classification manageable,
- pilot dispute rate below 1%,
- responsible-use controls accepted,
- liquidity spread below 8% in top markets,
- breakeven path credible.

---

## 21. VASP / USDC Fallback Option

| Element | Detail |
|---|---|
| Horizon | H3 |
| Timeline | Post-18 months |
| Owner function | Strategy + Regulatory + Payments |
| Budget estimate | $1M |
| Dependency | 19 |
| Success metric | Trigger only if GEL-settled route is blocked but VASP / crypto-native route is legally viable |

### Description

This option explores a narrower crypto-native launch using VASP / USDC infrastructure.

### Why it is fallback, not default

The VASP route is fallback because VASP registration does not automatically solve event-contract legality. It may work for crypto-native users but weakens the mass-market trust and payment story.

### Trigger conditions

- GEL route blocked,
- VASP route receives legal confirmation,
- payment / off-ramp risk manageable,
- target segment narrowed to crypto-native users,
- reputational risk accepted by board.

---

## 22. AI-First Regulatory Compliance Automation

| Element | Detail |
|---|---|
| Horizon | H3 |
| Timeline | Post-18 months |
| Owner function | Regulatory & Platform Governance + Data/AI |
| Budget estimate | $1M+ |
| Dependency | 17, 19 |
| Success metric | Automated regulatory-monitoring and filing-draft workflow ready for scaled platform |

### Description

This initiative builds more advanced AI support for regulatory monitoring, reporting, filing drafts, and compliance risk scoring.

### Why it belongs in H3

The AI Opportunity Map identifies regulatory compliance automation as a Future Option because Georgian regulatory reporting standards are still evolving and NBG can define new virtual-asset services through normative acts.

### Deliverables

- regulation-monitoring workflow,
- compliance risk-scoring model,
- filing draft generator,
- reporting calendar agent,
- escalation system for regulatory changes.

---

## 23. Advanced Market-Integrity and Account-Linkage Graph

| Element | Detail |
|---|---|
| Horizon | H3 |
| Timeline | Post-18 months |
| Owner function | Data, AI & Market Integrity |
| Budget estimate | $1M+ |
| Dependency | 16, 17, 20 |
| Success metric | Manipulation detection, related-account graph, and insider-risk monitoring ready for scaled public launch |

### Description

This initiative builds the advanced surveillance layer for a larger public prediction-market platform.

### Why it belongs in H3

The sandbox can begin with rule-based surveillance and human review. Public launch requires more sophisticated detection of insider information, related accounts, wash trading, suspicious timing, and concentrated positions.

### Deliverables

- account-linkage graph,
- related-device detection,
- suspicious timing model,
- insider-risk monitoring,
- position concentration dashboards,
- automatic escalation to Market Integrity team.

---

# 5. Dependency Logic

Initiatives 01 through 12 form the H1 foundation. The H1 portfolio has two purposes: first, it creates near-term value and AI-readiness through collections, fraud detection, customer service, and robo-advisory; second, it creates the governance, data, legal, payment, and responsible-use foundation needed for a prediction-market sandbox.

**Initiative 06: Market Governance and AI Risk Function** is the critical prerequisite for all platform work because the platform cannot list markets, use AI risk scoring, or report to NBG without named decision rights and escalation rules.

**Initiative 07: Data Governance and Official Event-Source Registry** is the critical technical prerequisite because prediction markets require official data sources for transparent outcome resolution.

H2 then uses the H1 foundation to run the controlled sandbox pilot, build liquidity, deploy market surveillance, automate resolution reporting, and validate unit economics.

H3 experiments activate only if H2 proves the platform can satisfy NBG, payment partners, users, market makers, and the board.

```text
H1 quick wins and foundations
→ H2 sandbox and platform infrastructure
→ H3 public launch or fallback option
```

---

# 6. Dependency Map

| From | To | Dependency type | Criticality | Consequence if skipped |
|---|---|---|---|---|
| 01 Collections Optimization | 13 Open Banking Foundation | Data maturity + cash-flow logic | High | H2 lacks practical AI governance and customer-risk data maturity |
| 02 Fraud Detection | 10 Payment-Rail Design | Payment risk foundation | High | Payment partners may reject or price rails too expensively |
| 03 Customer Service Automation | 14 Sandbox Pilot | Support capability | Medium | User disputes and education burden overload manual support |
| 04 Robo-Advisory MVP | 13 Open Banking Foundation | Customer engagement + data | High | Personalization layer lacks user behavior and education experience |
| 05 Change Management | All initiatives | Adoption and execution | Critical | Teams work around new governance and AI workflows |
| 06 Market Governance | 08, 09, 11, 12, 14 | Decision rights | Critical | Markets launch without accountable approval |
| 07 Source Registry | 11, 12, 17 | Data foundation | Critical | Event contracts cannot resolve cleanly |
| 08 NBG Package | 14 Sandbox Pilot | Regulatory gate | Critical | Public or pilot launch may be legally unsafe |
| 09 Responsible Use | 14, 16 | Consumer protection | Critical | Platform may be viewed as gambling or harmful speculation |
| 10 Payment-Rail Design | 14 | Payment and onboarding | Critical | Users cannot deposit / withdraw safely in GEL |
| 11 Contract Templates | 14, 15 | Market listing foundation | Critical | Market wording and payout rules become inconsistent |
| 12 Event Risk Scoring | 14, 16 | AI decision support | High | Risk routing remains manual and slow |
| 14 Sandbox Pilot | 19 Launch Gate | Evidence generation | Critical | Board has no basis for go / no-go decision |
| 15 Liquidity Programme | 19 Launch Gate | Market quality evidence | Critical | Unit economics cannot be validated |
| 16 Surveillance + Responsible Use AI | 19 Launch Gate | Risk evidence | Critical | Board cannot assess manipulation and harm risk |
| 17 Reporting Automation | 19 Launch Gate | Regulator evidence | High | NBG / payment partners lack evidence of control |
| 19 Launch Gate | 20, 21, 22, 23 | Board decision | Critical | H3 options cannot be responsibly activated |

---

# 7. Detailed Funding Narrative and Financial Breakdown

## 7.1 Financial logic of the roadmap

The roadmap should not be funded as one large product launch. It should be funded as a staged transformation portfolio.

The financial logic is:

```text
H1 = build cash-flow, AI readiness, governance, and reusable infrastructure
H2 = fund sandbox, liquidity, reporting, and platform validation
H3 = commit scale capital only if regulatory and unit-economics gates are passed
```

This is consistent with the Three Horizons logic: H1 initiatives strengthen the existing business and create efficiency gains, H2 builds platform and data capabilities, and H3 remains an option until the foundation is in place.

The prediction-market platform is not expected to be profitable in the early sandbox phase. Its first financial purpose is to produce evidence on regulation, liquidity, payment cost, CAC, user demand, and contribution margin.

---

## 7.2 Financial reconciliation with ROI model

The roadmap budget and the ROI model use different levels of analysis.

The ROI model estimates the monthly operating economics of the prediction-market platform itself. It is denominated in GEL and focuses on:

- active users,
- trading volume per user,
- take rate,
- payment cost,
- liquidity subsidy,
- compliance/legal run cost,
- platform run cost,
- CAC,
- contribution margin,
- and breakeven active users.

The roadmap budget is broader. It includes both prediction-market-specific initiatives and enabling bank transformation initiatives such as collections optimization, payment fraud detection, customer service automation, robo-advisory, open banking personalization, and SME credit scoring.

Therefore, the roadmap should be read in two layers:

1. **Prediction-market-specific investment**  
   Governance, data source registry, NBG package, responsible-use controls, payment design, MVP workflow, sandbox pilot, liquidity, surveillance, reporting, and launch gate.

2. **Broader transformation investment**  
   H1 and H2 bank-side AI capabilities that fund or enable the prediction-market option.

The ROI model’s base-case fixed monthly cost is:

```text
Liquidity subsidy: GEL 50,000
Compliance/legal run cost: GEL 30,000
Platform run cost: GEL 70,000
Total fixed cost: GEL 150,000 per month
```

A six-month pilot at this base monthly run rate implies:

```text
GEL 150,000 × 6 = GEL 900,000
```

This figure represents the platform operating-cost core of the sandbox. It does not fully include one-time setup, legal work, data infrastructure, change management, payment integration, NBG engagement, reporting automation, or contingency.

Budget labels in the roadmap follow the course template’s USD order-of-magnitude categories. The ROI model itself remains in GEL. Final submission should convert roadmap budgets into GEL using a stated FX assumption if both sections are presented together.

---

## 7.3 Budget summary by horizon

| Horizon | Main purpose | Included initiatives | Budget range | Funding logic |
|---|---|---|---:|---|
| H1: Months 1–6 | Build readiness and near-term AI value | Collections AI, fraud detection, customer service automation, robo-advisory, governance, data registry, NBG package, responsible use, payment design, MVP workflow, AI risk scoring prototype | **$3.8M–$5.2M** | Funded from current bank innovation / digital transformation budget; partly justified by H1 efficiency gains |
| H2: Months 7–18 | Run sandbox and build platform evidence | Open banking foundation, sandbox pilot, liquidity programme, surveillance AI, reporting automation, SME scoring, public launch gate | **$4.5M–$6.5M** | Ring-fenced transformation budget; approved after H1 governance and NBG feasibility gate |
| H3: Post-18 months | Scale or pivot option | Public GEL launch, VASP fallback, advanced compliance automation, market-integrity graph | **$7M–$15M+** | Board-approved only if H2 gates are passed |
| Change management | Adoption, training, governance shift | Runs across H1 and H2 | **20–30% of total transformation cost** | Required because the project changes governance, risk, product, and AI workflows |

### Interpretation

The first 18 months require approximately **$8.3M–$11.7M**, excluding H3 scale commitment.

This number should not be presented as the cost to launch the full platform. It is better framed as the cost to:

- build the operating foundation,
- validate regulatory feasibility,
- run a controlled sandbox,
- test liquidity,
- produce user and unit-economics evidence,
- and prepare the board for a launch / pivot / stop decision.

---

## 7.4 Prediction-market-specific budget view

This view separates the actual prediction-market platform pathway from the broader bank transformation portfolio.

| Phase | Prediction-market-specific initiatives | Estimated budget |
|---|---|---:|
| H1 foundation | Market governance, event-source registry, NBG package, responsible-use framework, payment design, MVP workflow, AI event-risk prototype | **~$2.3M** |
| H2 sandbox | Controlled sandbox pilot, liquidity programme, AI surveillance / responsible-use scoring, outcome resolution and reporting automation, unit-economics gate | **~$3.1M** |
| H3 scale option | Public GEL-settled launch | **$5M+** |
| H3 fallback option | VASP / USDC route | **~$1M** |

### Interpretation

The prediction-market-specific first 18-month budget is approximately:

```text
H1 prediction-market foundation: ~$2.3M
H2 prediction-market sandbox and validation: ~$3.1M
Total before H3 public launch: ~$5.4M
```

This is separate from broader transformation initiatives such as collections AI, robo-advisory, open banking personalization, and SME credit scoring.

---

## 7.5 Broader transformation budget view

The broader transformation budget includes all roadmap items, not only the prediction-market platform.

| Category | Initiatives included | Estimated budget |
|---|---|---:|
| H1 bank-side AI quick wins | Collections, fraud detection, customer service automation, robo-advisory | **~$1.6M** |
| H1 prediction-market foundation | Governance, source registry, NBG package, responsible use, payment design, MVP workflow, AI event-risk prototype | **~$2.3M** |
| H1 / H2 change management | Training, adoption, operating-model change, governance adoption | **20–30% of total transformation cost** |
| H2 broader platform infrastructure | Open banking personalization and SME scoring pilot | **~$2M** |
| H2 prediction-market sandbox and validation | Sandbox pilot, liquidity, surveillance, reporting, launch gate | **~$3.1M** |

### Interpretation

The broader portfolio is larger because it includes H1 and H2 initiatives that build the bank’s AI maturity and data foundation, not only the prediction-market platform itself.

This is strategically useful because it allows the client to avoid treating the prediction market as an isolated risky bet. Instead, the bank builds reusable capabilities that also improve the core business.

---

## 7.6 Detailed initiative-level budget breakdown

| # | Initiative | Total budget | People | Technology / vendor | Legal / compliance | Data / infrastructure | Change / training | Notes |
|---|---|---:|---:|---:|---:|---:|---:|---|
| 01 | Loan A/R Collections Optimization | $500K | $180K | $150K | $40K | $80K | $50K | Covers model development, collections workflow redesign, dashboarding, compliance review, and pilot training |
| 02 | Real-Time Payment Fraud Detection Upgrade | $500K | $150K | $170K | $50K | $90K | $40K | Covers anomaly detection, device fingerprinting, alert workflow, fraud dashboard, and payment-risk governance |
| 03 | Customer Service Automation | $100K | $30K | $30K | $5K | $10K | $25K | Covers chatbot flows, Georgian-language content, escalation logic, and support-team training |
| 04 | Wealth Management Robo-Advisory MVP | $500K | $160K | $140K | $50K | $80K | $70K | Covers AI explanations, risk-profiling logic, brokerage integration, content review, and advisor training |
| 05 | Change Management Programme | 20–30% of total transformation cost | $250K–$500K | $100K–$200K | $50K–$100K | $50K–$100K | $800K–$1.5M | Runs across roadmap; includes training, adoption tracking, playbooks, and stakeholder management |
| 06 | Market Governance and AI Risk Function | $100K | $35K | $10K | $35K | $10K | $10K | Covers committee setup, AI override policy, escalation thresholds, and decision rights |
| 07 | Data Governance and Official Event-Source Registry | $500K | $150K | $80K | $40K | $200K | $30K | Covers source registry, data pipelines, audit logs, source-confidence rules, and data ownership model |
| 08 | NBG Pre-Consultation and Legal Classification Package | $100K | $15K | $5K | $70K | $5K | $5K | Covers legal memo, NBG pack, sandbox scope, sample contracts, and risk-control documentation |
| 09 | Responsible-Use and Customer Protection Framework | $100K | $30K | $15K | $25K | $10K | $20K | Covers loss limits, deposit alerts, cooling-off rules, quiz design, complaint workflow, and policy review |
| 10 | KYC, AML, and GEL Payment-Rail Design | $500K | $120K | $150K | $70K | $120K | $40K | Covers KYC flow, wallet ledger, payment partner integration design, AML monitoring, and reconciliation process |
| 11 | MVP Market Listing Workflow and Contract Templates | $500K | $220K | $120K | $60K | $60K | $40K | Covers admin workflow, contract templates, user-facing explanation screens, and market approval tooling |
| 12 | AI-Assisted Event Risk Scoring Prototype | $500K | $180K | $130K | $40K | $110K | $40K | Covers event-risk model, source-confidence model, prohibited-topic classifier, review dashboard, and model monitoring |
| 13 | Open Banking Personalization and Consent Foundation | $1M | $300K | $250K | $100K | $300K | $50K | Covers consent layer, API/data architecture, personalization pilots, and privacy review |
| 14 | Controlled Prediction-Market Sandbox Pilot | $1M | $250K | $250K | $150K | $150K | $200K | Covers pilot operations, user cohort setup, reporting, support, training, and limited platform operations |
| 15 | Liquidity and Market-Maker Programme | $500K | $80K | $50K | $40K | $30K | $0 | $300K reserved for market-maker retainer, spread support, and liquidity incentives |
| 16 | AI Market Surveillance and Responsible-Use Scoring | $1M | $300K | $250K | $100K | $250K | $100K | Covers manipulation alerts, account-linkage logic, user-risk scoring, dashboards, and intervention workflows |
| 17 | Outcome Resolution and Regulator Reporting Automation | $500K | $120K | $100K | $100K | $150K | $30K | Covers resolution memos, official-result extraction, audit logs, dispute summaries, and reporting templates |
| 18 | SME Credit Scoring Alternative Data Pilot | $1M | $300K | $200K | $100K | $350K | $50K | Included as H2 data-platform use case; strengthens alternative-data and explainability capability |
| 19 | Unit Economics and Public Launch Gate | $100K | $30K | $10K | $30K | $10K | $20K | Covers final ROI model, legal update, board pack, go/no-go evidence, and external review |
| 20 | Public GEL-Settled Prediction-Market Launch Option | $5M+ | $1.5M+ | $1.5M+ | $500K+ | $1M+ | $500K+ | H3 only; requires board approval after sandbox evidence |
| 21 | VASP / USDC Fallback Option | $1M | $250K | $300K | $250K | $150K | $50K | H3 fallback if GEL route is blocked but crypto-native route is legally viable |
| 22 | AI-First Regulatory Compliance Automation | $1M+ | $250K+ | $250K+ | $250K+ | $200K+ | $50K+ | H3 option after platform reporting requirements are clearer |
| 23 | Advanced Market-Integrity and Account-Linkage Graph | $1M+ | $300K+ | $250K+ | $100K+ | $300K+ | $50K+ | H3 option for scaled manipulation detection and insider-risk monitoring |

---

## 7.7 H1 financial detail: months 1–6

H1 has two financial roles.

First, H1 creates near-term value through AI initiatives that can be deployed using current bank capabilities. Second, H1 builds the governance, data, legal, and payment foundations required before a prediction-market sandbox can safely begin.

### H1 budget by category

| Cost category | Estimated spend | What it buys |
|---|---:|---|
| People and project teams | $1.0M–$1.4M | Product managers, data scientists, engineers, compliance analysts, business owners, PMO support |
| AI / analytics tooling | $700K–$1.0M | Model development, monitoring tools, dashboards, workflow automation, chatbot / generative AI tooling |
| Data governance and infrastructure | $600K–$900K | Event-source registry, data pipelines, audit logs, feature store, API foundations |
| Legal and regulatory work | $250K–$400K | NBG pre-consultation, legal classification memo, responsible-use review, payment-risk review |
| KYC / AML and payment design | $300K–$500K | Wallet ledger design, onboarding flow, payment partner review, reconciliation design |
| Change management | $800K–$1.3M | Training, playbooks, communication, adoption tracking, operating-model workshops |
| Contingency | $150K–$300K | Rework buffer due to regulatory and payment uncertainty |
| **Total H1 estimate** | **$3.8M–$5.2M** | Foundation and readiness phase |

### H1 value creation

H1 should not be justified only by the prediction-market project. It also produces direct business value for the bank.

| H1 initiative | Financial value logic | Repository anchor |
|---|---|---|
| Loan A/R Collections Optimization | Preserves portfolio value by reducing roll-rate from early delinquency to later delinquency | Three Horizons / AI Opportunity Map |
| Payment Fraud Detection | Reduces fraud losses and strengthens payment-partner confidence before micro-stakes trading is introduced | AI Opportunity Map |
| Customer Service Automation | Reduces cost-to-serve and creates reusable support infrastructure for future prediction-market disputes and settlement questions | AI Opportunity Map |
| Wealth Management Robo-Advisory | Increases activation of low-balance brokerage users and builds education capability for later event-contract explanations | Three Horizons / AI Opportunity Map |

### H1 financial decision rule

H1 should proceed if it delivers at least one of the following:

- measurable reduction in operational risk,
- improved AI governance readiness,
- reusable data infrastructure,
- NBG engagement progress,
- payment-rail feasibility,
- or reduced cost of H2 implementation.

---

## 7.8 H2 financial detail: months 7–18

H2 is the main investment phase. It should be funded as a ring-fenced sandbox and platform-validation programme.

### H2 budget by category

| Cost category | Estimated spend | What it buys |
|---|---:|---|
| Controlled sandbox operations | $700K–$1.2M | Pilot cohort management, market operations, customer support, reporting, risk reviews |
| Liquidity and market-maker support | $500K–$800K | Market-maker retainer, spread support, seed liquidity, liquidity monitoring |
| AI surveillance and responsible-use scoring | $800K–$1.2M | Price-move alerts, account concentration, user-risk scoring, manipulation detection |
| Outcome resolution and reporting automation | $400K–$700K | Official result extraction, dispute memos, regulator-ready reporting, audit exports |
| Open banking and consent infrastructure | $800K–$1.2M | Consent management, governed APIs, customer data layer, personalization use cases |
| SME credit scoring pilot | $800K–$1.2M | Alternative data testing, explainability, credit-risk review, model validation |
| Legal, compliance, and governance run cost | $400K–$700K | Legal updates, regulator reporting, policy maintenance, risk committee support |
| Board gate and external review | $100K–$200K | Final ROI model, external review, board decision pack |
| **Total H2 estimate** | **$4.5M–$6.5M** | Sandbox and validation phase |

### H2 value creation

H2 should be judged on evidence, not only profit.

The prediction-market sandbox may be loss-making during months 7–18 because liquidity, compliance, legal, technology, and support costs arrive before meaningful trading scale.

H2 value comes from proving or disproving:

- whether NBG will accept a sandbox / pre-consultation route,
- whether payment partners will support the model,
- whether users understand and repeat-use event contracts,
- whether markets can stay liquid,
- whether disputes remain low,
- whether responsible-use controls work,
- and whether contribution margin can support a future launch.

### H2 success metrics with financial meaning

| Metric | Why it matters financially |
|---|---|
| CAC | Determines whether bank-backed distribution actually lowers acquisition cost |
| Payment processing cost | Determines whether micro-stakes trading can be profitable |
| Monthly active traders | Drives gross revenue |
| Monthly volume per user | Drives gross revenue and liquidity |
| Take rate / spread capture | Drives platform monetization |
| Market-maker subsidy | Major fixed cost before network effects |
| Dispute rate | Proxy for legal, support, and reputational cost |
| Responsible-use intervention rate | Measures social and regulatory risk |
| Contribution margin per user | Determines breakeven active users |

---

## 7.9 Prediction-market pilot budget detail

The controlled sandbox pilot is the financial center of the roadmap. It is where the strategic thesis becomes measurable.

### Sandbox pilot budget

| Cost item | Months 7–12 estimate | Detail |
|---|---:|---|
| Product and engineering support | $150K–$250K | MVP maintenance, bug fixes, admin workflow, trading interface improvements |
| Market operations team | $100K–$150K | Market listing, contract review, liquidity coordination, resolution operations |
| Compliance and legal run cost | $100K–$200K | NBG reporting, legal updates, AML/KYC review, responsible-use review |
| Customer support and dispute operations | $50K–$100K | Support tickets, dispute handling, settlement questions, education content |
| Liquidity subsidy / market-maker support | $250K–$400K | Retainers, spread support, seed liquidity, liquidity incentives |
| Data and reporting infrastructure | $100K–$150K | Audit logs, dashboards, resolution reports, regulator-ready exports |
| User education and controlled acquisition | $50K–$100K | Invite-only onboarding, learning modules, risk explanations |
| Contingency | $100K–$150K | Rework due to regulatory feedback, payment issues, contract redesign |
| **Total sandbox estimate** | **$900K–$1.45M** | Fits $1M roadmap budget with buffer depending on scope |

### Reconciliation to ROI model

The ROI model’s base-case fixed monthly cost is **GEL 150,000**. Over six months, this equals **GEL 900,000** of platform operating cost.

The sandbox budget above is broader because it includes:

- one-time setup,
- reporting infrastructure,
- legal review,
- customer education,
- controlled acquisition,
- contingency,
- and governance work.

Therefore, the sandbox budget and the ROI model are directionally consistent but not identical. The ROI model measures ongoing monthly economics; the roadmap budget measures a full programme phase.

---

## 7.10 H3 financial detail: post-18 months

H3 should not receive full capital commitment during the first 18 months.

H3 should remain an option until the month-18 board gate.

### H3 option budgets

| H3 option | Estimated capital | What it funds | Trigger condition |
|---|---:|---|---|
| Public GEL-settled launch | $5M–$10M+ | Full platform scaling, larger engineering team, expanded market operations, compliance, liquidity pool, user acquisition, market-integrity systems | NBG path confirmed, payment rails approved, unit economics credible |
| VASP / USDC fallback | $1M–$3M | Crypto-native architecture, VASP legal work, wallet / custody / settlement integration, narrower user acquisition | GEL route blocked but VASP route legally viable |
| AI-first compliance automation | $1M–$2M | Regulatory monitoring, filing-draft agents, compliance risk scoring, reporting automation | Reporting burden from H2 proves high and rules are stable enough to automate |
| Advanced market-integrity graph | $1M–$3M | Account-linkage graph, insider-risk detection, manipulation models, network analytics | Public launch scale requires stronger surveillance |

### H3 financial decision rule

Move from option to commitment only if all four gates pass:

| Gate | Required proof |
|---|---|
| Regulatory gate | NBG / legal path is feasible |
| Liquidity gate | Top markets maintain target spread and depth |
| Unit-economics gate | CAC, payment cost, trading volume, and contribution margin show credible breakeven path |
| Reputational gate | Responsible-use controls and dispute rates remain acceptable |

If one gate fails, the board should not approve the public GEL-settled launch.

---

## 7.11 Unit-economics gate at month 18

The public launch decision should be based on the same unit-economics logic used in the ROI model.

### Required unit-economics dashboard

| Metric | Conservative warning zone | Base-case target | Upside target |
|---|---:|---:|---:|
| Monthly active traders | Below 2,000 | 7,500–15,000 | 20,000+ |
| Monthly volume per user | Below GEL 100 | GEL 300 | GEL 700+ |
| Take rate / spread capture | Below 1% | 2% | 3% |
| Payment processing cost | Above 1.5% | 1% | 0.5% |
| CAC | Above GEL 150 | GEL 75 | GEL 30 |
| Monthly liquidity subsidy | Above GEL 100k without improving spreads | GEL 50k–100k | Efficiently supports narrow spreads |
| Contribution per user | Negative | Around GEL 3/month | GEL 17+/month |
| Breakeven active users | Not viable | Around 50,000 | Around 15,400 |

### Interpretation

The board should not approve public launch simply because users like the product. The product should only scale if:

- payment cost is low enough,
- CAC is low enough,
- user trading volume is high enough,
- liquidity subsidy is manageable,
- and contribution margin supports a credible breakeven path.

---

## 7.12 Funding source and approval model

### Funding source by phase

| Phase | Funding source | Approval level | Reason |
|---|---|---|---|
| H1 quick wins | Existing digital / AI transformation budget | Executive committee | Initiatives improve current operations and build AI readiness |
| H1 prediction-market foundation | Innovation / regulatory sandbox budget | Executive committee + Compliance approval | Needed to test feasibility before capital commitment |
| H2 sandbox and infrastructure | Ring-fenced transformation budget | Board approval | Requires cross-functional investment and regulatory exposure |
| H3 public launch | Strategic growth capital | Board approval | Creates new business category and reputational risk |
| H3 fallback route | Smaller option budget | Board / executive strategy approval | Activated only if preferred GEL route is blocked |

### Why ring-fencing matters

The prediction-market platform should not be evaluated with the same short-term ROI hurdle as normal banking products.

It should be ring-fenced because the first 18 months are designed to create:

- regulatory evidence,
- liquidity evidence,
- user behavior evidence,
- unit-economics evidence,
- market-integrity evidence,
- and payment-partner confidence.

Without ring-fencing, the project may be killed too early because pilot economics look weak before the platform reaches scale.

---

## 7.13 Financial risks and controls

| Financial risk | Where it appears | Control |
|---|---|---|
| H1 savings do not materialize | Collections, fraud, support automation | Require benefits tracking and monthly value dashboard |
| H2 cost overruns | Sandbox, data infrastructure, legal, liquidity | Stage-gate funding by month 6 and month 12 |
| Liquidity subsidy becomes permanent | Market-maker programme | Track subsidy per market and spread improvement monthly |
| CAC is higher than modeled | User acquisition | Require CAC evidence from pilot before public launch |
| Payment cost remains too high | PSP / bank rails | Collect at least two payment quotes in H1 and negotiate bank-embedded rails |
| Compliance cost rises with scale | Legal and reporting | Build reporting automation before public launch |
| H3 public launch approved too early | Board gate | Require unit-economics dashboard and stop/go criteria |
| VASP fallback consumes resources | H3 option | Fund only if GEL route is blocked and legal route is confirmed |

---

## 7.14 Financial narrative for the board

The board should read the roadmap as a staged investment, not a single product launch.

The first six months build the bank’s AI readiness and the minimum safe operating foundation. Months 7 to 18 test the prediction-market thesis under controlled conditions. Post-18-month investment should only be approved if the platform passes four gates: regulation, liquidity, responsible use, and unit economics.

The financial case is not that the platform is profitable immediately. The financial case is that a bank-backed structure may create a defensible category if it can reduce CAC, lower payment costs, and support liquidity before network effects form.

The board’s decision is therefore not:

> Should we launch a prediction-market app?

The better decision is:

> Should we buy an 18-month option to create a regulated event-market category in Georgia, with clear stop/go gates before full-scale capital commitment?

---

# 8. Change Management Initiative

Change management must begin before any AI deployment or sandbox launch.

| Element | Your entry |
|---|---|
| Initiative name | Change Management Programme |
| Horizon | H1 |
| Timeline | Months 1 to 18, ongoing |
| Owner function | Transformation Office / PMO, with support from Regulatory & Platform Governance |
| Budget estimate | 20 to 30% of total transformation cost |
| Dependency | None: begins before any AI deployment |
| Success metric | 90% of involved employees complete training; monthly adoption score above 75%; all high-risk operating-model changes have named owner and communication plan |

## Scope

The change programme covers:

- AI governance training,
- market-approval workflow training,
- responsible-use culture,
- regulatory communication process,
- dispute-handling playbooks,
- customer-support readiness,
- market-integrity escalation,
- board reporting cadence,
- and payment-partner communication.

## Why it matters

The platform requires a cultural shift. Teams must stop thinking of the product as a normal app and start treating it as a supervised marketplace.

---

# 9. Board Decision Gates

## Gate 1: Month 5 — Regulatory Feasibility

### Decision

Continue to MVP / sandbox preparation or stop.

### Required evidence

- legal classification memo,
- NBG feedback or meeting record,
- approved event taxonomy,
- responsible-use framework,
- first payment-rail feasibility review.

### Stop condition

Stop or redesign if legal counsel indicates event contracts are likely to be treated as gambling with no feasible sandbox route.

---

## Gate 2: Month 6 — Sandbox Readiness

### Decision

Approve controlled sandbox pilot.

### Required evidence

- market listing workflow,
- source registry,
- contract templates,
- AI risk scoring prototype,
- KYC / AML design,
- payment architecture,
- change-management readiness,
- responsible-use rules.

### Stop condition

Do not launch sandbox if markets cannot be resolved from official sources or if payment rails are not feasible.

---

## Gate 3: Month 12 — Pilot Quality

### Decision

Continue, expand, or pause sandbox.

### Required evidence

- active users,
- monthly trading volume,
- payment success rate,
- dispute rate,
- complaint rate,
- spread and liquidity performance,
- responsible-use interventions,
- market-integrity alerts.

### Stop condition

Pause expansion if dispute rate exceeds 1% of active traders per market, spreads remain above 8%, or responsible-use alerts indicate harmful behavior is not controlled.

---

## Gate 4: Month 18 — Public Launch Decision

### Decision

Choose one:

1. public GEL-settled launch,
2. extended sandbox,
3. VASP / USDC fallback route,
4. project stop.

### Required evidence

- final regulatory path,
- payment cost,
- CAC,
- active users,
- trading volume per user,
- contribution margin,
- liquidity subsidy requirement,
- compliance run cost,
- market-integrity incidents,
- board-approved risk appetite.

### Stop condition

Do not proceed to public launch if base-case breakeven path is not credible or if regulatory classification remains unresolved.

---

# 10. Roadmap Risk Controls

| Risk | Roadmap control | Owner |
|---|---|---|
| AI pilot cannot scale | Data governance and event-source registry before AI deployment | Data, AI & Market Integrity |
| Product classified as gambling | NBG pre-consultation before pilot | Regulatory & Platform Governance |
| Payment partners reject product | Payment-rail design and PSP quote pack in H1 | Payments, KYC & Settlement |
| Liquidity too weak | Market-maker programme before public launch | Market Operations & Liquidity |
| Outcome disputes damage trust | Official source registry and resolution memos | Resolution Committee / Data Governance |
| Users overtrade or suffer harm | Responsible-use controls before first trade | Responsible Use & Customer Trust |
| Roadmap becomes list of dates | Every initiative has owner, budget, dependency, metric | Transformation Office |
| Existing bank culture resists platform | Change management from month 1 | PMO |
| Public launch approved too early | Month 18 board gate requires regulatory, liquidity, and unit-economics evidence | Board / Executive Steering Committee |

---

# 11. Quality Check

- **Every initiative has all seven required elements.**  
  Yes.

- **H1 initiatives are deployable within 6 months with current capabilities.**  
  Yes. H1 initiatives either use existing bank infrastructure or build governance / data foundations.

- **Every H2 initiative has at least one named H1 dependency.**  
  Yes.

- **Change management appears as a named initiative with a budget estimate.**  
  Yes. It is Initiative 05 and runs from months 1 to 18.

- **Data governance appears in months 1 to 6 before any AI deployment initiative.**  
  Yes. Initiative 07 precedes event-risk scoring, surveillance, resolution automation, and H3 platform scale.

- **Every initiative has a named owner function.**  
  Yes.

- **The success metric for each initiative is measurable within the initiative timeline.**  
  Yes.

## One-sentence roadmap logic

> H1 generates AI readiness and operating discipline, H2 converts that foundation into a controlled sandbox with real evidence, and H3 scales only if regulation, liquidity, responsible use, and unit economics are proven.

---

# 12. References

Christensen, C. M. (1997). *The innovator’s dilemma: When new technologies cause great firms to fail*. Harvard Business School Press.

Rogers, D. L. (2023). *The digital transformation roadmap: Rebuild your organization for continuous change*. Columbia Business School Publishing.

National Bank of Georgia. (2025). *Financial Innovation Office*. https://www.nbg.gov.ge/en/pages/financial-innovation-office

National Bank of Georgia. (2025). *Financial Literacy Survey 2024*. https://www.nbg.gov.ge/uploads/pressreleases/2025/Financial_Literacy_Survey_2024.pdf

Georgian Foundation for Strategic and International Studies. (2024). *Georgia’s cryptocurrency regulation landscape*. https://www.gfsis.org.ge/publications/georgia-s-cryptocurrency-regulation-landscape

Georgian Stock Exchange. (2024). *Annual report 2024*. https://gse.ge/Uploads/2024%20Annual%20Report.pdf

TBC Bank. (2024). *TBC Capital individual brokerage services*. https://www.tbcbank.ge/en/corporate/tbc-capital/tbc-capital-individuals

CoinDesk. (2024, November 12). *Polymarket crypto prediction market hits $1B in monthly volume for first time*. https://www.coindesk.com/markets/2024/11/12/polymarket-crypto-prediction-market-hits-1b-in-monthly-volume-for-first-time/

Gaming Intelligence. (2024, July). *Georgia tightens gambling regulations further*. https://www.gamingintelligence.com/regulation/georgia-tightens-gambling-regulations-further/
