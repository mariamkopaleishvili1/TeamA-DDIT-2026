# AI Landscape and Opportunity Analysis

## Project

Team A: Georgian Prediction-Market Platform
Industry: Fintech
Market: Republic of Georgia
Client assumption: TBC-backed launch model
Recommended strategic option: TBC-owned, GEL-settled prediction-market platform under an NBG special-designation or sandbox-first route

---

## Purpose

This document updates the Week 2 AI Opportunity Map for final submission.

The final strategy has changed in an important way. The project is no longer framed as a standalone fintech venture trying to launch a prediction-market app. The final strategy is a TBC-backed platform that should be integrated into or adjacent to the mobile banking ecosystem, with TBC controlling the wallet, GEL settlement, KYC layer, customer relationship, risk controls, and regulator-facing governance.

This changes the role of AI.

AI should not be presented as a tool for predicting market outcomes. That would make the platform look speculative and could weaken regulatory credibility. The stronger role of AI is to make the prediction-market platform more governable.

The core AI thesis is:

> AI should first protect trust, not predict outcomes. Its primary role is to help TBC screen events, explain contracts, monitor trading behavior, detect user-harm signals, support outcome resolution, route disputes, and prepare regulator-ready evidence.

---

## 1. AI Adoption State in the Relevant Industry

### 1.1 Industry context

The relevant industry is not only prediction markets. It is the intersection of:

* mobile banking;
* digital wallets;
* payment monitoring;
* brokerage and trading interfaces;
* crypto and VASP platforms;
* betting substitutes;
* emerging event-contract marketplaces;
* regulatory and responsible-use systems.

This matters because no regulated Georgian prediction-market platform currently exists. Therefore, the AI adoption analysis cannot be based on local prediction-market incumbents. It must use comparable areas where similar capabilities already exist: market surveillance, fraud detection, payment monitoring, KYC, user support, trading-risk controls, and compliance reporting.

### 1.2 Current adoption evidence by capability

The current adoption pattern is uneven. AI and automation are already normal in adjacent financial services, but not yet integrated into a Georgian prediction-market operating model.

| Capability area                        | Current adoption evidence                                                                                                                                                | Relevance to prediction market                                                                                               | Adoption maturity                                 |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| Fraud detection and payment monitoring | Banks, PSPs, and crypto platforms already use rule-based and increasingly AI-assisted transaction monitoring, account-linkage checks, and suspicious activity detection. | Needed for wallet funding, withdrawal holds, duplicate identity checks, payment-risk alerts, and AML escalation.             | Medium to high                                    |
| KYC and identity checks                | Digital onboarding and KYC are already core to fintech and banking platforms.                                                                                            | Needed before users can access a TBC-linked prediction-market wallet.                                                        | High                                              |
| Market surveillance                    | Securities and crypto venues use surveillance logic to flag manipulation, concentration, unusual order flow, and suspicious trading patterns.                            | Needed to detect price manipulation, coordinated trading, insider-risk patterns, and market abuse.                           | Medium                                            |
| Responsible-use monitoring             | Betting and gambling platforms use limits, exclusions, risk flags, and intervention tools. Financial platforms also use suitability and risk warnings.                   | Needed to separate the platform from gambling-style speculation and protect users showing harmful patterns.                  | Medium                                            |
| Contract and disclosure generation     | Generative AI can draft explanations, summarize rules, and produce plain-language content, but legal and compliance review remain necessary.                             | Useful for market descriptions, risk warnings, source explanations, and bilingual user education.                            | Medium                                            |
| Customer support automation            | Chatbots and ticket routing are common in digital finance.                                                                                                               | Useful for onboarding questions, product education, support routing, and escalation of sensitive disputes.                   | High for basic routing, lower for sensitive cases |
| Outcome-resolution support             | Data extraction and document summarization can support result verification.                                                                                              | Useful for reading official source publications and drafting resolution memos, but should not approve payouts automatically. | Medium                                            |
| Regulatory reporting automation        | AI can draft and summarize reports, but external submissions still need human sign-off.                                                                                  | Useful for monthly NBG packs, payment-partner packs, incident reports, and audit evidence.                                   | Medium                                            |
| Prediction of event outcomes           | AI can generate forecasts, but using AI to predict event outcomes would create positioning and trust problems.                                                           | Should not be a core early use case because the platform should not be seen as trading against users.                        | Low priority                                      |

### 1.3 AI adoption conclusion

AI adoption in adjacent financial services is already strong enough to support a controlled platform, but the platform should not begin with “AI prediction.”

The correct sequence is:

1. first use AI for control, explanation, detection, and reporting;
2. then use AI for operational optimization;
3. only later consider advanced personalization or market-intelligence products, and only if data governance and responsible-use rules are mature.

---

## 2. AI Opportunity Map

### 2.1 Scoring method

Each use case is scored on five criteria.

| Criterion                             | Meaning                                                                                                 | Score range |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------- | ----------: |
| Business value                        | Impact on trust, revenue, adoption, risk reduction, or platform viability                               |      1 to 5 |
| Implementation readiness              | Whether the capability can be built with current or near-current data, systems, and governance          |      1 to 5 |
| Regulatory importance                 | Importance for NBG comfort, payment partner confidence, data protection, or responsible-use credibility |      1 to 5 |
| Mobile banking integration importance | Importance for placing the product safely inside or adjacent to the TBC mobile app and wallet           |      1 to 5 |
| Risk if absent                        | How damaging it would be if the platform launched without this capability                               |      1 to 5 |

Total score is out of 25.

### 2.2 Full opportunity map

| Rank | AI use case                                                | Value chain activity                     | Business value | Readiness | Regulatory importance | Mobile integration importance | Risk if absent | Total | Horizon  | Priority                       |
| ---: | ---------------------------------------------------------- | ---------------------------------------- | -------------: | --------: | --------------------: | ----------------------------: | -------------: | ----: | -------- | ------------------------------ |
|    1 | Market surveillance and manipulation detection             | Market integrity, trading operations     |              5 |         4 |                     5 |                             3 |              5 |    22 | H1 to H2 | Deploy first                   |
|    2 | Responsible-use scoring and intervention routing           | User protection, risk controls           |              5 |         4 |                     5 |                             5 |              5 |    24 | H1 to H2 | Deploy first                   |
|    3 | Payment, KYC, wallet, and fraud-risk monitoring            | Wallet, onboarding, payment controls     |              5 |         4 |                     5 |                             5 |              5 |    24 | H1 to H2 | Deploy first                   |
|    4 | AI-assisted market explanations and risk disclosures       | Customer education, app UX, transparency |              4 |         5 |                     4 |                             5 |              4 |    22 | H1       | Deploy first                   |
|    5 | Event eligibility screening                                | Market approval, governance              |              5 |         3 |                     5 |                             3 |              5 |    21 | H1       | Deploy first with human review |
|    6 | Outcome-resolution support                                 | Resolution, settlement, evidence         |              5 |         3 |                     5 |                             3 |              5 |    21 | H2       | Invest to enable               |
|    7 | Dispute triage and support routing                         | Customer Trust, support, complaints      |              4 |         4 |                     4 |                             4 |              4 |    20 | H1 to H2 | Deploy with guardrails         |
|    8 | Liquidity and market-maker monitoring                      | Market quality, market operations        |              4 |         3 |                     3 |                             2 |              4 |    16 | H2       | Invest to enable               |
|    9 | Regulatory and payment-partner reporting automation        | Compliance, reporting, audit             |              4 |         3 |                     5 |                             2 |              4 |    18 | H2       | Invest to enable               |
|   10 | Mobile app personalization and product suitability prompts | App journey, onboarding, education       |              3 |         3 |                     4 |                             5 |              3 |    18 | H2       | Use carefully                  |
|   11 | Advanced market-intelligence analytics                     | Data products, institutional insights    |              3 |         2 |                     2 |                             1 |              2 |    10 | H3       | Future option                  |
|   12 | AI outcome prediction tools                                | Forecasting, user-facing analytics       |              2 |         3 |                     2 |                             2 |              1 |    10 | H3       | Do not prioritize              |

### 2.3 Quadrant view

| Quadrant         | Meaning                                                              | Use cases                                                                                                                  |
| ---------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Deploy first     | High value, high readiness, high control importance                  | Market explanations, responsible-use routing, payment and wallet monitoring, market surveillance prototype, dispute triage |
| Invest to enable | High value, medium readiness, requires data or governance investment | Event eligibility screening, outcome-resolution support, liquidity monitoring, reporting automation                        |
| Use carefully    | Useful but potentially risky if over-personalized or poorly governed | Mobile app personalization, product suitability prompts                                                                    |
| Future option    | Not required for sandbox launch or risky for positioning             | Advanced market-intelligence products, AI outcome prediction tools                                                         |

---

## 3. Priority Use Cases With Full Scoring Rationale

## 3.1 Market surveillance and manipulation detection

### Summary

This use case monitors trading activity, price movements, order concentration, related-account behavior, liquidity anomalies, and market-pause triggers.

### Score

| Criterion                     |  Score | Rationale                                                                                                                                                     |
| ----------------------------- | -----: | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Business value                |      5 | Market integrity is central to trust. If users think prices are manipulated, the platform loses credibility.                                                  |
| Implementation readiness      |      4 | Basic anomaly detection and dashboarding can begin with simulated markets and sandbox data. More advanced related-account detection requires more investment. |
| Regulatory importance         |      5 | NBG and payment partners will need evidence that market abuse can be detected and escalated.                                                                  |
| Mobile integration importance |      3 | The user-facing app does not show all surveillance logic, but surveillance outputs affect market warnings, pauses, and support messages.                      |
| Risk if absent                |      5 | Launching without surveillance would make the platform look ungoverned and gambling-like.                                                                     |
| **Total**                     | **22** | Deploy first.                                                                                                                                                 |

### Recommended first version

The first version should not try to detect every possible manipulation pattern. It should detect and log:

* rapid price moves without public news;
* order concentration by one user or related accounts;
* abnormal volume spikes;
* liquidity withdrawal from top markets;
* repeated same-direction trades from linked accounts;
* market-maker quote failures;
* user complaints about execution quality.

### Human control

AI may flag suspicious behavior, but it should not impose final sanctions, freeze accounts, or submit regulator reports without human review.

---

## 3.2 Responsible-use scoring and intervention routing

### Summary

This use case identifies user patterns that may indicate harmful or impulsive trading behavior. It routes cases to warnings, deposit alerts, cooling-off periods, or human review.

### Score

| Criterion                     |  Score | Rationale                                                                                             |
| ----------------------------- | -----: | ----------------------------------------------------------------------------------------------------- |
| Business value                |      5 | Responsible use is essential for separating the platform from betting-style speculation.              |
| Implementation readiness      |      4 | Rule-based thresholds can be implemented early. AI-assisted risk scoring can be added during sandbox. |
| Regulatory importance         |      5 | The product will not be credible to regulators or payment partners without user-protection controls.  |
| Mobile integration importance |      5 | Warnings, limits, cooling-off periods, and appeals must appear inside the mobile journey.             |
| Risk if absent                |      5 | Without this use case, the platform creates reputational and user-harm risk.                          |
| **Total**                     | **24** | Deploy first.                                                                                         |

### Recommended first version

The first version should include:

* daily loss limits;
* deposit alerts;
* repeated deposit-after-loss detection;
* rapid-trading alerts;
* cooling-off triggers;
* risk quiz before first trade;
* appeal route for restrictions;
* in-app warnings written in plain language.

### Human control

AI may identify patterns and recommend intervention. It should not impose long restrictions without human review.

---

## 3.3 Payment, KYC, wallet, and fraud-risk monitoring

### Summary

This use case monitors the TBC-linked wallet journey: onboarding, deposits, withdrawals, duplicate identities, suspicious activity, payment holds, and wallet restrictions.

### Score

| Criterion                     |  Score | Rationale                                                                                                                                       |
| ----------------------------- | -----: | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Business value                |      5 | The wallet is central to the TBC strategy. If the wallet flow fails, the business model weakens.                                                |
| Implementation readiness      |      4 | Banks already operate KYC, fraud, and payment-monitoring systems. The prediction-market layer needs custom thresholds and workflow integration. |
| Regulatory importance         |      5 | KYC, AML, payment security, and wallet monitoring are non-negotiable for a bank-backed product.                                                 |
| Mobile integration importance |      5 | Funding, withdrawal, restrictions, and user notices happen inside the app journey.                                                              |
| Risk if absent                |      5 | Weak wallet controls could create fraud, AML, user-trust, and payment-partner issues.                                                           |
| **Total**                     | **24** | Deploy first.                                                                                                                                   |

### Recommended first version

The first version should monitor:

* KYC completion before first trade;
* duplicate identity signals;
* unusual funding velocity;
* withdrawal holds;
* related accounts;
* payment failure patterns;
* false-positive rates;
* wallet restriction reasons;
* user notices and appeals.

### Human control

AI may trigger a review, but it should not create prolonged payment holds, wallet freezes, or onboarding rejections without human review.

---

## 3.4 AI-assisted market explanations and risk disclosures

### Summary

This use case helps create simple user-facing explanations for event contracts. It explains the event, source, resolution rule, possible loss, and payout logic in plain Georgian and English.

### Score

| Criterion                     |  Score | Rationale                                                                                  |
| ----------------------------- | -----: | ------------------------------------------------------------------------------------------ |
| Business value                |      4 | Clear explanations improve activation, reduce support burden, and reduce misunderstanding. |
| Implementation readiness      |      5 | Generative AI can draft explanations now, with human review.                               |
| Regulatory importance         |      4 | Poor wording could make the product look promotional, misleading, or gambling-like.        |
| Mobile integration importance |      5 | Explanations and warnings are part of the mobile app customer journey.                     |
| Risk if absent                |      4 | Users may misunderstand the product, causing complaints and reputational risk.             |
| **Total**                     | **22** | Deploy first.                                                                              |

### Recommended first version

The system should produce draft language for:

* what the market asks;
* what Yes and No mean;
* what official source resolves the outcome;
* when the market resolves;
* what the maximum loss is;
* what the user should understand before trading;
* why the product is not a guaranteed-return product.

### Human control

AI may draft, but Compliance and Market Operations must approve user-facing market text before publication.

---

## 3.5 Event eligibility screening

### Summary

This use case screens proposed event markets before they enter the approval workflow.

### Score

| Criterion                     |  Score | Rationale                                                                                                                 |
| ----------------------------- | -----: | ------------------------------------------------------------------------------------------------------------------------- |
| Business value                |      5 | Bad market selection can damage the platform before it scales.                                                            |
| Implementation readiness      |      3 | Screening rules can be built early, but reliable classification needs taxonomy, source registry, and governance approval. |
| Regulatory importance         |      5 | Event selection determines whether the product looks like a supervised marketplace or gambling-style speculation.         |
| Mobile integration importance |      3 | Only approved events should appear in the app, but users do not need to see the internal scoring.                         |
| Risk if absent                |      5 | Without screening, inappropriate markets could be listed.                                                                 |
| **Total**                     | **21** | Deploy first, but with strict human approval.                                                                             |

### Recommended first version

The event screening tool should check:

* whether the event is inside the approved taxonomy;
* whether it has an official source;
* whether resolution is objective;
* whether the event involves prohibited categories;
* whether the wording could be interpreted as betting promotion;
* whether the market could create reputational harm for TBC.

### Human control

AI may screen and flag. It may not approve a market for listing.

---

## 3.6 Outcome-resolution support

### Summary

This use case helps extract official results, compare source publications, draft resolution memos, and prepare payout evidence.

### Score

| Criterion                     |  Score | Rationale                                                                           |
| ----------------------------- | -----: | ----------------------------------------------------------------------------------- |
| Business value                |      5 | Correct resolution is central to user trust and payout reliability.                 |
| Implementation readiness      |      3 | It depends on source registry quality, publication formats, and dispute procedures. |
| Regulatory importance         |      5 | Resolution evidence is central to auditability and regulator comfort.               |
| Mobile integration importance |      3 | Users see settlement status and dispute options in the app.                         |
| Risk if absent                |      5 | Incorrect or slow resolution can create disputes and reputational damage.           |
| **Total**                     | **21** | Invest to enable.                                                                   |

### Recommended first version

The tool should support:

* official-source monitoring;
* source publication capture;
* result extraction;
* confidence scoring;
* resolution memo drafting;
* dispute trigger detection;
* payout approval evidence packs.

### Human control

AI may draft a resolution memo. It may not approve payouts automatically.

---

## 3.7 Dispute triage and support routing

### Summary

This use case routes user support cases to the correct owner: Customer Trust, Payments, Responsible Use, Market Operations, Resolution Committee, or Compliance.

### Score

| Criterion                     |  Score | Rationale                                                             |
| ----------------------------- | -----: | --------------------------------------------------------------------- |
| Business value                |      4 | Fast routing reduces complaints and improves user trust.              |
| Implementation readiness      |      4 | Ticket classification and routing can be implemented early.           |
| Regulatory importance         |      4 | Sensitive cases need documented escalation.                           |
| Mobile integration importance |      4 | The app is the main support entry point.                              |
| Risk if absent                |      4 | Misrouted payout, restriction, or payment cases can escalate quickly. |
| **Total**                     | **20** | Deploy with guardrails.                                               |

### Recommended first version

AI should route cases involving:

* payout disputes;
* withdrawal holds;
* wallet restrictions;
* account freezes;
* responsible-use appeals;
* market-resolution complaints;
* self-exclusion or financial distress;
* legal complaints.

### Human control

AI may route cases, but it should not close material disputes automatically.

---

## 3.8 Liquidity and market-maker monitoring

### Summary

This use case monitors spreads, depth, market-maker quote obligations, and user execution complaints.

### Score

| Criterion                     |  Score | Rationale                                                                        |
| ----------------------------- | -----: | -------------------------------------------------------------------------------- |
| Business value                |      4 | Liquidity quality directly affects user trust and trading volume.                |
| Implementation readiness      |      3 | Requires live order-book data and defined market-maker obligations.              |
| Regulatory importance         |      3 | Important for fairness, but less directly regulated than KYC or responsible use. |
| Mobile integration importance |      2 | Users may see market-quality warnings, but most monitoring is operational.       |
| Risk if absent                |      4 | Poor spreads and thin markets can kill adoption.                                 |
| **Total**                     | **16** | Invest to enable.                                                                |

### Recommended first version

The monitoring system should track:

* bid-ask spread;
* order-book depth;
* quote uptime;
* market-maker missed obligations;
* volume by market;
* liquidity subsidy usage;
* user execution complaints.

### Human control

AI may flag liquidity breaches. It should not remove market warnings or change market status without review.

---

## 3.9 Regulatory and payment-partner reporting automation

### Summary

This use case prepares draft reporting packs for NBG, payment partners, internal governance, and board review.

### Score

| Criterion                     |  Score | Rationale                                                                 |
| ----------------------------- | -----: | ------------------------------------------------------------------------- |
| Business value                |      4 | Reporting quality helps sustain regulator and payment-partner confidence. |
| Implementation readiness      |      3 | Requires clean logs, source data, and report templates.                   |
| Regulatory importance         |      5 | External reporting must be reliable and human-reviewed.                   |
| Mobile integration importance |      2 | Mostly internal, but app journey and wallet data feed the reports.        |
| Risk if absent                |      4 | Poor evidence weakens board and regulator confidence.                     |
| **Total**                     | **18** | Invest to enable.                                                         |

### Recommended first version

The reporting system should draft:

* market approval summaries;
* source registry summaries;
* incident logs;
* responsible-use intervention reports;
* payment-hold summaries;
* dispute metrics;
* market-quality dashboards;
* board launch-gate evidence.

### Human control

AI may draft reports, but it may not send external reports.

---

## 3.10 Mobile app personalization and suitability prompts

### Summary

This use case adjusts education, warnings, and user prompts inside the mobile banking journey based on user behavior and consented data.

### Score

| Criterion                     |  Score | Rationale                                                                                 |
| ----------------------------- | -----: | ----------------------------------------------------------------------------------------- |
| Business value                |      3 | Personalization may improve understanding and reduce support load.                        |
| Implementation readiness      |      3 | Depends on mobile app integration, data governance, and consent design.                   |
| Regulatory importance         |      4 | Personalization can become risky if it encourages trading or uses sensitive data.         |
| Mobile integration importance |      5 | This use case exists inside the mobile banking app.                                       |
| Risk if absent                |      3 | The product can still launch without personalization, using standard warnings and limits. |
| **Total**                     | **18** | Use carefully.                                                                            |

### Recommended first version

The first version should not personalize trading encouragement. It should personalize only:

* education reminders;
* risk warnings;
* support prompts;
* responsible-use messages;
* product-understanding checks.

### Human control

The system should not personalize markets or incentives in a way that encourages vulnerable users to trade more.

---

## 4. AI Adoption Evidence by Use Case

### 4.1 Evidence from adjacent financial services

Because Georgian prediction markets do not yet exist as a regulated local product, evidence must come from adjacent use cases.

| AI use case                 | Evidence from adjacent industries                                                                                       | What this means for the platform                                                                  |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| Market surveillance         | Trading venues and crypto exchanges already monitor price movement, concentration, order flow, and suspicious behavior. | A prediction market should adopt surveillance logic before public trading.                        |
| Fraud and wallet monitoring | Banks and fintechs already use automated fraud and payment-risk tools.                                                  | TBC can adapt existing wallet, KYC, AML, and payment controls to the platform.                    |
| Responsible-use scoring     | Betting and consumer-protection systems already use limits, exclusions, alerts, and risk flags.                         | The platform should use responsible-use controls from day one to avoid gambling-like positioning. |
| Market explanations         | Generative AI can draft plain-language explanations, but legal review remains necessary.                                | AI can support contract explanation, not replace Compliance approval.                             |
| Outcome-resolution support  | AI can extract structured information from official documents and draft summaries.                                      | Useful for resolution memos, but not for final payout approval.                                   |
| Dispute triage              | Customer-service systems already route cases by topic, risk, and urgency.                                               | Useful for app-based support, but sensitive cases must go to humans.                              |
| Reporting automation        | AI can summarize operational evidence and draft reports.                                                                | Useful for board and regulator packs, but external reports need sign-off.                         |

### 4.2 Evidence from the project repository

The internal evidence base supports three conclusions:

First, the Week 2 AI Opportunity Map already stated that AI should make the event-contract platform safer, clearer, more transparent, and more credible for users, regulators, and banking partners.

Second, the governance plan identifies nine AI-enabled platform capabilities and treats them as one control system. The final version adds mobile banking integration as the tenth capability.

Third, the roadmap places data governance, source registry, payment/KYC design, responsible-use rules, and MVP workflow before AI-enabled scale. This confirms that AI deployment must follow governance readiness, not precede it.

---

## 5. Strategic Implications of the AI Capability Trajectory

### 5.1 AI moves from content support to control infrastructure

The first AI use cases should be simple but important:

* market explanation drafting;
* support routing;
* surveillance prototype;
* responsible-use triggers;
* wallet-risk alerts.

These tools do not require full automation. They make the platform more explainable and more controlled.

Over time, AI can move deeper into market operations:

* event screening;
* liquidity monitoring;
* outcome-resolution support;
* dispute triage;
* reporting automation.

The long-term capability is a supervised market-operations system that helps TBC manage the platform at scale.

### 5.2 AI must be embedded into the mobile banking journey

Because the platform should sit inside or adjacent to TBC’s mobile app, AI cannot be treated as a back-office tool only.

AI outputs affect:

* eligibility gates;
* product-understanding checks;
* risk warnings;
* deposit alerts;
* cooling-off messages;
* support routing;
* payment-hold notices;
* market-quality warnings;
* dispute status;
* user-facing explanations.

This means AI governance and mobile UX must be designed together. A risk score that does not translate into a clear app message will create confusion and complaints.

### 5.3 AI should protect TBC from becoming only a payment rail

If TBC only processes payments for another platform, it carries operational and reputational exposure without owning the platform intelligence.

A TBC-owned AI control layer helps keep strategic value inside the bank ecosystem:

* wallet-risk data;
* market-quality data;
* responsible-use evidence;
* support and dispute patterns;
* event-demand signals;
* regulator-ready reporting.

This supports the broader platform strategy: TBC should own the local wallet and governance layer.

### 5.4 AI should not optimize for maximum trading

The platform should avoid AI that pushes users toward more trading, more deposits, or more risk. That would weaken the responsible-use story and create reputational risk.

The appropriate optimization goals are:

* comprehension;
* safety;
* fair access;
* market integrity;
* low dispute rates;
* timely settlement;
* low false-positive restrictions;
* high reporting quality;
* controlled adoption.

### 5.5 AI readiness depends on data governance

No advanced AI system should be deployed before the data foundations are in place.

Required data foundations include:

* event source registry;
* market taxonomy;
* contract wording repository;
* wallet ledger;
* KYC and AML event logs;
* responsible-use logs;
* surveillance alerts;
* human override records;
* support and dispute taxonomy;
* outcome-resolution evidence archive;
* mobile-app journey analytics.

Without this foundation, AI outputs will be difficult to audit and unsafe to use in high-impact decisions.

---

## 6. Gap Analysis Against the Most Comparable Advanced Organisation

### 6.1 Benchmark selection

The most relevant external benchmark is **Kalshi**, because it represents the regulated event-contract exchange model. Polymarket is also important as a liquidity and user-growth benchmark, but it is crypto-native and does not match the recommended TBC-owned, GEL-settled, regulator-facing strategy.

Kalshi is not used here as a legal template for Georgia. It is used as a strategic benchmark for what a regulated event-contract venue must eventually prove:

* clear contract rules;
* approved market categories;
* supervised market operations;
* user-facing risk disclosures;
* settlement rules;
* market integrity controls;
* regulatory reporting;
* dispute handling;
* operational trust.

### 6.2 Gap summary

| Capability               | Kalshi-style regulated benchmark                                                                | Current Georgian/TBC-backed concept                                                            | Gap            | Required action                                              |
| ------------------------ | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | -------------- | ------------------------------------------------------------ |
| Regulatory category      | Operates inside a defined U.S. event-contract exchange framework                                | Georgian classification still requires NBG engagement or special designation                   | High           | Build NBG classification package and sandbox route           |
| Market approval          | Contracts require formal approval and structured rules                                          | Market taxonomy and approval workflow still need to be built                                   | High           | Create event taxonomy, prohibited categories, approval memo  |
| User interface           | Event contracts shown in a dedicated trading venue                                              | Proposed model must integrate into TBC mobile banking or wallet journey                        | Medium to high | Design controlled mobile entry point, risk quiz, wallet flow |
| Market surveillance      | Regulated exchange model requires integrity controls                                            | Surveillance prototype and rules must be built before scale                                    | High           | Build surveillance dashboard and escalation workflow         |
| Responsible-use controls | Event trading still requires user protections and clear disclosures                             | Responsible-use model is central because Georgian platform must avoid betting-style perception | High           | Implement limits, cooling-off, warnings, appeals             |
| Wallet and settlement    | Uses its own regulated settlement framework                                                     | TBC model should use GEL wallet or bank-linked funding                                         | Medium         | Build TBC-linked wallet flow and reconciliation              |
| Data governance          | Regulated exchange requires auditability                                                        | Source registry, override logs, and report packs must be built                                 | High           | Establish data lineage and audit-log routines                |
| AI use                   | Public details are limited; regulated operations require controlled automation and human review | AI should be used as decision support, not final authority                                     | Medium         | Build model register, human override, monitoring             |
| Liquidity                | Needs usable markets and adequate participation                                                 | Georgian platform faces cold-start liquidity problem                                           | High           | Fund market-maker programme and market-quality monitoring    |
| Reporting                | Regulator-facing evidence is expected                                                           | NBG and payment-partner reporting packs must be designed                                       | High           | Build reporting automation with human sign-off               |

### 6.3 Interpretation

Kalshi shows that the regulated version of prediction markets is an exchange-like operating model, not only a consumer interface. That is the main lesson for TBC.

The largest gaps are not front-end design gaps. They are operating-model gaps:

* regulatory classification;
* market approval;
* surveillance;
* responsible use;
* resolution;
* wallet controls;
* reporting;
* liquidity.

This supports the recommendation that TBC should not launch the product as a normal app feature. It should launch through a controlled sandbox path with mobile banking integration, governance, data infrastructure, and AI controls built before public scale.

### 6.4 Polymarket comparison

Polymarket should be treated as a liquidity and user-demand benchmark, not a regulatory benchmark.

It shows that public events can attract high trading activity when markets are timely, liquid, and easy to understand. However, its crypto-native structure does not solve the Georgian platform’s key problems:

* NBG classification;
* GEL settlement;
* TBC wallet ownership;
* local KYC and AML controls;
* responsible-use expectations;
* bank-brand risk;
* regulator-facing reporting.

### 6.5 Strategic conclusion from the benchmark

The benchmark analysis supports this conclusion:

> TBC should not copy Kalshi or Polymarket directly. It should build a Georgian model that combines Kalshi-style regulatory discipline with Polymarket-style product simplicity, but with TBC-owned wallet control and mobile banking integration.

---

## 7. AI Roadmap Integration

### H1: Months 1 to 6

H1 AI work should focus on design, governance, and safe prototypes.

Required H1 AI-enabled capabilities:

* market explanation drafting with human approval;
* event eligibility screening rules;
* responsible-use thresholds;
* payment and wallet-risk rule design;
* support and dispute taxonomy;
* AI model register;
* human override log;
* event source registry;
* mobile-app risk-warning content;
* market surveillance prototype using simulated or internal data.

H1 should not include fully automated enforcement.

### H2: Months 7 to 18

H2 should test AI-enabled controls during sandbox.

Required H2 AI-enabled capabilities:

* market surveillance monitoring;
* responsible-use scoring and intervention routing;
* payment and wallet-risk alerting;
* outcome-resolution support;
* dispute triage;
* liquidity monitoring;
* report drafting;
* mobile app adoption and risk-signal monitoring.

H2 should measure false positives, review times, user complaints, market-quality alerts, and appeal outcomes.

### H3: Post-18 months

H3 AI options should remain conditional.

Possible H3 capabilities:

* advanced market-quality analytics;
* automated regulator dashboards;
* institutional data products;
* advanced user education personalization;
* predictive liquidity allocation;
* expanded event-demand forecasting.

AI prediction of market outcomes should remain a low-priority future option because it could create conflict-of-interest concerns if users believe the platform trades against them or nudges them toward risk.

---

## 8. Governance Requirements for AI Deployment

AI deployment must follow four rules.

### 8.1 Human approval for user-impacting decisions

AI may screen, draft, flag, score, summarize, and route. It should not independently:

* approve market listings;
* publish binding contract text;
* freeze accounts;
* restrict users for long periods;
* approve payouts;
* close material disputes;
* send external regulator reports.

### 8.2 Every high-risk output must be logged

High-impact AI outputs should record:

* input data;
* model output;
* confidence score;
* human reviewer;
* final decision;
* reason code;
* user notice if applicable;
* appeal outcome if applicable.

### 8.3 Mobile-app messages must be understandable

If an AI-supported process affects a user’s ability to trade, deposit, withdraw, settle, or dispute, the app must show a clear explanation and route to support.

### 8.4 Data use must be narrow

Responsible-use, KYC, wallet, and trading data should not be reused for marketing unless separately justified, consented, and governed.

---

## 9. AI Risks and Mitigations

| Risk                                 | Why it matters                                              | Mitigation                                                                   |
| ------------------------------------ | ----------------------------------------------------------- | ---------------------------------------------------------------------------- |
| AI explains contracts incorrectly    | Users may misunderstand risk or payout rules                | Human review before publication; approved wording library                    |
| AI over-restricts users              | False positives can reduce trust and create complaints      | Human review thresholds; appeal route; false-positive tracking               |
| AI under-detects harmful behavior    | User harm and reputational risk increase                    | Conservative sandbox limits; manual review; model monitoring                 |
| AI misroutes disputes                | Payout or wallet cases may escalate                         | Sensitive keyword escalation; SLA monitoring; Customer Trust review          |
| AI creates biased access outcomes    | Some users may be unfairly blocked or delayed               | Bias monitoring by user type, payment method, geography, and device patterns |
| AI creates regulatory overconfidence | Teams may rely on automation before classification is clear | Committee sign-off; external reports require human approval                  |
| AI uses sensitive data too broadly   | Data protection and trust issues arise                      | Purpose limitation, access control, audit logs, privacy review               |

---

## 10. Board-Level Conclusion

The AI opportunity is not to make the platform smarter than users. The AI opportunity is to make the platform safer, clearer, and more controllable.

The highest-priority AI use cases are:

1. responsible-use scoring and intervention routing;
2. payment, KYC, wallet, and fraud-risk monitoring;
3. market surveillance and manipulation detection;
4. AI-assisted market explanations and risk disclosures;
5. event eligibility screening;
6. outcome-resolution support.

These use cases support the real strategic objective:

> TBC should own a regulated wallet-to-market platform where AI helps protect trust, monitor risk, explain event contracts, support fair resolution, and produce evidence for regulators and payment partners.

AI is therefore not a separate innovation layer. It is part of the operating model required to make a TBC-backed prediction-market platform acceptable to users, regulators, payment partners, and the board.

---

## 11. Presentation Takeaways

This section should support four slide-level conclusions:

1. **AI should first protect trust, not predict outcomes.**
2. **The top AI use cases are market integrity, responsible use, wallet-risk monitoring, and contract explanation.**
3. **The biggest AI gap is not model sophistication; it is controlled data, mobile-app integration, human override, and regulator-ready evidence.**
4. **Kalshi proves the regulated-market discipline; Polymarket proves demand and liquidity. TBC needs a Georgian model combining product simplicity with bank-grade control.**

---

## References and Internal Evidence Base

Team A. `deli wk2/Completed/ai_opportunity_mapping_activity.md`

Team A. `Deliverables WK3/Completed/governance_change_management_plan.md`

Team A. `Deliverables WK3/Completed/roadmap_draft_v1.md`

Team A. `Deliverables WK3/Completed/pm_roi_v3.md`

Team A. `Deliverables WK3/Completed/platform_strategy_final.md`

Team A. `Deliverables WK3/Completed/industry_competitive_analysis.md`

Team A. `FINAL/final_presentation_structure.md`

National Bank of Georgia. Regulatory Sandbox Guide.
https://nbg.gov.ge/en/page/regulatory-sandbox-guide

National Bank of Georgia. Financial Innovation Office.
https://nbg.gov.ge/en/page/financial-innovation-office

National Bank of Georgia. Open Banking and Non-Banking Institutions.
https://nbg.gov.ge/en/media/news/nbg-invites-non-banking-institutions-to-open-banking

World Bank. Digital Payments in Georgia: Bolstering the Regulatory Environment and Developing Infrastructure for an Inclusive Future.
https://www.worldbank.org/en/news/feature/2023/10/02/digital-payments-in-georgia-bolstering-the-regulatory-environment-and-developing-infrastructure-for-an-inclusive-future

McKinsey & Company. Enduring Ideas: The Three Horizons of Growth.
https://www.mckinsey.com/capabilities/strategy-and-corporate-finance/our-insights/enduring-ideas-the-three-horizons-of-growth
