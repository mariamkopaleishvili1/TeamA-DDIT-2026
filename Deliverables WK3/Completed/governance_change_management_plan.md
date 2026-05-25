# Governance and Change Management Plan

## Project

Team A: Georgian Prediction-Market Platform  
Industry: Fintech  
Market: Republic of Georgia  
Recommended option: NBG sandbox-first, GEL-settled where possible, bank-backed, with responsible-use controls embedded from day one  
Submission file: `governance_change_management_plan.pdf`  
Working file: `governance_change_management_plan.md`

---

## 1. Purpose

This document sets out the governance and change management framework for the proposed Georgian prediction-market platform.

It supersedes earlier governance drafts. The scope is now limited to the prediction-market business model and the AI-enabled operating capabilities needed to launch it responsibly. It does not assess unrelated banking AI use cases such as loan collections, SME credit scoring, or generic robo-advisory.

The platform being evaluated is a bank-backed event-contract marketplace where users can take positions on clearly defined public outcomes. Early markets should be limited to verifiable categories such as inflation releases, GEL exchange-rate bands, NBG policy decisions, election turnout, and other official-data outcomes.

The core governance question is not whether the technology can be built. The core question is whether a Georgian fintech or bank-backed sponsor can operate the product in a way that is acceptable to regulators, payment partners, users, and the bank’s own risk appetite.

The answer depends on four controls:

1. a named oversight body with real decision rights;
2. a human override protocol for every high-risk AI use case;
3. clear Georgian personal data protection controls;
4. a funded change management workstream that makes the new operating model adoptable.

---

## 2. Governance Scope

The governance plan covers nine AI-enabled capabilities required for the prediction-market platform.

1. AI-assisted event eligibility screening
2. AI-assisted contract drafting and risk-disclosure generation
3. Market surveillance and manipulation detection
4. Responsible-use scoring and intervention routing
5. Payment, KYC, and fraud-risk monitoring for platform wallets
6. Outcome-resolution support
7. Dispute triage and user-support routing
8. Liquidity and market-maker monitoring
9. Regulatory and payment-partner reporting automation

These are not separate experiments. They form one control system. A weak event-screening process creates bad markets. Bad markets create disputes. Poor dispute handling damages trust. Weak surveillance invites manipulation. Weak responsible-use controls make the platform look like gambling. Weak reporting makes regulators and payment partners uncomfortable.

For that reason, governance must be designed before scale, not added after launch.

---

## 3. Governance Principles

The governance plan follows six practical principles.

### 3.1 AI supports decisions, but humans own them

During the sandbox phase, AI may screen, flag, draft, score, summarize, and route. It may not independently approve market listings, freeze accounts, resolve payouts, extend trading restrictions, or submit regulator-facing reports.

### 3.2 No official source, no market

A prediction-market platform can only be trusted if outcomes are resolvable. Every listed market must have a pre-approved official source, a publication time, a resolution rule, and a dispute process.

### 3.3 Responsible use is part of the product, not a side policy

Loss limits, deposit alerts, cooling-off periods, risk warnings, and appeal rights must be embedded before the first sandbox user trades. These controls are central to separating the platform from betting-style alternatives.

### 3.4 User-impacting decisions must be contestable

If an AI-supported process leads to a trading restriction, deposit limit, payment hold, account review, payout delay, or dispute outcome, the user must receive a meaningful notice and a route to human review.

### 3.5 Data use must be narrow and auditable

Trading, payment, KYC, dispute, and responsible-use data should be used only for defined platform purposes. Data collected for safety or compliance should not quietly become marketing data.

### 3.6 Public launch requires evidence, not optimism

The platform should not move from sandbox to public launch until the governance system has produced evidence: market approval logs, override logs, surveillance investigations, dispute outcomes, responsible-use interventions, payment hold reviews, and regulator-ready reports.

---

# 4. Oversight Body

## 4.1 Name

The oversight body should be called the:

**Prediction Market Governance and AI Risk Committee**

This is not a discussion forum. It is the decision-making body for high-risk market, AI, user protection, and regulatory issues.

## 4.2 Membership by function

The committee should include the following functions:

- Prediction Market General Manager, chair
- Compliance Lead or MLRO
- Legal Counsel
- Head of Data and AI
- Market Operations Lead
- Market Integrity Lead
- Responsible Use Lead
- Payments, KYC, and Settlement Lead
- Customer Trust Lead
- Information Security Lead
- Bank sponsor representative, if the platform is bank-backed
- Internal Audit observer, non-voting
- Board Risk Committee representative for launch-gate meetings

The composition matters. If only product and engineering are represented, the platform will move too quickly. If only compliance and legal are represented, the platform will not move at all. The committee must balance product viability with regulatory defensibility.

## 4.3 Decision rights

The committee has final decision rights over:

- approved and prohibited market categories;
- exceptions to the event taxonomy;
- launch of new market categories;
- AI model deployment into sandbox;
- AI model rollback;
- responsible-use thresholds;
- extended market pauses;
- severe market-integrity cases;
- disputed outcomes above threshold;
- regulator-facing incident reports;
- payment-partner reporting packs;
- recommendation to proceed, pause, pivot, or stop at board gates.

The committee should not approve routine operational cases. Routine cases should stay with the responsible owner. The committee should focus on decisions that change platform risk.

## 4.4 Review cadence

The committee cadence should change by phase.

During months 1 to 3, the committee meets monthly. The focus is policy design, event taxonomy, AI inventory, and NBG pre-consultation preparation.

During months 4 to 6, the committee meets every two weeks. The focus is sandbox readiness, contract templates, official-source registry, human override procedures, and user notices.

During the sandbox period, months 7 to 18, the committee meets every two weeks and holds emergency sessions within 24 hours for severe incidents.

Before public launch, the committee prepares a board pack with evidence on regulation, liquidity, responsible use, market integrity, payment operations, AI performance, and user complaints.

## 4.5 Escalation path if the committee cannot decide

If the committee cannot reach a decision, the escalation path depends on the type of issue.

For legal classification, NBG engagement, or gambling-risk concerns, the decision escalates to the Chief Compliance Officer, external legal counsel, and the Board Risk Committee.

For payment access, wallet controls, or AML issues, the decision escalates to the Chief Risk Officer delegate and the bank sponsor’s payments risk owner.

For user-harm concerns, responsible-use thresholds, or public reputation risk, the decision escalates to the Prediction Market General Manager and Board Risk Committee representative.

For technical model failure, drift, or incomplete audit logs, the decision escalates to the Head of Data and AI, Information Security Lead, and Internal Audit observer.

If the unresolved issue affects legality, payout accuracy, user funds, account restrictions, or regulator communication, the default decision is to pause the relevant workflow until the escalation is resolved.

---

# 5. EU AI Act Risk Classification

The EU AI Act is used here as a benchmark, not because Georgia is directly applying the EU AI Act in the same way as an EU member state, but because it gives a clear structure for classifying AI systems by user impact.

The platform should prohibit unacceptable-risk AI. It should not use social scoring, biometric surveillance, emotion recognition, vulnerability exploitation, political profiling, or automated manipulation of users’ weaknesses.

Most platform AI use cases are high risk because they may affect trading access, payment access, user restrictions, market integrity, payout timing, or regulator-facing evidence.

## 5.1 Risk classification summary

| AI use case | EU AI Act-style risk tier | Rationale |
|---|---|---|
| AI-assisted event eligibility screening | Limited if advisory; high if automatic approval is allowed | Screening is acceptable as decision support. It becomes high risk if it automatically approves or rejects markets, because market eligibility affects regulatory exposure and user access to products. |
| AI-assisted contract drafting and risk-disclosure generation | Limited if human-reviewed; high if binding text is published without review | AI-generated explanations can mislead users if wording is unclear, promotional, or inconsistent with the resolution rule. |
| Market surveillance and manipulation detection | High | Alerts can lead to account review, market pause, withdrawal hold, sanctions, or regulator escalation. |
| Responsible-use scoring and intervention routing | High | Scores can trigger deposit alerts, cooling-off periods, trading restrictions, or account review. |
| Payment, KYC, and fraud-risk monitoring | High | The system can block onboarding, hold deposits, delay withdrawals, or freeze wallet access. |
| Outcome-resolution support | High | AI-supported result extraction can affect payout timing and user trust. |
| Dispute triage and support routing | Limited if routing only; high if it closes or rejects disputes | Routing is lower risk, but automatic dispute rejection would affect user rights and payout outcomes. |
| Liquidity and market-maker monitoring | Limited if monitoring only; high if it automatically pauses markets or changes user-facing status | Monitoring spread and depth is low to moderate impact. Automatic market action creates higher risk. |
| Regulatory and payment-partner reporting automation | Limited if drafting only; high if submitted without sign-off | AI-drafted reports are acceptable with review. Automatic submission or legal classification would create material governance risk. |

---

# 6. Georgian Data Protection Law Obligations

The platform will process personal data in several ways: KYC, wallet transactions, deposits, withdrawals, trading activity, device signals, responsible-use behavior, complaints, disputes, and support communications.

The governance approach should apply the following obligations under Georgia’s personal data protection framework.

## 6.1 Purpose limitation

Each dataset must have a defined purpose. Trading data used for market surveillance should not automatically be reused for marketing. Responsible-use data should not be used to stimulate more trading.

## 6.2 Data minimization

The platform should collect only what is needed for KYC, payments, market integrity, responsible-use controls, resolution, dispute handling, and reporting. Optional personalization must be separated from mandatory safety controls.

## 6.3 Privacy by design and by default

Access to sensitive data should be restricted from the start. Market Operations should not see full KYC records. Customer Support should not see full surveillance scores unless required for a case. Reporting should use aggregated data unless user-level evidence is necessary.

## 6.4 Security of processing

KYC records, wallet ledgers, device signals, responsible-use histories, and account-linkage data require access control, encryption, audit logs, and incident response procedures.

## 6.5 Transparency and user rights

Users should be informed that the platform uses automated systems for market integrity, fraud prevention, responsible-use controls, outcome-resolution support, and support routing. If an AI-supported process affects access, payment, trading, payout, or dispute handling, the user must have a route to human review.

## 6.6 Auditability

Every high-impact decision should have a record of the input data, model output, human reviewer, final decision, user notice, and appeal outcome.

---

# 7. Human Override Protocols

This section is the operational core of the governance plan. Every high-risk use case has a measurable trigger, a named override authority, a documentation requirement, and a maximum review time.

## 7.1 Event eligibility screening

AI may support initial screening, but it may not list a market.

Human review is required if:

- event-risk score is above 30 out of 100;
- official-source confidence is below 95 percent;
- the event is outside the approved sandbox taxonomy;
- projected market exposure exceeds GEL 50,000;
- the event involves NBG, elections, sports, war, medical outcomes, crime, private individuals, or regulated financial institutions;
- more than one official source could produce a materially different result.

The override authority is the **Market Governance Committee**, with Compliance Lead sign-off for restricted categories.

The documentation requirement is an event approval memo, official-source record, risk score, final decision, and reason for any override.

The maximum review time is 48 hours for standard sandbox markets and five business days for new or restricted market categories.

## 7.2 Contract drafting and risk disclosure

AI may draft wording, but it may not publish binding contract text without review.

Human review is required if:

- AI confidence in contract wording is below 98 percent;
- Georgian and English versions differ in legal meaning;
- the market belongs to a new category;
- the wording could be read as investment advice, guaranteed income, or betting promotion;
- the payout rule depends on a delayed, revised, or multi-source official publication.

The override authority is the **Market Operations Lead**, with Compliance Lead approval for risk warnings and Resolution Committee approval for payout-rule clarity.

The documentation requirement is the AI draft version, final approved wording, reviewer name, change log, and risk-disclosure checklist.

The maximum review time is two business days for standard markets and five business days for new categories.

## 7.3 Market surveillance and manipulation detection

AI may flag suspicious behavior, but it may not impose final sanctions.

Human review is required if:

- market price moves more than 20 percentage points within 15 minutes without verified public news;
- one user or related-account cluster holds more than 25 percent of one side of a market;
- a market pause would last more than 30 minutes;
- withdrawal hold would last more than 30 minutes;
- more than GEL 1,000 of user funds is affected;
- account suspension is proposed;
- account-linkage confidence exceeds 80 percent and enforcement action is considered.

The override authority is the **Market Integrity Lead**. Severe cases require Compliance Lead review. Cases involving account suspension or regulator communication escalate to the Market Governance Committee.

The documentation requirement is the surveillance alert, investigation memo, evidence bundle, action taken, user notice if applicable, and reviewer sign-off.

The maximum review time is four hours for market-pause decisions, one business day for withdrawal holds, and three business days for account sanctions.

## 7.4 Responsible-use scoring and intervention routing

AI may identify risk patterns, but long restrictions require human review.

Human review is required if:

- user deposits more than GEL 500 within 24 hours during sandbox;
- user makes more than 20 trades in one hour;
- user hits the GEL 100 daily loss limit three times in seven days;
- restriction would last more than 48 hours;
- responsible-use score increases by more than 30 points in one day;
- user requests review of a cooling-off decision;
- user makes repeated rapid deposits after losses.

The override authority is the **Responsible Use Lead**. If the restriction is extended beyond 48 hours, Compliance Lead review is required.

The documentation requirement is the trigger log, user notice, human decision, appeal outcome if any, and responsible-use case note.

The maximum review time is 24 hours for deposit or trading-limit reviews and three business days for extended restrictions.

## 7.5 Payment, KYC, and fraud-risk monitoring

AI may trigger payment review, but it may not create prolonged holds without human review.

Human review is required if:

- payment hold exceeds 30 minutes;
- withdrawal hold exceeds 30 minutes;
- transaction value exceeds GEL 1,000;
- duplicate identity signal would block onboarding;
- the same user has two false-positive holds within 30 days;
- account freeze is proposed;
- AML escalation is considered.

The override authority is the **Fraud and KYC Lead**. AML-related cases escalate to the Compliance Lead.

The documentation requirement is the payment hold log, KYC review record, fraud alert, final action, user notice, and release or escalation decision.

The maximum review time is one business day for payment holds, three business days for account freezes, and immediate escalation for AML concerns.

## 7.6 Outcome-resolution support

AI may extract official results and draft a resolution memo, but it may not approve payouts.

Human review is required if:

- AI extraction confidence is below 98 percent;
- official result is delayed by more than 24 hours;
- official source revises the result within 48 hours;
- two approved sources conflict;
- more than 10 disputes are filed on one market;
- more than 1 percent of active traders in a market dispute the result;
- official source is unavailable more than two hours after expected publication.

The override authority is the **Resolution Committee Chair**. Material disputes escalate to the Market Governance Committee.

The documentation requirement is the official-source evidence, resolution memo, payout approval record, dispute log, and user notification record.

The maximum review time is 24 hours for normal resolution exceptions and five business days for material disputes.

## 7.7 Dispute triage and support routing

AI may route cases, but it may not close material disputes.

Human review is required if:

- user mentions payout dispute;
- user mentions fraud, account freeze, withdrawal hold, legal complaint, self-exclusion, gambling harm, addiction, or financial distress;
- ticket involves more than GEL 100;
- complaint remains unresolved after 24 hours;
- user files more than three complaints in 30 days;
- AI routing confidence is below 90 percent.

The override authority is the **Customer Trust Lead**. Payout cases go to the Resolution Committee. Responsible-use cases go to the Responsible Use Lead.

The documentation requirement is the support ticket, routing label, escalation record, human response, and closure reason.

The maximum review time is 24 hours for standard escalations, one business day for payment and restriction disputes, and five business days for payout disputes.

## 7.8 Liquidity and market-maker monitoring

AI may monitor liquidity, but it may not remove market warnings or alter market status without review.

Human review is required if:

- bid-ask spread exceeds 8 percent for more than 30 minutes;
- order-book depth falls below GEL 10,000 on either side for a top-20 market;
- market-maker misses quote obligations for three monitoring intervals;
- internal liquidity provision exceeds 20 percent of open interest;
- user execution complaints exceed five cases in 24 hours;
- a market-quality warning would be removed after a breach.

The override authority is the **Market Operations and Liquidity Lead**. Cases involving internal liquidity conflict or material user harm escalate to the Market Governance Committee.

The documentation requirement is the liquidity dashboard extract, breach log, market-maker scorecard, action taken, and subsidy review note.

The maximum review time is four hours for top-market liquidity breaches and two business days for market-maker performance reviews.

## 7.9 Regulatory and payment-partner reporting automation

AI may draft reports, but it may not send external reports.

Human review is required for:

- 100 percent of NBG-facing reports;
- 100 percent of payment-partner reports;
- any serious incident report;
- any legal classification update;
- any report including user-identifiable data;
- any change to compliance controls;
- any report with incomplete source data.

The override authority is the **Regulatory and Platform Governance Lead**, with Compliance Lead sign-off for external submissions.

The documentation requirement is the AI-generated draft, source log, redaction checklist, reviewer comments, final signed version, and submission register.

The maximum review time is three business days for routine monthly reports and 24 hours for serious incident reports.

---

# 8. Responsible AI Principles for H1 Platform Use Cases

The H1 platform use cases are those that must be designed before sandbox trading begins. They are event eligibility screening, contract drafting, payment and KYC design, responsible-use framework, and reporting readiness.

## 8.1 Event eligibility screening

The bias and fairness risk is category bias. The AI may treat globally popular prediction-market categories as acceptable even when they are not appropriate for a Georgian bank-backed platform. It may also over-reject Georgian civic events because they look politically sensitive.

The transparency obligation is to disclose the official source, resolution rule, market category, risk warning, and dispute process on each listed market. Internal AI scores do not need to be shown to users.

The accountability structure is clear: Market Operations prepares the market, Compliance reviews the legal and regulatory risk, and the Market Governance Committee approves listing.

If an adverse outcome occurs, such as a disputed or inappropriate market being listed, accountability sits with the Market Governance Committee because AI is only a screening tool.

## 8.2 Contract drafting and risk disclosure

The bias and fairness risk is comprehension inequality. A contract can be formally correct but still not understandable for entry-level users. This matters because the business model is based on intuitive event contracts.

The transparency obligation is to make every user-facing market page clear about what the user is trading, what the downside is, when the result is determined, what source controls the result, and how disputes work.

The accountable owner is the Market Operations Lead for contract wording, Compliance Lead for risk warnings, and Resolution Committee Chair for payout-rule clarity.

If a user is misled by unclear market wording, the issue escalates to Customer Trust, then Market Operations, then the Market Governance Committee if the wording affected multiple users.

## 8.3 Responsible-use framework

The bias and fairness risk is both over-protection and under-protection. A strict system may over-restrict active but healthy users. A weak system may fail users who show harmful trading patterns.

The transparency obligation is high. Before trading, users must see the sandbox limits and know what actions can trigger a cooling-off period, deposit review, or trading restriction.

The accountable owner is the Responsible Use Lead. The Compliance Lead reviews whether the system is strong enough for regulator and payment-partner expectations.

If a user is incorrectly restricted, the appeal goes to the Responsible Use Lead. If multiple similar appeals occur, the model and thresholds go to the Market Governance Committee.

## 8.4 Payment, KYC, and fraud-risk monitoring

The bias and fairness risk is false-positive exclusion. Users with shared devices, irregular payment patterns, or external payment rails may be flagged more often than existing bank customers.

The transparency obligation is limited because fraud rules cannot be fully disclosed. Still, users must be informed when a payment, withdrawal, or onboarding flow is delayed due to security review.

The accountable owner is the Fraud and KYC Lead. AML-sensitive cases escalate to Compliance.

If a user is wrongly blocked or a withdrawal is wrongly delayed, the case must be logged as a false positive and included in monthly model review.

## 8.5 Reporting readiness

The bias and fairness risk is selective reporting. A report generator may summarize favorable metrics and understate disputes, user complaints, or intervention frequency if the input structure is weak.

The transparency obligation is internal and external. Internal reviewers must know which parts of a report were AI-generated. External reports to NBG or payment partners must be human-reviewed and signed.

The accountable owner is the Regulatory and Platform Governance Lead. Compliance has final sign-off before any report leaves the organization.

If an inaccurate report is produced, the issue escalates to Compliance, the Market Governance Committee, and the Board Risk Committee if the report was already sent externally.

---

# 9. Change Management Workstream

## 9.1 Definition

Change management is a named workstream of the transformation. It is not a risk mitigation note.

The workstream exists because the platform changes how the organization makes decisions. A prediction-market product cannot be governed like a standard mobile app. It requires new habits around market approval, source validation, AI review, user protection, dispute resolution, market surveillance, liquidity monitoring, and regulator reporting.

The workstream should be called:

**Prediction Market Change Management Workstream**

## 9.2 Owner function

The owner should be the **Transformation Office or PMO**, with joint sponsorship from the Prediction Market General Manager and Compliance Lead.

The PMO owns execution discipline. The General Manager owns adoption inside product and operations. The Compliance Lead ensures that adoption does not weaken controls.

## 9.3 Budget

Change management budget should be **20 to 30 percent of the first 18-month transformation investment**.

For planning, the prediction-market-specific first 18-month transformation investment is **GEL 15.93 million**. This includes the H1 foundation and H2 sandbox-validation period before full public launch.

The resulting change management range is:

- 20 percent: **GEL 3.19 million**
- 25 percent: **GEL 3.98 million**
- 30 percent: **GEL 4.78 million**

The recommended planning figure is **GEL 4.0 million**, equal to approximately 25 percent of the first 18-month transformation investment.

This budget should be treated as a dedicated workstream budget. It is not a communications reserve and not a general contingency line. The platform changes how the organization approves markets, reviews AI alerts, handles user restrictions, validates official sources, resolves outcomes, reports to regulators, and decides whether the product can scale. Those changes require structured adoption work.

### Budget breakdown

| Budget category | GEL amount | What it funds | Main owner |
|---|---:|---|---|
| PMO and change leadership | GEL 550k | Change lead, PMO support, workstream planning, dependency tracking, adoption dashboard, board-gate preparation | Transformation Office / PMO |
| Stakeholder analysis and process redesign | GEL 350k | Role-impact mapping, decision-rights mapping, process redesign workshops, RACI documentation, handoff design across Product, Compliance, Legal, Market Operations, Payments, Data, and Customer Trust | PMO with Prediction Market General Manager |
| Role-based training and certification | GEL 750k | Training modules, staff certification, market-approval training, AI override training, responsible-use training, dispute-handling training, payment-hold training, and onboarding for new team members | PMO with functional leads |
| Tabletop exercises and sandbox rehearsals | GEL 450k | Simulations for disputed outcomes, suspicious trading, payment holds, account freezes, responsible-use restrictions, market pauses, and regulator incident reporting | Compliance Lead, Market Integrity Lead, Customer Trust Lead |
| Communication plan and leadership alignment | GEL 300k | Internal communication, leadership briefings, employee FAQs, bank-sponsor materials, payment-partner narrative, and board-readiness materials | Prediction Market General Manager and PMO |
| Customer Trust and support readiness | GEL 450k | Georgian and English support scripts, adverse-action notice templates, escalation playbooks, appeal-handling process, complaint taxonomy, and quality review | Customer Trust Lead |
| Compliance, legal, and governance adoption | GEL 500k | Committee operating routines, approval-pack templates, compliance review workflow, legal decision log, controlled market approval process, and regulator-ready documentation habits | Compliance Lead and Legal Counsel |
| Data, AI, and audit-log adoption | GEL 400k | Training and process adoption for AI model register, human override log, event source registry, resolution evidence archive, surveillance alert logs, and data-access controls | Head of Data and AI |
| Adoption measurement and post-launch reinforcement | GEL 250k | Monthly adoption reporting, training refreshers, workflow-compliance reviews, resistance log, lessons learned, and month-18 change readiness assessment | PMO |
| **Total recommended change-management budget** | **GEL 4.0M** |  |  |

### What will change because of this budget

The change-management budget funds concrete operating changes, not general awareness.

**Market Operations will change from content preparation to controlled market approval.**  
The team will no longer treat event pages as normal product content. Each market must have an official source, payout rule, risk disclosure, dispute path, and approval record. The change budget funds templates, training, review checklists, and process rehearsals.

**Compliance and Legal will change from late-stage reviewers to embedded decision owners.**  
Compliance cannot be asked to approve a legally ambiguous product at the end of the process. The budget funds early involvement in market taxonomy, event-category rules, legal classification logs, approval-pack design, and escalation routines.

**Product and Engineering will change from feature delivery to controlled workflow delivery.**  
The product team must build around auditability, source validation, user notices, human override logs, and responsible-use controls. The budget funds the adoption work needed so that product requirements reflect governance requirements before sandbox launch.

**Customer Trust will change from normal support handling to regulated dispute and appeal handling.**  
Support agents must distinguish ordinary technical issues from payout disputes, payment holds, market-resolution complaints, account restrictions, and responsible-use appeals. The budget funds scripts, escalation trees, bilingual notices, quality review, and case-handling training.

**Data and AI teams will change from model development to model accountability.**  
AI systems cannot only produce alerts or scores. Each high-impact AI output needs a record of input data, model output, human reviewer, final decision, reason code, and user notice where applicable. The budget funds training and adoption around the AI model register, human override log, and model monitoring routines.

**Payments, KYC, and Fraud teams will change from standard onboarding controls to platform-specific wallet and trading controls.**  
Prediction-market users may deposit, withdraw, trade frequently, recycle balances, and trigger account-linkage or payment-risk alerts. The budget funds new review procedures for payment holds, duplicate-identity signals, suspicious wallet activity, and withdrawal delays.

**Senior leadership will change from project sponsorship to stage-gate decision-making.**  
The board and executive sponsors must not approve public launch based only on technical readiness. They need evidence on regulatory comfort, market quality, liquidity, user harm, dispute rates, payment reliability, and unit economics. The budget funds board-pack preparation and adoption measurement.

### Required change-management outputs

The GEL 4.0M budget should produce the following artifacts:

- stakeholder impact map;
- decision-rights map;
- RACI for market approval, market pause, outcome resolution, payment holds, user restrictions, and regulator reporting;
- role-based training materials;
- staff certification records;
- market approval checklist;
- event source validation checklist;
- adverse-action notice templates;
- user appeal playbook;
- support escalation scripts in Georgian and English;
- human override log procedure;
- AI model register adoption guide;
- tabletop exercise results;
- sandbox readiness pack;
- monthly adoption dashboard;
- resistance log;
- month-18 change readiness assessment for the board.

### Budget release logic

The change budget should be released in phases rather than spent upfront.

| Phase | Timing | Budget release | Purpose |
|---|---:|---:|---|
| Phase 1: Governance setup and stakeholder alignment | Months 1 to 3 | GEL 900k | Establish decision rights, committee routines, stakeholder map, and early training |
| Phase 2: Process adoption and sandbox readiness | Months 4 to 6 | GEL 1.20M | Train teams, build templates, run tabletop exercises, and prepare sandbox workflows |
| Phase 3: Live sandbox adoption | Months 7 to 12 | GEL 1.10M | Support live adoption, monitor workflow compliance, correct process failures, and refresh training |
| Phase 4: Scale readiness and institutionalization | Months 13 to 18 | GEL 800k | Prepare board decision materials, institutionalize routines, and assess readiness for public launch |
| **Total** | **Months 1 to 18** | **GEL 4.0M** |  |

### Adoption metrics tied to the budget

The change-management workstream should be judged through operational evidence.

| Metric | Target |
|---|---:|
| Impacted staff completing role-specific training before sandbox | 90 percent or higher |
| High-risk workflows with named owner, threshold, and documentation template before user onboarding | 100 percent |
| Market approval files with complete source, payout rule, risk warning, and approval record | 95 percent or higher |
| High-risk AI alerts reviewed within SLA during sandbox | 95 percent or higher |
| Adverse user actions with documented reason code and owner | 100 percent |
| Sensitive support cases routed correctly on first review | 90 percent or higher |
| Tabletop exercises completed before sandbox launch | At least 4 |
| Monthly adoption reports delivered to the governance committee | 100 percent on time |
| Unresolved process failures older than two review cycles | 0 |

### Why this budget is necessary

A prediction-market platform fails if the organization treats it like a normal app launch. The product requires new decision habits across market approval, source validation, user protection, dispute handling, market surveillance, payment review, outcome resolution, and regulator reporting.

The GEL 4.0M change-management budget is therefore a control investment. It reduces the risk that the platform is technically built but operationally ungovernable. It also gives the board evidence that the organization can follow the operating model before approving public launch.

## 9.4 Why the budget is justified

The platform’s failure risk is not only technical. It is organizational.

Without a funded change workstream:

- product teams may push market launches before controls are ready;
- compliance may slow down decisions because accountability is unclear;
- support teams may mishandle payout or restriction disputes;
- market operations may treat contract templates as content rather than control documents;
- data teams may build models without enough auditability;
- executives may approve scale before evidence is strong enough.

The change budget is therefore not soft spending. It funds the adoption of the operating model.

---

# 10. Change Management Timeline

## Phase 1: Governance setup and stakeholder alignment, months 1 to 3

The first phase establishes ownership and reduces resistance before technical build accelerates.

Key activities:

- identify affected stakeholder groups;
- map decision rights across Product, Compliance, Legal, Data, Market Operations, Payments, Customer Trust, and Risk;
- confirm the Market Governance Committee membership;
- create the first version of the event taxonomy;
- define human override roles;
- prepare the communication narrative for bank leadership and payment partners;
- train core team members on why the product is a supervised marketplace, not a standard app.

The main deliverable is a signed governance charter and stakeholder map.

The success metric is that all named committee members accept their decision rights and escalation responsibilities by the end of month 3.

## Phase 2: Process adoption and sandbox readiness, months 4 to 6

The second phase turns governance rules into working practices.

Key activities:

- train Market Operations on contract templates and source validation;
- train Compliance and Legal on the market approval workflow;
- train Customer Trust on adverse action notices and appeal handling;
- run tabletop exercises for market disputes, payout delays, suspicious trading alerts, and payment holds;
- test human override logs;
- prepare support scripts in Georgian and English;
- create readiness dashboards for board gate review.

The main deliverable is a sandbox readiness pack.

The success metric is that 100 percent of sandbox workflows have named owners, review thresholds, and documentation templates before user onboarding.

## Phase 3: Live sandbox adoption, months 7 to 12

The third phase tests whether the organization actually follows the model under real user conditions.

Key activities:

- run weekly issue reviews for the first eight weeks of sandbox;
- measure support escalation accuracy;
- track override decisions and false positives;
- review responsible-use interventions;
- monitor market approval cycle time;
- collect feedback from compliance, operations, support, and users;
- adjust training where teams misunderstand procedures.

The main deliverable is a monthly adoption and control report.

The success metric is that at least 95 percent of high-risk AI alerts are reviewed within SLA and 100 percent of adverse user actions have a documented reason.

## Phase 4: Scale readiness and institutionalization, months 13 to 18

The final phase prepares the organization for the month-18 public launch decision.

Key activities:

- review whether decision rights worked in practice;
- update policies based on sandbox evidence;
- refresh training for new team members;
- prepare board materials;
- document control failures and fixes;
- assess whether additional hiring is required for public launch;
- finalize the scale or stop recommendation.

The main deliverable is a change readiness assessment for the board.

The success metric is that the board receives evidence on adoption, control quality, user complaints, override rates, and unresolved organizational risks before deciding on public launch.

---

# 11. Stakeholder Resistance

The role most likely to resist is the **Compliance Lead or MLRO assigned to the prediction-market pilot**.

The source of resistance is specific. The Compliance Lead may become accountable for a legally ambiguous product where the upside belongs to product and innovation teams, but the downside of NBG concern, gambling classification, payment-partner rejection, user harm, or media criticism falls heavily on compliance.

This is rational resistance. The correct response is not to ask Compliance to be less conservative. The operating model should give Compliance formal authority, clear decision rights, better evidence, and recognition for enabling controlled experimentation.

The incentive metric must change.

Old metric: zero regulatory breaches and minimum compliance exceptions.

New metric: **Controlled Market Approval Quality Rate**

Definition:

```text
Controlled Market Approval Quality Rate =
number of listed sandbox markets with complete approval pack, source registry match, responsible-use controls, and audit trail
divided by
total listed sandbox markets
```

Target: 95 percent or higher during sandbox.

Measurement frequency: monthly during sandbox and at every board gate.

Measured by: Market Governance Committee, with Chief Compliance Officer sign-off.

Compensation link: a portion of performance evaluation should recognize safe innovation enablement, not only incident avoidance. This includes timely reviews, complete approval packs, on-time NBG reporting, and zero unresolved high-risk exceptions.

---

# 12. Adoption Measurement

The change management workstream should track adoption through operational evidence, not surveys alone.

The first metric is workflow compliance. At least 95 percent of market approvals, AI alerts, responsible-use interventions, payout exceptions, and payment holds should have complete documentation.

The second metric is review timeliness. At least 95 percent of high-risk AI alerts should be reviewed within their SLA.

The third metric is training completion. At least 90 percent of affected staff should complete role-specific training before sandbox launch.

The fourth metric is override quality. 100 percent of overrides should include a reason code, reviewer name, timestamp, and final action.

The fifth metric is support accuracy. At least 90 percent of sensitive support cases should be routed correctly on first review.

The sixth metric is unresolved resistance. The PMO should maintain a resistance log. Any issue that remains unresolved for more than two review cycles should be escalated to the Prediction Market General Manager.

---

# 13. Board-Level Governance Gates

## Gate 1: Regulatory feasibility

Timing: month 5

The board or executive steering group should review legal classification, NBG feedback, event taxonomy, responsible-use framework, and payment-rail feasibility.

If event contracts appear likely to be treated as gambling with no feasible sandbox path, the platform should stop or be redesigned.

## Gate 2: Sandbox readiness

Timing: month 6

The board should review contract templates, source registry, AI risk scoring prototype, KYC and payment workflow, human override protocol, adverse action notice system, and change readiness.

If official-source resolution or payment controls are not ready, sandbox should not launch.

## Gate 3: Pilot quality

Timing: month 12

The board should review active users, disputes, market quality, user complaints, responsible-use interventions, payment holds, surveillance alerts, and model performance.

If disputes exceed tolerance, liquidity is too weak, or user-harm signals are not controlled, the platform should not expand.

## Gate 4: Public launch decision

Timing: month 18

The board should decide whether to launch publicly, extend sandbox, pivot to fallback route, or stop.

The launch decision should require regulatory comfort, payment-partner acceptance, reliable outcome resolution, low dispute rate, acceptable responsible-use evidence, manageable liquidity subsidy, and credible unit economics.

The board pack should explicitly include:

- total investment to recover;
- Year 1 capital requirement, including GEL 7.40M CapEx and GEL 4.60M OpEx;
- annual benefit;
- payback period;
- IRR;
- 5-year NPV at 18 percent discount rate;
- severe downside stress test; and
- sensitivity analysis for adoption and turnover per active user.

---

# 14. Final Governance Position

The governance model should make one thing clear: the platform is not ready for public launch just because the app works.

It is ready only if the organization can prove that markets are approved carefully, users are protected, suspicious trading is investigated, payments are controlled, outcomes are resolved fairly, disputes are contestable, reports are accurate, and AI-supported decisions remain under human accountability.

The platform can use AI, but the bank cannot delegate judgment to AI.

During sandbox, AI should assist. Humans should decide. The audit trail should prove it.

---

# 15. References

European Commission. (2026). AI Act. Shaping Europe’s Digital Future. https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai

European Union. (2024). Regulation (EU) 2024/1689 laying down harmonised rules on artificial intelligence.

Personal Data Protection Service of Georgia. (2024). Current Law of Georgia on Personal Data Protection. https://pdps.ge/content/1063/LAWS

Personal Data Protection Service of Georgia. (2024). Guide for business, Part III: Compliance assurance. https://pdps.ge/content/1085/nawili-III.-kanonSesabamisobis-uzrunvelyofa

Personal Data Protection Service of Georgia. (2024). Guide for business, Part IV: Personal data security. https://pdps.ge/content/1086/nawili-IV.-personalur-monacemTa-usafrTxoebis-dacva

Organisation for Economic Co-operation and Development. (2019). OECD principles on artificial intelligence.

Westerman, G., Bonnet, D., & McAfee, A. (2014). Leading digital: Turning technology into business transformation. Harvard Business Review Press.
