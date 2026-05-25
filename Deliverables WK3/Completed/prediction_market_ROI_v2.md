# Prediction-Market ROI Model

## Project Context

Team A: Georgian Prediction-Market Platform  
Industry: Fintech  
Market: Republic of Georgia  
Recommended strategic option: NBG sandbox-first, GEL-settled where possible, bank-backed, with responsible-use controls embedded from day one  

---

## Executive Summary

This model estimates the revenue potential, cost structure, breakeven point, and payback profile of a Georgian prediction-market platform.

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

The model uses a **1 percent take rate** across all scenarios. This is intentionally conservative.

A 1 percent rate is more appropriate for a bank-backed, regulator-facing product than a high margin assumption. Revenue may come from explicit transaction fees, spread capture, or a hybrid structure. For modeling purposes, the take rate is treated as blended platform monetization.

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

### 5.3 Payment assumptions

| Driver | Conservative | Base case | Upside |
|---|---:|---:|---:|
| Monthly platform turnover | GEL 170.5M | GEL 426.1M | GEL 767.1M |
| Funding flow ratio | 25 percent | 20 percent | 15 percent |
| Monthly funding flow | GEL 42.6M | GEL 85.2M | GEL 115.1M |
| Payment processing cost | 1.5 percent | 1.0 percent | 0.5 percent |
| Monthly payment cost | GEL 639k | GEL 852k | GEL 575k |

### 5.4 Interpretation

The conservative case assumes weaker bank integration and more reliance on external PSP or card rails. This produces a higher payment cost.

The base case assumes partial bank support and negotiated payment pricing.

The upside case assumes deeper integration into a bank ecosystem, where users can fund and withdraw through lower-cost internal account, wallet, or closed-loop rails.

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
| Monthly payment cost | GEL 639k | GEL 852k | GEL 575k |
| Net trading contribution | GEL 1.07M | GEL 3.41M | GEL 7.10M |
| Fixed monthly cost | GEL 550k | GEL 1.08M | GEL 2.05M |
| Monthly operating profit before CAC recovery | GEL 516k | GEL 2.33M | GEL 5.05M |
| Monthly operating profit per active user | GEL 19.8 | GEL 35.8 | GEL 43.1 |

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
| Payment cost per active user | GEL 24.55 | GEL 13.09 | GEL 4.91 |
| Net contribution per active user before fixed cost | GEL 40.91 | GEL 52.37 | GEL 60.55 |
| Fixed monthly cost | GEL 550k | GEL 1.08M | GEL 2.05M |
| Breakeven active users | 13,443 | 20,623 | 33,856 |

### 8.3 Interpretation

The breakeven point is lower than in the earlier pilot-scale model because this model assumes significantly higher turnover per active user.

This does not mean the platform is easy to scale. It means the key question changes. The board should focus less on whether the platform can charge enough and more on whether the platform can credibly generate turnover, support liquidity, manage harm, resolve markets, and keep payment costs low.

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

### 10.1 First 18-month transformation investment

For payback purposes, the model uses a first 18-month prediction-market transformation investment of:

```text
GEL 15.93M
```

This estimate comes from the platform roadmap logic:

- H1 foundation: governance, NBG pre-consultation, source registry, market taxonomy, payment design, responsible-use framework, and MVP workflow;
- H2 validation: controlled sandbox pilot, liquidity programme, surveillance, reporting, and board launch gate.

This investment does not include full post-18-month public launch capital.

### 10.2 Payback formula

```text
Total investment to recover =
First 18-month transformation investment + Scenario CAC
```

```text
Payback period =
Total investment to recover ÷ Monthly operating profit before CAC recovery
```

### 10.3 Payback output

| Metric | Conservative | Base case | Upside |
|---|---:|---:|---:|
| First 18-month transformation investment | GEL 15.93M | GEL 15.93M | GEL 15.93M |
| Scenario CAC | GEL 3.91M | GEL 4.88M | GEL 3.52M |
| Total investment to recover | GEL 19.84M | GEL 20.81M | GEL 19.45M |
| Monthly operating profit before CAC recovery | GEL 516k | GEL 2.33M | GEL 5.05M |
| Estimated payback period | 38.5 months | 8.9 months | 3.9 months |

### 10.4 Interpretation

The conservative case is viable but slow. It takes more than three years to recover transformation investment and acquisition costs.

The base case is financially attractive if the assumptions hold. Payback under one year is possible because users generate high monthly turnover and the bank-backed route reduces acquisition and payment friction.

The upside case is highly attractive financially, but it should not be treated as the planning case. It depends on strong adoption, strong liquidity, low payment cost, low CAC, and regulatory comfort.

---

## 11. Scenario Narratives

### 11.1 Conservative case

The conservative case assumes 4 percent adoption of the estimated risk-active pool, equal to 26,040 monthly active users.

This case is plausible if the platform launches through a controlled bank-backed model but does not immediately become mainstream. Users trade actively, but acquisition remains relatively expensive and payment costs remain high because the platform still depends partly on external rails or incomplete bank integration.

The conservative case generates positive monthly operating profit, but payback is slow. It supports continued operation and learning, but not aggressive public expansion.

### 11.2 Base case

The base case assumes 10 percent adoption of the estimated risk-active pool, equal to 65,100 monthly active users.

This case requires the bank-backed strategy to work. The platform needs trusted distribution, GEL settlement, KYC and AML infrastructure, understandable event contracts, enough liquidity, responsible-use controls, and reliable outcome resolution.

The base case is the main planning case. It shows that the platform can become economically attractive if it captures a minority of the existing risk-active market.

### 11.3 Upside case

The upside case assumes 18 percent adoption of the estimated risk-active pool, equal to 117,180 monthly active users.

This case requires strong bank-app placement, broad awareness, strong liquidity, repeat engagement, and event categories that generate frequent trading without pushing the product into gambling-style positioning.

The upside case produces strong economics, but it also increases regulatory, reputational, surveillance, dispute, and responsible-use risk. It should be treated as a strategic option, not as the default launch case.

---

## 12. Sensitivity Analysis

### 12.1 Most important assumptions

The model is most sensitive to five variables:

1. monthly turnover per active user;
2. adoption rate;
3. take rate;
4. payment cost on funding flow;
5. liquidity subsidy.

### 12.2 Turnover sensitivity

The central assumption is:

```text
Monthly turnover per active user = GEL 6,546
```

If actual prediction-market turnover is only half of that, revenue and contribution fall materially.

Base case at full turnover:

```text
65,100 users × GEL 6,546 × 1 percent = GEL 4.26M monthly gross revenue
```

Base case at half turnover:

```text
65,100 users × GEL 3,273 × 1 percent = GEL 2.13M monthly gross revenue
```

The half-turnover case may still be viable, but the margin for liquidity, compliance, and platform operating costs becomes much tighter.

### 12.3 Take-rate sensitivity

At base-case monthly turnover of GEL 426.1M:

| Take rate | Monthly gross revenue |
|---:|---:|
| 0.5 percent | GEL 2.13M |
| 1.0 percent | GEL 4.26M |
| 1.5 percent | GEL 6.39M |

A higher take rate improves revenue, but it may create regulatory and reputational concerns if the product appears to extract gambling-style margins. A 1 percent take rate is therefore the cleaner base-case assumption.

### 12.4 Payment-cost sensitivity

Payment cost is manageable only if it is applied to funding flow rather than full trading turnover. This depends on users recycling balances inside the platform.

If users frequently deposit and withdraw, funding flow rises and payment costs increase. If the platform relies heavily on external PSP or card rails, payment costs may remain too high. This is why GEL settlement and bank-backed rails are central to the model.

### 12.5 Liquidity sensitivity

Liquidity support is the largest operating uncertainty after user activity.

If the platform cannot maintain narrow spreads without heavy subsidy, the model weakens. Liquidity should be monitored at market level, not only platform level.

Key metrics include:

- average bid-ask spread;
- order-book depth;
- market-maker uptime;
- user abandonment after seeing price;
- subsidy per GEL of trading volume;
- number of markets that fail spread thresholds.

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
