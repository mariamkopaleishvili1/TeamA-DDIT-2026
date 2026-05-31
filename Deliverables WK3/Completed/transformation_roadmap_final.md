# 18-Month Transformation Roadmap

Submission file: transformation_roadmap_final.pdf or transformation_roadmap_final.xlsx

## Post-Presentation Update Note

This roadmap reflects the final post-presentation strategy update. The platform is now framed as a TBC-owned, GEL-settled, mobile-banking-integrated event-contract marketplace, rather than a standalone fintech app. The roadmap therefore places data governance, NBG engagement, wallet design, responsible-use controls, and mobile banking integration before any public-scale launch.

## Purpose

This document sets out the 18-month transformation roadmap for a Georgian, bank-backed prediction-market platform.

The roadmap becomes Section 7 of the final project report. It is scoped only to the prediction-market platform and the capabilities required to launch it responsibly. It does not include unrelated bank AI initiatives such as collections optimization, SME credit scoring, robo-advisory, or generic customer-service automation.

The recommended strategic option is:

> TBC-owned, GEL-settled, mobile-banking-integrated prediction-market platform under an NBG special-designation or sandbox-first route, with responsible-use controls embedded from day one.

The strategic logic is that a Georgian prediction-market platform cannot be treated as a normal mobile app launch. It is closer to building a supervised event-contract marketplace. The product needs regulatory engagement, payment rails, market approval rules, market surveillance, liquidity support, outcome resolution, responsible-use controls, and a clear decision gate before public launch.

---

## 1. Roadmap Logic

The first six months should not be spent trying to maximize user growth. They should be spent making the product legally, operationally, and reputationally testable.

The roadmap therefore follows a staged sequence.

Months 1 to 6 build the control foundation: governance, regulatory engagement, official source registry, market taxonomy, contract templates, responsible-use rules, payment and KYC design, and an MVP workflow.

Months 7 to 18 test the platform in a controlled sandbox. This phase measures whether users understand the product, whether payments work, whether markets are liquid enough, whether disputes stay low, whether responsible-use controls work, and whether unit economics can support eventual scale.

Post-18-month activities remain options. Public launch should only happen if the sandbox shows a credible regulatory path, acceptable user behavior, manageable liquidity subsidy, and a realistic breakeven path.

The most important principle is this:

> The platform should buy the right to scale by proving control first.

---

## 2. Initiative Table

| # | Initiative name | Horizon | Timeline | Owner function | Budget estimate | Dependency | Success metric |
|---|---|---|---|---|---|---|---|
| 01 | Market Governance and Regulatory Design | H1 | Months 1 to 2 | Prediction Market General Manager, Compliance Lead, Legal Counsel | $100K | None | Governance committee charter approved; decision rights, escalation rules, and prohibited-market categories signed off |
| 02 | NBG Pre-Consultation and Legal Classification Package | H1 | Months 1 to 4 | Compliance Lead, Legal Counsel, Regulatory Affairs | $100K | 01 | NBG Financial Innovation Office engagement completed or documented; legal memo covers sandbox, securities, gambling, VASP, and payment risks |
| 03 | Official Event Source Registry and Data Governance | H1 | Months 1 to 4 | Data Governance Lead, Market Operations Lead | $500K | 01 | Source registry covers NBG, Geostat, CEC, FX reference data, and backup-source rules; no test market lacks an approved source |
| 04 | Market Taxonomy, Contract Templates, and Risk Disclosures | H1 | Months 2 to 5 | Market Operations Lead, Compliance Lead, Product Lead | $500K | 01, 03 | At least 15 test contracts drafted; every contract has source, payout rule, risk warning, dispute path, and human approval record |
| 05 | Payment, KYC, AML, and GEL Wallet Design | H1 | Months 2 to 6 | Payments, KYC, and Settlement Lead | $500K | 01, 02 | GEL settlement design approved; at least two PSP or bank-rail cost quotes collected; sandbox onboarding and withdrawal process documented |
| 06 | Responsible-Use Framework and User Protection Rules | H1 | Months 2 to 6 | Responsible Use Lead, Customer Trust Lead, Compliance Lead | $100K | 01, 02 | Daily loss limit, deposit alert, cooling-off rule, risk quiz, adverse-action notice, and appeal process approved before sandbox |
| 07 | MVP Trading Workflow and Internal Admin Tools | H1 | Months 4 to 6 | Product Lead, Engineering Lead, Market Operations Lead | $1M | 03, 04, 05, 06 | Internal pilot completes market listing, order placement, wallet movement, outcome resolution, and dispute logging without critical failure |
| 08 | Controlled Sandbox Pilot | H2 | Months 7 to 12 | Prediction Market General Manager | $1M | 02, 05, 06, 07 | Sandbox launches with capped users and approved markets; payout dispute rate stays below 1 percent of active traders per market |
| 09 | Liquidity and Market-Maker Programme | H2 | Months 7 to 13 | Market Operations and Liquidity Lead | $500K | 04, 07, 08 | Top markets keep bid-ask spread below 8 percent for 80 percent of monitored trading hours; monthly market-maker scorecard produced |
| 10 | Market Surveillance and Responsible-Use Monitoring | H2 | Months 8 to 14 | Market Integrity Lead, Responsible Use Lead, Data and AI Lead | $1M | 06, 08 | 95 percent of high-risk alerts reviewed within SLA; all adverse user actions have reason code, owner, and audit log |
| 11 | Outcome Resolution, Disputes, and Reporting Automation | H2 | Months 10 to 15 | Resolution Committee Chair, Regulatory Governance Lead | $500K | 03, 08, 10 | 100 percent of resolved markets have resolution memo, official-source evidence, dispute log, and report-ready audit trail |
| 12 | Unit Economics and Board Launch Gate | H2 | Months 15 to 18 | Board Risk Committee, CFO, Prediction Market General Manager | $100K | 08, 09, 10, 11 | Board receives go, continue, pivot, or stop recommendation based on CAC, payment cost, liquidity subsidy, contribution margin, dispute rate, and regulatory status |
| 13 | Public GEL-Settled Launch Option | H3 | Post month 18 | Board, Prediction Market General Manager | $5M or more | 12 | Activated only if NBG path, payment rails, market integrity, responsible use, and base-case economics are validated |
| 14 | VASP or USDC Fallback Option | H3 | Post month 18 | Strategy Lead, Compliance Lead, Payments Lead | $1M | 12 | Activated only if GEL-settled route is blocked and legal counsel confirms VASP route does not solve, but can support, a narrower crypto-native model |
| 15 | Advanced Market Integrity and Data Products Option | H3 | Post month 18 | Data and AI Lead, Market Integrity Lead | $1M or more | 10, 11, 13 | Activated only after public launch decision; account-linkage graph, market-quality analytics, and regulator-grade reporting designed for scale |

---

## 3. Horizon Definitions

### Horizon 1: months 1 to 6

H1 is the foundation phase. It is deployable with current capabilities because it mainly requires governance design, legal work, data-source mapping, product design, payment architecture, and a limited MVP build.

H1 is not expected to produce meaningful prediction-market revenue. Its return is risk reduction. It should answer whether the platform can be tested without creating unacceptable legal, payment, reputational, or consumer-protection risk.

The H1 deliverables are:

- governance committee charter;
- legal classification memo;
- NBG pre-consultation package;
- approved market taxonomy;
- official event-source registry;
- contract templates;
- responsible-use rules;
- payment and KYC design;
- MVP admin and trading workflow.

### Horizon 2: months 7 to 18

H2 is the validation phase. It requires investment before value is visible. This is where the platform tests whether the concept can work in the Georgian market.

H2 is not judged by profit alone. A sandbox pilot may be loss-making because compliance, legal review, liquidity support, user education, and platform operations arrive before scale. The correct question is whether H2 produces evidence strong enough to justify or reject public launch.

The H2 deliverables are:

- controlled sandbox pilot;
- market-maker programme;
- surveillance and responsible-use monitoring;
- dispute and outcome-resolution workflow;
- regulator-ready reporting;
- verified unit economics;
- board launch gate.

### Horizon 3: post-18-month option space

H3 is not a commitment. It is an option that activates only if H2 conditions are met.

The preferred H3 path is a public GEL-settled launch. The fallback H3 path is a narrower VASP or USDC route, but that route should not be treated as solving event-contract legality. It only changes the settlement and user-access architecture.

---

## 4. Detailed Initiative Logic

### 01. Market Governance and Regulatory Design

The first initiative creates the internal authority structure for the platform. Without it, product, legal, compliance, engineering, and market operations will each make partial decisions without one owner for platform risk.

The committee should be named the Prediction Market Governance and AI Risk Committee. It should include the Prediction Market General Manager, Compliance Lead, Legal Counsel, Market Operations Lead, Data and AI Lead, Payments and KYC Lead, Responsible Use Lead, Customer Trust Lead, and a bank sponsor representative if the launch is bank-backed.

This initiative is small in direct cash cost but high in importance. The $100K label covers legal workshops, committee design, policy drafting, operating-model documentation, decision-rights mapping, and outside counsel support for the governance charter.

The success metric is not the existence of a meeting. The success metric is signed decision rights: who can approve a market, who can pause a market, who can block a payout, who can override an AI alert, and who can escalate to the board.

### 02. NBG Pre-Consultation and Legal Classification Package

This is the legal feasibility workstream. The platform cannot rely on vague language such as “financial education” or “fintech innovation.” Event contracts may be viewed as financial instruments, gambling-like products, virtual-asset activity, payment activity, or a new supervised innovation category.

The NBG Financial Innovation Office is relevant because it exists to create a communication channel between fintech innovators and supervisors and to provide feedback on supervisory questions. NBG states that the office helps innovators understand supervisory approaches and discusses regulatory issues, constraints, and barriers related to financial-technology products.

The $100K budget covers external legal memo, regulatory mapping, NBG engagement materials, draft sandbox scope, sample contracts, responsible-use explanation, and payment-risk summary. It is not a public-launch legal budget. It is a pre-consultation budget.

The success metric is documented regulatory feedback or a clear record of engagement. If the feedback suggests that the product is likely to be treated as gambling with no feasible sandbox pathway, the roadmap should stop or redesign before further spending.

### 03. Official Event Source Registry and Data Governance

This initiative is the most important technical control before AI deployment. A prediction market is only credible if each market has a source that users, regulators, and payment partners can understand.

The initial source registry should focus on official Georgian or clearly verifiable public sources:

- NBG for policy rate, monetary decisions, and official exchange-rate data;
- Geostat for inflation and economic releases;
- CEC for election turnout and official electoral results;
- approved FX reference sources as backup for exchange-rate bands;
- official government or regulator publications for narrowly defined civic outcomes.

The $500K budget covers data engineering, source mapping, data lineage, audit-log design, data-quality rules, official-source monitoring, and source-confidence scoring. This is not a simple spreadsheet. It is an operating control that will later support outcome resolution, user disclosures, and regulator-ready evidence.

The success metric is that no test market can enter the listing workflow without a source, backup-source rule, publication timing, and resolution rule.

### 04. Market Taxonomy, Contract Templates, and Risk Disclosures

This initiative translates the legal strategy into actual markets. It defines what the platform will and will not list during sandbox.

The initial approved categories should be narrow:

- inflation prints;
- GEL exchange-rate bands;
- NBG policy-rate decisions;
- election turnout;
- official macroeconomic releases;
- clearly verifiable public-data outcomes.

Restricted or prohibited categories should include sports, war outcomes, individual criminal cases, medical outcomes, celebrity events, private-person outcomes, ambiguous political claims, and any event without an official source.

The $500K budget covers product design, legal review, contract drafting, bilingual wording, risk-disclosure design, user testing, and internal admin templates. This is higher than a normal content budget because wording is not just marketing copy. It defines payout rules, dispute risk, and user understanding.

The success metric is that every test contract contains the question, official source, payout rule, resolution date, dispute path, risk warning, and named approver.

### 05. Payment, KYC, AML, and GEL Wallet Design

This initiative defines how users enter and leave the platform. It covers onboarding, deposits, withdrawals, settlement, wallet ledger, KYC, AML monitoring, payment holds, and reconciliation.

The preferred design is GEL-settled and bank-backed. This matters financially. External Georgian PSP pricing can be expensive for a micro-stakes product. The repository’s competitive landscape uses Payze as a local payment gateway proxy and records 2.5 to 3 percent commission rates. That supports the assumption that a standalone PSP route can damage unit economics. A bank-backed wallet or internal transfer model can plausibly reduce payment cost, but this must be validated with quotes.

The $500K budget covers payment architecture, vendor or bank-rail integration design, KYC flow, AML process, wallet ledger design, reconciliation process, fraud-review workflow, and security review. This is a design and build budget for sandbox readiness, not a full public-scale payments platform.

The success metric is that the team has at least two payment cost quotes and one approved sandbox payment architecture before user onboarding.

### 06. Responsible-Use Framework and User Protection Rules

Responsible use is not a reputational add-on. It is part of the platform design.

The platform should begin with clear sandbox limits:

- GEL 100 daily loss limit;
- GEL 500 deposit alert within 24 hours;
- cooling-off periods after repeated loss-limit events;
- risk quiz before first trade;
- plain-language warning on fixed downside and payout uncertainty;
- adverse-action notice for restrictions;
- human appeal route.

The $100K budget covers policy design, behavioral-risk input, legal review, user testing, support scripts, and product requirements. It is small because much of the actual implementation is inside the MVP and monitoring budgets.

The success metric is board and compliance approval before any sandbox user trades.

### 07. MVP Trading Workflow and Internal Admin Tools

This is the first major technology build. It does not need to be a full public platform. It must support the controlled sandbox.

The MVP should include:

- user onboarding;
- wallet balance view;
- market listing workflow;
- event-contract page;
- order placement or simplified trading flow;
- admin approval screen;
- responsible-use limits;
- manual outcome-resolution workflow;
- dispute logging;
- basic reporting export.

The $1M budget is justified because the MVP is not only a front-end experiment. It includes wallet logic, KYC hooks, admin workflow, audit logs, source registry integration, responsible-use controls, and settlement procedures. It also needs security review because user funds and identity data are involved.

The success metric is an internal end-to-end test: market creation, approval, user trade, payment movement, outcome resolution, payout, and dispute log.

### 08. Controlled Sandbox Pilot

The sandbox pilot tests whether the platform works in practice. It should not be open to the full market. User access should be capped, markets should be limited, and every high-risk process should be logged.

The $1M budget covers six months of pilot operations. The completed prediction-market ROI model now provides the platform’s unit-economics inputs, including adoption, turnover, take rate, payment cost, liquidity support, compliance cost, CAC, contribution margin, and breakeven thresholds. This roadmap uses that model to align sandbox evidence with board decision criteria.

The sandbox budget includes operating team, engineering support, compliance and legal run cost, customer support, user education, data/reporting, and contingency. It does not include the full liquidity programme, which is separated as Initiative 09.

The success metric is not signups. The success metric is whether users can trade, markets resolve cleanly, disputes remain low, and regulators or payment partners receive credible evidence.

### 09. Liquidity and Market-Maker Programme

Liquidity is a cold-start problem. Prediction markets are not useful if users see wide spreads, empty order books, or no exit price.

The $500K budget covers a market-maker retainer, spread support, quote monitoring, internal liquidity risk review, and market-quality reporting. The updated unit-economics model now uses liquidity support planning assumptions of GEL 150,000 conservative, GEL 300,000 base, and GEL 650,000 upside. This roadmap budget includes reserve capacity, tooling, market-maker contracting, risk oversight, and contingency to support those scenarios.

The success metric is bid-ask spread below 8 percent for 80 percent of monitored trading hours in top pilot markets. If this cannot be achieved without excessive subsidy, the platform should not scale.

### 10. Market Surveillance and Responsible-Use Monitoring

This initiative turns the safety rules into live monitoring. It covers manipulation alerts, account concentration, unusual price moves, deposit behavior, trade frequency, repeated loss-limit events, and user restrictions.

The $1M budget is justified because this is a high-risk control layer. It requires data pipelines, alert logic, dashboards, reviewer workflows, case management, false-positive review, user notice templates, and audit logs. It also supports regulator confidence. A platform that cannot detect suspicious trading or harmful user behavior is not credible as a supervised marketplace.

The success metric is that 95 percent of high-risk alerts are reviewed within SLA and every adverse user action has a reason code, owner, and audit record.

### 11. Outcome Resolution, Disputes, and Reporting Automation

Outcome resolution is the trust core of the business. If users do not trust settlement, the product fails.

This initiative builds the evidence process around market results. It should generate draft resolution memos, attach official-source evidence, track disputes, prepare monthly governance reports, and support NBG or payment-partner reporting.

The $500K budget covers reporting workflow, official-source extraction, dispute dashboard, audit-log exports, compliance templates, and integration with the source registry. It is not full regulatory automation. Every external report still needs human sign-off.

The success metric is that 100 percent of resolved markets have an official-source evidence package and resolution memo.

### 12. Unit Economics and Board Launch Gate

This initiative converts sandbox evidence into a decision. The board should not approve public launch because the app works or because users are curious. It should approve only if the economics and controls are credible.

The $100K budget covers final ROI model update, external review, legal update, payment-cost validation, market-maker cost review, board pack, and go or stop recommendation.

The gate should include:

- total investment to recover;
- Year 1 capital requirement, including GEL 7.40M CapEx and GEL 4.60M OpEx;
- annual benefit;
- payback period;
- IRR;
- 5-year NPV at 18 percent discount rate;
- severe downside stress test;
- sensitivity to adoption and turnover per active user;
- payment processing cost;
- CAC;
- liquidity subsidy;
- compliance and legal run cost;
- platform run cost;
- dispute cost;
- contribution margin per user;
- breakeven active users;
- NBG and payment-partner status.

The success metric is a board-ready recommendation with four options: launch, continue sandbox, pivot to fallback route, or stop.

### 13. Public GEL-Settled Launch Option

This is the preferred H3 path. It should be activated only if the sandbox proves regulatory comfort, payment feasibility, market quality, user protection, and unit economics.

The $5M or more label is appropriate because public launch requires expanded engineering, production security, larger customer support, legal and compliance operations, market surveillance, liquidity support, user acquisition, incident response, and board-level capital commitment.

The existence of large global prediction-market volumes does not mean Georgia can support the same scale. It only proves that the category can attract massive attention when regulatory access, distribution, and liquidity align. The Georgian public launch must still be justified by local evidence.

### 14. VASP or USDC Fallback Option

This is not the recommended mass-market path. It is a fallback option if GEL settlement is blocked but a narrower crypto-native model remains legally possible.

The $1M budget covers legal work, wallet architecture, VASP-related compliance, custody or settlement design, crypto onboarding flow, and narrower go-to-market testing.

The trigger condition is strict. VASP status does not automatically solve event-contract legality. It only affects the settlement and virtual-asset side of the product. The event contract still needs legal classification.

### 15. Advanced Market Integrity and Data Products Option

This option activates only after a public-launch decision. It covers account-linkage graphs, manipulation detection, market-quality analytics, regulator-grade reporting, and possible aggregated data products.

The $1M or more budget is appropriate because this moves beyond sandbox dashboards into production-grade surveillance and analytics.

The trigger is clear: do not fund this until the platform has passed the month-18 launch gate.

---

## 5. Dependency Logic

Initiatives 01 through 07 form the H1 foundation. Market Governance and Regulatory Design is the critical prerequisite because the platform cannot safely list markets, use AI screening, onboard users, or report to regulators without a named body that owns decisions. The second critical prerequisite is the Official Event Source Registry because every market needs a source before it can be listed, traded, resolved, or disputed. The H2 infrastructure then validates the operating model through sandbox trading, liquidity support, surveillance, responsible-use monitoring, resolution, and reporting. H3 options activate only if the board sees evidence that regulation, payments, liquidity, user protection, and unit economics are strong enough for public launch.

---

## 6. Funding Narrative

### 6.1 What funds H1

H1 should be funded from the sponsor’s innovation, compliance-readiness, or regulatory sandbox budget. It should not depend on prediction-market revenue because there will be no meaningful platform revenue before sandbox.

The H1 financial case is avoided rework. Spending early on governance, source registry, legal classification, payment design, and responsible-use controls prevents a more expensive failure later. A prediction-market product that launches before resolving those questions could be reclassified, blocked by payment partners, attacked as gambling, or damaged by payout disputes.

The H1 platform-specific budget is approximately $2.8M, or GEL 7.6M using the planning exchange rate of 1 USD equals 2.70 GEL.

This includes:

| H1 item | USD budget | GEL budget at 2.70 | Financial basis |
|---|---:|---:|---|
| Governance and regulatory design | $100K | GEL 270K | Legal workshops, committee design, decision-rights documentation |
| NBG pre-consultation and legal memo | $100K | GEL 270K | External counsel, sandbox pack, legal classification analysis |
| Source registry and data governance | $500K | GEL 1.35M | Data engineering, audit logs, source registry, reporting foundation |
| Market taxonomy and contract templates | $500K | GEL 1.35M | Legal/product design, bilingual templates, risk disclosure |
| Payment, KYC, AML, and wallet design | $500K | GEL 1.35M | Payment architecture, KYC flow, PSP and bank-rail review |
| Responsible-use framework | $100K | GEL 270K | Policy, user notices, risk rules, appeal workflow |
| MVP workflow and admin tools | $1M | GEL 2.7M | Product, engineering, wallet workflow, admin tools, audit logs |
| **H1 total** | **$2.8M** | **GEL 7.56M** | Foundation phase |

### 6.2 What funds H2

H2 should be approved as a ring-fenced sandbox investment. It should not be judged as a mature product P&L.

The H2 platform-specific budget is approximately $3.1M, or GEL 8.37M.

| H2 item | USD budget | GEL budget at 2.70 | Financial basis |
|---|---:|---:|---|
| Controlled sandbox pilot | $1M | GEL 2.7M | Six-month pilot operations, engineering support, support, compliance run cost, reporting, contingency |
| Liquidity and market-maker programme | $500K | GEL 1.35M | Market-maker retainer, spread support, monitoring, reserve capacity |
| Market surveillance and responsible-use monitoring | $1M | GEL 2.7M | High-risk control system, alerts, dashboards, case management, audit logs |
| Outcome resolution and reporting automation | $500K | GEL 1.35M | Official-source evidence, resolution memos, dispute tracking, NBG and payment-partner reporting |
| Unit economics and launch gate | $100K | GEL 270K | ROI model update, external review, board pack |
| **H2 total** | **$3.1M** | **GEL 8.37M** | Validation phase |

The H2 investment is justified only if H1 proves that a sandbox route is feasible. If NBG engagement or legal review indicates no viable pathway, H2 should not proceed.

### 6.3 H3 option funding

H3 is not approved automatically. It is a conditional option.

The preferred H3 path is public GEL-settled launch with a budget of at least $5M, or GEL 13.5M. That figure reflects a full production launch with stronger engineering, more customer support, more compliance staff, greater liquidity support, marketing, market integrity systems, and board-level oversight.

The fallback VASP or USDC route is budgeted at approximately $1M, or GEL 2.7M. This is smaller because it targets a narrower crypto-native segment, but it is not necessarily safer. It may reduce payment-friction issues but increase reputational and regulatory ambiguity.

### 6.4 Financial evidence supporting the budget logic

The budget is based on five evidence points.

First, the completed prediction-market ROI model now provides the platform’s unit-economics inputs. It details adoption, turnover, take rate, payment cost, liquidity support, compliance cost, customer acquisition cost, contribution margin, and breakeven thresholds. This roadmap uses that model to align sandbox evidence with board decision criteria.

Second, local payment economics matter. The repository’s competitive landscape uses Payze as a Georgian payment-gateway proxy and lists 2.5 to 3 percent commission rates. A micro-stakes trading product cannot ignore this. If payment cost remains near external PSP levels, the platform’s economics become weak. This is why H1 includes payment-rail validation and why bank-backed rails are strategically important.

Third, NBG’s Financial Innovation Office is relevant but not a guarantee. NBG describes the office as a communication channel for fintech innovators to receive feedback on supervisory questions. It explicitly frames itself around responsible innovation and supervisory understanding. That supports H1 pre-consultation, but it does not mean the platform receives approval.

Fourth, global prediction-market volume shows that the category can scale, but it also shows why Georgia should avoid a blind copy of sports-heavy models. Recent reporting described prediction-market volume rising sharply, including estimates of global monthly trading reaching $24B by March 2026, while other coverage notes that sports dominate much of the recent volume. For the Georgian base case, sports should not be the foundation because it creates gambling-comparison risk.

Fifth, institutional interest, including ICE’s announced investment of up to $2B in Polymarket at an $8B pre-money valuation, supports the strategic relevance of the category. It does not prove the Georgian platform will succeed. It supports treating H3 as an option worth testing, not as a guaranteed launch.

### 6.5 Unit economics to validate before public launch

The month-18 board gate should require the completed prediction-market ROI model and evidence that the platform can support public launch.

The model uses the following core assumptions:

- risk-active user pool: 651,000;
- conservative adoption: 4 percent, equal to 26,040 monthly active users;
- base-case adoption: 10 percent, equal to 65,100 monthly active users;
- upside adoption: 18 percent, equal to 117,180 monthly active users;
- monthly turnover per active user: GEL 6,546;
- take rate: 1 percent;
- funding-flow ratio: 20 percent across all primary scenarios.

The board pack should include:

- base-case monthly platform turnover: GEL 426.1M;
- base-case monthly gross revenue: GEL 4.26M;
- base-case monthly payment cost: GEL 852k;
- base-case monthly operating profit before CAC recovery: GEL 2.33M;
- base-case annual benefit: GEL 27.95M;
- base-case total investment to recover, including CAC: GEL 20.81M;
- base-case payback period: 8.9 months;
- base-case 5-year NPV at 18 percent discount rate: GEL 57.99M;
- base-case IRR: 99.9 percent;
- Year 1 capital requirement: GEL 12.00M total, including GEL 7.40M CapEx and GEL 4.60M OpEx;
- first 18-month transformation investment: GEL 15.93M;
- change management budget range: 20 percent = GEL 3.19M, 25 percent = GEL 3.98M, 30 percent = GEL 4.78M, with GEL 4.0M recommended;
- severe downside stress test: 2 percent adoption, GEL 3,273 monthly turnover per active user, 0.75 percent take rate, negative operating profit, no payback, negative NPV;
- sensitivity to adoption and turnover per active user.

The board should approve public launch only if the sandbox shows a credible path toward these assumptions and the model demonstrates robustness to adoption and turnover outcomes.

---

## 7. Change Management Initiative

Change management is a named initiative, not a generic mitigation.

| Element | Entry |
|---|---|
| Initiative name | Prediction Market Change Management Programme |
| Horizon | H1 |
| Timeline | Months 1 to 18 |
| Owner function | Transformation Office or PMO, jointly sponsored by Prediction Market General Manager and Compliance Lead |
| Budget estimate | 20 to 30 percent of total prediction-market transformation cost |
| Dependency | None. Begins before AI deployment and before sandbox launch |
| Success metric | 90 percent of impacted staff trained before sandbox; 95 percent of high-risk workflows documented; monthly adoption review completed throughout sandbox |

The prediction-market-specific H1 and H2 transformation budget is approximately $5.9M, or GEL 15.93M at 1 USD equals 2.70 GEL. The change management budget should therefore be:

- 20 percent: GEL 3.19M
- 25 percent: GEL 3.98M
- 30 percent: GEL 4.78M

The recommended planning figure is GEL 4.0M.

This is high but defensible because the product changes the way the organization makes decisions. The workstream must cover stakeholder analysis, communication plan, training, process rehearsals, adoption measurement, support readiness, and board reporting.

The key activities are:

- stakeholder map for Product, Compliance, Legal, Payments, Market Operations, Engineering, Data, Customer Trust, and Risk;
- communication plan explaining why the platform is a supervised marketplace, not a normal app;
- training on market taxonomy, contract templates, source registry, responsible-use rules, and human override thresholds;
- tabletop exercises for disputed outcomes, suspicious trading, payment holds, and cooling-off appeals;
- adoption dashboard tracking whether teams actually use the new workflows.

---

## 8. Board Decision Gates

### Gate 1: regulatory feasibility, month 4

The board or executive steering group reviews the legal classification memo, NBG engagement record, market taxonomy, payment-risk view, and responsible-use framework.

The decision is to continue, redesign, or stop.

The stop condition is a legal view that event contracts are likely to be treated as gambling with no feasible sandbox route.

### Gate 2: sandbox readiness, month 6

The board reviews the MVP workflow, source registry, payment design, KYC and AML process, responsible-use rules, contract templates, and override protocols.

The decision is whether to approve controlled sandbox launch.

The stop condition is inability to resolve markets through official sources or inability to support safe deposits and withdrawals.

### Gate 3: pilot quality, month 12

The board reviews active users, user retention, payment success, spread quality, disputes, user complaints, responsible-use interventions, and market-integrity alerts.

The decision is to continue sandbox, expand slightly, narrow scope, or pause.

The stop condition is persistent dispute rate above 1 percent of active traders in a market, spreads above 8 percent in top markets despite subsidy, or unresolved responsible-use concerns.

### Gate 4: public launch decision, month 18

The board reviews final regulatory status, payment-partner position, unit economics, market quality, liquidity subsidy, responsible-use evidence, and operational readiness.

The decision is one of four options:

1. launch public GEL-settled product;
2. continue sandbox;
3. pivot to narrower VASP or USDC route;
4. stop the project.

The launch condition is that regulation, payment, liquidity, user protection, and contribution margin are all credible.

---

## 9. Roadmap Risk Controls

The main roadmap risks are known from the beginning.

The first risk is regulatory misclassification. The control is NBG pre-consultation before sandbox and legal review before any public launch.

The second risk is gambling perception. The control is a narrow initial market taxonomy, no sports base case, responsible-use limits, and plain-language risk warnings.

The third risk is payment-cost pressure. The control is early PSP and bank-rail quote collection, plus preference for bank-backed GEL settlement.

The fourth risk is liquidity failure. The control is a market-maker programme before public launch and a spread target in sandbox.

The fifth risk is disputed resolution. The control is official-source registry, resolution memo, dispute window, and human sign-off.

The sixth risk is user harm. The control is daily loss limit, deposit alert, cooling-off periods, adverse-action notices, and human appeal.

The seventh risk is building before governance. The control is that no sandbox launch can happen before governance, source registry, contract templates, and responsible-use rules are complete.

---

## 10. Quality Check

Every initiative has all seven required elements: name, horizon, timeline, owner, budget, dependency, and measurable success metric.

H1 initiatives are deployable within six months because they focus on governance, legal work, source registry, payment design, user-protection rules, and MVP workflow.

Every H2 initiative has at least one named H1 dependency.

Change management appears as a named initiative with a GEL budget.

Data governance appears in months 1 to 4 before AI-assisted event screening, outcome resolution, surveillance, or reporting automation.

Every initiative has a named owner function.

Every success metric is measurable within the initiative timeline.

The roadmap logic is simple: H1 makes the platform testable, H2 proves or disproves the platform under controlled conditions, and H3 only activates if the evidence supports public launch.

---

## 11. References

National Bank of Georgia. Financial Innovation Office. https://nbg.gov.ge/en/page/financial-innovation-office

Personal Data Protection Service of Georgia. Current Law of Georgia on Personal Data Protection. https://pdps.ge/content/1063/LAWS

Payze commission-rate proxy is taken from the project repository file: `deliverables/competitive_landscape_matrix.md`.

The completed prediction-market ROI model is documented in `Deliverables WK3/Completed/pm_roi_v3.md`. It provides the platform's updated unit economics, funding-flow assumptions, investment requirements, payback period, IRR, NPV, and downside stress test.

MarketWatch. Wall Street is finding a new use for the latest retail-trading obsession. 2026.

Reuters. NYSE parent to invest up to $2 billion in Polymarket. 2025.

Financial Times. Betting on prediction markets has exploded over past two years. 2025.

European Commission. AI Act. https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
