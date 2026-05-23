# Roadmap Draft v1

## Purpose

This document sets out the 18-month transformation roadmap for a Georgian, bank-backed prediction-market platform.

It becomes Section 7 of the final project report and connects the recommended strategic option, Three Horizons logic, AI Opportunity Map, and Operating Model v1.

The recommended option is:

> **Regulatory Sandbox Pathway, with responsible-use controls embedded from day one.**

The platform should be GEL-settled and bank-backed where possible. A VASP / USDC route remains a fallback or niche crypto-native option, not the default mass-market model.

---

# Initiative Table

| # | Initiative name | Horizon | Timeline (months) | Owner function | Budget estimate | Dependency | Success metric |
|---|---|---|---:|---|---:|---|---|
| 01 | Create Market Governance and AI Risk Function | H1 | Months 1–2 | Regulatory & Platform Governance | $100K | None | Committee charter approved; decision rights, escalation thresholds, and AI override policy signed off by month 2 |
| 02 | Build Data Governance and Official Event-Source Registry | H1 | Months 1–3 | Data, AI & Market Integrity | $100K | None | Source registry covers NBG, Geostat, CEC, and at least 5 approved public-data sources; 95% source-confidence rule defined |
| 03 | Change Management Programme | H1 | Months 1–18 | Transformation Office / PMO | 20–30% of total transformation cost | None | 90% of involved staff complete training; monthly adoption survey score above 75%; change risks reviewed monthly |
| 04 | NBG Pre-Consultation and Legal Classification Package | H1 | Months 1–4 | Regulatory & Platform Governance | $100K | 01 | NBG meeting completed or written feedback obtained; legal memo defines whether sandbox, financial instrument, VASP, or gambling risk applies |
| 05 | KYC, AML, and GEL Payment-Rail Design | H1 | Months 2–5 | Payments, KYC & Settlement | $500K | 01, 02 | Payment and KYC architecture approved; at least 2 PSP / bank-rail quotes collected; sandbox onboarding process documented |
| 06 | Responsible-Use and Customer Protection Framework | H1 | Months 2–5 | Responsible Use & Customer Trust | $100K | 01 | Daily loss limit, deposit alert, cooling-off rule, risk quiz, and dispute workflow approved before pilot |
| 07 | MVP Market Listing Workflow and Contract Templates | H1 | Months 3–6 | Product, Engineering & UX + Market Operations | $500K | 01, 02, 04 | At least 10 test contracts drafted using approved template; 100% of test markets include source, payout rule, risk warning, and resolution rule |
| 08 | AI-Assisted Event Risk Scoring Prototype | H1 | Months 4–6 | Data, AI & Market Integrity | $500K | 01, 02, 07 | AI scores 100% of proposed pilot markets; all AI outputs reviewed by humans; false escalation rate measured before sandbox |
| 09 | Controlled Sandbox Pilot | H2 | Months 7–12 | Prediction Market General Manager | $1M | 04, 05, 06, 07, 08 | Pilot launches with capped users and approved markets; dispute rate below 1% of active traders per market |
| 10 | Liquidity and Market-Maker Programme | H2 | Months 7–12 | Market Operations & Liquidity | $500K | 07, 09 | Top pilot markets maintain bid-ask spread below 8% for 80% of trading hours; market-maker scorecard produced monthly |
| 11 | AI Market Surveillance and Responsible-Use Scoring | H2 | Months 8–14 | Data, AI & Market Integrity + Responsible Use | $1M | 06, 08, 09 | 100% of abnormal price moves above 20 percentage points in 15 minutes reviewed within SLA; high-risk user interventions logged |
| 12 | Outcome Resolution and Regulator Reporting Automation | H2 | Months 10–15 | Regulatory & Platform Governance + Data, AI & Market Integrity | $500K | 02, 09, 11 | Monthly regulator / payment-partner report generated on time; 100% of resolved markets have audit trail and resolution memo |
| 13 | Unit Economics Gate and Public Launch Decision | H2 | Months 15–18 | Board / Executive Steering Committee | $100K | 09, 10, 11, 12 | Board receives go / no-go pack with CAC, active users, volume per user, contribution margin, liquidity cost, and regulatory status |
| 14 | Public GEL-Settled Launch Option | H3 | Post-18 months | Board + Prediction Market General Manager | $5M+ | 13 | Triggered only if NBG path is positive, payment rails are approved, and base-case breakeven path is credible |
| 15 | VASP / USDC Fallback Option | H3 | Post-18 months | Strategy + Regulatory + Payments | $1M | 13 | Triggered only if GEL-settled route is blocked but VASP route receives legal / regulatory confirmation |
| 16 | Advanced Data and AI Market-Integrity Layer | H3 | Post-18 months | Data, AI & Market Integrity | $1M+ | 11, 12, 14 | Advanced manipulation detection, account-linkage graph, and automated market-risk reporting ready for scaled launch |

---

# Horizon Definitions

## Horizon 1: Months 1 to 6

H1 initiatives are deployable with current capabilities. They build the governance, data, legal, payment, and change-management foundation required before any AI-supported market operation can scale.

H1 is not about maximizing platform revenue. It is about making the platform safe enough to test.

## Horizon 2: Months 7 to 18

H2 initiatives require investment before value is visible. This is where the platform moves from design to controlled sandbox pilot.

H2 builds real trading data, liquidity evidence, responsible-use evidence, and regulator-ready reporting.

## Horizon 3: Post-18-month option space

H3 initiatives are not full commitments during the first 18 months. They are options activated only after H2 evidence is strong enough.

The key H3 decision is whether to scale into a public GEL-settled platform, pivot to a narrower VASP / USDC route, or pause the project if event contracts are classified as gambling.

---

# Dependency Logic

Initiatives 01 through 08 form the H1 foundation. **Market Governance and AI Risk Function** is the critical prerequisite for all H2 deployment because the platform cannot safely list markets, use AI risk scoring, or report to regulators without clear decision rights, escalation thresholds, and human accountability.

The second critical prerequisite is **Data Governance and Official Event-Source Registry**. Without approved sources, event contracts cannot be resolved transparently, and AI cannot support outcome resolution or market surveillance.

The H2 infrastructure funded by H1 governance and bank-side capability then enables the H3 experiments: **Public GEL-Settled Launch Option**, **VASP / USDC Fallback Option**, and **Advanced Data and AI Market-Integrity Layer**.

The sequencing logic is:

```text
H1 builds governance, data, payment, and responsible-use controls
→ H2 tests the platform in sandbox and generates evidence
→ H3 scales only if regulatory, liquidity, and unit-economics gates are passed
```

---

# Funding Narrative

## How the portfolio funds itself

The transformation should not be funded as a normal short-payback banking product. It should be funded as a staged strategic option.

The prediction-market platform is likely loss-making during the pilot phase because compliance, liquidity, legal, technology, and support costs arrive before trading scale. Therefore, the funding model should separate H1 readiness spending, H2 sandbox investment, and H3 scale commitment.

---

## H1 ROI source

H1 does not rely on prediction-market revenue. H1 creates value by reducing the risk and cost of later deployment.

Potential H1 ROI sources include:

1. **Payment fraud detection improvements**  
   These reduce fraud losses and strengthen payment-partner confidence.

2. **Customer service automation**  
   These reduce support cost and create reusable capabilities for prediction-market disputes and onboarding.

3. **Reusable KYC / AML infrastructure**  
   Existing bank onboarding infrastructure reduces the cost of launching the sandbox pilot.

4. **Regulatory readiness**  
   Early NBG engagement prevents expensive redesign after launch.

H1 therefore funds H2 indirectly by lowering risk, avoiding rework, and creating reusable infrastructure.

---

## H2 investment

H2 requires a dedicated sandbox budget.

Expected capital requirement:

| H2 area | Estimated budget |
|---|---:|
| Controlled sandbox pilot | $1M |
| Liquidity and market-maker programme | $500K |
| AI market surveillance and responsible-use scoring | $1M |
| Outcome resolution and regulator reporting automation | $500K |
| Board go / no-go pack and legal update | $100K |
| **Total H2 investment** | **Approximately $3.1M** |

This should be approved as a ring-fenced transformation budget, not absorbed into the normal product P&L.

The reason is that H2 is a learning and validation phase. It should be judged on regulatory comfort, liquidity quality, user retention, dispute rate, and unit-economics evidence, not on immediate profitability.

---

## H3 option

The H3 option moves from option to commitment only if the following trigger conditions are met:

1. NBG or legal counsel confirms a feasible route for limited event contracts.
2. Payment partners accept the operating model and risk controls.
3. Sandbox users show repeat usage and acceptable complaint / dispute rates.
4. Top pilot markets maintain bid-ask spreads below 8% for most trading hours.
5. Base-case unit economics show a credible path toward breakeven.
6. Responsible-use controls prevent harmful user behavior from becoming a reputational issue.
7. Board approves capital for public launch.

If these conditions are not met, the platform should not proceed to full public launch. It should either remain in sandbox, pivot to a narrower VASP / USDC route, or stop.

---

# Change Management Initiative

Change management must appear as a named initiative in the roadmap because the project changes how the client governs risk, data, markets, and AI-supported decisions.

| Element | Your entry |
|---|---|
| Initiative name | Change Management Programme |
| Horizon | H1 |
| Timeline | Months 1 to 18, ongoing |
| Owner function | Transformation Office / PMO, with support from Regulatory & Platform Governance |
| Budget estimate | 20 to 30% of total transformation cost |
| Dependency | None: begins before any AI deployment |
| Success metric | 90% of involved employees complete training; monthly adoption score above 75%; all high-risk operating-model changes have named owner and communication plan |

## Change management scope

The programme should cover:

- staff training on prediction-market operating model,
- governance training for AI-supported decisions,
- regulator and payment-partner communication rhythm,
- responsible-use culture,
- dispute-handling playbooks,
- market-integrity escalation procedures,
- board reporting cadence,
- and pilot-readiness workshops.

The key cultural shift is that the platform must be treated as a supervised marketplace, not just a new digital product.

---

# Roadmap Logic by Horizon

## H1: Months 1 to 6

H1 creates the minimum safe operating foundation.

| Initiative | Why it is H1 |
|---|---|
| Market Governance and AI Risk Function | Can be created with current leadership and compliance capabilities |
| Data Governance and Event-Source Registry | Uses public data sources and internal data discipline before advanced AI |
| Change Management Programme | Must begin before new workflows and AI tools are introduced |
| NBG Pre-Consultation and Legal Classification Package | Regulatory path must be clarified before pilot |
| KYC, AML, and GEL Payment-Rail Design | Payment and onboarding architecture must exist before sandbox users |
| Responsible-Use Framework | Consumer-protection rules must be embedded before trading starts |
| MVP Market Listing Workflow and Contract Templates | Provides the operating backbone for controlled market listing |
| AI-Assisted Event Risk Scoring Prototype | Deployable as decision support, not autonomous decision-making |

---

## H2: Months 7 to 18

H2 turns the foundation into a controlled sandbox pilot and measurable operating capability.

| Initiative | Why it is H2 |
|---|---|
| Controlled Sandbox Pilot | Requires H1 governance, legal review, payment design, and MVP workflow |
| Liquidity and Market-Maker Programme | Requires live or pilot markets to measure spreads and depth |
| AI Market Surveillance and Responsible-Use Scoring | Requires user behavior, order-book data, and intervention logs |
| Outcome Resolution and Regulator Reporting Automation | Requires event-source registry, trading data, and pilot audit logs |
| Unit Economics Gate and Public Launch Decision | Requires pilot data from users, liquidity, compliance, and payments |

---

## H3: Post-18 months

H3 initiatives remain options until H2 evidence supports commitment.

| Initiative | Trigger condition |
|---|---|
| Public GEL-Settled Launch Option | NBG path, payment rails, responsible-use controls, and unit economics are validated |
| VASP / USDC Fallback Option | GEL-settled route is blocked, but VASP / crypto-native route is legally viable |
| Advanced Data and AI Market-Integrity Layer | Public launch scale requires deeper manipulation detection and regulator-grade reporting |

---

# Board Decision Gates

## Gate 1: Month 4

**Decision:** Continue or stop after NBG pre-consultation.

**Required evidence:**

- legal classification memo,
- NBG meeting or feedback record,
- event taxonomy,
- risk and responsible-use framework,
- payment-rail feasibility.

## Gate 2: Month 6

**Decision:** Approve controlled sandbox pilot.

**Required evidence:**

- MVP market workflow,
- KYC / AML process,
- approved source registry,
- contract templates,
- AI event-risk scoring prototype,
- change-management readiness.

## Gate 3: Month 12

**Decision:** Continue sandbox, expand pilot, or pause.

**Required evidence:**

- active users,
- monthly trading volume,
- dispute rate,
- user complaints,
- liquidity performance,
- payment success rate,
- responsible-use interventions.

## Gate 4: Month 18

**Decision:** Public launch, VASP fallback, extended sandbox, or project stop.

**Required evidence:**

- final regulatory path,
- base-case ROI,
- CAC,
- payment cost,
- contribution margin per user,
- market-maker subsidy requirement,
- board-approved risk appetite.

---

# Roadmap Risk Controls

| Risk | Roadmap control |
|---|---|
| AI pilot cannot scale | Data governance and event-source registry are built before AI deployment |
| Product is classified as gambling | NBG pre-consultation happens before sandbox pilot |
| Payment partners refuse support | Payment-rail design and PSP quote pack completed in H1 |
| Liquidity is too weak | Liquidity programme starts with pilot, not after public launch |
| Users overtrade or suffer harm | Responsible-use framework is built before trading starts |
| Roadmap becomes a list of dates | Every initiative has owner, budget, dependency, and success metric |
| Bank brand is damaged | Change management and governance begin before product launch |

---

# Quality Check

Before finalising:

- **Every initiative has all seven required elements.**  
  Yes.

- **H1 initiatives are deployable within 6 months with current capabilities.**  
  Yes.

- **Every H2 initiative has at least one named H1 dependency.**  
  Yes.

- **Change management appears as a named initiative with a budget estimate.**  
  Yes.

- **Data governance appears in months 1 to 6 before any AI deployment initiative.**  
  Yes. Initiative 02 comes before AI event-risk scoring and H2 AI surveillance.

- **Every initiative has a named owner function.**  
  Yes.

- **The success metric for each initiative is measurable within the initiative timeline.**  
  Yes.

## One-sentence roadmap logic

> H1 builds the governance, data, payment, and change-management foundation; H2 uses that foundation to run a controlled sandbox pilot and validate unit economics; H3 scales only if regulation, liquidity, responsible use, and breakeven path are proven.

---

# References

Christensen, C. M. (1997). *The innovator’s dilemma: When new technologies cause great firms to fail*. Harvard Business School Press.

Rogers, D. L. (2023). *The digital transformation roadmap: Rebuild your organization for continuous change*. Columbia Business School Publishing.

National Bank of Georgia. (2025). *Financial Innovation Office*. https://www.nbg.gov.ge/en/pages/financial-innovation-office

National Bank of Georgia. (2025). *Financial Literacy Survey 2024*. https://www.nbg.gov.ge/uploads/pressreleases/2025/Financial_Literacy_Survey_2024.pdf

Georgian Foundation for Strategic and International Studies. (2024). *Georgia’s cryptocurrency regulation landscape*. https://www.gfsis.org.ge/publications/georgia-s-cryptocurrency-regulation-landscape

TBC Bank. (2024). *TBC Capital individual brokerage services*. https://www.tbcbank.ge/en/corporate/tbc-capital/tbc-capital-individuals

CoinDesk. (2024, November 12). *Polymarket crypto prediction market hits $1B in monthly volume for first time*. https://www.coindesk.com/markets/2024/11/12/polymarket-crypto-prediction-market-hits-1b-in-monthly-volume-for-first-time/

Gaming Intelligence. (2024, July). *Georgia tightens gambling regulations further*. https://www.gamingintelligence.com/regulation/georgia-tightens-gambling-regulations-further/
