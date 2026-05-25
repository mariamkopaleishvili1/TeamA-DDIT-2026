# Prediction-Market ROI Model

## Project Context

Team A: Georgian Prediction-Market Platform  
Industry: Fintech  
Market: Republic of Georgia  
Recommended strategic option: NBG sandbox-first, GEL-settled where possible, bank-backed, with responsible-use controls embedded from day one  
Repository file: `deli wk2/Completed/prediction_market_roi_model.md`

---

## Executive Summary

This model estimates the revenue potential, cost structure, breakeven point, payback period, IRR, and 5-year NPV of a Georgian prediction-market platform.

The model is based on market research showing that Georgia already has a meaningful population engaged in risk-active financial behavior. The research identifies an estimated **651,000 risk-active users**, made up of gambling-related users, cryptocurrency users, and retail stock users. This user pool is not treated as a perfectly de-duplicated census count. It is used as a planning proxy for the population already familiar with speculative, event-based, digital, or risk-based financial activity.

The central financial insight is that this market should be analyzed through **turnover velocity**, not only through deposits, balances, or net user losses. Gambling, cryptocurrency trading, brokerage, and prediction markets all allow capital to be recycled repeatedly. A user can generate high transaction volume with a smaller underlying cash balance if they trade or bet multiple times during the month.

Based on the research file, the model uses **GEL 6,546 average monthly turnover per active risk user** as the core volume assumption. This figure represents capital cycling through risk-based activity, not monthly disposable income spent.

At a **1 percent platform take rate**, the revenue scenarios are:

| Scenario | Adoption of 651k risk-active pool | Monthly active users | Monthly platform turnover | Monthly gross revenue |
|---|---:|---:|---:|---:|
| Conservative | 4 percent | 26,040 | GEL 170.5M | GEL 1.70M |
| Base case | 10 percent | 65,100 | GEL 426.1M | GEL 4.26M |
| Upside | 18 percent | 117,180 | GEL 767.1M | GEL 7.67M |

The model shows that the platform can become financially attractive if it captures a small but meaningful share of Georgia’s existing risk-active turnover. The economics are not driven by a high fee rate. They are driven by user adoption, high turnover velocity, low payment cost, liquidity quality, and trusted bank-backed distribution.

The base-case financials are:

| Base-case metric | Value |
|---|---:|
| Monthly active users | 65,100 |
| Monthly platform turnover | GEL 426.1M |
| Monthly gross revenue | GEL 4.26M |
| Monthly operating profit before CAC recovery | GEL 2.33M |
| Annual benefit at stabilization | GEL 27.95M |
| Total investment to recover, including CAC | GEL 20.81M |
| Payback period | 8.9 months |
| 5-year NPV at 18 percent discount rate | GEL 57.99M |
| IRR | 99.9 percent |

The strategic implication is clear:

> A Georgian prediction-market platform is financially meaningful only if it converts existing risk-active behavior into a regulated, GEL-settled, trustable event-contract marketplace. The platform should not launch as a standalone speculative app. It should launch through a bank-backed, regulatory-first path where payment rails, market integrity, responsible-use controls, and outcome resolution are solved before scale.

---

## 1. Purpose of the Model

This model answers four questions.

First, how large is the risk-active user base that could plausibly create demand for prediction markets in Georgia?

Second, how much monthly trading turnover could the platform generate if it captures a portion of that user base?

Third, what monthly revenue can the platform produce at a conservative take rate?

Fourth, after payment costs, liquidity support, compliance, legal, platform operations, and customer acquisition costs, does the platform have a credible path to breakeven?

The model is not a final forecast. It is a structured planning model designed for board-level decision-making. It separates sourced inputs, research-derived assumptions, and analyst assumptions.

---

## 2. Source Base

### 2.1 Gambling and betting turnover

Geostat publishes turnover data for enterprises engaged in gambling and betting activities. This data is important because gambling turnover represents the volume of bets made, not net gambling revenue or net user losses.

This distinction matters for prediction markets. Event-contract platforms can also produce high transaction turnover because users may recycle capital across multiple short-duration contracts.

Source:  
https://www.geostat.ge/en/modules/categories/622/turnover-of-enterprises-engaged-in-gambling-and-betting-activities

### 2.2 Gambling-related user estimate

Eurasianet reports that anti-gambling groups estimated between **350,000 and 600,000** Georgians as problem gamblers. This model uses the midpoint, **475,000**, as a planning proxy for the gambling-related risk-active segment.

This estimate is not an official count of active gambling accounts. It is used only as a market-sizing proxy for the scale of risk-based behavior in Georgia. The platform should not be positioned toward vulnerable or gambling-excluded users.

Source:  
https://eurasianet.org/georgian-government-moves-to-rein-in-gambling

### 2.3 Cryptocurrency users

Triple-A estimates that more than **115,000 people** in Georgia own cryptocurrency. This supports the existence of a digitally active speculative user base familiar with volatility, wallets, market pricing, and risk-based financial behavior.

Source:  
https://www.triple-a.io/cryptocurrency-ownership-data/georgia

### 2.4 Digital-assets revenue and user context

Statista’s Digital Assets Market Insights for Georgia provides a supporting benchmark for the local digital-assets market. It reports projected digital-assets revenue, users, and average revenue per user. This model uses Triple-A’s 115,000 crypto-owner estimate for the crypto user segment, while Statista is used as a supporting context source for the digital-assets market.

Source:  
https://www.statista.com/outlook/fmo/digital-assets/georgia

### 2.5 Brokerage and retail stock turnover

The retail stock segment is estimated using a reverse take-rate methodology. The research applies a brokerage fee coefficient to the combined brokerage revenues of TBC Capital and Galt & Taggart to estimate securities trading turnover.

The brokerage estimate is lower-confidence than the gambling turnover figure because it depends on the exact interpretation of financial statement line items. It is still useful as a proxy for formal retail investment and trading activity.

Sources:

- Reportal.ge, TBC Capital LLC financial statements: https://reportal.ge/ka/Reports/Report?q=204929961
- Reportal.ge, Galt & Taggart LLC financial statements: https://reportal.ge/ka/Reports/Report?q=211359206
- TBC Bank Group PLC investor reports: https://www.tbcbankgroup.com/
- Lion Finance Group annual reports: https://lionfinancegroup.uk/annual-reports/annual-report-archive/

---

## 3. Market Sizing Logic

### 3.1 Risk-active population

The model defines the risk-active population as people already involved in gambling, cryptocurrency, or retail stock trading activity.

```text
Risk-active population =
Gambling-related segment
+ Cryptocurrency segment
+ Retail stock segment
```

Using the research inputs:

```text
475,000 + 115,000 + 61,000 = 651,000 users
```

This figure is a planning proxy. It may include overlap across the three categories. For example, a user may gamble, hold crypto, and trade stocks. The model therefore does not treat 651,000 as a verified unique-user count. It treats it as a directional estimate of the population already participating in risk-based financial or speculative activity.

### 3.2 Turnover velocity

The model uses:

```text
Average monthly turnover per active risk user = GEL 6,546
```

This number should be interpreted as turnover, not net income, net losses, or monthly deposits. It represents the amount of capital that cycles through risk-based activity during a month.

The assumption is relevant for prediction markets because prediction-market users can also recycle capital. A user can trade multiple short-term contracts, exit positions, re-enter new markets, and generate transaction volume that is larger than the initial deposit.

### 3.3 Implication for prediction markets

The platform does not need users to deposit GEL 6,546 per month. It needs active users to generate turnover through repeated trading. This makes turnover velocity the correct revenue driver.

The financial opportunity depends on whether the platform can migrate part of the existing risk-active turnover into a regulated, bank-backed, event-contract marketplace.

---

## 4. Revenue Model

### 4.1 Core formula

```text
Monthly active users =
Risk-active user pool × Adoption rate
```

```text
Monthly platform turnover =
Monthly active users × Average monthly turnover per active user
```

```text
Monthly gross revenue =
Monthly platform turnover × Take rate
```

### 4.2 Scenario assumptions

The model uses a **1 percent take rate** across all three primary scenarios. This is intentionally conservative.

A 1 percent rate is more appropriate for a bank-backed, regulator-facing product than a high-margin assumption. Revenue may come from explicit transaction fees, spread capture, or a hybrid structure. For modeling purposes, the take rate is treated as blended platform monetization.

| Driver | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Risk-active user pool | 651,000 | 651,000 | 651,000 |
| Adoption rate | 4 percent | 10 percent | 18 percent |
| Monthly active users | 26,040 | 65,100 | 117,180 |
| Monthly turnover per active user | GEL 6,546 | GEL 6,546 | GEL 6,546 |
| Monthly platform turnover | GEL 170.5M | GEL 426.1M | GEL 767.1M |
| Take rate | 1 percent | 1 percent | 1 percent |
| Monthly gross revenue | GEL 1.70M | GEL 4.26M | GEL 7.67M |

### 4.3 Scenario interpretation

The conservative case assumes 4 percent adoption of the estimated risk-active pool. This is a limited migration of users who are already familiar with risk-based activity. It is not a mass-market adoption case.

The base case assumes 10 percent adoption. This requires bank-backed distribution, trusted GEL payment rails, understandable event contracts, visible liquidity, and a reputation advantage over offshore or informal substitutes.

The upside case assumes 18 percent adoption. This requires strong app distribution, high repeat usage, trusted resolution, and broader public awareness. It should be treated as a scale scenario, not a launch-stage expectation.

---

## 5. Payment Cost Logic

### 5.1 Why payment cost is not applied to full turnover

Payment processing cost should not be applied directly to full trading turnover.

If users keep balances inside the platform and recycle funds across multiple trades, payment providers do not charge on every internal trade. Payment costs apply mainly to deposits, withdrawals, card top-ups, bank transfers, wallet funding, failed payments, refunds, chargebacks, and off-ramp activity.

Therefore, the model separates two concepts:

```text
Trading turnover drives platform revenue.
Funding flow drives payment cost.
```

### 5.2 Funding flow formula

```text
Monthly funding flow =
Monthly platform turnover × Funding flow ratio
```

```text
Monthly payment cost =
Monthly funding flow × Payment processing cost
```

### 5.3 Funding flow assumption

The model uses a **20 percent funding flow ratio across all scenarios**.

This means that for every GEL 100 of trading turnover, GEL 20 flows through payment rails as deposits, withdrawals, or balance movement. The remaining turnover comes from users recycling balances inside the platform.

The funding flow ratio is held constant because the main scenario driver should be user adoption, not assumed optimization of payment behavior. The platform may improve payment cost through bank-backed rails, but the model does not rely on a large improvement in funding-flow behavior to make the upside case work.

### 5.4 Payment assumptions

| Driver | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Monthly platform turnover | GEL 170.5M | GEL 426.1M | GEL 767.1M |
| Funding flow ratio | 20 percent | 20 percent | 20 percent |
| Monthly funding flow | GEL 34.1M | GEL 85.2M | GEL 153.4M |
| Payment processing cost | 1.5 percent | 1.0 percent | 0.5 percent |
| Monthly payment cost | GEL 511k | GEL 852k | GEL 767k |

### 5.5 Interpretation

The conservative case assumes weaker bank integration and more reliance on external PSP or card rails. This produces a higher payment cost.

The base case assumes partial bank support and negotiated payment pricing.

The upside case assumes deeper integration into a bank ecosystem, where users can fund and withdraw through lower-cost internal account, wallet, or closed-loop rails.

The key correction is that funding flow is now held constant across scenarios. Payment cost may still improve by scenario because payment pricing can improve with bank integration and scale, but the model does not depend on users recycling a much higher share of balances in the upside case.

This is why the bank-backed strategy matters financially. Bank backing is not only a trust and regulatory advantage. It can also reduce the payment cost that would otherwise weaken micro-stakes economics.

---

## 6. Operating Cost Model

The platform requires fixed operating costs even before it reaches scale.

These costs include:

- market-maker and liquidity support;
- compliance, legal, and governance;
- platform technology, cybersecurity, and monitoring;
- support, disputes, reporting, and market operations.

### 6.1 Fixed monthly cost assumptions

| Cost item | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Liquidity and market-maker support | GEL 150k | GEL 300k | GEL 650k |
| Compliance, legal, and governance | GEL 80k | GEL 150k | GEL 250k |
| Platform technology and security | GEL 220k | GEL 450k | GEL 800k |
| Support, disputes, reporting, and market operations | GEL 100k | GEL 180k | GEL 350k |
| Total fixed monthly cost | GEL 550k | GEL 1.08M | GEL 2.05M |

### 6.2 Cost interpretation

Fixed costs rise with scale. The upside case has more users, more markets, more disputes, more alerts, more liquidity requirements, and more reporting burden.

Liquidity is one of the most important costs. Prediction markets are not useful if users see empty order books, wide spreads, or no exit price. Market-maker support is therefore not optional during early scale-up.

Technology and security costs are also material. The platform handles KYC data, wallet balances, trading records, outcome-resolution evidence, responsible-use triggers, user restrictions, and dispute logs. This requires stronger auditability and monitoring than a standard content or information app.

---

## 7. Monthly Contribution and Operating Profit

### 7.1 Formula

```text
Net trading contribution =
Monthly gross revenue - Monthly payment cost
```

```text
Monthly operating profit before CAC recovery =
Net trading contribution - Fixed monthly cost
```

### 7.2 Scenario output

| Metric | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Monthly active users | 26,040 | 65,100 | 117,180 |
| Monthly platform turnover | GEL 170.5M | GEL 426.1M | GEL 767.1M |
| Monthly gross revenue | GEL 1.70M | GEL 4.26M | GEL 7.67M |
| Monthly payment cost | GEL 511k | GEL 852k | GEL 767k |
| Net trading contribution | GEL 1.19M | GEL 3.41M | GEL 6.90M |
| Fixed monthly cost | GEL 550k | GEL 1.08M | GEL 2.05M |
| Monthly operating profit before CAC recovery | GEL 643k | GEL 2.33M | GEL 4.85M |
| Monthly operating profit per active user | GEL 24.7 | GEL 35.8 | GEL 41.4 |

### 7.3 Interpretation

The model becomes attractive when the platform reaches meaningful adoption from the risk-active pool.

The base case generates approximately **GEL 2.33M monthly operating profit before CAC recovery**. This result depends heavily on the turnover velocity assumption. If adopted users generate materially lower turnover than GEL 6,546 per month, the economics weaken.

The model therefore shifts the main strategic risk. The primary risk is not whether a 1 percent take rate can generate revenue. The primary risk is whether the platform can attract risk-active users, support high turnover with enough liquidity, and maintain regulatory comfort and responsible-use controls.

---

## 8. Breakeven Analysis

### 8.1 Breakeven formula

```text
Net contribution per active user before fixed cost =
Monthly turnover per user × Take rate
-
Monthly turnover per user × Funding flow ratio × Payment processing cost
```

```text
Breakeven active users =
Monthly fixed cost ÷ Net contribution per active user before fixed cost
```

### 8.2 Breakeven output

| Metric | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Monthly turnover per active user | GEL 6,546 | GEL 6,546 | GEL 6,546 |
| Gross revenue per active user | GEL 65.46 | GEL 65.46 | GEL 65.46 |
| Payment cost per active user | GEL 19.64 | GEL 13.09 | GEL 6.55 |
| Net contribution per active user before fixed cost | GEL 45.82 | GEL 52.37 | GEL 58.91 |
| Fixed monthly cost | GEL 550k | GEL 1.08M | GEL 2.05M |
| Breakeven active users | 12,003 | 20,623 | 34,796 |
| Scenario active users | 26,040 | 65,100 | 117,180 |
| Position vs breakeven | Above breakeven | Above breakeven | Above breakeven |

### 8.3 Interpretation

All three primary scenarios reach operating breakeven because all three preserve the core turnover assumption of GEL 6,546 monthly turnover per active user.

The conservative case has the narrowest margin because it has higher payment cost and fewer active users. The base case reaches breakeven comfortably. The upside case has the highest fixed cost, but the larger user base more than offsets that cost.

A separate severe downside stress test is included later because the primary conservative case is not a failure case. It is a lower-adoption but still functioning case.

---

## 9. Customer Acquisition Cost and Payback

### 9.1 CAC assumptions

| Driver | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Monthly active users acquired | 26,040 | 65,100 | 117,180 |
| CAC per active user | GEL 150 | GEL 75 | GEL 30 |
| Total CAC to reach scenario | GEL 3.91M | GEL 4.88M | GEL 3.52M |

### 9.2 CAC interpretation

The conservative case has high CAC because the platform depends more on paid acquisition, referral incentives, education, community-building, and onboarding campaigns.

The base case assumes bank-backed distribution lowers CAC through existing app access, trusted brand, KYC infrastructure, customer communications, and lower user friction.

The upside case assumes embedded distribution through a major bank or fintech ecosystem, resulting in the lowest CAC.

This is why distribution is part of the financial model. The platform is not only competing on product features. It is also competing on the cost of reaching eligible, trustable, repeat-active users.

---

## 10. Investment Requirement and Payback

### 10.1 Source and proxy basis

No public Polymarket or Kalshi financial statement provides a detailed operating-cost structure that can be copied directly into this model. The investment requirement is therefore built from a bottom-up platform budget and checked against public fintech and exchange comparables.

The main proxy sources are:

- Robinhood, a retail trading platform, which reported a 2025 adjusted operating expense forecast of approximately **US$2.28B**. This shows that regulated trading platforms require large ongoing spending on technology, compliance, operations, and customer infrastructure at scale.
- CME Group, a regulated derivatives exchange, reported quarterly operating expenses above **US$500M** in Q1 2025, with higher technology spending cited as a cost driver. This supports the assumption that exchange-like infrastructure is fixed-cost heavy.
- ICE announced an investment of up to **US$2B** in Polymarket at an approximately **US$8B pre-money valuation**. This does not provide operating costs, but it confirms that prediction-market infrastructure has become a serious institutional category rather than a small app experiment.

These sources are not direct cost inputs for Georgia. They are reasonableness checks. The actual Georgian model uses a smaller bottom-up budget based on the required platform capabilities: regulatory work, MVP build, wallet and payment design, source registry, market surveillance, responsible-use controls, outcome resolution, liquidity support, and reporting.

### 10.2 First 18-month investment requirement

The model assumes a first 18-month prediction-market transformation investment of:

```text
GEL 15.93M
```

This is the platform-specific investment before full public launch. It includes H1 foundation and H2 sandbox validation.

It excludes large post-18-month public launch capital, such as mass-market advertising, expanded liquidity pools, broader market-category expansion, and full production scaling.

### 10.3 Year 1 capital requirement

Year 1 means the first 12 months from project approval. This includes H1 foundation and the first six months of controlled sandbox activity.

| Year 1 cost item | Type | GEL amount | Rationale |
|---|---|---:|---|
| Core MVP, wallet workflow, admin tools, and trading interface | CapEx | GEL 2.70M | Product and engineering build for market listing, trading, wallet movement, settlement, and admin workflow |
| Official source registry, data governance, and audit logs | CapEx | GEL 1.35M | Required for event resolution, reporting, source confidence, and regulator-ready evidence |
| Payment, KYC, AML, and wallet-ledger integration | CapEx | GEL 1.20M | Required before sandbox users can deposit, withdraw, and trade safely |
| Market surveillance and responsible-use monitoring tools | CapEx | GEL 1.35M | Required for manipulation alerts, user-risk triggers, adverse actions, and auditability |
| Outcome-resolution and reporting automation build | CapEx | GEL 0.80M | Required for resolution memos, dispute tracking, and reporting packs |
| Legal, regulatory, and NBG pre-consultation | OpEx | GEL 0.54M | External counsel, regulatory classification, NBG engagement, governance design |
| Market taxonomy, contract templates, and disclosures | OpEx | GEL 0.90M | Contract design, bilingual market wording, risk warnings, user testing |
| Sandbox operations, support, and user education | OpEx | GEL 1.00M | Pilot operations, customer support, onboarding education, user communication |
| Liquidity and market-maker reserve | OpEx | GEL 1.35M | Market-maker support, spread support, quote monitoring, liquidity reserve |
| Compliance, governance, and reporting run cost | OpEx | GEL 0.81M | Governance committee operations, reporting, risk review, compliance support |
| **Year 1 CapEx total** | **CapEx** | **GEL 7.40M** |  |
| **Year 1 OpEx total** | **OpEx** | **GEL 4.60M** |  |
| **Total Year 1 capital requirement** | **Total** | **GEL 12.00M** |  |

The remaining **GEL 3.93M** of the first 18-month investment is allocated to months 13 to 18. That period covers extended surveillance, reporting, market-quality improvement, final legal review, payment-cost validation, liquidity testing, and the board launch gate.

### 10.4 Total investment by scenario

The total investment to recover includes the first 18-month platform investment plus customer acquisition cost required to reach each scenario’s active-user base.

```text
Total investment to recover =
First 18-month transformation investment + Scenario CAC
```

| Metric | Conservative | Base case | Upside |
|---|---:|---:|---:|
| First 18-month transformation investment | GEL 15.93M | GEL 15.93M | GEL 15.93M |
| CAC per active user | GEL 150 | GEL 75 | GEL 30 |
| Scenario active users | 26,040 | 65,100 | 117,180 |
| Scenario CAC | GEL 3.91M | GEL 4.88M | GEL 3.52M |
| Total investment to recover | GEL 19.84M | GEL 20.81M | GEL 19.45M |

The conservative CAC is higher because weaker adoption requires more paid acquisition and user education per active user. The upside CAC is lower because it assumes embedded bank distribution, stronger organic adoption, and lower onboarding friction.

### 10.5 Annual benefit

Annual benefit is defined as annualized operating profit before CAC recovery.

```text
Annual benefit =
Monthly operating profit before CAC recovery × 12
```

| Metric | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Monthly operating profit before CAC recovery | GEL 643k | GEL 2.33M | GEL 4.85M |
| Annual benefit | GEL 7.72M | GEL 27.95M | GEL 58.24M |

### 10.6 Payback period

```text
Payback period =
Total investment to recover ÷ Monthly operating profit before CAC recovery
```

| Metric | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Total investment to recover | GEL 19.84M | GEL 20.81M | GEL 19.45M |
| Monthly operating profit before CAC recovery | GEL 643k | GEL 2.33M | GEL 4.85M |
| Payback period | 30.8 months | 8.9 months | 4.0 months |

The base-case payback period is short because the model assumes high turnover velocity once the platform reaches 65,100 monthly active users. This should be treated as a model output, not as a guaranteed result. The main validation requirement is whether sandbox data confirms the turnover assumption.

### 10.7 Five-year NPV and IRR

The NPV and IRR use the following assumptions:

- discount rate: 18 percent;
- Year 0 cash flow: total investment to recover;
- Year 1 benefit: 60 percent of annual benefit;
- Year 2 benefit: 85 percent of annual benefit;
- Year 3 benefit: 100 percent of annual benefit;
- Year 4 benefit: 110 percent of annual benefit;
- Year 5 benefit: 120 percent of annual benefit.

The 18 percent discount rate is an analyst assumption. It reflects the risk of a new regulated fintech category in Georgia, legal classification uncertainty, liquidity risk, payment risk, and user-adoption uncertainty.

| Metric | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Total investment to recover | GEL 19.84M | GEL 20.81M | GEL 19.45M |
| Annual benefit at stabilization | GEL 7.72M | GEL 27.95M | GEL 58.24M |
| 5-year NPV at 18 percent | GEL 1.93M | GEL 57.99M | GEL 144.77M |
| IRR | 21.7 percent | 99.9 percent | 208.7 percent |

### 10.8 Severe downside stress test

The primary scenario table keeps the original assumptions: 4 percent, 10 percent, and 18 percent adoption; GEL 6,546 turnover per active user; and 1 percent take rate. Under those assumptions, even the conservative case remains above breakeven.

A separate severe downside stress test is required because a credible downside should show what happens if the core turnover thesis fails.

The severe downside stress test assumes:

- adoption falls to 2 percent of the risk-active pool;
- monthly turnover per active user falls to GEL 3,273, equal to 50 percent of the base assumption;
- effective take rate falls to 0.75 percent;
- payment processing cost is 1.5 percent;
- funding flow ratio remains 20 percent;
- fixed monthly cost rises to GEL 650k because the platform still carries regulatory, compliance, and infrastructure cost despite weak adoption;
- CAC per active user is GEL 180 because weak organic demand forces higher paid acquisition.

| Severe downside stress-test metric | Value |
|---|---:|
| Monthly active users | 13,020 |
| Monthly turnover per active user | GEL 3,273 |
| Monthly gross revenue | GEL 320k |
| Monthly payment cost | GEL 128k |
| Fixed monthly cost | GEL 650k |
| Monthly operating profit before CAC recovery | -GEL 458k |
| Total investment to recover | GEL 18.27M |
| Annual benefit | -GEL 5.50M |
| 5-year NPV at 18 percent | -GEL 33.78M |
| IRR | Not meaningful |
| Payback period | Not achieved |

This stress test is the true failure case. It shows that the platform should not move to public launch unless sandbox evidence confirms that adoption and turnover are much closer to the base case than to the severe downside.

### 10.9 Interpretation

The model now meets the financial case requirement:

- base-case total investment: **GEL 20.81M**, including transformation investment and CAC;
- base-case annual benefit: **GEL 27.95M**;
- base-case payback period: **8.9 months**;
- base-case IRR: **99.9 percent**;
- base-case 5-year NPV: **GEL 57.99M** at an 18 percent discount rate;
- Year 1 capital requirement: **GEL 12.00M**, split into **GEL 7.40M CapEx** and **GEL 4.60M OpEx**.

The severe downside case does not reach breakeven, does not pay back, and produces a negative NPV. This keeps the model credible. The platform should not move to public launch unless sandbox evidence shows that adoption, turnover velocity, payment cost, liquidity, and responsible-use controls are tracking closer to the base case than the severe downside case.

---

## 11. Scenario Narratives

### 11.1 Conservative case

The conservative case assumes 4 percent adoption of the estimated risk-active pool, equal to 26,040 monthly active users.

This case is plausible if the platform launches through a controlled bank-backed model but does not immediately become mainstream. Users trade actively, but acquisition remains relatively expensive and payment costs remain high because the platform still depends partly on external rails or incomplete bank integration.

The conservative case generates positive monthly operating profit, but payback is slower than the base case. It supports continued operation and learning, but not aggressive public expansion.

### 11.2 Base case

The base case assumes 10 percent adoption of the estimated risk-active pool, equal to 65,100 monthly active users.

This case requires the bank-backed strategy to work. The platform needs trusted distribution, GEL settlement, KYC and AML infrastructure, understandable event contracts, enough liquidity, responsible-use controls, and reliable outcome resolution.

The base case is the main planning case. It shows that the platform can become economically attractive if it captures a minority of the existing risk-active market.

### 11.3 Upside case

The upside case assumes 18 percent adoption of the estimated risk-active pool, equal to 117,180 monthly active users.

This case requires strong bank-app placement, broad awareness, strong liquidity, repeat engagement, and event categories that generate frequent trading without pushing the product into gambling-style positioning.

The upside case produces strong economics, but it also increases regulatory, reputational, surveillance, dispute, and responsible-use risk. It should be treated as a strategic option, not as the default launch case.

### 11.4 Severe downside stress case

The severe downside stress case is not the primary planning case. It exists to test whether the project still works if the two most important assumptions fail.

The case assumes the platform reaches only 2 percent adoption of the risk-active pool and users generate only half of the expected monthly turnover. Under those conditions, the platform becomes loss-making and does not pay back.

This has a clear strategic implication. Public launch should not be approved simply because the app works technically. It should be approved only if sandbox data shows that users are adopting the platform and generating trading turnover at levels that support the economics.

---

## 12. Sensitivity Analysis

### 12.1 Most important assumptions

The model is most sensitive to two assumptions:

1. monthly turnover per active user;
2. adoption rate, meaning the number of monthly active users.

These two assumptions matter more than small changes in the funding-flow ratio. For that reason, the funding-flow ratio is held constant at 20 percent across the primary scenarios.

### 12.2 Sensitivity table 1: monthly turnover per active user

This table keeps base-case active users fixed at 65,100 and changes only turnover per active user.

| Turnover assumption | Monthly turnover per active user | Monthly operating profit | Payback period |
|---|---:|---:|---:|
| 50 percent of base | GEL 3,273 | GEL 625k | 33.3 months |
| 75 percent of base | GEL 4,910 | GEL 1.48M | 14.1 months |
| 100 percent of base | GEL 6,546 | GEL 2.33M | 8.9 months |
| 125 percent of base | GEL 8,183 | GEL 3.18M | 6.5 months |

The key lesson is that the model remains positive at half of the base turnover assumption, but payback becomes much longer. Therefore, sandbox trading must measure actual turnover per active user, not only registrations or first trades.

### 12.3 Sensitivity table 2: adoption rate

This table keeps turnover per active user fixed at GEL 6,546 and changes only adoption. CAC changes with the number of active users at the base-case CAC of GEL 75 per active user.

| Adoption assumption | Monthly active users | Monthly operating profit | Payback period |
|---|---:|---:|---:|
| 5 percent adoption | 32,550 | GEL 625k | 29.4 months |
| 7.5 percent adoption | 48,825 | GEL 1.48M | 13.3 months |
| 10 percent adoption | 65,100 | GEL 2.33M | 8.9 months |
| 15 percent adoption | 97,650 | GEL 4.03M | 5.8 months |

The adoption sensitivity shows why bank-backed distribution is central to the strategy. The platform does not need to capture the whole risk-active market, but it does need to move meaningfully beyond a small niche user base.

### 12.4 Sensitivity interpretation

The two most consequential assumptions are user adoption and turnover per active user.

If adoption is weak, fixed costs dominate. If turnover is weak, revenue per active user is too low to justify liquidity, compliance, and platform operations.

The public launch decision should therefore depend on two evidence tests during sandbox:

- actual monthly turnover per active user;
- realistic path to at least 5 to 10 percent adoption of the risk-active pool.

If both tests fail, the platform should not scale, even if the product works technically.

---

## 13. Strategic Implications

The model supports five strategic conclusions.

First, Georgia has a real market opportunity because large numbers of users already participate in risk-based activity through gambling, crypto, and retail trading.

Second, prediction-market revenue should be modeled through turnover velocity, not deposits or net user spend.

Third, the bank-backed route is economically important. It can lower CAC, reduce payment cost, improve trust, and make GEL settlement more credible.

Fourth, the base case should not rely on sports contracts. Sports may increase volume, but they also increase gambling-comparison risk. The regulator-friendly base case should focus on macro, civic, and official-data events.

Fifth, the public launch decision should depend on sandbox evidence. The key evidence is actual monthly turnover per active user, payment cost, dispute rate, liquidity quality, responsible-use interventions, and contribution margin.

---

## 14. Board Decision Metrics

Before public launch, the board should require evidence in five areas.

### 14.1 Demand metrics

- monthly active traders;
- activation rate from invited users;
- repeat trading rate;
- monthly turnover per active user;
- turnover by market category.

### 14.2 Revenue metrics

- gross take rate;
- spread capture;
- gross revenue;
- revenue by market category;
- fee sensitivity.

### 14.3 Cost metrics

- payment cost as percent of funding flow;
- liquidity subsidy per market;
- compliance and legal run cost;
- platform run cost;
- support cost per active user;
- CAC per active user.

### 14.4 Risk metrics

- dispute rate;
- payout delay rate;
- suspicious trading alerts;
- responsible-use interventions;
- deposit-limit triggers;
- user complaints;
- market pause frequency.

### 14.5 Launch gates

Public launch should require:

- regulatory path not blocked by NBG engagement;
- payment partners accepting the risk-control framework;
- active user adoption tracking toward at least the conservative case;
- monthly turnover per active user materially above low micro-stakes levels;
- liquidity within acceptable spread targets;
- responsible-use controls functioning without excessive complaints;
- positive contribution margin after payment cost and fixed operating cost.

---

## 15. Model Limitations and Validation Requirements

### 15.1 User overlap

The 651,000 risk-active population may include duplicated users. A user may gamble, hold crypto, and trade stocks. The figure is used as a market proxy, not a verified unique-user count.

### 15.2 Gambling estimate

The 475,000 gambling-related estimate is based on the midpoint of a 350,000 to 600,000 estimate cited by Eurasianet from anti-gambling groups. It is not an official count of active gambling accounts.

The figure is useful for market sizing, but it should not be used to define the target customer as vulnerable or gambling-excluded users.

### 15.3 Responsible-use risk

The platform should not position itself as a substitute for gambling-excluded or vulnerable users. Gambling data proves that risk-based event behavior exists in Georgia. It does not define the acquisition strategy.

The target should be eligible, banked, digitally active adults who pass KYC, AML, and responsible-use screening.

### 15.4 Turnover migration

The central assumption is that adopted users generate GEL 6,546 monthly prediction-market turnover. This is plausible because prediction markets allow repeated short-term trading, but it must be validated through sandbox data.

### 15.5 Payment-cost treatment

Payment costs are modeled on funding flow, not full trading turnover. This is correct if users keep balances and recycle funds. If users frequently deposit and withdraw, payment costs rise.

### 15.6 Liquidity capacity

High turnover requires strong liquidity. The model assumes market-maker or internal liquidity support can sustain meaningful trading volume. This must be tested before scale.

### 15.7 Regulatory classification

Strong economics do not solve legal classification. The financial case is valid only if the sandbox or legal pathway is feasible.

---

## 16. Final Recommendation

The ROI model supports a bank-backed sandbox strategy.

The platform can become financially attractive if it captures a small but meaningful share of Georgia’s existing risk-active turnover. The economic case is strongest when the product has trusted distribution, GEL payment rails, low payment cost, credible liquidity, official-source resolution, and strong responsible-use controls.

The correct next step is not immediate public launch. The correct next step is a controlled, bank-backed, regulatory-first pilot that validates the assumptions in this model.

The public launch decision should be conditional on evidence from sandbox trading:

- actual monthly turnover per active user;
- actual payment cost;
- actual liquidity subsidy;
- dispute and payout-resolution performance;
- responsible-use intervention rate;
- CAC by acquisition channel;
- regulator and payment-partner comfort;
- contribution margin and breakeven path.

The board should approve scale only if the platform proves that user demand, unit economics, market integrity, and responsible-use controls can operate together.

---

## 17. References

Geostat. Turnover of enterprises engaged in gambling and betting activities.  
https://www.geostat.ge/en/modules/categories/622/turnover-of-enterprises-engaged-in-gambling-and-betting-activities

Eurasianet. Georgian government moves to rein in gambling.  
https://eurasianet.org/georgian-government-moves-to-rein-in-gambling

Triple-A. Cryptocurrency ownership data: Georgia.  
https://www.triple-a.io/cryptocurrency-ownership-data/georgia

Statista. Digital Assets: Georgia.  
https://www.statista.com/outlook/fmo/digital-assets/georgia

Reportal.ge. TBC Capital LLC financial statements.  
https://reportal.ge/ka/Reports/Report?q=204929961

Reportal.ge. Galt & Taggart LLC financial statements.  
https://reportal.ge/ka/Reports/Report?q=211359206

TBC Bank Group PLC. Annual investor reports.  
https://www.tbcbankgroup.com/

Lion Finance Group. Annual reports archive.  
https://lionfinancegroup.uk/annual-reports/annual-report-archive/

Reuters. Robinhood profit surpasses expectations as retail traders ride market momentum.  
https://www.reuters.com/business/finance/robinhood-profit-skyrockets-retail-traders-ride-market-momentum-2025-11-05/

Reuters. CME's profit narrowly misses estimate as higher costs offset trading gains.  
https://www.reuters.com/business/finance/cmes-quarterly-profit-jumps-strong-trading-activity-2025-04-23/

Reuters. NYSE parent to invest up to $2 billion in Polymarket.  
https://www.reuters.com/business/nyse-parent-nears-deal-2-billion-stake-polymarket-wsj-reports-2025-10-07/
