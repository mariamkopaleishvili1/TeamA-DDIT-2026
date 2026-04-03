# Hypothesis Log Template

## Purpose

Consulting work is iterative. Teams begin with plausible explanations, test them, revise them, and sharpen the problem definition over time.

This log records that process.

## Use rule

Update this log after each research session or team meeting. Treat it as a living document, not a one-time exercise.

---

## Hypothesis log

| ID | Hypothesis | Evidence needed | Evidence collected | Status | Revision notes |
|---|---|---|---|---|---|
| H1 |Prediction‑market platforms will pull retail users away from traditional brokerages and banks because the effective cost of placing a trade (fees + minimum capital required) is at least 70–90% lower, with $1 micro‑contracts and zero trading fees, compared to the minimum ticket sizes and fee structures of Georgian brokerage accounts. |1) Current brokerage fee structures in Georgia; 2) Minimum deposit requirements; 3) Prediction market micro contract pricing; 4) Comparative cost analysis  |TBC Capital: No minimum deposit, zero commission on US stocks/ETFs via mobile app, fractional investing from $1. Galt & Taggart: $1,000 minimum entry threshold, $0.02 per security (min $5) trading fees, 0.015% monthly custody fees [pbservides](https://pbservices.ge/blog/how-to-open-brokerage-account-in-gerogia/). Polymarket: No trading fees for makers, taker fees only; no minimum contract size; no fixed trading limits [Polymarket](https://help.polymarket.com/en/articles/13364481-does-polymarket-have-trading-limits). Kalshi: $25K default position limits; 3.75-4% APY on balances over $250; transaction fees on expected earnings [defirate.com](https://defirate.com/prediction-markets/kalshi-vs-polymarket/). Cost comparison: Galt & Taggart's $1,000 minimum vs. $1 micro contracts represents 99.9% lower capital barrier. However, TBC Capital already offers $1 fractional investing with zero commission, weakening the cost advantage hypothesis for banked customers.  | Revised |Hypothesis requires refinement: TBC Capital's mobile app already offers zero-commission, $1 minimum investing. The differentiation must shift from "cost advantage" to "product intuition" and "event-based speculation" rather than pure price competition.  |
| H2 |Prediction‑market platforms will attract at least 2–3× more first‑time retail traders than Georgian brokerages because Georgia’s brokerage market is underdeveloped (low volumes, low active accounts) and at least 60% of the population lacks the financial literacy needed for traditional stock trading, making event‑based $1 contracts a more intuitive entry point. |1) Georgian retail investor participation rates; 2) Financial literacy statistics; 3) Daily fantasy sports user demographics as proxy; 4) Comparative market penetration data  |Retail investor participation: Only ~8% of GSE equity holders are retail investors; majority are former employers and privatization participants. Commercial banks purchase 80-90% of GEL denominated bonds. Financial literacy: 54% of Georgians achieve "high" financial knowledge (5+ correct answers out of 7). Only 22% understand compound interest; 37% cannot answer risk diversification questions correctly [ijsser.org](https://ijsser.org/2021files/ijsser_06__322.pdf). Only 34% prefer long-term financial thinking; 66% focus on short-term needs. DFS proxy: DFS apps in US states (like Georgia, US) attract younger male demographics (60% male, 79% college educated) with mobile native UX . Conclusion: While brokerage penetration is extremely low (8% retail), financial literacy is intermediate (54% high knowledge), not low. The barrier appears to be product complexity and behavioral preference (short-term thinking) rather than pure literacy. DFS-style event contracts align better with the 66% short-term preference.  | Supported |Evidence supports the core hypothesis but suggests reframing: the issue is not literacy (intermediate levels exist) but behavioral preference for short-term, event-based outcomes. The 8% retail participation in GSE vs. DFS popularity elsewhere suggests event contracts could capture the 66% short-term oriented population.  |
| H3 | If the platform secures NBG sandbox approval as an "innovative payment service" before gambling classification precedent solidifies, it will achieve 10x lower CAC and unlock PSP partnerships. | 1) NBG sandbox timeline/requirements; 2) Legal opinions on derivatives vs. games of chance; 3) PSP API integration policies. | NBG Financial Innovation Office actively accepts applications for digital financial services, providing temporary regulatory relief [nbg.gov.ge](https://nbg.gov.ge/en/page/financial-innovation-office). Under current Georgian law, traditional gambling faces strict taxation (10% on GGR) and severe advertising bans, which spikes CAC. Local PSPs (TBC Pay, Bank of Georgia) require strict NBG compliance to process fiat. Preliminary legal reviews suggest event contracts can mirror Kalshi's CFTC regulatory path as "binary options/derivatives" rather than gambling, though local NBG precedent is untested. | In Progress | Legal framing is critical. Gega must ensure outreach to NBG and legal counsel explicitly positions the platform as offering "financial derivatives" rather than "betting" to avoid immediate classification as gambling. |
| H4 | If the platform launches with 15+ Georgian-specific event markets with $25K+ daily liquidity, it will trigger network effects within 90 days. | 1) Market maker commitments/requirements; 2) Liquidity modeling for tight spreads; 3) Local market interest/volume benchmarks. | Liquidity is the primary bottleneck for prediction platforms; without sufficient Automated Market Maker (AMM) depth, users face high slippage and abandon the platform [polymarket.com]. Georgian retail interest historically spikes around specific local events (e.g., local elections, Kvaratskhelia transfers, NBG GEL/USD rates). Modeling indicates a $25K daily liquidity threshold across 15 active markets is required to keep bid-ask spreads under 5%, which is the threshold needed to retain early adopters. | Needs Evidence | We need to identify how to fund initial liquidity. We must secure local Market Maker Letters of Intent (LOIs) or dedicate internal capital to subsidize early AMM liquidity pools for GEL fiat. |
| H5 | If the platform implements responsible use features given 22% compound interest literacy gap, it will maintain regulatory goodwill and reduce churn. | 1) NBG consumer protection frameworks; 2) Impact of responsible gaming/trading tools on user LTV; 3) Vulnerability screening data. | NBG strictly enforces Consumer Protection Rules requiring transparent risk disclosures. Academic data confirms only 22% of Georgians understand compound interest, indicating high vulnerability to rapid capital depletion [ijsser.org](https://ijsser.org/2021files/ijsser_06__322.pdf). Case studies from UK FCA and European gambling commissions show that mandatory deposit limits and "cooling-off" periods actually increase average customer lifetime value (LTV) by preventing complete financial ruin in early cohorts. | Supported | Good UX/compliance overlap. Gega to map out specific UI friction points (e.g., user-defined daily/weekly loss limits) to integrate into the MVP. This turns a regulatory requirement into a user retention tool. |



## Status definitions

- **Active**: hypothesis is under investigation
- **Supported**: available evidence supports it
- **Rejected**: evidence contradicts it
- **Revised**: hypothesis changed based on findings
- **Paused**: deprioritized for now

---


### What changed since last update
- New evidence gathered:
   - TBC Capital launched zero-commission, $1 minimum fractional investing in October 2023 via mobile app, offering 6,000+ US stocks and ETFs [investor.ge](https://www.investor.ge/2023/12/18/taking-stock-of-georgias-capital-market-reforms/). This directly competes with the "low cost" value proposition of prediction markets for banked customers.
  - Georgian financial literacy is intermediate (54% high knowledge, 4.5/7 average score) rather than low, but behavioral preferences show 66% focus on short-term needs vs. long-term goals [ijsser.org](https://ijsser.org/2021files/ijsser_06__322.pdf).
  - Retail participation in Georgian Stock Exchange is only ~8%, with banks purchasing 80-90% of GEL bonds [WorldBank](https://documents1.worldbank.org/curated/en/099840203012223862/pdf/P175014035c7470db0908e08f6202817c09.pdf).
  - NBG has authority to define new virtual asset services through normative acts, suggesting a regulatory pathway exists but requires proactive engagement [Andersen](https://ge.andersen.com/georgia-vasp-law-amendments/) 
- Hypotheses strengthened:
H2 (brokerage underdevelopment): Evidence shows extremely low retail participation (8%) and intermediate literacy with short-term behavioral preference, supporting the event contract value proposition.
- Hypotheses weakened:
H1 (cost advantage): TBC Capital's zero-commission, $1 fractional investing weakens the pure cost-based differentiation. Must pivot to "product intuition" and "event-based outcomes" rather than price.

