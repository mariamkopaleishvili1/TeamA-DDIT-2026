# Responsible AI Assessment

## Project

Team A: Georgian Prediction-Market Platform  
Industry: Fintech  
Market: Republic of Georgia  
Recommended strategic option: TBC-owned, GEL-settled, mobile-banking-integrated prediction-market platform under an NBG special-designation or sandbox-first route, with responsible-use controls embedded from day one.  
Submission file: `responsible_ai_assessment.pdf`  
Working file: `responsible_ai_assessment.md`

---

## 1. Purpose

This document applies the EU AI Act risk framework and Responsible AI principles to the AI use cases required for a Georgian prediction-market platform.

The scope is deliberately narrow. This is not a general bank AI assessment. It does not assess loan collections, SME credit scoring, generic banking chatbots, or unrelated bank automation. The only AI systems assessed here are those needed to launch, operate, monitor, and govern a bank-backed event-contract marketplace in Georgia.

The platform’s strategic idea is simple but sensitive: users take positions on clearly defined public outcomes, such as inflation releases, exchange-rate bands, central-bank decisions, election turnout, or other official-data events. The product can only be credible if regulators, payment partners, bank leadership, and users believe that markets are listed carefully, monitored fairly, resolved transparently, and controlled for harm.

Responsible AI is therefore not an add-on. It is part of the operating license of the platform.

---

## 2. Scope of AI Use Cases

The assessment covers nine AI use cases that are directly tied to the prediction-market platform:

1. AI-assisted event eligibility screening
2. AI-assisted contract drafting and risk-disclosure generation
3. Market surveillance and manipulation detection
4. Responsible-use scoring and intervention routing
5. Payment, KYC, and fraud-risk monitoring for platform wallets
6. Outcome-resolution support
7. Dispute triage and user-support routing
8. Liquidity and market-maker monitoring
9. Regulatory and payment-partner reporting automation

These use cases should be treated as one connected control system. A failure in one area can create failures elsewhere. For example, a poorly screened market can create outcome disputes. Weak surveillance can create manipulation risk. Poor responsible-use scoring can make the product look like gambling. Weak reporting can reduce regulator or payment-partner confidence.

The assessment is written as a practical consulting deliverable. It identifies the risk tier, bias risk, transparency obligation, accountability structure, Georgian personal-data obligation, and human override threshold for each use case.

---

## 3. Assessment Method

The EU AI Act is used as the risk-classification benchmark. The Act defines four broad levels of AI risk: unacceptable, high, limited or transparency risk, and minimal risk. High-risk AI systems are subject to stronger obligations, including risk assessment, high-quality data, logging, documentation, clear information to deployers, human oversight, robustness, cybersecurity, and accuracy.

The Georgian legal lens is based on the Law of Georgia on Personal Data Protection and guidance from the Personal Data Protection Service. For this platform, the most relevant obligations are:

- process personal data only for a defined and lawful purpose;
- collect only the data needed for that purpose;
- design the product so that privacy protections are built in by default;
- limit access to sensitive user, payment, and trading data;
- protect data through technical and organizational security controls;
- keep evidence of how data was used in high-impact decisions;
- inform users when their data is used in a way that affects access, restrictions, payout review, or dispute handling.

This is not a legal opinion. The legal classification of event contracts and the final interpretation of Georgian personal-data obligations should be validated by Georgian counsel before launch.

---

## 4. Portfolio-Level Risk View

The platform should not use any unacceptable-risk AI. In practical terms, this means the platform should not use social scoring, biometric surveillance, emotion detection, political profiling, or vulnerability exploitation to segment users.

Most of the platform’s important AI systems should be governed as high-risk, even if they are technically used for decision support rather than autonomous decision-making. The reason is that the platform operates in a sensitive financial context. AI outputs may affect user access, account review, market pauses, payout timing, or regulatory reporting.

The platform’s lower-risk AI use cases are limited to explanation, routing, and content generation. Even there, users need disclosure when they are interacting with AI or receiving AI-generated market explanations.

The highest-risk AI systems are:

- market surveillance;
- responsible-use scoring;
- payment and fraud-risk monitoring;
- outcome-resolution support;
- account-linkage analysis;
- regulator and payment-partner reporting automation, if reports are sent without human sign-off.

These systems should never take final adverse action without human accountability during the sandbox phase.

---

## 5. AI Use Case Assessments

### 5.1 AI-Assisted Event Eligibility Screening

This model screens proposed markets before listing. It checks whether an event belongs to an approved category, whether it has an official source, whether it resembles gambling, whether it is politically or socially sensitive, and whether it can be resolved cleanly.

The risk tier should be treated as **limited risk** if the model only supports human review. It becomes **high risk** if it can automatically approve or reject markets. For the sandbox phase, the model must remain advisory. The final listing decision should stay with the Market Governance Committee.

The main fairness risk is not traditional demographic discrimination. The larger risk is category bias. The model may over-reject Georgian civic or political events because they appear sensitive, while under-rejecting imported event formats copied from global prediction-market platforms. It may also treat sports, war, crime, celebrity, or medical outcomes as acceptable because they exist on global platforms, even though these categories would be inappropriate for the Georgian bank-backed launch.

The mitigation is a Georgian-specific event taxonomy. Approved categories should be narrow at first: inflation releases, NBG policy decisions, GEL exchange-rate bands, election turnout, and other official-data public outcomes. Restricted categories should include sports, individual criminal cases, war outcomes, medical outcomes, private-person events, ambiguous political claims, and anything without an official source.

Users do not need to see the internal AI risk score. However, every listed market should disclose why the contract is resolvable. The market page should show the official source, resolution date, payout rule, dispute window, and a plain-language risk warning.

The accountable owner is the **Market Governance Committee**. Compliance owns the legal classification check. Market Operations owns contract readiness. The escalation path should be: AI screening output, Market Operations review, Compliance review, Market Governance Committee decision.

The Georgian personal-data obligation is limited unless personal user behavior is used to decide which markets to list. If user search, watchlist, or trading-interest data is used for event selection, the platform must apply purpose limitation, data minimization, and privacy-by-design controls.

Human review is required when any of the following thresholds are met:

- event-risk score above 30 out of 100;
- official-source confidence below 95%;
- proposed market is outside the approved sandbox taxonomy;
- projected exposure above GEL 50,000 during sandbox;
- event involves NBG, elections, regulated financial institutions, war, medical outcomes, crime, sports, or private individuals;
- more than one official source could produce different results.

The control artifacts are the event-risk score log, official-source record, approval memo, and human override log.

---

### 5.2 AI-Assisted Contract Drafting and Risk-Disclosure Generation

This system drafts the first version of the market question, contract description, payout rule, risk warning, and user explanation. It helps users understand what they are trading, but it should not define the legally binding contract without review.

The risk tier is **limited risk** if the system only drafts text for human approval. It becomes **high risk** if the AI-generated wording becomes the binding market contract without human review. During sandbox, all generated wording must be reviewed by Market Operations and Compliance.

The fairness risk is comprehension inequality. Users with lower financial literacy may misunderstand probabilistic pricing, fixed downside, settlement rules, or market cancellation conditions. Georgian-language wording may also lose precision if it is translated from English. A vague or overly promotional explanation can make the product look safer than it is.

The mitigation is a plain-language review process. Each contract should be tested for clarity in Georgian and English. The contract should separate three things: the user-friendly explanation, the legally controlling resolution rule, and the responsible-use warning. The explanation should never suggest that the platform is investment advice or guaranteed income.

The transparency obligation is direct. If market explanations are AI-assisted, internal reviewers should know that. Users do not necessarily need a label on every sentence, but the platform should disclose in its terms and market information policy that AI may assist in preparing explanations that are reviewed before publication.

The accountable owner is the **Head of Market Operations**. Compliance signs off on risk warnings. The Resolution Committee signs off on the clarity of payout and dispute terms.

The Georgian personal-data obligation is low for generic contract drafting. It becomes relevant if the model personalizes explanations based on user behavior, financial profile, or open-banking data. In that case, the platform needs purpose limitation, data minimization, and user notice.

Human review is required when:

- contract text confidence is below 98%;
- the contract is in a new market category;
- the Georgian and English versions differ in legal meaning;
- the payout rule depends on a revised or delayed official data source;
- the explanation mentions expected profit, investment advice, guaranteed outcome, or language similar to betting promotion;
- the contract would be shown to sandbox users for the first time.

The control artifacts are the contract template library, AI-draft version history, compliance sign-off record, and plain-language review checklist.

---

### 5.3 Market Surveillance and Manipulation Detection

This system monitors trading activity to detect manipulation, suspicious timing, abnormal price movement, concentrated positions, coordinated accounts, and potential insider-informed trading.

The risk tier is **high risk**. Even if the model is used to protect the market, its outputs may trigger market pauses, account reviews, withdrawal holds, or regulatory escalation. These are adverse or high-impact decisions.

The main fairness risk is over-enforcement against active but legitimate users. A user who trades frequently, uses shared Wi-Fi, trades during unusual hours, or has a crypto-native trading pattern may look suspicious even when their behavior is lawful. Shared devices in families, universities, or workplaces can also create false account-linkage signals.

The mitigation is multi-signal review. No enforcement action should rely on a single signal such as IP address, device match, or trade frequency. The platform should require a combination of behavior, timing, order pattern, payment instrument, identity signal, and market context before sanctions are considered.

The transparency obligation is careful. The platform should not disclose surveillance rules in a way that helps manipulation. However, if surveillance leads to a user restriction, withdrawal hold, account review, or delayed payout, the user should receive an adverse action notice. The notice should explain the action at a category level, such as unusual account-linkage signal or abnormal trading pattern, without revealing the detection logic.

The accountable owner is the **Market Integrity Lead**. The Head of Data and AI owns model performance. Compliance owns escalation for suspicious activity reports or regulator-facing issues. The escalation path is Market Integrity Analyst, Market Integrity Lead, Compliance Lead, then Market Governance Committee for severe cases.

The Georgian personal-data obligation is significant. Surveillance uses trading behavior, account metadata, device signals, payment data, and sometimes identity information. The platform must apply purpose limitation, privacy by design, access control, logging, and security measures. Account-linkage datasets should be tightly permissioned.

Human review is required when:

- market price moves by more than 20 percentage points within 15 minutes without verified public news;
- one account or related-account cluster holds more than 25% of one side of a market;
- a proposed market pause would last more than 30 minutes;
- withdrawal hold would exceed 30 minutes;
- more than GEL 1,000 of user funds is affected;
- account suspension is proposed;
- the model’s account-linkage confidence exceeds 80% but enforcement action is considered.

The control artifacts are the surveillance alert log, investigation memo, market-pause register, account-linkage evidence bundle, and human approval record.

---

### 5.4 Responsible-Use Scoring and Intervention Routing

This system monitors user behavior to detect harmful trading patterns. It looks at losses, deposits, trading frequency, failed risk checks, cooling-off history, and repeated disputes.

The risk tier is **high risk** because the model can affect access to trading, deposit limits, cooling-off periods, and account reviews. It is also central to the platform’s claim that it is not a gambling substitute.

The fairness risk is over-restriction or under-protection. Users with irregular income or unusual schedules may be over-flagged. Wealthier users may avoid alerts because their losses look affordable in relative terms. Younger users, first-time traders, or users with low financial literacy may need stronger protection even if their absolute losses are small.

The mitigation is to base the system on observed trading harm rather than demographic assumptions. During sandbox, the rules should be simple and uniform. The model can support routing, but hard limits should be clearly disclosed and applied consistently.

The transparency obligation is strong. Before trading, users should see the core responsible-use rules. These include daily loss limits, deposit alerts, cooling-off periods, risk quiz requirements, and appeal rights. If a restriction is applied, the user should receive the reason, duration, and review channel.

The accountable owner is the **Responsible Use Lead**. Customer Trust owns user communication. Compliance oversees whether the responsible-use framework is sufficient for regulator and payment-partner confidence.

The Georgian personal-data obligation is important because responsible-use scoring processes behavioral, payment, and trading data. The platform must process that data for a clearly defined safety purpose, use only necessary variables, restrict access, and keep an intervention log.

Human review is required when:

- user deposits more than GEL 500 within 24 hours during sandbox;
- user makes more than 20 trades in one hour;
- user hits the GEL 100 daily loss limit three times in seven days;
- restriction would last more than 48 hours;
- user requests review of a cooling-off decision;
- responsible-use score changes by more than 30 points in one day;
- user shows repeated rapid deposits after losses.

The control artifacts are the responsible-use trigger log, user notice, appeal record, intervention history, and fairness review.

---

### 5.5 Payment, KYC, and Fraud-Risk Monitoring for Platform Wallets

This system monitors deposits, withdrawals, identity signals, account duplication, payment failures, and suspicious wallet behavior. It is not a generic bank fraud model. It is specifically the control layer for prediction-market payments and settlement.

The risk tier is **high risk** because it can block deposits, delay withdrawals, freeze platform wallet activity, or prevent onboarding. The model directly affects access to funds and platform participation.

The fairness risk is false positives. Users who travel, use shared devices, use older phones, change cards, rely on family payment instruments, or have irregular deposit patterns may be flagged. A bank-backed product may also over-trust existing bank customers and under-protect users onboarding through external rails.

The mitigation is a tiered review process. Low-risk anomalies should trigger step-up authentication rather than account freezes. Freezes and withdrawal holds should require human review. The model should be tuned using sandbox evidence rather than copied from generic card-fraud rules.

The transparency obligation is limited but real. The platform should not reveal fraud-detection logic. Still, users must be told if their deposit, withdrawal, onboarding, or account access is delayed because of a security review. The notice should include expected review time and support channel.

The accountable owner is the **Fraud and KYC Lead**. Payments owns operational resolution. Compliance owns AML escalation. The escalation path is Fraud Analyst, Fraud and KYC Lead, Compliance Lead, Chief Risk delegate if funds are frozen or reporting is required.

The Georgian personal-data obligation is significant. The system processes identity, payment, device, wallet, and transaction data. The platform must apply data minimization, access restrictions, security controls, audit logs, and purpose limitation.

Human review is required when:

- payment hold exceeds 30 minutes;
- withdrawal hold exceeds 30 minutes;
- transaction value exceeds GEL 1,000;
- the same user has two false-positive holds within 30 days;
- account freeze is proposed;
- duplicate identity or device signal would block onboarding;
- AML escalation is considered.

The control artifacts are the payment hold log, KYC review record, fraud false-positive dashboard, wallet ledger audit, and user notice template.

---

### 5.6 Outcome-Resolution Support

This system reads official sources and prepares a draft resolution memo. For example, it may extract the published inflation figure from Geostat, a policy-rate decision from NBG, an exchange-rate reference, or election turnout from CEC.

The risk tier is **high risk**. Outcome resolution determines payouts. A wrong extraction, wrong timestamp, wrong source, or ambiguous interpretation can create direct financial harm and destroy trust.

The main risk is not demographic bias. It is source and language reliability. Georgian-language official publications may be formatted inconsistently. Data may be revised. Publication may be delayed. Multiple sources may describe the same event differently. Users with less information may be less able to challenge an incorrect resolution.

The mitigation is a strict source registry. Every market must have an official source, publication time, backup-source rule, revision rule, and dispute window before it is listed. AI can prepare evidence, but humans must approve final resolution.

The transparency obligation is strong. Each market must disclose its official source, resolution rule, expected timing, dispute process, and payout logic before trading opens. If resolution is delayed, users should receive a notice with the reason and expected review timeline.

The accountable owner is the **Resolution Committee Chair**. Data Governance owns the source registry. Market Operations owns user notification. Compliance is involved when delay or dispute becomes material.

The Georgian personal-data obligation is usually limited if resolution depends only on public official data. It becomes relevant when payout records, user positions, disputes, and support logs are connected to the resolution. Those records must be secured, limited to the resolution purpose, and auditable.

Human review is required when:

- AI extraction confidence is below 98%;
- official result is delayed by more than 24 hours;
- official source revises the result within 48 hours;
- more than 10 disputes are filed on one market;
- more than 1% of active traders in a market dispute the result;
- official source is unavailable for more than two hours after expected publication;
- two approved sources conflict.

The control artifacts are the resolution memo, official-source evidence archive, payout approval record, dispute register, and user notification log.

---

### 5.7 Dispute Triage and User-Support Routing

This system classifies user complaints and routes them to the right team. It may identify whether the issue concerns payout, account restriction, deposit delay, responsible-use limit, market wording, or technical error.

The risk tier is **limited risk** if the model only routes cases. It becomes **high risk** if it closes disputes, rejects appeals, or decides payout outcomes automatically. The sandbox design should prohibit automatic closure of material complaints.

The fairness risk is unequal access to support. Users writing in Georgian, using informal language, showing distress, or lacking financial vocabulary may be routed incorrectly. Users who are less persistent may receive weaker outcomes than users who know how to phrase complaints.

The mitigation is human escalation for sensitive categories. Any dispute involving payout, account freeze, withdrawal hold, responsible-use restriction, legal threat, self-exclusion, or user harm should go to a human queue. The AI should assist routing, not decide the dispute.

The transparency obligation is simple. Users should know when the first response is automated and how to request human review. If a case affects money, access, or payout, the user should receive a human-reviewed response.

The accountable owner is the **Customer Trust Lead**. The Resolution Committee owns payout disputes. Responsible Use owns trading-limit appeals. Payments owns deposit and withdrawal cases.

The Georgian personal-data obligation is relevant because support tickets can include identity data, financial distress, payment details, screenshots, and behavioral information. The platform must limit support-data access, define retention periods, and prevent support conversations from being reused for unrelated profiling.

Human review is required when:

- user mentions payout dispute;
- user mentions fraud, account freeze, withdrawal hold, legal complaint, self-exclusion, gambling harm, addiction, or financial distress;
- complaint remains unresolved after 24 hours;
- user files more than three complaints in 30 days;
- ticket involves more than GEL 100;
- AI confidence in routing is below 90%.

The control artifacts are the case-routing log, escalation record, complaint category taxonomy, and human response record.

---

### 5.8 Liquidity and Market-Maker Monitoring

This system monitors bid-ask spreads, depth, quote uptime, market-maker performance, and whether users are seeing fair entry and exit conditions. It supports liquidity operations and market-quality governance.

The risk tier is **limited risk** if it only monitors and reports. It becomes **high risk** if it automatically changes market-maker incentives, pauses markets, cancels orders, or changes user-facing market status.

The fairness risk is market-quality inequality. Some markets may be liquid and easy to trade, while others have wide spreads and poor depth. Less experienced users may trade in markets where the price is technically available but economically unfair. Market makers may also prioritize high-volume categories while leaving public-interest markets thin.

The mitigation is minimum market-quality standards. The platform should not list too many markets before liquidity capacity exists. It should monitor spread, depth, quote uptime, and abandonment after users see prices. Markets below quality thresholds should be labeled or paused for review.

The transparency obligation is user-facing in a practical way. Users should see that prices may move, liquidity may be limited, and exit prices are not guaranteed. If a market is paused or labeled illiquid, the interface should explain the status clearly.

The accountable owner is the **Market Operations and Liquidity Lead**. The CFO or Risk Lead should review internal liquidity support because it creates conflict-of-interest concerns.

The Georgian personal-data obligation is moderate. The model mainly uses market data, but it can touch user trading behavior and order history. Access should be limited, and user-level trading data should not be reused for unrelated profiling.

Human review is required when:

- bid-ask spread is above 8% for more than 30 minutes;
- order-book depth is below GEL 10,000 on either side for a top-20 market;
- market-maker misses quote obligations for three monitoring intervals;
- internal liquidity provision exceeds 20% of open interest;
- market quality warning would be removed after a breach;
- user complaints about execution exceed five cases in 24 hours.

The control artifacts are the liquidity dashboard, market-maker scorecard, spread breach log, and subsidy review memo.

---

### 5.9 Regulatory and Payment-Partner Reporting Automation

This system drafts reports for NBG, payment partners, bank leadership, or internal governance committees. It summarizes market activity, user restrictions, disputes, payout delays, fraud alerts, responsible-use interventions, and market-integrity incidents.

The risk tier is **limited risk** if the system drafts internal reports for human review. It becomes **high risk** if it submits regulatory reports, changes compliance classifications, or communicates with NBG or payment partners without human sign-off.

The main risk is accuracy and omission. A reporting model may understate disputes, misclassify incidents, omit user-harm signals, or produce a confident but legally inaccurate summary. It may also rely too heavily on English-language regulatory references and miss Georgian-language legal nuance.

The mitigation is source-bound reporting. The system should only generate reports from approved internal logs and official sources. Every regulator-facing report should include source references and be signed off by Compliance and Regulatory Governance.

The transparency obligation is mostly internal and regulator-facing. Internal reviewers must know what was AI-generated, what sources were used, and what requires verification. Regulator-facing content should never be represented as fully automated.

The accountable owner is the **Regulatory and Platform Governance Lead**. Compliance signs off on external reports. Legal counsel reviews classification-sensitive content.

The Georgian personal-data obligation is important because reports may include user-level incidents, complaints, payment holds, and trading restrictions. Reports should use aggregated data where possible. User-identifiable details should be included only when necessary and access should be restricted.

Human review is required for:

- 100% of NBG-facing reports;
- 100% of payment-partner reports;
- any report mentioning legal classification of event contracts;
- any report including user-identifiable data;
- any serious incident report;
- any change to compliance controls;
- any report where source completeness is below 100%.

The control artifacts are the reporting source log, draft history, compliance sign-off record, external submission register, and redaction checklist.

---

## 6. Cross-Cutting Responsible AI Controls

The prediction-market platform needs a small number of non-negotiable controls that apply across all AI systems.

First, the platform needs an **AI Model Register**. Every model should have a named owner, risk tier, purpose, input data, output, deployment status, monitoring metric, and rollback rule.

Second, the platform needs an **Event Source Register**. Every market must have an official source before listing. No official source means no market. This is one of the cleanest ways to separate a regulated event-contract platform from informal betting.

Third, the platform needs a **Human Override Log**. When a human approves, rejects, or changes an AI recommendation, the reason must be recorded. This protects users, regulators, and the bank.

Fourth, the platform needs an **Adverse Action Notice** system. Users must be told when an AI-supported review contributes to a restriction, hold, delay, or dispute outcome. The notice does not need to disclose trade-surveillance logic, but it must give a meaningful reason and appeal route.

Fifth, the platform needs a **Fairness and False Positive Review**. The most likely fairness problem is not classic demographic discrimination alone. It is the over-flagging of users with unusual but legitimate behavior: high-frequency traders, shared-device users, rural users, users with irregular deposits, and users who trade around news.

Finally, the platform needs a **Regulator-Ready Audit Pack**. For each month of sandbox operation, the team should be able to show what markets were listed, why they were approved, what sources resolved them, what disputes occurred, what AI alerts were triggered, what humans overrode, and what user restrictions were applied.

---

## 7. Georgian Personal Data Protection Control Map

The platform processes sensitive personal and behavioral data. That includes KYC data, wallet transactions, deposits, withdrawals, trading history, device signals, complaints, disputes, and responsible-use indicators.

The Georgian-law control environment should be designed around the following obligations.

**Purpose limitation.** Each dataset must have a defined purpose. Trading behavior used for surveillance should not automatically be reused for marketing. Responsible-use data should not be reused to profile users for speculative engagement.

**Data minimization.** The platform should collect only what is necessary for KYC, settlement, market integrity, responsible-use controls, and reporting. Optional personalization should be separated from mandatory safety controls.

**Privacy by design and by default.** Access to user-level data should be restricted from the beginning. Market Operations should not see more identity data than needed. Customer Support should not see full surveillance scores unless required for a case. Reporting should use aggregated data unless user-level evidence is necessary.

**Security of processing.** KYC records, wallet ledgers, user restrictions, device signals, and account-linkage data require strong access controls, audit logs, encryption, and incident response. This is especially important because a leak of responsible-use or account-linkage data could damage users and the bank.

**Transparency and user rights.** Users should be informed that the platform uses automated monitoring for market integrity, fraud prevention, responsible use, and outcome-resolution support. They should have a route to request human review when an AI-supported process affects access, payment, trading, or payout.

**Auditability.** Every high-impact AI-supported decision must leave a trace: model output, data used, human reviewer, decision, reason, user notice, and appeal outcome.

---

## 8. Human Override Register

The following thresholds should be treated as hard handoff rules during sandbox.

**Event eligibility screening** requires human review if the event-risk score is above 30 out of 100, official-source confidence is below 95%, the event is outside the approved sandbox taxonomy, or projected exposure exceeds GEL 50,000.

**Contract drafting** requires human review if text confidence is below 98%, the Georgian and English versions differ materially, the market belongs to a new category, or the wording could be read as investment advice or betting promotion.

**Market surveillance** requires human review if price moves more than 20 percentage points within 15 minutes without verified public news, one account cluster holds more than 25% of one side, or a market pause would exceed 30 minutes.

**Responsible-use scoring** requires human review if a user deposits more than GEL 500 within 24 hours, makes more than 20 trades in one hour, hits the GEL 100 daily loss limit three times in seven days, or restriction would last more than 48 hours.

**Payment and fraud monitoring** requires human review if a payment or withdrawal hold exceeds 30 minutes, transaction value exceeds GEL 1,000, duplicate identity would block onboarding, or account freeze is proposed.

**Outcome resolution** requires human review if AI extraction confidence is below 98%, official result is delayed by more than 24 hours, more than 10 disputes are filed, or more than 1% of active traders in the market dispute the outcome.

**Dispute triage** requires human review if the user mentions payout, fraud, account freeze, withdrawal hold, legal complaint, self-exclusion, gambling harm, addiction, or financial distress.

**Liquidity monitoring** requires human review if bid-ask spread is above 8% for more than 30 minutes, order-book depth is below GEL 10,000 on either side for a top-20 market, or internal liquidity provision exceeds 20% of open interest.

**Regulatory reporting automation** requires human review for every NBG-facing report, payment-partner report, serious incident report, legal classification update, or report that includes user-identifiable data.

---

## 9. Transparency and Notice Standard

The platform should not overwhelm users with technical AI explanations. The standard should be plain, practical, and tied to user impact.

Before trading, users should be told that the platform uses automated systems to monitor market integrity, detect fraud, apply responsible-use controls, assist with outcome resolution, and route support cases.

When AI has no adverse effect, a general disclosure is enough. For example, AI-generated explanations can be covered by a platform notice and internal review.

When AI contributes to an adverse action, a specific notice is needed. This includes trading restrictions, deposit limits, cooling-off periods, payment holds, account freezes, payout delays, and dispute decisions.

A good notice should include:

- what happened;
- whether AI-supported review contributed;
- the main reason category;
- how long the action lasts;
- who reviews it;
- how the user can appeal;
- when the user can expect a response.

Example wording:

```text
Your trading access has been temporarily limited because your account reached a responsible-use threshold during the sandbox. Automated monitoring detected the threshold, and the rule applies to all sandbox users. You can still view markets, but trading will reopen after the cooling-off period unless a human review extends the restriction. If you believe the limit was applied incorrectly, you can request a review through Customer Support.
```

---

## 10. Accountability Model

The platform should avoid accountability gaps. For every AI-supported decision, one human function should own the outcome.

**Market Governance Committee** owns the decision to approve or reject event categories and high-risk market listings.

**Market Operations Lead** owns contract readiness, market templates, and listing workflow.

**Compliance Lead** owns legal classification review, regulator-facing assumptions, and policy exceptions.

**Market Integrity Lead** owns manipulation alerts, market pauses, and trading-surveillance investigations.

**Responsible Use Lead** owns user limits, cooling-off periods, and high-risk user interventions.

**Fraud and KYC Lead** owns onboarding blocks, duplicate-account reviews, payment holds, and suspicious payment escalation.

**Resolution Committee Chair** owns final payout resolution and dispute decisions.

**Regulatory and Platform Governance Lead** owns NBG and payment-partner reporting.

**Head of Data and AI** owns model performance, drift monitoring, version control, and rollback readiness.

The board should not approve public launch until this accountability model has operated through a sandbox period and produced evidence.

---

## 11. Residual Risk Assessment

After controls, some risk remains. The platform cannot remove all risk because prediction markets are inherently sensitive. The realistic goal is to make risks visible, bounded, and governable.

**Event eligibility screening** has medium residual risk. Human approval and official-source requirements reduce the risk, but controversial events may still create reputational exposure.

**Contract drafting** has low to medium residual risk if all user-facing wording is reviewed. The main remaining risk is user misunderstanding.

**Market surveillance** has high residual risk. Manipulation detection is difficult, and false positives can harm legitimate users. This is one of the most important controls to test in sandbox.

**Responsible-use scoring** has high residual risk. It is necessary for regulator and payment-partner trust, but it can over-restrict users or fail to detect harm early enough.

**Payment and fraud monitoring** has medium residual risk. False positives will occur, but fast human review can reduce user harm.

**Outcome resolution** has high residual risk. Payout decisions are central to user trust, and source ambiguity can create disputes even with strong controls.

**Dispute triage** has medium residual risk. Human escalation for sensitive cases keeps the risk manageable.

**Liquidity monitoring** has medium residual risk. The model can identify poor market quality, but it cannot guarantee liquidity without sufficient market-maker support.

**Regulatory reporting automation** has medium residual risk if every external report is human-signed. It becomes high risk if the platform allows automatic reporting without review.

---

## 12. Implementation Priorities

The platform should not try to automate everything at launch. The first phase should prioritize governance over speed.

Before sandbox trading, the platform needs the Market Governance Committee, event-source register, approved event taxonomy, contract templates, responsible-use policy, KYC and payment-risk workflow, adverse action notice template, and human override log.

During sandbox, the platform should activate surveillance dashboards, responsible-use logs, payment false-positive monitoring, dispute tracking, resolution memos, and monthly governance reports.

Before public launch, the platform should complete a full review of model performance, false-positive rates, dispute outcomes, responsible-use interventions, liquidity quality, payment-partner feedback, and NBG feedback. If these do not support a credible control story, the platform should stay in sandbox or stop.

The key implementation principle is simple: AI can assist, route, monitor, and summarize. It should not autonomously approve markets, freeze users, resolve payouts, or communicate with regulators during the first operating phase.

---

## 13. Conclusion

The responsible AI assessment supports the project’s strategic recommendation: a Georgian prediction-market platform should be launched only through a controlled, regulator-first pathway.

The platform’s AI systems are not mainly about prediction. They are about trust. They help decide which markets can be listed, which trading behavior looks suspicious, which users may need protection, which official result resolves a market, and what evidence regulators receive.

That makes the AI portfolio high impact. The strongest controls are not abstract principles. They are specific operating mechanisms: official-source registry, market approval committee, adverse action notices, human override thresholds, responsible-use logs, resolution memos, market-surveillance investigations, and regulator-ready audit packs.

A bank-backed platform can be defensible only if these controls are in place before scale. The public launch decision should therefore depend not only on user demand and unit economics, but also on whether the platform proves that its AI-supported decisions are fair, explainable, secure, contestable, and accountable.

---

## References

European Commission. (2026). AI Act. Shaping Europe’s Digital Future. https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai

European Union. (2024). Regulation (EU) 2024/1689 laying down harmonised rules on artificial intelligence.

Personal Data Protection Service of Georgia. (2024). Current Law of Georgia on Personal Data Protection. https://pdps.ge/content/1063/LAWS

Personal Data Protection Service of Georgia. (2024). Guide for business, Part III: Compliance assurance. https://pdps.ge/content/1085/nawili-III.-kanonSesabamisobis-uzrunvelyofa

Personal Data Protection Service of Georgia. (2024). Guide for business, Part IV: Personal data security. https://pdps.ge/content/1086/nawili-IV.-personalur-monacemTa-usafrTxoebis-dacva

Organisation for Economic Co-operation and Development. (2019). OECD principles on artificial intelligence.

Westerman, G., Bonnet, D., & McAfee, A. (2014). Leading digital: Turning technology into business transformation. Harvard Business Review Press.
