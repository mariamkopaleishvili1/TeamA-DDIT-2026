# Risk Register, Responsible AI Reflection, and AI Tool Disclosure Appendix

## Project

Team A: Georgian Prediction-Market Platform  
Industry: Fintech  
Market: Republic of Georgia  
Client assumption: TBC-backed launch model  
Recommended strategic option: TBC-owned, GEL-settled prediction-market platform under an NBG special-designation or sandbox-first route

---

# 1. Risk Register

## 1.1 Risk register overview

The risk register covers the material risks that could prevent the prediction-market platform from becoming legally acceptable, operationally controllable, financially viable, or strategically valuable for TBC.

The main risk logic is simple:

> The platform should not scale unless it proves regulatory comfort, wallet control, user protection, market integrity, liquidity quality, official-source resolution, and unit economics in sandbox.

Likelihood and impact are scored qualitatively as Low, Medium, High, or Very High.

| # | Risk | Description | Likelihood | Impact | Mitigation | Owner function | Residual risk |
|---:|---|---|---|---|---|---|---|
| 1 | Regulatory or gambling reclassification risk | The platform may be viewed as gambling-like speculation rather than a supervised event-contract marketplace. This could block launch, create reputational risk, or force the product into an unsuitable licensing category. | High | Very High | Begin with NBG pre-consultation, use a sandbox-first or special-designation route, restrict early markets to official-source public outcomes, avoid sports-betting-style positioning, require legal review for every new market category, and maintain regulator-ready evidence. | Compliance Lead, Legal Counsel, Prediction Market Governance and AI Risk Committee | Medium |
| 2 | NBG engagement delay risk | NBG may require more time, more evidence, or a different classification path than expected. This could delay the roadmap and weaken first-mover timing. | Medium | High | Prepare a complete legal classification package, sample contracts, responsible-use framework, source registry, payment architecture, and sandbox scope before formal engagement. Include a board gate before further scale investment. | Compliance Lead, Legal Counsel, Regulatory Affairs | Medium |
| 3 | Wallet and payment control risk | Funding, withdrawal, settlement, or reconciliation may fail if the TBC-linked GEL wallet is not designed with platform-specific controls. Weak wallet design would weaken the entire TBC ownership story. | Medium | Very High | Build a TBC-linked GEL wallet flow, payment-hold procedure, withdrawal review process, reconciliation workflow, fraud-risk monitoring, user notice templates, and wallet event logs before sandbox. | Payments, KYC, and Settlement Lead | Medium |
| 4 | Mobile banking integration risk | The product may be integrated into the TBC mobile app as if it were a normal feature, making access too frictionless or risk warnings too weak. This could increase user harm, complaints, and regulatory concern. | Medium | High | Treat mobile banking integration as a governed workstream. Require eligibility gates, product education, risk quiz or acknowledgement, maximum-loss display, limit visibility, cooling-off messages, support entry point, and app-release governance approval. | Mobile Banking Product Lead, Compliance Lead, Responsible Use Lead | Medium |
| 5 | User harm and reputational risk | Users may trade impulsively, misunderstand risk, chase losses, or view the product as bank-endorsed gambling. This could damage TBC’s brand. | High | Very High | Implement deposit alerts, daily loss limits, exposure caps, cooling-off periods, self-exclusion, risk warnings, product education, support escalation, adverse-action notices, and human appeal process. Avoid promotional urgency and “easy money” language. | Responsible Use Lead, Customer Trust Lead, Compliance Lead | Medium |
| 6 | Liquidity cold-start risk | Users may not trust the market if spreads are wide, order books are shallow, or markets feel inactive. Low liquidity can reduce adoption even if the app works technically. | High | High | Fund a market-maker or liquidity-support programme, define quote obligations, monitor spreads and depth, set market-quality thresholds, and add warnings or pause rules when liquidity quality is weak. | Market Operations and Liquidity Lead | Medium |
| 7 | Market manipulation risk | Users or related-account clusters may attempt to manipulate thin markets, exploit information asymmetry, coordinate trading, or create artificial price signals. | Medium | High | Deploy market surveillance, related-account monitoring, concentration alerts, price-move alerts, suspicious trading escalation, manual investigation workflow, and market-pause authority. | Market Integrity Lead | Medium |
| 8 | Outcome-resolution dispute risk | Users may dispute the result if the source is delayed, revised, unavailable, or interpreted differently. Incorrect resolution would directly damage trust. | Medium | High | Apply “no official source, no market.” Every market needs an approved source, backup-source rule, resolution time, payout rule, dispute path, evidence archive, and Resolution Committee sign-off for exceptions. | Resolution Committee Chair, Market Operations Lead | Low to Medium |
| 9 | Contract wording and disclosure risk | Users may misunderstand the market because the contract wording, risk warning, source description, or payout rule is unclear. | Medium | High | Use standardized contract templates, bilingual wording review, AI-assisted drafting only with human approval, plain-language risk disclosures, user testing, and legal sign-off for new categories. | Market Operations Lead, Compliance Lead, Legal Counsel | Medium |
| 10 | AI false-positive restriction risk | AI-supported monitoring may incorrectly restrict users, hold payments, route users into cooling-off, or flag normal behavior as suspicious. | Medium | Medium to High | Require human review for high-impact decisions, track false positives, create user appeal routes, log reason codes, and review model performance monthly. | Head of Data and AI, Responsible Use Lead, Fraud and KYC Lead | Medium |
| 11 | AI false-negative risk | AI systems may fail to detect harmful trading patterns, fraud, manipulation, or liquidity problems. | Medium | High | Combine AI alerts with rules-based thresholds, manual review, market dashboards, sample audits, incident reviews, and conservative sandbox limits. | Head of Data and AI, Market Integrity Lead, Compliance Lead | Medium |
| 12 | Data protection and privacy risk | The platform processes KYC, wallet, payment, trading, responsible-use, dispute, and support data. Broad reuse of this data could create legal and trust issues. | Medium | High | Apply purpose limitation, data minimization, access controls, encryption, audit logs, consent controls where needed, and separate safety/compliance data from marketing use. | Data Governance Lead, Information Security Lead, Compliance Lead | Low to Medium |
| 13 | Customer support and dispute-handling risk | Support teams may mishandle payout disputes, wallet holds, account restrictions, responsible-use appeals, or legal complaints. | Medium | High | Build Customer Trust playbooks, Georgian and English scripts, escalation taxonomy, adverse-action templates, ticket routing, quality review, and SLA monitoring before sandbox. | Customer Trust Lead | Medium |
| 14 | Platform economics risk | Adoption, turnover velocity, take rate, payment costs, or liquidity subsidy may perform worse than the base case. Severe downside could result in no payback. | Medium | Very High | Use sandbox to validate active users, monthly turnover per user, funding flow, take rate, payment cost, liquidity cost, CAC, and contribution margin. Public launch requires board gate approval. | CFO, Prediction Market General Manager, Board Risk Committee | Medium |
| 15 | Cost of acquisition risk | If TBC cannot use mobile banking distribution effectively, CAC may be closer to standalone fintech economics than bank-backed economics. | Medium | High | Use controlled in-app distribution, customer education, TBC-owned wallet onboarding, referral restrictions during sandbox, and CAC tracking by channel. | Product Lead, Mobile Banking Product Lead, CFO | Medium |
| 16 | Partner dependency risk | External technology, liquidity, PSP, or foreign-platform partners may capture too much control or become operational bottlenecks. | Medium | High | Keep wallet ownership, user relationship, KYC, GEL settlement, event taxonomy, and regulator-facing governance inside TBC. Use partners only for specific support functions. | Prediction Market General Manager, Legal Counsel, Procurement | Medium |
| 17 | Change adoption risk | Product, compliance, legal, support, payments, data, and mobile banking teams may not adopt the new operating model. The platform could be technically built but operationally ungovernable. | Medium | High | Fund the Prediction Market Change Management Workstream, use role-based training, tabletop exercises, RACI maps, adoption dashboards, and stage-gate evidence before scale. | Transformation Office / PMO | Medium |
| 18 | Public communication and media risk | The platform may be publicly interpreted as TBC entering gambling or encouraging speculation. | Medium | High | Use careful positioning, regulator-first messaging, responsible-use evidence, official-source markets, avoidance of betting language, and board-approved communication plan. | Communications Lead, Compliance Lead, Prediction Market General Manager | Medium |
| 19 | Cybersecurity and wallet security risk | A security incident involving wallet balances, KYC data, or trading records would create financial and reputational harm. | Low to Medium | Very High | Apply bank-grade security review, penetration testing, access controls, encryption, monitoring, incident response, and third-party vendor review. | Information Security Lead | Low to Medium |
| 20 | Board decision delay risk | If the board delays the controlled launch path, foreign platforms, crypto wallets, betting operators, or another local bank may define the category first. | Medium | High | Present the decision as a staged investment, not immediate public launch. Approve H1 control foundation first, with later board gates for sandbox and public scale. | Board Sponsor, Prediction Market General Manager | Medium |

## 1.2 Risk register conclusion

The highest-priority risks are regulatory classification, user harm, wallet/payment control, liquidity, and platform economics. These risks are connected. A platform with weak wallet controls cannot prove trust. A platform with weak responsible-use controls may be treated like gambling. A platform with weak liquidity will not retain users. A platform with unclear event resolution will create disputes.

The mitigation logic is therefore not to launch faster. The mitigation logic is to prove control before scale.

---

# 2. Responsible AI Reflection

## 2.1 Purpose

This section is the Weekend 4 addition to the final report. It applies responsible AI principles to the H1 AI use cases required before sandbox trading begins.

The main principle is:

> AI should first protect trust, not predict outcomes.

For the prediction-market platform, AI should support screening, drafting, monitoring, routing, explaining, and reporting. It should not independently approve markets, restrict users for long periods, approve payouts, or send external regulator-facing reports.

The responsible AI reflection covers each H1 AI use case and states:

- bias or fairness risk;
- transparency obligation to affected individuals;
- accountability structure if the model produces an adverse outcome.

---

## 2.2 H1 AI use case 1: Event eligibility screening

### Use case

AI supports the initial review of proposed event markets. It checks whether the event fits the approved taxonomy, has an official source, avoids prohibited categories, and can be resolved objectively.

### Bias or fairness risk

The main fairness risk is category bias. The model may over-accept event types that are common on global prediction-market platforms but inappropriate for a Georgian bank-backed platform. It may also over-reject Georgian civic or macroeconomic events because they appear politically sensitive.

There is also geographic and language bias. If source information is stronger in English than Georgian, the system may treat Georgian-language sources as less reliable even when they are official.

### Transparency obligation

Users do not need to see the internal AI score. However, every listed market must disclose:

- the market question;
- the event category;
- the official source;
- the resolution rule;
- the resolution date or trigger;
- the risk warning;
- the dispute path.

The platform should not list a market without explaining how the outcome will be resolved.

### Accountability structure

AI may screen and flag, but it may not list a market.

Accountability sits with:

- Market Operations Lead for market preparation;
- Compliance Lead for regulatory and positioning review;
- Prediction Market Governance and AI Risk Committee for final approval of restricted or new categories.

If an inappropriate market is listed, the issue escalates to the Governance Committee. If the market creates regulatory concern, it escalates to Compliance, Legal, and the Board Risk Committee.

---

## 2.3 H1 AI use case 2: Contract drafting and risk-disclosure support

### Use case

AI drafts plain-language descriptions of event contracts, risk warnings, official-source explanations, and payout-rule summaries in Georgian and English.

### Bias or fairness risk

The main fairness risk is comprehension inequality. A contract may be formally correct but too difficult for entry-level users to understand. Users with lower financial literacy, weaker English skills, or less experience with trading may misunderstand the risk.

There is also promotional-language risk. AI-generated text may accidentally make the product sound like an opportunity to earn money rather than a defined-risk event contract.

### Transparency obligation

Before trading, users must see clear information about:

- what the market asks;
- what Yes and No mean;
- what the maximum possible loss is;
- what source resolves the outcome;
- when the outcome is resolved;
- whether the result can be delayed or revised;
- how to dispute an outcome.

The platform should disclose that user-facing explanations are standardized and reviewed, not personalized investment advice.

### Accountability structure

AI may draft, but it may not publish binding market text.

Accountability sits with:

- Market Operations Lead for contract wording;
- Compliance Lead for risk warnings;
- Legal Counsel for new or sensitive categories;
- Resolution Committee Chair for payout-rule clarity.

If unclear wording misleads users or causes disputes, the issue escalates to Customer Trust and Market Operations. If multiple users are affected, it escalates to the Governance Committee.

---

## 2.4 H1 AI use case 3: Responsible-use framework and intervention routing

### Use case

AI or rules-based monitoring identifies patterns that may require warnings, deposit alerts, cooling-off periods, trading restrictions, or human review.

### Bias or fairness risk

The main fairness risk is over-protection or under-protection.

Over-protection occurs when active but healthy users are restricted too aggressively. Under-protection occurs when users showing harmful patterns are not flagged. The model may also treat users differently based on payment method, device sharing, region, income proxy, or activity style.

There is also risk of behavioral bias. Users who trade frequently may be flagged even if they trade small amounts and understand the risk.

### Transparency obligation

Users must be told before first trade that the platform uses automated and manual controls to detect risky behavior.

If a responsible-use action affects the user, the platform must explain:

- what action was taken;
- the general reason category;
- how long the restriction lasts;
- whether the user can appeal;
- how to contact support.

The platform does not need to reveal the full detection logic because that could create gaming risk.

### Accountability structure

Accountability sits with:

- Responsible Use Lead for thresholds and interventions;
- Compliance Lead for regulator and payment-partner acceptability;
- Customer Trust Lead for user notices and appeals;
- Head of Data and AI for model monitoring.

If a user is incorrectly restricted, the appeal goes to the Responsible Use Lead. If false positives become repeated, thresholds and model behavior must be reviewed by the Governance Committee.

---

## 2.5 H1 AI use case 4: Payment, KYC, wallet, and fraud-risk monitoring

### Use case

AI supports detection of suspicious wallet funding, duplicate identities, payment failures, withdrawal risks, account-linkage patterns, and fraud signals.

### Bias or fairness risk

The main fairness risk is false-positive exclusion. Users with shared devices, irregular payment patterns, rural connectivity issues, new bank relationships, or non-standard funding behavior may be flagged more often than long-standing bank customers.

There is also financial inclusion risk. A strict model could make access easier for existing TBC customers and harder for newer or less digitally active users.

### Transparency obligation

Fraud and AML rules cannot be fully disclosed. However, affected users must be told when:

- onboarding is delayed;
- payment is held;
- withdrawal is delayed;
- account review is required;
- wallet access is restricted.

The notice should include a general reason category, expected review time, and a human support route where appropriate.

### Accountability structure

Accountability sits with:

- Fraud and KYC Lead for payment and identity review;
- Compliance Lead or MLRO for AML-sensitive cases;
- Payments, KYC, and Settlement Lead for wallet workflow;
- Customer Trust Lead for user notices.

If a user is wrongly blocked or a withdrawal is wrongly delayed, the case must be logged as a false positive and included in monthly review.

---

## 2.6 H1 AI use case 5: Market surveillance prototype

### Use case

AI or automated rules monitor test and sandbox markets for suspicious price movement, abnormal volume, concentration, related-account behavior, liquidity withdrawal, and possible manipulation.

### Bias or fairness risk

The fairness risk is unequal enforcement. New users, active users, or users trading in smaller markets may be flagged more often than professional or better-capitalized participants.

There is also risk that the model mistakes legitimate information-based trading for manipulation.

### Transparency obligation

Users do not need to see all surveillance logic. However, if surveillance leads to a market pause, account review, withdrawal hold, or trading restriction, affected users must receive a clear notice explaining:

- what action was taken;
- the general reason category;
- the review process;
- the expected review time;
- the appeal or support route if available.

### Accountability structure

AI may flag suspicious behavior, but it may not impose final sanctions.

Accountability sits with:

- Market Integrity Lead for investigation;
- Compliance Lead for severe cases;
- Governance Committee for account suspension, serious incidents, or regulator communication.

All surveillance investigations must produce an evidence bundle, action log, reviewer sign-off, and user notice if applicable.

---

## 2.7 H1 AI use case 6: Dispute triage and customer-support routing

### Use case

AI routes user messages and support tickets to the correct owner: Customer Trust, Payments, Responsible Use, Market Operations, Resolution Committee, or Compliance.

### Bias or fairness risk

The main risk is misclassification. The system may treat a serious payout dispute, financial distress message, or legal complaint as a routine support case. It may also perform less accurately in Georgian, mixed Georgian-English, slang, or short messages.

### Transparency obligation

Users should know when they are interacting with automated support or automated routing.

For sensitive issues, the platform must provide human escalation. Sensitive issues include:

- payout dispute;
- account freeze;
- withdrawal hold;
- fraud claim;
- responsible-use appeal;
- self-exclusion;
- gambling harm;
- financial distress;
- legal complaint.

### Accountability structure

Accountability sits with:

- Customer Trust Lead for routing quality;
- Responsible Use Lead for harm-related cases;
- Payments Lead for payment and wallet cases;
- Resolution Committee for payout disputes;
- Compliance Lead for legal or regulator-sensitive cases.

If AI routes a sensitive case incorrectly, the case should be logged and reviewed in the monthly support-quality review.

---

## 2.8 H1 AI use case 7: Reporting readiness and governance evidence

### Use case

AI supports the drafting and summarizing of internal governance reports, sandbox readiness packs, payment-partner summaries, and regulator-facing evidence packs.

### Bias or fairness risk

The main fairness and accountability risk is selective reporting. AI may summarize favorable metrics while under-emphasizing complaints, disputes, false positives, user restrictions, or unresolved incidents.

There is also data-context risk. If the input data is incomplete, the report may create false confidence for the board or regulators.

### Transparency obligation

Internal reviewers must know which parts of a report were AI-generated or AI-assisted.

External reports to NBG or payment partners must be human-reviewed and signed. Reports using user-identifiable data must follow data minimization and redaction procedures.

### Accountability structure

Accountability sits with:

- Regulatory and Platform Governance Lead for report preparation;
- Compliance Lead for external submission approval;
- Data Governance Lead for source data quality;
- Board Risk Committee for launch-gate interpretation.

AI may draft or summarize, but it may not submit external reports.

---

## 2.9 H1 AI use case 8: Mobile banking app integration controls

### Use case

AI-supported or rules-based logic helps control the mobile banking journey. This includes eligibility gates, product education prompts, risk quiz routing, responsible-use messages, payment-hold notices, and support routing inside the app.

### Bias or fairness risk

The main fairness risk is access inequality. The app may make access easier for existing digitally active TBC customers and harder for users who need more explanation, use different devices, or interact in Georgian-language support channels.

There is also behavioral risk. If personalization is used badly, it could encourage more trading rather than safer use.

### Transparency obligation

Users must be told before first trade that the platform uses automated controls for eligibility, wallet safety, responsible-use checks, market integrity, and support routing.

If an automated control affects access, funding, trading, withdrawal, settlement, or support routing, the app must provide:

- clear user-facing message;
- general reason category;
- next step;
- review timeline where applicable;
- route to human support.

### Accountability structure

Accountability sits with:

- Mobile Banking Product Lead for app journey and user messages;
- Compliance Lead for warning language and product positioning;
- Responsible Use Lead for limit and cooling-off messaging;
- Customer Trust Lead for support escalation;
- Head of Data and AI for model and rule monitoring.

If app-based controls create repeated confusion or complaints, the issue escalates to the Governance Committee before access is expanded.

---

## 2.10 Responsible AI conclusion

The responsible AI position is clear:

> AI should support a controlled marketplace. It should not become the final decision maker for high-impact user, market, payout, or regulatory decisions.

The platform’s early AI use cases should be judged by whether they improve:

- user understanding;
- fairness of access;
- market integrity;
- responsible-use protection;
- payout accuracy;
- support escalation;
- auditability;
- regulator and payment-partner confidence.

This is why AI is part of the control layer, not a separate technology story.

---

# 3. AI Tool Disclosure Appendix

## 3.1 Purpose

This appendix discloses the use of AI tools in the preparation of the final project materials.

AI tools were used substantially for drafting, restructuring, consistency checking, and synthesis. The team retained responsibility for selecting the strategic direction, reviewing the outputs, checking the logic against professor feedback, validating key numbers, and deciding what to include in the final report.

## 3.2 AI tools used

| Tool | How it was used | Sections supported |
|---|---|---|
| ChatGPT | Drafting, rewriting, synthesis of repository materials, consistency checking, speaker-note shortening, report-section structuring, and alignment with professor feedback. | Executive Summary, Industry and Competitive Analysis, Platform Strategy, Strategic Options, Business Model, ROI narrative, Roadmap, Governance, Change Management, Risk Register, Responsible AI Reflection, AI Tool Disclosure |
| GitHub-connected AI assistance | Repository review, locating related files, comparing sections, identifying missing deliverables, and preparing file-specific update instructions. | Final report assembly, repository consistency checks, WK2 to WK3 updates |
| Codex or code-assistant workflow | Intended for combining completed Markdown files into one final report, removing duplicates, and checking consistency across repository files. | Final report compilation and formatting |
| NotebookLM or infographic generation support | Used to create or test visual slide concepts and infographic layouts. | Final presentation visuals, platform dynamics visuals, regulatory unlock visuals, business model visuals |
| General AI-assisted writing tools | Used for wording refinement, shortening, and improving clarity in presentation and report materials. | Presentation speaker notes and selected narrative sections |

## 3.3 How AI outputs were verified

AI-generated outputs were not accepted as final without review.

The verification process included:

1. **Repository cross-checking**  
   Outputs were compared against the completed project files in `Deliverables WK3/Completed/`, including the ROI model, governance plan, roadmap, AI opportunity analysis, platform strategy, and industry analysis.

2. **Professor feedback alignment**  
   The final direction was adjusted to reflect feedback that the project needed a stronger TBC-specific story, clearer wallet logic, stronger mobile banking integration, and a clearer answer to why TBC should fund the platform instead of only partnering with international platforms.

3. **ROI consistency check**  
   Financial claims were checked against the updated ROI model. The final report should use the updated figures: 651,000 risk-active users, 65,100 base-case active users, GEL 6,546 monthly turnover per active user, GEL 4.26M monthly gross revenue, GEL 27.95M annual benefit, GEL 20.81M total investment to recover, 8.9-month payback, 99.9 percent IRR, and GEL 57.99M 5-year NPV.

4. **Scope check**  
   Sections were reviewed to remove unrelated banking AI use cases such as loan collections, SME credit scoring, generic robo-advisory, and generic bank automation unless explicitly identified as out of scope.

5. **Regulatory framing check**  
   AI outputs were adjusted to avoid presenting regulatory approval as guaranteed. The report uses the assumption that NBG may be open to exploring a special-designation or sandbox-first route, not that approval has already been granted.

6. **Responsible AI check**  
   AI use cases were reviewed to ensure that AI supports decisions but does not independently approve markets, freeze accounts, approve payouts, reject disputes, or submit external regulator-facing reports.

7. **Language and style check**  
   The final text was edited to use plain academic and consulting-report language. Overly promotional, poetic, or generic AI-sounding language was removed.

## 3.4 Human decisions retained by the team

The team retained control over:

- the final recommendation;
- the TBC-backed strategic framing;
- the decision to emphasize wallet ownership and mobile banking integration;
- the choice of the NBG special-designation or sandbox-first route;
- the scenario assumptions in the ROI model;
- the final selection of risks;
- the responsible AI position;
- the presentation storyline;
- the final report structure.

AI tools supported drafting and synthesis, but the team remained responsible for the content.

## 3.5 Limits of AI use

The AI tools were not used as primary factual authority. When factual or numerical claims were included, they were checked against project files, cited sources, or the team’s own research inputs.

AI outputs may contain incomplete assumptions if used without review. For that reason, all final sections should be checked against:

- the updated ROI model;
- the governance and change management plan;
- the roadmap;
- the responsible AI materials;
- the final presentation requirements;
- the team’s source list.

## 3.6 Disclosure statement for final report

The following statement may be included in the final report:

> AI tools were used to support drafting, restructuring, synthesis, visual planning, and consistency checking across the project materials. The team reviewed and edited the outputs, checked them against repository files and source materials, corrected scope errors, and retained responsibility for the final analysis, recommendations, financial assumptions, and conclusions. AI tools were not treated as independent factual authorities.