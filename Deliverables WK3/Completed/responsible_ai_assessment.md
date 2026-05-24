# Responsible AI Assessment

## Project

Team A — Georgian Prediction-Market Platform  
Industry: Fintech  
Market: Republic of Georgia  
Recommended strategic option: Regulatory Sandbox Pathway with responsible-use controls embedded from day one  
Submission file: `responsible_ai_assessment.pdf`  
Working Markdown file: `responsible_ai_assessment.md`

---

## 1. Purpose

This standalone document applies the EU AI Act framework and Responsible AI principles to the AI use-case portfolio in the transformation roadmap.

The assessment extends the governance plan by adding ethical and regulatory analysis for each AI use case. It evaluates:

- EU AI Act risk tier,
- bias and fairness risk,
- transparency obligation,
- accountability structure,
- Georgian personal data protection obligation,
- and measurable human override threshold.

The purpose is not only to show that the platform can technically deploy AI, but to show how the client can deploy AI responsibly in a regulated Georgian fintech context.

---

## 2. Scope

This assessment covers the AI use cases included in the roadmap:

1. Loan A/R Collections Optimization
2. Real-Time Payment Fraud Detection Upgrade
3. Customer Service Automation for Digital Banking
4. Wealth Management Robo-Advisory MVP
5. AI-Assisted Event Risk Scoring
6. Open Banking Personalization and Consent Foundation
7. AI Market Surveillance
8. Responsible-Use Scoring
9. Outcome Resolution and Regulator Reporting Automation
10. SME Credit Scoring Alternative Data Pilot
11. AI-First Regulatory Compliance Automation
12. Advanced Market-Integrity and Account-Linkage Graph

The prediction-market product itself is not treated as a single AI system. Instead, the assessment separates the AI systems that support the platform: event screening, market surveillance, responsible-use scoring, outcome resolution, fraud detection, and reporting automation.

---

## 3. Method

The assessment uses three reference layers.

### 3.1 EU AI Act-style risk classification

Each use case is classified as:

| Risk tier | Meaning in this assessment |
|---|---|
| Unacceptable | AI use should not be deployed because it is incompatible with rights, safety, or responsible use |
| High | AI may materially affect user access, financial activity, credit, payment access, trading restrictions, market integrity, or payout outcomes |
| Limited | AI interacts with users or generates content, but does not make final adverse decisions |
| Minimal | AI has low impact and does not affect user rights, financial access, or adverse decisions |

This project treats high-impact banking and platform decisions conservatively. If a model can restrict a user, influence credit, block payment access, pause markets, or affect payouts, it is treated as **High Risk** even if the strict legal classification may require further legal review.

### 3.2 Responsible AI principles

The assessment applies the following principles:

- fairness,
- transparency,
- accountability,
- reliability,
- privacy,
- inclusion,
- human oversight,
- contestability,
- market integrity,
- regulatory readiness.

### 3.3 Georgian law lens

The Georgian law obligation column is based on the **Law of Georgia on Personal Data Protection** and guidance from the Personal Data Protection Service of Georgia.

For this project, the recurring Georgian-law obligations are:

| Obligation | Operational meaning for this project |
|---|---|
| Lawful, fair, and purpose-specific processing | The platform must define why each category of personal data is processed and avoid using it for unrelated AI purposes |
| Privacy by design and by default | New product and AI workflows must minimize personal data by default and restrict access to only what is necessary |
| Data minimization | AI models should use only the data needed for the specific use case |
| Data security | Technical and organizational measures must protect data against unauthorized or unlawful processing, accidental loss, destruction, or damage |
| Data subject information and access | Users must be informed about processing and have an accessible route to request information or correction |
| Consent where required | Open-banking personalization and optional profiling should not proceed without clear user consent |
| Auditability | High-risk AI workflows need logs showing what data was used, what the model recommended, who reviewed it, and what decision was made |

This assessment is not a legal opinion. Final wording should be validated by Georgian legal counsel before submission or client use.

---

# 4. Portfolio-Level Assessment Summary

| AI use case | EU AI Act risk tier | Main reason |
|---|---|---|
| Loan A/R Collections Optimization | High | Affects credit treatment, collection escalation, and customer financial outcomes |
| Real-Time Payment Fraud Detection | High | May block payments, trigger holds, or restrict access to funds |
| Customer Service Automation | Limited | User-facing chatbot/content tool, but should not make final adverse decisions |
| Wealth Management Robo-Advisory MVP | Limited; High if it gives regulated investment advice automatically | Educational explanation is limited risk; automated suitability/recommendation becomes high risk |
| AI-Assisted Event Risk Scoring | Limited; High if it auto-approves/rejects markets | Decision-support is limited risk; autonomous listing control is high risk |
| Open Banking Personalization | High | Uses sensitive financial behavior and may shape product access, risk warnings, or affordability controls |
| AI Market Surveillance | High | May trigger market pauses, account reviews, trading restrictions, or manipulation investigations |
| Responsible-Use Scoring | High | May impose limits, cooling-off periods, or user restrictions |
| Outcome Resolution and Reporting Automation | High | Errors can affect payouts, disputes, and regulator trust |
| SME Credit Scoring | High | Affects credit access, pricing, and approval decisions |
| Regulatory Compliance Automation | Limited; High if it files or changes controls automatically | Drafting is limited risk; automatic filing/control execution becomes high risk |
| Advanced Market-Integrity and Account-Linkage Graph | High | Can identify related accounts, trigger sanctions, or support fraud/manipulation enforcement |

---

# 5. Detailed Responsible AI Assessment Matrix

## 5.1 Loan A/R Collections Optimization

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **High Risk** |
| Risk-tier rationale | The model affects credit treatment, collection priority, borrower contact strategy, and potential escalation from early delinquency to later-stage collections. It can influence user financial outcomes and treatment by the bank. |
| Bias and fairness risk | The model may over-prioritize borrowers from lower-income regions, unstable employment groups, or users with thin digital histories. It may also penalize users who transact mostly in cash or have irregular income patterns. |
| Bias mitigation | Disaggregate performance by region, income proxy, employment type, language, age band, and digital activity level. Require quarterly fairness audit. Remove features that act as strong proxies for protected or socioeconomic disadvantage unless legally justified and risk-approved. |
| Transparency obligation | If AI changes the customer’s treatment path, the customer should be informed that automated risk assessment was used to prioritize review or contact strategy. If a harsher collections action is taken, the notice should include the main reason categories: missed payment history, repayment pattern, account activity, or contact failure. |
| Accountability structure | **Head of Collections** owns operational use. **Credit Risk Lead** owns model risk. Escalation path: Collections Officer → Collections Team Lead → Credit Risk Lead → Model Governance Committee. |
| Georgian law obligation | Lawful and purpose-specific processing; data minimization; privacy by design; security of borrower financial data; explainable handling of customer information if challenged. |
| Human override threshold | Human review required if model recommends escalation to legal collection, restructuring refusal, or high-intensity contact for any borrower with exposure above GEL 5,000 or where repayment-history data completeness is below 95%. |
| Required control artifact | Collections AI decision log, reason-code record, human override log, monthly fairness dashboard. |
| Roadmap connection | Initiative 01: Loan A/R Collections Optimization; Initiative 06: Market Governance and AI Risk Function. |

---

## 5.2 Real-Time Payment Fraud Detection Upgrade

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **High Risk** |
| Risk-tier rationale | The model may block payments, delay withdrawals, freeze transactions, trigger step-up authentication, or restrict access to funds. This directly affects user access to payment services. |
| Bias and fairness risk | False positives may disproportionately affect users who travel, use older devices, live in border regions, transact at unusual hours, or have lower digital consistency. Users with shared family devices may be misclassified as suspicious. |
| Bias mitigation | Monitor false-positive rates by device type, region, time-of-day pattern, language preference, customer segment, and transaction channel. Tune thresholds separately for known benign patterns such as travel or shared-device use. |
| Transparency obligation | If a payment is held, the user must receive a clear notice that the transaction is under security review, the general trigger category, expected review time, and appeal/support route. Do not disclose fraud rules that would enable evasion. |
| Accountability structure | **Fraud Risk Lead** owns alert policy. **Payments, KYC & Settlement Lead** owns operational resolution. Escalation path: Fraud Analyst → Fraud Risk Lead → Compliance Lead → Chief Risk Officer delegate. |
| Georgian law obligation | Data security; purpose limitation for payment-risk data; audit trail for transaction monitoring; access control over payment and identity data; breach response if payment data is exposed. |
| Human override threshold | Human review required if payment hold exceeds 30 minutes, transaction value exceeds GEL 1,000, user has two false-positive holds within 30 days, or account freeze is proposed. |
| Required control artifact | Fraud alert log, payment hold register, false-positive dashboard, customer notice template. |
| Roadmap connection | Initiative 02: Real-Time Payment Fraud Detection Upgrade; Initiative 10: KYC, AML, and GEL Payment-Rail Design. |

---

## 5.3 Customer Service Automation for Digital Banking

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **Limited Risk** |
| Risk-tier rationale | The chatbot interacts with users and provides answers or routing. It should not make final decisions on payments, trading restrictions, credit, disputes, or complaints. The main obligation is user disclosure and human escalation. |
| Bias and fairness risk | Georgian-language users, minority-language users, older users, or users with low digital literacy may receive lower-quality support. The chatbot may misunderstand emotional distress, financial hardship, or dispute urgency. |
| Bias mitigation | Test answer quality in Georgian and English; monitor escalation rates by language, age proxy, and channel. Require human fallback on sensitive categories such as complaints, payout disputes, fraud, hardship, or responsible-use concerns. |
| Transparency obligation | Users must be clearly told they are interacting with AI. The interface must show a human-support option at all times. AI-generated answers must not be presented as legal, financial, or regulatory advice. |
| Accountability structure | **Customer Experience Lead** owns chatbot performance. **Product Lead** owns interface disclosure. Escalation path: Chatbot → Support Agent → Customer Trust Lead → Compliance if complaint involves adverse decision. |
| Georgian law obligation | Inform users about processing; limit conversation data to support purposes; avoid using support conversations for unrelated profiling without consent; protect chat logs as personal data. |
| Human override threshold | Immediate human handoff required if user mentions fraud, gambling harm, addiction, self-exclusion, complaint, legal threat, payout dispute, account freeze, or failed identity verification. |
| Required control artifact | Chatbot disclosure banner, escalation log, answer-quality review, conversation-retention policy. |
| Roadmap connection | Initiative 03: Customer Service Automation; Initiative 09: Responsible-Use and Customer Protection Framework. |

---

## 5.4 Wealth Management Robo-Advisory MVP

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **Limited Risk if educational; High Risk if suitability decisions are automated** |
| Risk-tier rationale | If the system only explains portfolios and teaches basic investing concepts, it is limited risk. If it recommends specific securities, portfolio allocation, risk classification, or suitability decisions without advisor review, it becomes high risk. |
| Bias and fairness risk | Users with low balances, lower financial literacy, or less complete transaction history may receive generic or overly conservative guidance. The model may also steer users toward products that fit bank economics rather than user needs. |
| Bias mitigation | Separate education from advice. Monitor recommendations by income proxy, age band, balance size, and risk profile. Require suitability review for any product-specific advice. |
| Transparency obligation | The user must be told whether the output is educational explanation, investment guidance, or regulated advice. If AI generates portfolio explanations, the app must label them as AI-assisted. |
| Accountability structure | **TBC Capital / Brokerage Lead** owns investment-content governance. **Compliance Lead** owns suitability boundary. Escalation path: AI output → Advisor review if product-specific → Brokerage Compliance → Investment Committee. |
| Georgian law obligation | Purpose-specific processing of financial profile data; data minimization; consent for using banking behavior in investment personalization; secure processing of portfolio and identity data. |
| Human override threshold | Human/advisor review required before any recommendation to buy, sell, rebalance, change risk category, or move more than GEL 1,000 into a specific investment product. |
| Required control artifact | Advice-boundary policy, AI output log, suitability review record, user disclosure. |
| Roadmap connection | Initiative 04: Wealth Management Robo-Advisory MVP; Initiative 13: Open Banking Personalization and Consent Foundation. |

---

## 5.5 AI-Assisted Event Risk Scoring

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **Limited Risk if advisory; High Risk if automated approval/rejection is allowed** |
| Risk-tier rationale | Event scoring is acceptable as decision support. It becomes high risk if it automatically approves or rejects market listings because market availability affects users, regulatory exposure, and reputational risk. |
| Bias and fairness risk | The system may over-flag politically sensitive Georgian events, under-flag imported global events, or misclassify civic events based on language ambiguity. It may also treat some event categories as safe because global platforms list them, even if Georgian regulation is different. |
| Bias mitigation | Use a Georgian-specific prohibited-market taxonomy. Require bilingual review for Georgian and English event wording. Compare AI classification against human compliance review. Keep VASP, gambling, sports, war, medical, and private-person events in restricted categories. |
| Transparency obligation | Users do not need to see internal risk scores, but listed markets should disclose why the event is eligible: official source, resolution date, payout rule, and risk warning. Regulators and payment partners should receive the event approval log. |
| Accountability structure | **Market Governance Committee** owns final listing. **Compliance Lead** owns legal classification. Escalation path: AI score → Market Operations review → Compliance review → Market Governance Committee. |
| Georgian law obligation | Privacy by design if user demand or behavior data informs event selection; purpose limitation for market-interest analytics; avoid using personal data to infer political preference without a lawful basis. |
| Human override threshold | Human review required if event-risk score exceeds 30/100, source-confidence score is below 95%, projected exposure exceeds GEL 50,000 during sandbox, or market category is new/restricted. |
| Required control artifact | Event-risk score log, source-confidence record, approval memo, override register. |
| Roadmap connection | Initiative 07: Data Governance and Official Event-Source Registry; Initiative 11: MVP Market Listing Workflow; Initiative 12: AI-Assisted Event Risk Scoring Prototype. |

---

## 5.6 Open Banking Personalization and Consent Foundation

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **High Risk if used for affordability, eligibility, or responsible-use controls; Limited Risk if used only for generic education** |
| Risk-tier rationale | Open-banking data can reveal income, spending, debt burden, financial stress, and behavioral patterns. If used to shape access, warnings, limits, or product offers, it can materially affect users. |
| Bias and fairness risk | Users with irregular income, informal employment, cash-heavy behavior, rural payment patterns, or low digital banking usage may be misclassified as higher risk or lower value. |
| Bias mitigation | Require consent-based personalization. Do not use open-banking data as the sole basis for restrictions. Compare model outcomes across income patterns, region, age bands, and digital activity levels. |
| Transparency obligation | Users must be told what banking data is used, for what purpose, for how long, whether it affects personalization or restrictions, and how consent can be withdrawn. |
| Accountability structure | **Open Banking Lead** owns consent architecture. **Data Protection Officer / Privacy Owner** owns lawful processing controls. Escalation path: Product Owner → Open Banking Lead → DPO/Privacy Owner → Compliance. |
| Georgian law obligation | Explicit consent where required; purpose limitation; data minimization; privacy by design/default; access logs; user rights to information/correction; secure processing of financial behavior data. |
| Human override threshold | Human review required if personalization logic would impose a restriction, affordability warning, or exclusion based on open-banking data, or if data completeness is below 90%. |
| Required control artifact | Consent register, data-use map, opt-out log, open-banking DPIA-style assessment. |
| Roadmap connection | Initiative 13: Open Banking Personalization and Consent Foundation. |

---

## 5.7 AI Market Surveillance

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **High Risk** |
| Risk-tier rationale | The model detects manipulation, suspicious trading, price jumps, concentration, related accounts, and abnormal market behavior. It can trigger account review, market pause, or regulatory reporting. |
| Bias and fairness risk | Active traders, professional users, crypto-native users, users with shared devices, and users trading during unusual hours may be over-flagged. New users may be under-flagged due to limited history. |
| Bias mitigation | Monitor alert rates by account age, device type, trading frequency, geography, payment method, and market category. Separate “high activity” from “suspicious activity.” Require human investigation before sanctions. |
| Transparency obligation | Users do not need disclosure of surveillance rules, but must be informed if a surveillance alert leads to restriction, account review, market pause affecting positions, or delayed withdrawal. |
| Accountability structure | **Market Integrity Lead** owns surveillance actions. **Head of Data & AI** owns model performance. Escalation path: Surveillance alert → Market Integrity Analyst → Market Integrity Lead → Compliance / Market Governance Committee. |
| Georgian law obligation | Purpose-specific processing of trading data; data security; access control; audit trail for surveillance decisions; privacy by design/default for account-linkage analytics. |
| Human override threshold | Human review required if price moves more than 20 percentage points in 15 minutes without verified public news, one account cluster holds more than 25% of one side, or market pause would exceed 30 minutes. |
| Required control artifact | Surveillance alert log, investigation memo, market-pause register, model drift dashboard. |
| Roadmap connection | Initiative 16: AI Market Surveillance and Responsible-Use Scoring; Initiative 23: Advanced Market-Integrity and Account-Linkage Graph. |

---

## 5.8 Responsible-Use Scoring

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **High Risk** |
| Risk-tier rationale | The model may lead to deposit limits, cooling-off periods, trading restrictions, risk warnings, or account review. It directly affects user access and consumer protection. |
| Bias and fairness risk | The model may over-flag users with low income, irregular work schedules, high engagement but low losses, or culturally different payment behavior. It may under-flag affluent users who can lose more money but show fewer standard risk signals. |
| Bias mitigation | Use behavior-based signals rather than demographic proxies. Test outcomes by age band, region, income proxy, device type, and account tenure. Keep hard limits transparent and uniform during sandbox. |
| Transparency obligation | Users must be informed before trading about loss limits, deposit alerts, cooling-off periods, and what behavior can trigger a review. Any restriction must include reason code, duration, and appeal route. |
| Accountability structure | **Responsible Use Lead** owns interventions. **Customer Trust Lead** owns user communication. Escalation path: AI score → Responsible Use Review Queue → Responsible Use Lead → Compliance if restriction is extended. |
| Georgian law obligation | Purpose limitation for responsible-use data; data minimization; transparent user notice; secure processing of behavioral and payment data; user ability to request information about restrictions. |
| Human override threshold | Human review required if user deposits more than GEL 500 in 24 hours, makes more than 20 trades in one hour, hits GEL 100 daily loss limit 3 times in 7 days, or restriction would last longer than 48 hours. |
| Required control artifact | Responsible-use trigger log, adverse action notice, appeal log, fairness dashboard. |
| Roadmap connection | Initiative 09: Responsible-Use and Customer Protection Framework; Initiative 16: AI Market Surveillance and Responsible-Use Scoring. |

---

## 5.9 Outcome Resolution and Regulator Reporting Automation

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **High Risk** |
| Risk-tier rationale | Outcome resolution affects payouts. Reporting automation affects regulator and payment-partner trust. A wrong result extraction or incomplete evidence pack can create financial, legal, and reputational harm. |
| Bias and fairness risk | Bias risk is lower demographically but high operationally. Georgian-language sources, delayed official publications, revised data, or ambiguous event wording could produce inconsistent outcomes. Users in less-informed groups may be less able to dispute errors. |
| Bias mitigation | Use only pre-approved official sources. Require bilingual verification for Georgian-language source extraction. Keep a 48-hour dispute window for eligible markets. Publish plain-language resolution memos. |
| Transparency obligation | Every market must disclose official source, resolution date/time, payout rule, dispute process, and whether AI assisted with result extraction. If payout is delayed, users must receive reason and expected review timeline. |
| Accountability structure | **Resolution Committee Chair** owns final payout decisions. **Regulatory & Platform Governance Lead** owns reporting. Escalation path: AI extraction → Data Governance verification → Resolution Committee → Compliance/NBG reporting. |
| Georgian law obligation | Data accuracy; data security; auditability; purpose limitation for dispute and payout data; user information rights if personal data is involved in payout delay or dispute handling. |
| Human override threshold | Human verification required if AI extraction confidence is below 98%, official result is delayed more than 24 hours, source is revised within 48 hours, more than 10 disputes are filed, or more than 1% of active traders in a market dispute the result. |
| Required control artifact | Resolution memo, official-source evidence archive, dispute register, regulator-ready audit pack. |
| Roadmap connection | Initiative 17: Outcome Resolution and Regulator Reporting Automation. |

---

## 5.10 SME Credit Scoring Alternative Data Pilot

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **High Risk** |
| Risk-tier rationale | Credit scoring affects access to finance, pricing, limits, and approval decisions for SMEs. Under EU AI Act-style logic, credit access is a high-risk area. |
| Bias and fairness risk | The model may disadvantage SMEs outside Tbilisi, cash-heavy businesses, women-owned businesses if historical lending patterns are biased, new firms, seasonal firms, or businesses with thin digital data. |
| Bias mitigation | Validate model performance by region, sector, firm age, owner profile where legally permitted, turnover volatility, and banking history. Require explainability and compare model output to human credit committee decisions. |
| Transparency obligation | If the model contributes to rejection, lower limit, or worse pricing, the SME must receive an adverse action notice with the main reason categories and a human review channel. |
| Accountability structure | **Credit Risk Lead** owns model use. **Credit Committee** owns final lending decision. Escalation path: AI score → Credit Officer review → Credit Risk Lead → Credit Committee. |
| Georgian law obligation | Lawful and purpose-specific processing of SME and owner personal data; data minimization; transparency notice; accuracy of credit-relevant data; security; human review for materially adverse automated decisions. |
| Human override threshold | Human credit officer review required for every rejection, limit reduction, pricing deterioration above 2 percentage points, or application above GEL 50,000. |
| Required control artifact | Credit model validation report, adverse action notice, human review record, bias monitoring dashboard. |
| Roadmap connection | Initiative 18: SME Credit Scoring Alternative Data Pilot. |

---

## 5.11 AI-First Regulatory Compliance Automation

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **Limited Risk if drafting only; High Risk if it submits filings or changes controls automatically** |
| Risk-tier rationale | Drafting reports and monitoring rules is limited risk. Automatically submitting regulatory reports or changing compliance controls is high risk because it may misrepresent the platform’s regulatory position. |
| Bias and fairness risk | The model may over-rely on English-language or EU sources, underweight Georgian-language legal updates, or misinterpret NBG guidance. It may also hallucinate legal obligations if not grounded in approved sources. |
| Bias mitigation | Use retrieval from approved legal sources only. Require Georgian-language legal review. Maintain source citations and version history. Do not allow automatic submission. |
| Transparency obligation | Internal users must know when a report or legal summary was AI-generated. Any regulator-facing output must be human-reviewed and signed off before submission. |
| Accountability structure | **Compliance Lead** owns filings. **Regulatory & Platform Governance Lead** owns reporting workflow. Escalation path: AI draft → Compliance review → Legal review if needed → Authorized signatory. |
| Georgian law obligation | Accuracy and accountability in processing compliance data; security of regulatory documents; access control; no reuse of personal data in compliance summaries beyond stated purpose. |
| Human override threshold | Human sign-off required for 100% of regulator-facing filings, legal classification updates, NBG communication, payment-partner reports, or changes to compliance controls. |
| Required control artifact | AI-generated report log, source citation archive, legal review checklist, sign-off record. |
| Roadmap connection | Initiative 17: Outcome Resolution and Regulator Reporting Automation; Initiative 22: AI-First Regulatory Compliance Automation. |

---

## 5.12 Advanced Market-Integrity and Account-Linkage Graph

| Item | Assessment |
|---|---|
| EU AI Act risk tier | **High Risk** |
| Risk-tier rationale | Account-linkage graphs can identify related accounts, suspected manipulation, multi-accounting, insider-risk clusters, and potential coordinated trading. Outputs may lead to account freezes, withdrawal holds, sanctions, or regulator reports. |
| Bias and fairness risk | Shared households, family devices, university networks, workplace IP addresses, or rural shared connectivity may be falsely classified as coordinated manipulation. Crypto-native users may also be over-flagged due to wallet behavior. |
| Bias mitigation | Require multiple independent signals before enforcement: device, payment instrument, behavior timing, account metadata, and trade pattern. Do not sanction based on IP/device alone. Monitor false positives by household/device-sharing indicators. |
| Transparency obligation | Do not disclose detection logic in detail, but users must receive notice if account linkage contributes to restriction, withdrawal hold, suspension, or dispute outcome. |
| Accountability structure | **Market Integrity Lead** owns investigations. **Fraud/KYC Lead** owns identity and account-linkage review. Escalation path: Graph alert → Market Integrity Analyst → Fraud/KYC review → Compliance → Market Governance Committee for severe cases. |
| Georgian law obligation | Privacy by design/default; data minimization; purpose limitation; strict access controls for identity and behavioral graph data; security measures to prevent unauthorized processing. |
| Human override threshold | Human review required if related-account confidence exceeds 80%, if a withdrawal hold would exceed 30 minutes, if more than GEL 1,000 is affected, or if account suspension is proposed. |
| Required control artifact | Account-linkage investigation log, evidence bundle, human approval record, appeal route. |
| Roadmap connection | Initiative 23: Advanced Market-Integrity and Account-Linkage Graph. |

---

# 6. Cross-Cutting Bias and Fairness Register

| Bias category | Where it may appear | Mitigation |
|---|---|---|
| Geographic bias | Collections, SME scoring, fraud detection, responsible-use scoring | Segment testing by region, urban/rural pattern, and payment-channel access |
| Digital-access bias | Chatbot, open banking, fraud detection, robo-advisory | Human fallback channel; non-digital support route; device-type monitoring |
| Income-proxy bias | Collections, responsible use, SME scoring, personalization | Avoid using income proxy as sole adverse factor; review disparate impacts |
| Language bias | Customer service, event scoring, regulatory automation, outcome resolution | Georgian-language testing; bilingual review; plain-language UX review |
| Behavioral bias | Market surveillance, responsible-use scoring, account-linkage graph | Distinguish high activity from suspicious activity; require multi-signal confirmation |
| Historical-data bias | Collections, SME scoring, robo-advisory | Compare outcomes to policy goals; review historical patterns before training |
| Shared-device bias | Fraud detection and account-linkage graph | Do not sanction based only on IP/device; require payment and behavioral corroboration |

---

# 7. Transparency and User Notice Standard

## 7.1 When disclosure is required

The organization must disclose AI use when:

- a chatbot interacts with the user,
- AI generates market explanations,
- AI contributes to a trading restriction,
- AI contributes to a deposit limit or cooling-off period,
- AI contributes to payment hold or account freeze,
- AI contributes to credit scoring,
- AI contributes to payout delay or dispute handling,
- AI contributes to user personalization using open-banking data.

## 7.2 Adverse action notice contents

Every adverse action notice should include:

1. action taken,
2. whether AI-supported review contributed,
3. main reason code,
4. data category considered,
5. duration of restriction or delay,
6. human review owner,
7. appeal route,
8. expected review timeline.

## 7.3 Example notice

```text
Your trading access has been temporarily limited because your account reached the sandbox daily loss limit. This limit is part of the platform’s responsible-use controls. AI-supported monitoring detected the threshold, but the rule applies automatically to all sandbox users and was disclosed before trading. You may continue to view markets, but trading will reopen after the cooling-off period. If you believe this was applied incorrectly, you may request a human review through Customer Support.
```

---

# 8. Accountability Structure

| AI use case | Accountable owner | Escalation path |
|---|---|---|
| Collections Optimization | Head of Collections | Collections Officer → Team Lead → Credit Risk Lead → Model Governance Committee |
| Payment Fraud Detection | Fraud Risk Lead | Fraud Analyst → Fraud Risk Lead → Compliance → Chief Risk Officer delegate |
| Customer Service Automation | Customer Experience Lead | Chatbot → Support Agent → Customer Trust Lead → Compliance if complaint |
| Robo-Advisory MVP | TBC Capital / Brokerage Lead | AI output → Advisor review → Brokerage Compliance → Investment Committee |
| Event Risk Scoring | Market Governance Committee | AI score → Market Operations → Compliance → Market Governance Committee |
| Open Banking Personalization | Open Banking Lead | Product Owner → Open Banking Lead → DPO/Privacy Owner → Compliance |
| Market Surveillance | Market Integrity Lead | Alert → Market Integrity Analyst → Market Integrity Lead → Compliance |
| Responsible-Use Scoring | Responsible Use Lead | AI score → Review Queue → Responsible Use Lead → Compliance |
| Outcome Resolution | Resolution Committee Chair | AI extraction → Data Governance → Resolution Committee → Compliance/NBG reporting |
| SME Credit Scoring | Credit Risk Lead | AI score → Credit Officer → Credit Risk Lead → Credit Committee |
| Regulatory Compliance Automation | Compliance Lead | AI draft → Compliance Review → Legal Review → Authorized Signatory |
| Account-Linkage Graph | Market Integrity Lead + Fraud/KYC Lead | Graph alert → Market Integrity → Fraud/KYC → Compliance → Governance Committee |

---

# 9. Human Override Threshold Register

| AI use case | Human override threshold |
|---|---|
| Loan A/R Collections Optimization | Exposure above GEL 5,000, legal escalation, restructuring refusal, or training data completeness below 95% |
| Real-Time Payment Fraud Detection | Payment hold above 30 minutes, transaction above GEL 1,000, two false-positive holds in 30 days, or account freeze proposed |
| Customer Service Automation | Any mention of fraud, gambling harm, addiction, complaint, legal threat, payout dispute, account freeze, or failed identity verification |
| Wealth Management Robo-Advisory | Any recommendation to buy/sell/rebalance, change risk category, or move more than GEL 1,000 into a product |
| AI-Assisted Event Risk Scoring | Event-risk score above 30/100, source-confidence below 95%, projected exposure above GEL 50,000, or new/restricted category |
| Open Banking Personalization | Any restriction, affordability warning, exclusion, or data completeness below 90% |
| AI Market Surveillance | Price move above 20 percentage points in 15 minutes, account cluster above 25% of one side, or pause above 30 minutes |
| Responsible-Use Scoring | Deposit above GEL 500 in 24 hours, more than 20 trades/hour, GEL 100 loss limit hit 3 times in 7 days, or restriction above 48 hours |
| Outcome Resolution | AI confidence below 98%, result delayed more than 24 hours, source revised within 48 hours, more than 10 disputes, or more than 1% trader dispute rate |
| SME Credit Scoring | Rejection, limit reduction, pricing deterioration above 2 percentage points, or application above GEL 50,000 |
| Regulatory Compliance Automation | 100% of regulator-facing filings, NBG communication, legal classification updates, and control changes |
| Account-Linkage Graph | Related-account confidence above 80%, withdrawal hold above 30 minutes, more than GEL 1,000 affected, or suspension proposed |

---

# 10. Georgian Law Compliance Control Map

| Georgian personal data protection obligation | Implementation control |
|---|---|
| Lawful and purpose-specific processing | Data-use register for each AI model |
| Privacy by design and by default | Product launch checklist requiring data minimization and default access restrictions |
| Data minimization | Feature approval list for each model; unnecessary personal fields blocked |
| Security of processing | Role-based access control, encryption, access logs, incident response plan |
| Data accuracy | Data-quality thresholds before training and inference |
| Transparency and data subject information | Privacy notice, AI disclosure, adverse action notice |
| Consent where needed | Open-banking consent register and opt-out workflow |
| User rights | Support route for information, correction, appeal, and deletion where legally applicable |
| Accountability | Named model owner, data owner, and decision owner |
| Auditability | AI decision log, model registry, training dataset register, human override log |

---

# 11. Implementation Priorities

## Priority 1: Before any sandbox trading

The following controls must exist before users trade:

- Market Governance Committee,
- AI Model Registry,
- Event Source Registry,
- Responsible-Use Policy,
- Adverse Action Notice template,
- Human Override Protocol,
- KYC/AML and payment-risk review,
- chatbot escalation rules,
- official market contract templates.

## Priority 2: During sandbox

The following controls must be active during the pilot:

- market surveillance dashboard,
- responsible-use trigger log,
- payment fraud false-positive tracking,
- model performance dashboard,
- dispute and payout audit trail,
- monthly governance report,
- bias and fairness dashboard.

## Priority 3: Before public launch

The following controls must be completed before public launch:

- external model-risk review,
- full legal review of event-contract classification,
- regulator-ready reporting pack,
- payment-partner risk approval,
- final responsible-use policy,
- board approval of risk appetite,
- final unit-economics gate.

---

# 12. Final Risk View

| Use case | Residual risk after controls | Reason |
|---|---|---|
| Collections Optimization | Medium | High impact on borrowers, but risk is controllable with human review |
| Payment Fraud Detection | Medium | False positives remain likely, but payment holds can be reviewed quickly |
| Customer Service Automation | Low-Medium | Risk is manageable if chatbot cannot make final decisions |
| Robo-Advisory MVP | Medium | Risk rises if educational content becomes advice |
| Event Risk Scoring | Medium | Human committee approval prevents autonomous market listing |
| Open Banking Personalization | Medium-High | Sensitive financial behavior data requires strict consent and minimization |
| Market Surveillance | High | Manipulation detection is necessary but enforcement mistakes can harm users |
| Responsible-Use Scoring | High | Strong consumer-protection value, but high risk of overrestriction or stigma |
| Outcome Resolution | High | Payout errors directly harm trust and platform legitimacy |
| SME Credit Scoring | High | Credit access is a high-impact decision |
| Regulatory Compliance Automation | Medium | Drafting risk is manageable; automatic filing should be prohibited |
| Account-Linkage Graph | High | Graph errors can falsely associate users with manipulation |

---

# 13. Conclusion

The AI portfolio can support the Georgian prediction-market strategy, but only if the client treats AI governance as decision governance rather than IT governance.

The highest-risk systems are not the chatbot or content-generation tools. The highest-risk systems are:

- market surveillance,
- responsible-use scoring,
- outcome resolution,
- payment fraud detection,
- account-linkage graph,
- and SME credit scoring.

These systems can affect user access, payment access, trading rights, payout outcomes, and credit decisions. Therefore, they require human oversight, audit trails, adverse action notices, measurable override thresholds, and clear accountability.

The platform should not move to public launch until the responsible AI controls are tested in sandbox conditions and reviewed by the board.

---

# 14. References

European Commission. (2026). *AI Act*. Shaping Europe’s Digital Future. https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai

European Union. (2024). *Regulation (EU) 2024/1689 laying down harmonised rules on artificial intelligence*.

Organisation for Economic Co-operation and Development. (2019). *OECD principles on artificial intelligence*.

Personal Data Protection Service of Georgia. (2024). *Current Law of Georgia on Personal Data Protection*. https://pdps.ge/content/1063/LAWS

Personal Data Protection Service of Georgia. (2024). *Guide for business: Compliance assurance*. https://pdps.ge/content/1085/nawili-III.-kanonSesabamisobis-uzrunvelyofa

Personal Data Protection Service of Georgia. (2024). *Guide for business: Personal data security*. https://pdps.ge/content/1086/nawili-IV.-personalur-monacemTa-usafrTxoebis-dacva

Westerman, G., Bonnet, D., & McAfee, A. (2014). *Leading digital: Turning technology into business transformation*. Harvard Business Review Press.
