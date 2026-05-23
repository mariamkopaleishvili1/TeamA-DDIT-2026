
# Prediction-Market Unit Economics Model

## Executive Summary

This model estimates the unit economics of a compliant Georgian prediction-market platform launched through a regulatory-first, bank-backed pathway. The model is designed for a Georgian fintech potentially backed by a major bank such as TBC.

The preferred launch path is GEL-settled and sandbox-first. A VASP/USDC route is treated only as a fallback or niche crypto-native option.

The model is built around three core revenue drivers:

1. monthly active traders,
2. average monthly trading volume per active user, and
3. gross take rate / spread capture.

It then deducts payment processing costs, market-maker or liquidity subsidies, compliance and legal run costs, platform operating costs, and customer acquisition costs.

The base case shows that the platform is unlikely to break even during the early pilot stage. At **2,000 monthly active traders**, **GEL 300 average monthly volume per user**, and a **2% gross take rate**, the platform generates only **GEL 12,000 in monthly gross revenue**. After payment costs, monthly contribution is approximately **GEL 6,000**, which is far below the estimated **GEL 150,000 monthly fixed cost** required for liquidity support, compliance, and platform operations.

The model becomes attractive only at scale. In the base case, breakeven requires approximately **50,000 monthly active traders**. In the upside case, where users trade more actively, take rate improves, payment costs fall, and CAC is reduced through bank-backed distribution, breakeven falls to approximately **15,400 monthly active traders**.

The main strategic implication is that a standalone launch is financially fragile. A bank-backed launch is not just helpful for regulation and trust; it is central to the economics. Without lower CAC, cheaper payment rails, and credible liquidity support, micro-stakes trading volume is unlikely to cover the fixed costs of operating a compliant prediction-market platform in Georgia.

---

## Important Modeling Note

This model is not a forecast. It is a structured assumption model.

Many of the key inputs are not directly observable for Georgia because no regulated local prediction-market platform currently exists. Therefore, the model separates:

- **sourced facts and external benchmarks**, and
- **analyst assumptions used for scenario modeling**.

The assumptions should be refined through:

- NBG or legal consultation,
- market-maker discussions,
- payment-provider pricing quotes,
- user interviews or survey data,
- pilot trading data, and
- bank distribution / CAC benchmarks.

This is especially important because prediction-market revenue can be misleading. Headline trading volume does not automatically translate into strong platform economics. Recent reporting on Kalshi argues that sports-related markets have been much more monetizable than slower macro, politics, and civic markets. Since the Georgian strategy should avoid relying on sports-style economics in the base case, this model uses conservative take-rate and activity assumptions.

Source: [Financial Times, prediction-market economics and Kalshi revenue discussion](https://www.ft.com/content/1ac03f57-bd5d-4196-85ff-4bd96dc69e0d)

---

## Part 1. Revenue Logic

### Core Revenue Formula

```text
Monthly Gross Revenue =
Monthly Active Traders × Average Monthly Trading Volume per User × Gross Take Rate
```

The model assumes that the platform earns revenue through spread capture, explicit fees, or a hybrid of the two. The project should not assume sportsbook-style margins, because the recommended positioning is a regulated financial-information/event-contract product rather than a gambling product.

### Scenario Assumptions

| Driver | Conservative | Base Case | Upside | Source / Proxy | Confidence |
|---|---:|---:|---:|---|---|
| Monthly active traders, Year 1 | 500 | 2,000 | 10,000 | Analyst assumption based on early-stage launch scale; must be validated through bank distribution access, survey evidence, and pilot signups | Low |
| Monthly active traders, Year 3 | 3,000 | 15,000 | 50,000 | Analyst assumption; upside requires bank-backed distribution and strong retention | Low |
| Average monthly trading volume per active user | GEL 100 | GEL 300 | GEL 700 | Analyst assumption based on micro-stakes positioning; should be validated through user survey and pilot trading behavior | Low |
| Gross take rate / spread capture | 1.0% | 2.0% | 3.0% | Global prediction-market fee/spread proxy; FT notes Kalshi’s monetization depends heavily on fee design and that sports markets are more revenue-rich than other event types | Medium |
| Monthly gross revenue, Year 1 | GEL 500 | GEL 12,000 | GEL 210,000 | Formula output | Medium |
| Monthly gross revenue, Year 3 | GEL 3,000 | GEL 90,000 | GEL 1,050,000 | Formula output | Medium |

### Revenue Interpretation

The base case is deliberately conservative. A compliant Georgian product focused on macro and civic events should not assume the same volume intensity as sports contracts. Recent reporting shows that sports markets have driven a large share of Kalshi’s recent trading and revenue, while non-sports event contracts may monetize more weakly.

Source: [Financial Times, prediction-market economics and Kalshi revenue discussion](https://www.ft.com/content/1ac03f57-bd5d-4196-85ff-4bd96dc69e0d)

This matters for Georgia because the regulatory-first path should probably begin with lower-risk, verifiable markets such as:

- GEL exchange-rate ranges,
- inflation prints,
- policy-rate decisions,
- public macroeconomic indicators,
- election turnout,
- municipal outcomes, and
- other clearly resolvable civic events.

These are more regulator-friendly than sports-style contracts, but they may produce lower repeat trading frequency.

---

## Part 2. Cost Logic

### Variable Cost Formula

```text
Monthly Payment Cost =
Monthly Active Traders × Average Monthly Trading Volume per User × Payment Processing Cost %
```

Payment cost is modeled as a percentage of trading volume for simplicity. In practice, the relevant cost base may be deposits, withdrawals, card top-ups, bank transfers, or wallet movements rather than gross trading volume. This should be refined once payment-provider pricing is available.

### Fixed Cost Formula

```text
Monthly Fixed Cost =
Market-Maker / Liquidity Subsidy
+ Compliance and Legal Run Cost
+ Platform Run Cost
```

### Scenario Assumptions

The original model used five major cost drivers: payment processing cost, liquidity subsidy, compliance and legal run cost, platform run cost, and customer acquisition cost. This section breaks those assumptions into more specific components so the cost model is easier to defend and validate.

These are still **analyst assumptions**, not final vendor quotes. Payment costs should be validated with PSPs and banks, liquidity costs with market makers, and compliance costs with Georgian legal counsel or bank compliance teams.

| Driver | Conservative | Base Case | Upside | Main components | Confidence |
|---|---:|---:|---:|---|---|
| Payment processing cost | 1.5% | 1.0% | 0.5% | PSP/card fee, bank/wallet transfer fee, chargeback reserve, reconciliation, gateway/API cost | Low |
| Market-maker / liquidity subsidy | GEL 50k/month | GEL 50k/month | GEL 100k/month | External market-maker retainer, liquidity rewards, seed liquidity usage, spread support, monitoring tools | Low-Medium |
| Compliance and legal run cost | GEL 50k/month | GEL 30k/month | GEL 50k/month | Legal counsel, compliance officer, AML/KYC monitoring, regulatory reporting, responsible-use review, market surveillance | Low |
| Platform run cost | GEL 60k/month | GEL 70k/month | GEL 120k/month | Product, engineering, DevOps, data/AI, QA, support, cloud, monitoring, security, analytics | Low |
| Customer acquisition cost | GEL 150 | GEL 75 | GEL 30 | Paid ads, referral bonuses, onboarding incentive, influencer/community, education content, KYC drop-off | Low |

---

### Detailed Cost Breakdown

## 1. Payment Processing Cost

### Original assumption

| Scenario | Cost |
|---|---:|
| Conservative | 1.5% |
| Base case | 1.0% |
| Upside | 0.5% |

### What this includes

Payment processing cost should include:

- card acquiring / PSP fee,
- bank transfer or wallet fee,
- refund and failed transaction handling,
- fraud and chargeback reserve,
- reconciliation cost,
- payment gateway / API fee,
- possible FX cost if crypto or USD rails are used.

### Scenario breakdown

| Component | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| PSP / card acquiring fee | 1.00% | 0.70% | 0.30% |
| Bank transfer / wallet fee | 0.20% | 0.10% | 0.05% |
| Fraud / chargeback reserve | 0.20% | 0.10% | 0.05% |
| Reconciliation / failed payment cost | 0.10% | 0.10% | 0.05% |
| Payment API / gateway cost | Included | Included | Included |
| **Total** | **1.50%** | **1.00%** | **0.50%** |

### Interpretation

The conservative case assumes the platform behaves like a standalone fintech using external PSP or card rails. The repository’s competitive landscape notes Payze’s 2.5–3% commission-rate range as a Georgian payment-gateway proxy, which supports the idea that external payment rails may be expensive for a micro-stakes trading product.

The base case assumes partial bank support and negotiated pricing.

The upside case assumes the product is embedded inside TBC or another large bank ecosystem, using lower-cost internal wallet, account-transfer, or closed-loop payment rails.

---

## 2. Market-Maker / Liquidity Subsidy

### Original assumption

| Scenario | Cost |
|---|---:|
| Conservative | GEL 50,000 / month |
| Base case | GEL 50,000 / month |
| Upside | GEL 100,000 / month |

### Why upside is higher

The upside case has more users, more markets, and higher trading activity. Therefore, the platform needs deeper order books, tighter spreads, and more market-maker capacity. Even though the upside case is more attractive economically, it also requires more liquidity support.

Prediction markets need liquidity providers or automated market-making structures because early markets may not naturally have enough buyers and sellers on both sides. Liquidity providers must be compensated because they take inventory risk, adverse-selection risk, and volatility risk.

### Scenario breakdown

| Component | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| External market-maker retainer | GEL 20,000 | GEL 20,000 | GEL 40,000 |
| Liquidity rewards / spread support | GEL 15,000 | GEL 15,000 | GEL 30,000 |
| Platform seed liquidity reserve usage | GEL 10,000 | GEL 10,000 | GEL 20,000 |
| Market-maker monitoring tools | GEL 3,000 | GEL 3,000 | GEL 5,000 |
| Risk buffer for volatile markets | GEL 2,000 | GEL 2,000 | GEL 5,000 |
| **Total** | **GEL 50,000** | **GEL 50,000** | **GEL 100,000** |

### Team / role implication

This line item assumes the platform has liquidity management capability, but staff salaries should stay inside **platform run cost** to avoid double counting.

| Role | FTE (Full-Time Equivalent) | Monthly cost assumption |
|---|---:|---:|
| Liquidity Manager | 1.0 | GEL 8,000–12,000 |
| Market Operations Analyst | 1.0 | GEL 4,000–7,000 |
| Part-time trading / risk advisor | 0.25–0.5 | GEL 5,000–10,000 equivalent |

### What to validate

Before final submission, the team should validate:

- number of markets live at launch,
- minimum order-book depth required per market,
- maximum acceptable bid-ask spread,
- whether liquidity is provided internally, externally, or through an AMM,
- whether NBG would allow internal market-making by the platform or bank sponsor.

---

## 3. Compliance and Legal Run Cost

### Original assumption

| Scenario | Cost |
|---|---:|
| Conservative | GEL 50,000 / month |
| Base case | GEL 30,000 / month |
| Upside | GEL 50,000 / month |

### What this includes

Compliance and legal run cost should include:

- Georgian legal counsel,
- regulatory counsel / sandbox application support,
- compliance officer or MLRO allocation,
- AML/KYC review,
- market-surveillance policy,
- responsible-use policy,
- dispute-resolution policy,
- NBG reporting,
- payment-partner reporting,
- audit and documentation.

### Scenario breakdown

| Component | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| External legal counsel | GEL 15,000 | GEL 8,000 | GEL 12,000 |
| Compliance officer / MLRO allocation | GEL 8,000 | GEL 7,000 | GEL 10,000 |
| Regulatory reporting / documentation | GEL 5,000 | GEL 4,000 | GEL 7,000 |
| AML/KYC monitoring support | GEL 5,000 | GEL 4,000 | GEL 7,000 |
| Market surveillance / integrity review | GEL 5,000 | GEL 3,000 | GEL 6,000 |
| Responsible-use / consumer protection review | GEL 5,000 | GEL 2,000 | GEL 4,000 |
| Audit / policy / governance buffer | GEL 7,000 | GEL 2,000 | GEL 4,000 |
| **Total** | **GEL 50,000** | **GEL 30,000** | **GEL 50,000** |

### Why base case is lower than conservative

The base case assumes:

- the bank partner already has compliance infrastructure,
- KYC/AML processes can be reused,
- the legal category is partially clarified through NBG pre-consultation,
- reporting can piggyback on existing bank controls.

The conservative case is higher because uncertainty remains high and more external legal review is needed.

The upside case rises again because scale increases the volume of monitoring, reporting, disputes, and market-integrity work.

### Suggested staffing

| Role | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| Compliance Lead / MLRO | 0.5 FTE | 0.5 FTE | 1.0 FTE |
| Legal Counsel | External | External / part-time | External + internal counsel |
| Market Surveillance Analyst | 0.5 FTE | 0.5 FTE | 1.0 FTE |
| Responsible-Use / Customer Protection Lead | 0.5 FTE | 0.25 FTE | 1.0 FTE |
| Regulatory Reporting Analyst | 0.25 FTE | 0.25 FTE | 0.5 FTE |

### What to validate

Before final submission, the team should get estimates from:

- Georgian legal counsel,
- bank compliance team,
- AML/KYC vendor,
- external audit or regulatory advisory provider.

---

## 4. Platform Run Cost

### Original assumption

| Scenario | Cost |
|---|---:|
| Conservative | GEL 60,000 / month |
| Base case | GEL 70,000 / month |
| Upside | GEL 120,000 / month |

### What this includes

Platform run cost should include:

- software engineering,
- product management,
- cloud hosting,
- APIs and data pipelines,
- market admin tools,
- security monitoring,
- customer support,
- DevOps / infrastructure,
- analytics and dashboards,
- official data-source ingestion.

---

### Conservative platform team: GEL 60,000 / month

This is a lean sandbox / MVP team.

| Role / cost item | FTE | Monthly cost assumption | Monthly total |
|---|---:|---:|---:|
| Product Manager | 0.5 | GEL 8,000 | GEL 4,000 |
| Backend Engineer | 1.0 | GEL 9,000 | GEL 9,000 |
| Frontend Engineer | 1.0 | GEL 8,000 | GEL 8,000 |
| Data / AI Engineer | 0.5 | GEL 10,000 | GEL 5,000 |
| DevOps / Security Engineer | 0.5 | GEL 10,000 | GEL 5,000 |
| QA / Test Engineer | 0.5 | GEL 4,000 | GEL 2,000 |
| Customer Support / Ops | 1.0 | GEL 3,000 | GEL 3,000 |
| UX / Content Designer | 0.25 | GEL 6,000 | GEL 1,500 |
| Cloud / infrastructure | n/a | n/a | GEL 8,000 |
| Monitoring / security tools | n/a | n/a | GEL 4,000 |
| Data/API subscriptions | n/a | n/a | GEL 3,000 |
| Admin tools / analytics | n/a | n/a | GEL 2,500 |
| Contingency | n/a | n/a | GEL 5,000 |
| **Total** |  |  | **GEL 60,000** |

---

### Base-case platform team: GEL 70,000 / month

This assumes a controlled pilot with stronger reliability and monitoring.

| Role / cost item | FTE | Monthly cost assumption | Monthly total |
|---|---:|---:|---:|
| Product Manager | 0.75 | GEL 8,000 | GEL 6,000 |
| Backend Engineer | 1.0 | GEL 9,000 | GEL 9,000 |
| Frontend Engineer | 1.0 | GEL 8,000 | GEL 8,000 |
| Data / AI Engineer | 1.0 | GEL 10,000 | GEL 10,000 |
| DevOps / Security Engineer | 0.75 | GEL 10,000 | GEL 7,500 |
| QA / Test Engineer | 0.75 | GEL 4,000 | GEL 3,000 |
| Customer Support / Ops | 1.5 | GEL 3,000 | GEL 4,500 |
| UX / Content Designer | 0.5 | GEL 6,000 | GEL 3,000 |
| Cloud / infrastructure | n/a | n/a | GEL 8,000 |
| Monitoring / security tools | n/a | n/a | GEL 4,000 |
| Data/API subscriptions | n/a | n/a | GEL 3,000 |
| Admin tools / analytics | n/a | n/a | GEL 2,000 |
| Contingency | n/a | n/a | GEL 2,000 |
| **Total** |  |  | **GEL 70,000** |

---

### Upside platform team: GEL 120,000 / month

This assumes stronger user activity, more markets, live surveillance, and a larger support burden.

| Role / cost item | FTE | Monthly cost assumption | Monthly total |
|---|---:|---:|---:|
| Product Manager | 1.0 | GEL 9,000 | GEL 9,000 |
| Engineering Lead | 1.0 | GEL 14,000 | GEL 14,000 |
| Backend Engineers | 2.0 | GEL 9,000 | GEL 18,000 |
| Frontend / Mobile Engineers | 1.5 | GEL 8,000 | GEL 12,000 |
| Data / AI Engineers | 1.5 | GEL 11,000 | GEL 16,500 |
| DevOps / Security Engineer | 1.0 | GEL 11,000 | GEL 11,000 |
| QA / Test Engineer | 1.0 | GEL 5,000 | GEL 5,000 |
| Customer Support / Ops | 3.0 | GEL 3,500 | GEL 10,500 |
| UX / Content Designer | 0.5 | GEL 6,000 | GEL 3,000 |
| Cloud / infrastructure | n/a | n/a | GEL 10,000 |
| Monitoring / security tools | n/a | n/a | GEL 5,000 |
| Data/API subscriptions | n/a | n/a | GEL 4,000 |
| Admin tools / analytics | n/a | n/a | GEL 2,000 |
| Contingency | n/a | n/a | GEL 10,000 |
| **Total** |  |  | **GEL 120,000** |

### Roles that matter most

For a Polymarket/Kalshi-type platform, the most important technical roles are not only generic app developers. The platform needs:

- backend / trading systems engineer,
- frontend / mobile engineer,
- data / AI engineer,
- DevOps / security engineer,
- market operations analyst,
- product manager,
- compliance / risk integration owner,
- support / dispute operations.

---

## 5. Data Source Fees

For the Georgian MVP, data costs should be modest because the first markets should rely on official public sources. The more important cost is not raw data purchase, but data governance: making sure every market has an approved source, backup source, timestamp, and resolution rule.

| Data source | Use | Expected cost |
|---|---|---:|
| Geostat | Inflation, economic indicators | Likely free / public |
| NBG | Policy rate, exchange rates, monetary data | Likely free / public |
| CEC | Election results, turnout | Likely free / public |
| FX reference data provider | Backup GEL/USD or global FX feeds | GEL 500–2,000 / month |
| Cloud database / data warehouse | Market data, user behavior, audit logs | Included in cloud / infrastructure |
| Analytics / BI tool | Dashboards, reporting | GEL 500–2,000 / month |

---

## 6. Customer Acquisition Cost

### Original assumption

| Scenario | CAC |
|---|---:|
| Conservative | GEL 150 |
| Base case | GEL 75 |
| Upside | GEL 30 |

### What CAC includes

Customer acquisition cost should include:

- paid social ads,
- influencer / podcast sponsorship,
- referral bonus,
- onboarding incentive,
- education content,
- app-store optimization,
- KYC drop-off cost,
- conversion funnel testing,
- affiliate / community campaigns.

### Scenario breakdown

| Component | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| Paid social / performance marketing | GEL 60 | GEL 30 | GEL 8 |
| Referral bonus / user incentive | GEL 40 | GEL 25 | GEL 12 |
| Influencer / podcast / community | GEL 20 | GEL 10 | GEL 3 |
| Education / onboarding content | GEL 10 | GEL 5 | GEL 3 |
| KYC / onboarding drop-off cost | GEL 15 | GEL 4 | GEL 3 |
| Campaign tools / CRM | GEL 5 | GEL 1 | GEL 1 |
| **Total CAC** | **GEL 150** | **GEL 75** | **GEL 30** |

### Interpretation

The conservative CAC assumes the platform is mostly standalone and must buy attention through paid acquisition.

The base case assumes some bank or payment-partner support, but not full app integration.

The upside case assumes TBC or another major bank embeds the product inside its existing app, reducing the need for paid acquisition.

### What to validate

Before final submission, validate:

- bank in-app campaign conversion rate,
- paid social cost per verified signup,
- KYC completion rate,
- cost per first deposit,
- cost per first trade,
- referral conversion rate,
- 30-day retained trader rate.

---

### Cost Interpretation

These costs behave differently as the platform scales.

**Payment cost** improves in the upside case because bank-backed rails reduce external PSP dependence.

**Liquidity subsidy** rises in the upside case because more users and more markets require deeper order books.

**Compliance cost** is lower in the base case if the bank can reuse existing compliance infrastructure, but rises again in the upside case because more users, disputes, and market surveillance require more oversight.

**Platform run cost** increases with scale because the product needs stronger engineering, data, security, and support.

**CAC** falls sharply in the upside case because distribution shifts from paid acquisition to bank-embedded acquisition.

The strongest strategic conclusion is:

> The platform does not become viable just because users trade micro-stakes. It becomes viable only if bank backing reduces CAC and payment cost while liquidity support makes markets usable before network effects form.

---

## Part 3. Contribution Margin

### Contribution Formula

```text
Contribution per User =
Average Monthly Trading Volume per User × (Gross Take Rate - Payment Processing Cost %)
```

This formula excludes one-time CAC. CAC is modeled separately because acquisition costs are usually paid upfront or amortized over the expected customer lifetime.

| Driver | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| Average monthly volume per user | GEL 100 | GEL 300 | GEL 700 |
| Gross take rate | 1.0% | 2.0% | 3.0% |
| Payment processing cost | 1.5% | 1.0% | 0.5% |
| Contribution per user / month | **-GEL 0.50** | **GEL 3.00** | **GEL 17.50** |

### Interpretation

The conservative case is structurally unviable because payment cost exceeds gross take rate. The platform loses money on each unit of trading volume before fixed costs.

The base case produces only **GEL 3.00 contribution per active user per month**, meaning the platform needs very large scale to cover fixed costs.

The upside case is much more attractive because higher user volume, stronger take rate, and lower payment cost create **GEL 17.50 contribution per active user per month**.

---

## Part 4. Breakeven Analysis

### Breakeven Formula

```text
Breakeven Active Users =
Monthly Fixed Cost ÷ Contribution per User
```

| Driver | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| Market-maker / liquidity subsidy | GEL 50,000 | GEL 50,000 | GEL 100,000 |
| Compliance and legal run cost | GEL 50,000 | GEL 30,000 | GEL 50,000 |
| Platform run cost | GEL 60,000 | GEL 70,000 | GEL 120,000 |
| Total monthly fixed cost | **GEL 160,000** | **GEL 150,000** | **GEL 270,000** |
| Contribution per user / month | **-GEL 0.50** | **GEL 3.00** | **GEL 17.50** |
| Breakeven active users | **Not viable** | **50,000** | **15,429** |

### Breakeven Interpretation

The base case is strategically possible but economically difficult. At **GEL 3.00 contribution per user per month**, the platform requires approximately **50,000 monthly active traders** just to cover liquidity support, compliance, legal, and platform run costs.

The upside case is much more attractive. At **GEL 17.50 contribution per user per month**, breakeven falls to about **15,400 monthly active traders**.

This is why the bank-backed assumption matters. If TBC or another large bank can lower CAC, reduce payment friction, and provide distribution through an existing app ecosystem, the platform becomes much more plausible.

---

## Part 5. Year 1 and Year 3 Scenario Outputs

### Year 1 Monthly Economics

| Metric | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| Monthly active traders | 500 | 2,000 | 10,000 |
| Average monthly volume per user | GEL 100 | GEL 300 | GEL 700 |
| Gross take rate | 1.0% | 2.0% | 3.0% |
| Monthly gross revenue | GEL 500 | GEL 12,000 | GEL 210,000 |
| Payment cost | GEL 750 | GEL 6,000 | GEL 35,000 |
| Monthly contribution before fixed costs | -GEL 250 | GEL 6,000 | GEL 175,000 |
| Monthly fixed cost | GEL 160,000 | GEL 150,000 | GEL 270,000 |
| Monthly operating profit / loss before CAC | **-GEL 160,250** | **-GEL 144,000** | **-GEL 95,000** |
| One-time CAC for Year 1 active base | GEL 75,000 | GEL 150,000 | GEL 300,000 |

### Year 3 Monthly Economics

| Metric | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| Monthly active traders | 3,000 | 15,000 | 50,000 |
| Average monthly volume per user | GEL 100 | GEL 300 | GEL 700 |
| Gross take rate | 1.0% | 2.0% | 3.0% |
| Monthly gross revenue | GEL 3,000 | GEL 90,000 | GEL 1,050,000 |
| Payment cost | GEL 4,500 | GEL 45,000 | GEL 175,000 |
| Monthly contribution before fixed costs | -GEL 1,500 | GEL 45,000 | GEL 875,000 |
| Monthly fixed cost | GEL 160,000 | GEL 150,000 | GEL 270,000 |
| Monthly operating profit / loss before CAC | **-GEL 161,500** | **-GEL 105,000** | **GEL 605,000** |

---

## Part 6. Customer Acquisition Economics

CAC is one of the most important bank-backed advantages in this model.

A standalone prediction-market startup would likely need to spend heavily on paid social, referral bonuses, influencer partnerships, app-store acquisition, and education.

A bank-backed platform could reduce CAC by embedding the product inside an existing mobile banking or brokerage ecosystem.

| Driver | Conservative | Base Case | Upside |
|---|---:|---:|---:|
| CAC | GEL 150 | GEL 75 | GEL 30 |
| Year 1 active users | 500 | 2,000 | 10,000 |
| Implied Year 1 acquisition spend | GEL 75,000 | GEL 150,000 | GEL 300,000 |
| Interpretation | Standalone paid acquisition | Mixed paid + partner distribution | Bank-backed embedded distribution |

### CAC Interpretation

The upside case does not assume CAC is low because Georgian users are cheap to acquire. It assumes CAC is low because the platform has access to bank-backed distribution.

The strategic logic is:

```text
Bank backing
→ lower CAC
→ higher trust
→ easier payment rails
→ faster scale
→ better liquidity
→ narrower spreads
→ higher retention
→ better unit economics
```

Without this distribution advantage, the base case remains weak.

---

## Part 7. Key Assumptions Table

| ID | Assumption | Scenario Range | Basis | Confidence | What to Validate |
|---|---|---:|---|---|---|
| A1 | Monthly active traders, Year 1 | 500 to 10,000 | Analyst assumption; depends heavily on TBC/bank distribution and regulatory confidence | Low | User survey, bank funnel data, pilot waitlist |
| A2 | Monthly active traders, Year 3 | 3,000 to 50,000 | Analyst assumption; upside requires network effects and repeat usage | Low | Retention, referral rate, repeat trading behavior |
| A3 | Monthly trading volume per user | GEL 100 to GEL 700 | Analyst assumption for micro-stakes event contracts | Low | User survey, beta trading data, deposit behavior |
| A4 | Gross take rate / spread capture | 1.0% to 3.0% | Global prediction-market fee/spread proxy; sports economics excluded from base case | Medium | Actual fee tolerance, spread targets, maker/taker structure |
| A5 | Payment processing cost | 0.5% to 1.5% | Analyst assumption; depends on bank/PSP rail | Low | Quotes from TBC Pay, Payze, card acquirer, bank transfer provider |
| A6 | Liquidity subsidy | GEL 50k to GEL 100k/month | Analyst assumption; liquidity providers require compensation for risk | Low-Medium | Market-maker conversations, pilot spread targets |
| A7 | Compliance/legal run cost | GEL 30k to GEL 50k/month | Analyst assumption for regulated/sandbox pilot | Low | Georgian legal counsel, compliance staffing plan |
| A8 | Platform run cost | GEL 60k to GEL 120k/month | Analyst assumption for MVP-to-scale platform operations | Low | Engineering, cloud, support, security, monitoring budget |
| A9 | CAC | GEL 30 to GEL 150 | Analyst assumption; lower end depends on bank-backed distribution | Low | Paid marketing test, bank in-app conversion benchmark |
| A10 | Breakeven active users | Not viable to 50,000 | Formula output | Medium | Recalculate after all above assumptions are validated |

---

## Part 8. Strategic Implications

### 1. Micro-stakes trading alone is not enough

The model shows that low-stakes trading can attract users, but it does not automatically create attractive economics.

In the base case, 2,000 active users trading GEL 300 per month at a 2% take rate produce only GEL 12,000 in monthly gross revenue.

### 2. The platform must reach liquidity scale quickly

Prediction markets become more useful when markets are liquid, spreads are narrow, and outcome resolution is trusted.

However, early liquidity is expensive. Until the platform has natural two-sided flow, it will likely need either market-maker subsidies or internal liquidity support.

### 3. Bank backing is central to the business case

A bank-backed route improves the model through three channels:

- lower CAC,
- cheaper payment rails, and
- higher user trust.

Without these advantages, the platform may remain strategically interesting but economically weak.

### 4. Sports economics should not be used in the base case

Sports contracts may generate much higher frequency and revenue, but they also increase gambling-law and reputational risk.

The base case should therefore rely on macro, civic, and financial-information markets, while sports-style economics should only appear in a clearly labeled risky upside scenario.

Recent reporting shows how prediction-market growth has become heavily tied to sports activity, which is exactly the positioning risk a Georgian bank-backed platform should avoid.

Source: [Financial Times, prediction-market economics and Kalshi revenue discussion](https://www.ft.com/content/1ac03f57-bd5d-4196-85ff-4bd96dc69e0d)

### 5. Market-integrity costs may rise as the platform scales

Prediction markets are exposed to insider-information and manipulation risks because users can trade directly on the outcome of events.

Reuters reported rising suspicious-trading concerns across Kalshi and Polymarket as the sector grew rapidly in 2026.

Source: [Reuters, suspicious trading in prediction markets](https://www.reuters.com/legal/government/prediction-markets-see-surge-suspicious-trades-popularity-explodes-2026-05-15/)

This means the model should not treat compliance cost as a small one-time legal expense. Market surveillance, insider-trading controls, restricted-user policies, event-design review, and dispute-resolution procedures should be built into recurring operating costs.

---

## Part 9. Recommended Model Conclusion

The prediction-market platform should proceed only if three conditions are met:

1. **Regulatory path:** NBG is willing to review or test limited event contracts under a sandbox or supervised innovation framework.
2. **Distribution path:** A bank-backed partner such as TBC can reduce CAC and payment friction through existing app, KYC, and payment infrastructure.
3. **Liquidity path:** The platform can secure market-maker support or an approved internal liquidity structure before public launch.

If these conditions are not met, the platform may still be interesting as a small crypto-native experiment, but the mass-market GEL-settled thesis becomes weak.

The model’s central finding is:

> A Georgian prediction-market platform is not primarily a technology bet. It is a regulated-liquidity and distribution bet. The economics only work if bank-backed trust, low-cost rails, and early liquidity support allow the platform to reach meaningful trading scale before fixed compliance and market-making costs overwhelm revenue.

---

## Source Notes

The global prediction-market benchmark is split between two different models:

- **Kalshi:** regulated U.S. event-contract exchange model.
- **Polymarket:** crypto-native prediction-market model.

These should not be treated as the same regulatory precedent.

Recent reporting on Kalshi suggests that sports-related markets have become much more important to revenue than slower macro or civic event contracts. This is why sports economics should not be used in the base case for a Georgian bank-backed launch.

Source: [Financial Times, prediction-market economics and Kalshi revenue discussion](https://www.ft.com/content/1ac03f57-bd5d-4196-85ff-4bd96dc69e0d)

Reuters reported that prediction-market growth has been accompanied by suspicious-trading and insider-information concerns. This supports including recurring market-integrity and compliance costs in the model.

Source: [Reuters, suspicious trading in prediction markets](https://www.reuters.com/legal/government/prediction-markets-see-surge-suspicious-trades-popularity-explodes-2026-05-15/)

Research on automated market makers and liquidity provision supports the assumption that liquidity is not free. Liquidity providers require compensation for taking inventory, adverse-selection, and volatility risk.

Source: [Automated market maker and liquidity-provider risk research, arXiv](https://arxiv.org/abs/2311.08725)

Recent academic work on Kalshi and Polymarket also shows that prediction-market prices can be useful, but they are not perfect probabilities across all domains. Calibration and market quality depend on event type, trading volume, platform design, and participant mix.

Source: [Prediction market calibration research, arXiv](https://arxiv.org/abs/2602.19520)

A Wall Street Journal report on Polymarket’s dispute-resolution process highlights why transparent outcome resolution and governance should be treated as operating requirements, not optional product details.

Source: [Wall Street Journal, Polymarket dispute-resolution discussion](https://www.wsj.com/finance/polymarket-bet-disputes-fb1b8c6a)

---
