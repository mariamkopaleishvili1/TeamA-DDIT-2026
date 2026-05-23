# Operating Model v1

## Purpose

This document defines the target operating model for a Georgian, bank-backed prediction-market platform. It is designed as Section 5 of the final project report.

The operating model is anchored on the recommended strategic option from the midterm:

> **Option 1: Regulatory Sandbox Pathway, with responsible-use controls embedded from day one.**

The recommended model is a GEL-settled, bank-backed prediction-market platform launched through NBG sandbox / pre-consultation first. VASP / USDC settlement remains a fallback or niche crypto-native route, not the default mass-market model.

---

## Strategic Anchor

The platform should not operate like a normal fintech app. It should operate like a supervised financial marketplace.

This matters because event contracts sit between several possible regulatory categories:

- financial instruments,
- virtual assets,
- gambling products,
- payment services,
- or a new supervised innovation category.

Therefore, the operating model must prioritize:

- NBG engagement before launch,
- clear market-approval rules,
- official event data sources,
- market-integrity monitoring,
- responsible-use controls,
- KYC / AML,
- payment-partner confidence,
- liquidity management,
- and regulator-ready audit trails.

The core operating process redesigned below is:

> **Event-contract market lifecycle management**

This process covers the full journey from proposing a market to listing, trading, monitoring, resolving outcomes, handling disputes, and reporting to regulators or payment partners.

---

# Part 1. Process Redesign

## Current state: the process as it operates today

### Name the process

**Event-contract market lifecycle management**

Because no regulated Georgian prediction-market platform currently exists, the current state is fragmented across adjacent substitutes: bank brokerage, crypto platforms, payment providers, and betting-style products. No single operating process currently governs event-contract design, legal review, liquidity, resolution, and responsible-use monitoring together.

| Decision point | Who decides | Information used | Failure mode |
|---|---|---|---|
| 1. Product / market idea selection | Product team, fintech founder, or business sponsor | Global examples such as Kalshi / Polymarket, user interest, news cycles, competitor observation | Product idea is copied from global platforms without adapting to Georgian regulation, consumer protection, or local payment realities |
| 2. Legal and regulatory classification | Legal counsel / compliance team, often after product concept is already formed | Gambling law, VASP rules, payment-service rules, securities-law interpretation, informal regulator feedback | Product may be misclassified as financial innovation when NBG or another authority may view it as gambling, unlicensed betting, or an unapproved virtual-asset activity |
| 3. Event design and outcome source selection | Product / research team | Public data sources, news sources, user demand, market relevance | Event is hard to resolve, politically sensitive, based on unclear data, or exposed to manipulation and disputes |
| 4. Liquidity, listing, and launch decision | Founder, treasury team, or product lead | Capital available, expected demand, informal market-maker interest | Market launches with thin liquidity, wide spreads, poor user experience, or excessive platform exposure |
| 5. User monitoring and responsible-use intervention | Compliance / fraud team if available; otherwise customer support reacts manually | KYC data, transaction history, complaints, manual alerts | Overtrading, multi-accounting, suspicious activity, or harmful user behavior is detected late |
| 6. Outcome resolution and dispute handling | Operations team or market creator | Official announcement, public result, manual interpretation | Outcome is disputed, payout is delayed, users lose trust, and regulator / payment partner concerns increase |

## Current process performance

- **Average time from start to decision:**  
  No standardized process exists. Estimated 5 to 15 business days for an informal product / legal / launch decision cycle, depending on legal review and availability of public data sources.  
  **Basis:** Analyst assumption because no regulated Georgian prediction-market operator currently exists.

- **Error rate or rework rate:**  
  High. Estimated 25% to 40% of proposed markets would require rework or rejection because of unclear source data, legal sensitivity, gambling resemblance, liquidity weakness, or poor event wording.  
  **Basis:** Analyst assumption based on the unresolved legal category and the repository’s identification of regulatory classification as a core barrier.

- **Customer impact of current failure modes:**  
  Users face confusing product positioning, unclear settlement rules, delayed payouts, wide spreads, and weak trust. If the product appears too similar to betting, mainstream users and payment partners may avoid it.

---

## Target state: the redesigned process

The redesigned process should create a formal **Market Lifecycle Governance Process** before any event contract is publicly listed.

### Target-state process logic

```text
Market idea
→ AI pre-screening
→ official data-source validation
→ legal / regulatory review
→ market design review
→ liquidity and exposure check
→ human approval
→ controlled listing
→ real-time monitoring
→ outcome resolution
→ dispute handling
→ regulator-ready reporting
```

| Decision point | AI handles | Human handles | Escalation threshold |
|---|---|---|---|
| 1. Market idea screening | Classifies proposed event into approved categories: macro, civic, financial-public-data, restricted, prohibited. Produces event-risk score from 0 to 100. | Market Governance Committee approves or rejects markets outside standard scope. | AI escalates if event-risk score is above 30 / 100, or if the event references sports, war outcomes, individual criminal cases, medical outcomes, non-public personal data, or politically sensitive entities. |
| 2. Data-source validation | Checks whether the event has an official source, clear publication time, machine-readable or verifiable output, and backup source. | Data Governance Lead approves source registry and backup-source protocol. | AI escalates if source-confidence score is below 95%, if more than one official source can produce conflicting results, or if the event source is not NBG, Geostat, CEC, or another pre-approved official source. |
| 3. Legal / regulatory classification | Matches event type against prior legal decisions, approved sandbox scope, prohibited market list, and NBG feedback log. | Legal counsel and Compliance Lead decide whether the market can proceed. | Escalation is required for any new event category, any market outside sandbox scope, any market involving NBG policy, elections, exchange rates, or a platform / bank conflict of interest. |
| 4. Market design and listing approval | Drafts contract language, user-facing explanation, risk warning, payout rule, and resolution rule. | Market Operations Lead and Market Governance Committee approve final listing. | Escalation is required if projected user exposure exceeds GEL 50,000 per market during sandbox, event resolution date is more than 90 days away, or contract text has AI confidence below 98%. |
| 5. Liquidity and market-quality monitoring | Monitors bid-ask spreads, order-book depth, concentration, market-maker performance, and price jumps. | Liquidity Manager and Market Integrity Lead intervene when thresholds are breached. | Escalation is required if bid-ask spread exceeds 8% for more than 30 minutes, order-book depth falls below GEL 10,000 on either side for a top-20 market, or one account cluster holds more than 25% of one side. |
| 6. Responsible-use monitoring | Scores user behavior based on deposits, losses, trade frequency, failed quizzes, cooling-off history, and disputes. | Responsible Use Lead reviews high-risk users and approves restrictions beyond automatic limits. | Automatic stop if user reaches GEL 100 daily loss limit. Escalation if user deposits more than GEL 500 in 24 hours during sandbox, makes more than 20 trades in one hour, or hits loss limit 3 times within 7 days. |
| 7. Outcome resolution | Pulls official result, compares with market rule, drafts resolution memo, and prepares user notification. | Resolution Committee approves final payout if any threshold is triggered. | Escalation if official result is delayed by more than 24 hours, AI extraction confidence is below 98%, more than 1% of active traders dispute the outcome, or more than 10 disputes are filed on one market. |

## Target process performance

- **Expected time from start to decision:**  
  - Standard low-risk market: 24 to 48 hours from proposal to listing approval.  
  - High-risk or new-category market: 5 to 10 business days because of legal and governance review.  
  **Basis:** Analyst assumption.

- **Expected error rate:**  
  - Rework rate for market wording / source selection reduced from estimated 25% to 40% to 10% to 15%.  
  - Disputed-resolution rate target: below 1% of active traders in a market.  
  **Basis:** Analyst assumption based on official source registry, standardized contract templates, and mandatory human review thresholds.

- **Basis for estimates:**  
  Analyst assumption. These estimates should be validated during the sandbox pilot using market approval logs, dispute logs, and liquidity monitoring data.

---

## Automation trap check

Confirm you redesigned the process rather than automating the existing one.

- **Did we start from the desired outcome and work backwards?**  
  Yes. The desired outcome is a regulator-ready, trusted, liquid, and responsibly controlled event-contract marketplace.

- **Did we eliminate steps that existed only because humans needed them?**  
  Yes. Manual first-pass event screening, source checking, and draft market explanations are replaced by AI-assisted workflow. Humans remain responsible for legal, regulatory, market-risk, and dispute decisions.

- **Is the escalation threshold specific and named?**  
  Yes. Examples include event-risk score above 30 / 100, source-confidence score below 95%, projected sandbox exposure above GEL 50,000, bid-ask spread above 8% for more than 30 minutes, GEL 100 daily loss limit, and more than 10 disputes on one market.

---

# Part 2. Team Structure

## Team design

| Team name | Mandate (one sentence) | Dataset owned | Agile level | Reporting line |
|---|---|---|---|---|
| Regulatory & Platform Governance | Own NBG engagement, legal classification, market-approval policy, and regulator-ready reporting. | NBG correspondence log, legal memo repository, approved event taxonomy, regulatory decision log, policy exception log | Governance / control function | Head of Regulatory & Governance → Prediction Market General Manager; dotted line to Chief Compliance Officer |
| Market Operations & Liquidity | Design, list, monitor, and resolve event-contract markets while maintaining liquidity and market quality. | Market registry, contract templates, order-book data, spread data, market-maker performance data, resolution logs | Product squad | Head of Market Operations → Prediction Market General Manager |
| Data, AI & Market Integrity | Build AI screening, market surveillance, risk scoring, data pipelines, model monitoring, and audit logs. | Event-source registry, AI model registry, feature store, anomaly alerts, account-linkage graph, manipulation alerts, model audit logs | Platform squad | Head of Data & AI → CTO / Chief Data Officer; dotted line to Chief Risk Officer |
| Payments, KYC & Settlement | Own GEL payment rails, wallet ledger, KYC / AML integration, settlement operations, and PSP / bank partner controls. | KYC records, payment transactions, wallet ledger, deposit / withdrawal logs, AML alerts, settlement records | Platform squad | Head of Payments & KYC → COO / Payments Lead; dotted line to Compliance |
| Responsible Use & Customer Trust | Own loss limits, cooling-off rules, user education, complaint handling, customer protection, and high-risk user review. | Responsible-use score dataset, limits history, cooling-off logs, complaints, disputes, education completion, support tickets | Product squad | Head of Customer Trust → Prediction Market General Manager; dotted line to Chief Risk Officer |
| Product, Engineering & UX | Build the user interface, admin tools, market-listing workflow, dashboards, and platform reliability layer. | Product analytics, onboarding funnel, clickstream data, feature flags, uptime logs, incident logs, user research data | Product squad | Product Lead / Engineering Lead → CTO and Prediction Market General Manager |
| Market Governance Committee | Approve high-risk markets, policy exceptions, AI model deployment, event categories, and dispute escalations. | Committee minutes, approval records, override logs, risk-acceptance register | Executive governance layer | Chaired by Prediction Market General Manager; reports to Executive Steering Committee |

---

## Single most important structural change

**Change:**  
Create a dedicated **Market Governance and AI Risk function** before AI deployment scales beyond a pilot.

**Reason it is a prerequisite:**  
AI will support event screening, source validation, market surveillance, responsible-use scoring, liquidity alerts, and resolution workflows. Without a formal governance function, AI outputs could become operational decisions without clear accountability. This would weaken regulator trust and increase legal, reputational, and market-integrity risk.

**H1 or H2 timeline:**  
H1, months 1 to 3.

**Estimated cost order of magnitude:**  
GEL 150,000 to GEL 300,000 initial setup cost, plus GEL 30,000 to GEL 50,000 monthly run cost during sandbox.

**Cost basis:**  
Analyst assumption. Cost includes legal counsel support, governance design, compliance setup, policy documentation, workflow tools, audit-log setup, and part-time senior risk / compliance involvement. This should be validated with Georgian legal counsel and bank compliance leadership.

---

## Incentive alignment

| Team | Current primary metric | New primary metric | Secondary metric added |
|---|---|---|---|
| Regulatory & Platform Governance | Speed of approval / legal sign-off | Percentage of markets launched with complete regulatory approval pack and audit trail | Number of regulator or payment-partner issues resolved within SLA |
| Market Operations & Liquidity | Number of markets launched | Percentage of markets meeting spread, depth, and resolution-quality targets | Share of markets with no disputes above 1% of active traders |
| Data, AI & Market Integrity | Model deployment speed | Percentage of AI alerts reviewed within defined SLA and false-positive / false-negative rate | Model audit completeness and override-log quality |
| Payments, KYC & Settlement | Successful onboarding and payment completion rate | Payment success rate with full KYC / AML compliance | Suspicious payment alerts resolved within SLA |
| Responsible Use & Customer Trust | Customer activity / trading volume | Percentage of high-risk users identified and controlled before harm threshold | Complaint resolution time and cooling-off compliance rate |
| Product, Engineering & UX | Feature delivery velocity | Safe activation rate: users onboarded, educated, and trading within approved limits | Uptime, incident rate, and onboarding drop-off |
| Market Governance Committee | Number of decisions completed | Percentage of high-risk decisions reviewed before launch or payout | Number of policy exceptions with documented rationale |

---

# Part 3. Roadmap Connection

## Roadmap logic

The target operating model follows two horizons:

- **H1: Months 1 to 6**  
  Build governance, manual controls, data foundations, AI-assisted screening, and sandbox readiness using current capabilities.

- **H2: Months 7 to 18**  
  Use pilot data and investment to scale AI-assisted market surveillance, responsible-use scoring, liquidity analytics, automated resolution support, and regulator-ready reporting.

The repository’s roadmap treats the prediction-market platform as a Horizon 2 / Horizon 3 bridge. Regulatory groundwork can start immediately, but full-scale launch depends on sandbox testing, legal classification, and market-integrity controls.

---

## Roadmap connection table

| Operating model item | Horizon tag | Roadmap initiative it enables | Dependency relationship |
|---|---|---|---|
| Create Market Governance and AI Risk function | H1 | Regulatory Sandbox Pathway; Regulatory Compliance Automation | Must precede |
| Define approved event taxonomy | H1 | AI-assisted event risk scoring; Prediction Market Platform | Must precede |
| Build official event-source registry | H1 | Outcome-resolution automation; Data synthesis for market settlement | Must precede |
| Draft standard market contract templates | H1 | Generative AI market explanations and risk warnings | Must precede |
| Define responsible-use rules and limits | H1 | Responsible-use scoring and customer protection workflow | Must precede |
| Build manual approval workflow with audit logs | H1 | Regulator-ready reporting and sandbox evidence pack | Must precede |
| Integrate KYC, AML, and GEL payment pathway design | H1 | Payment fraud detection; controlled sandbox onboarding | Must precede |
| Launch AI-assisted event-risk scoring prototype | H1 | Prediction Market Platform MVP | Enables |
| Build market surveillance dashboard | H2 | Market-integrity monitoring | Enables |
| Deploy liquidity and spread monitoring | H2 | Agent workflow for liquidity management | Enables |
| Deploy responsible-use scoring model | H2 | Responsible-use AI and customer trust controls | Enables |
| Automate regulator-ready reporting drafts | H2 | Regulatory Compliance Automation | Enables |
| Implement outcome-resolution automation | H2 | Multi-source event resolution and dispute handling | Enables |
| Build market-maker performance analytics | H2 | Liquidity management and market-maker governance | Enables |
| Add open-banking personalization layer | H2 | Open Banking-Powered Personalization | Enables |

---

## H1 operating model changes: Months 1 to 6

### H1 objective

Build a regulator-ready operating foundation before public launch.

### H1 changes

1. **Create Market Governance and AI Risk function**  
   - Enables: Regulatory Sandbox Pathway, AI governance, market approval workflow  
   - Output: committee charter, decision rights, escalation thresholds

2. **Define approved event taxonomy**  
   - Enables: event screening AI  
   - Output: approved, restricted, and prohibited event categories

3. **Build official event-source registry**  
   - Enables: outcome-resolution automation  
   - Output: source list covering NBG, Geostat, CEC, and other approved sources

4. **Draft standard market contract templates**  
   - Enables: generative AI explanations and consistent user disclosures  
   - Output: standard language for market question, event source, payout rule, risk warning

5. **Design responsible-use rules**  
   - Enables: customer protection and responsible-use AI  
   - Output: GEL 100 daily loss limit, GEL 500 daily deposit alert, cooling-off rules, quiz rules

6. **Build manual approval workflow with audit logs**  
   - Enables: regulator-ready reporting  
   - Output: approval log, override log, dispute log, policy exception log

7. **Integrate KYC / AML and GEL payment pathway design**  
   - Enables: controlled sandbox onboarding  
   - Output: payment and identity-control architecture

---

## H2 operating model changes: Months 7 to 18

### H2 objective

Move from manual control to AI-assisted supervised market operations after pilot data and regulator feedback.

### H2 changes

1. **Market-integrity automation**  
   - Enables: suspicious trading detection  
   - Output: price-jump alerts, account-concentration alerts, multi-account detection

2. **Liquidity automation**  
   - Enables: market-maker governance  
   - Output: spread alerts, depth monitoring, market-maker breach reports

3. **Responsible-use scoring model**  
   - Enables: harm prevention and payment-partner confidence  
   - Output: user risk score, limit recommendations, cooling-off triggers

4. **Resolution and reporting automation**  
   - Enables: faster settlement and NBG reporting  
   - Output: draft resolution memos, dispute summaries, regulator-ready reports

5. **Market-maker performance analytics**  
   - Enables: sustainable liquidity design  
   - Output: market-maker scorecards, subsidy estimates, spread-quality reporting

6. **Open-banking personalization layer**  
   - Enables: better onboarding, risk controls, and user segmentation  
   - Output: user-level affordability, personalization, and responsible-use insights

---

# Quality Check

Before finalising:

- **Both current state and target state are documented for the process, not only the target.**  
  Yes.

- **Every team has a named mandate, a named dataset, and a named agile level.**  
  Yes.

- **The single most important structural change is named and connected to a roadmap initiative.**  
  Yes. The structural change is the creation of a Market Governance and AI Risk function, connected to the Regulatory Sandbox Pathway and Regulatory Compliance Automation.

- **Every metric change names the old metric and the new metric.**  
  Yes.

- **Every operating model item is tagged H1 or H2.**  
  Yes.

---

# References

Bloomberg. (2025, October). *DraftKings and FanDuel face new challengers in daily fantasy sports*. https://www.bloomberg.com/news/articles/2025-10-28/draftkings-and-fanduel-face-new-challengers-in-daily-fantasy-sports

CoinDesk. (2024, November 12). *Polymarket crypto prediction market hits $1B in monthly volume for first time*. https://www.coindesk.com/markets/2024/11/12/polymarket-crypto-prediction-market-hits-1b-in-monthly-volume-for-first-time/

Gaming Intelligence. (2024, July). *Georgia tightens gambling regulations further*. https://www.gamingintelligence.com/regulation/georgia-tightens-gambling-regulations-further/

Georgian Foundation for Strategic and International Studies. (2024). *Georgia’s cryptocurrency regulation landscape*. https://www.gfsis.org.ge/publications/georgia-s-cryptocurrency-regulation-landscape

Georgian Stock Exchange. (2024). *Annual report 2024*. https://gse.ge/Uploads/2024%20Annual%20Report.pdf

Kalshi. (n.d.). *Platform documentation and fee structure*. https://www.kalshi.com/

National Bank of Georgia. (2025). *Financial Innovation Office*. https://www.nbg.gov.ge/en/pages/financial-innovation-office

National Bank of Georgia. (2025). *Financial Literacy Survey 2024*. https://www.nbg.gov.ge/uploads/pressreleases/2025/Financial_Literacy_Survey_2024.pdf

National Bank of Georgia. (2025). *Amendments to the Law on Operating of the Virtual Assets*. https://www.nbg.gov.ge/uploads/pressreleases/2025/Amendments_to_the_Law_on_Operating_of_the_Virtual_Assets.pdf

TBC Bank. (2024). *TBC Capital individual brokerage services*. https://www.tbcbank.ge/en/corporate/tbc-capital/tbc-capital-individuals

World Bank. (2022). *Financial Inclusion National Survey 2022: Georgia*. https://www.worldbank.org/en/country/georgia/publication/financial-inclusion-national-survey-2022
