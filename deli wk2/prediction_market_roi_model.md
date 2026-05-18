
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

| Driver | Conservative | Base Case | Upside | Source / Proxy | Confidence |
|---|---:|---:|---:|---|---|
| Payment processing cost | 1.5% | 1.0% | 0.5% | Analyst assumption; requires quotes from Georgian PSPs, banks, card acquirers, or wallet providers | Low |
| Market-maker / liquidity subsidy | GEL 50,000/month | GEL 50,000/month | GEL 100,000/month | Analyst assumption; prediction markets require liquidity providers or automated market-making structures, and AMM research shows liquidity providers require compensation for risk | Low-Medium |
| Compliance and legal run cost | GEL 50,000/month | GEL 30,000/month | GEL 50,000/month | Analyst assumption; higher in conservative and upside cases due to legal uncertainty or broader scale | Low |
| Platform run cost | GEL 60,000/month | GEL 70,000/month | GEL 120,000/month | Analyst assumption covering cloud, engineering, support, data, product, security, and monitoring | Low |
| Customer acquisition cost | GEL 150 | GEL 75 | GEL 30 | Analyst assumption; upside depends on bank-backed distribution reducing paid acquisition needs | Low |

### Cost Interpretation

Liquidity support is one of the most important uncertain costs. Prediction markets require enough two-sided liquidity for users to enter and exit positions without wide spreads.

In decentralized market structures, liquidity providers supply capital in exchange for fees and take risk when prices move against them. Research on automated market makers emphasizes that liquidity providers face trading and adverse-selection risks, meaning they must be compensated through fees or subsidies.

Source: [Automated market maker and liquidity-provider risk research, arXiv](https://arxiv.org/abs/2311.08725)

This is why the model includes a recurring liquidity subsidy. In a real launch, the platform could provide liquidity through:

- internal treasury market-making, if approved by the regulator,
- third-party market makers,
- bank-backed liquidity support,
- automated market maker pools, or
- a hybrid approach.

Each structure has different regulatory and conflict-of-interest implications.

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
