# ROI Model: AI-Driven Collections Transformation for TBC Bank

## Executive Summary

This document presents the financial case for implementing predictive early warning and automated collections orchestration at TBC Bank using AI/ML capabilities. The revised model projects a **19-month payback period** in the base case, with cumulative cash flow of **47.4M GEL ($17.6M USD)** over 5 years.

**Reviewer's take:** the original model looked overstated because it used high-end benchmark outcomes, did not clearly deduct recurring run costs, and tied scenarios too heavily to a single model-accuracy variable. This revised version uses TBC's actual 2024 scale metrics and more conservative ramp-up assumptions. [^1^] [^2^] [^5^]

---

## Part 1. Revenue Impact (Annual)

**Note:** Parts 1 and 2 below reflect the **revised base case gross benefit**. Net cash flow in Part 4 deducts recurring annual run costs for cloud, MLOps, model monitoring, vendor support, and governance. [^11^]

| Revenue driver | Year 1 | Year 2 | Year 3 | Year 4 | Year 5 | Assumption ID |
|---|---:|---:|---:|---:|---:|---|
| NPL reduction through early warning (charge-off avoidance and recovery improvement) | 2,800,000 GEL ($1.0M) | 5,000,000 GEL ($1.9M) | 6,500,000 GEL ($2.4M) | 7,600,000 GEL ($2.8M) | 9,000,000 GEL ($3.3M) | [A1] |
| Cure rate improvement (accounts brought current earlier) | 1,200,000 GEL ($440K) | 2,400,000 GEL ($890K) | 3,400,000 GEL ($1.3M) | 4,100,000 GEL ($1.5M) | 4,800,000 GEL ($1.8M) | [A2] |
| Customer retention value (prevented churn / relationship preservation) | 600,000 GEL ($220K) | 1,100,000 GEL ($410K) | 1,600,000 GEL ($590K) | 2,000,000 GEL ($740K) | 2,400,000 GEL ($890K) | [A3] |
| **Total revenue impact** | **4,600,000 GEL ($1.7M)** | **8,500,000 GEL ($3.1M)** | **11,500,000 GEL ($4.3M)** | **13,700,000 GEL ($5.1M)** | **16,200,000 GEL ($6.0M)** | |

*Exchange rate: 1 USD = 2.70 GEL (approximate average)*

---

## Part 2. Cost Impact (Annual Savings)

| Cost driver | Year 1 | Year 2 | Year 3 | Year 4 | Year 5 | Assumption ID |
|---|---:|---:|---:|---:|---:|---|
| Collections staff efficiency (workflow automation and prioritization) | 600,000 GEL ($220K) | 1,000,000 GEL ($370K) | 1,300,000 GEL ($480K) | 1,600,000 GEL ($590K) | 1,800,000 GEL ($670K) | [A4] |
| Reduced call center operations (digital self-service and automated outreach) | 300,000 GEL ($110K) | 500,000 GEL ($190K) | 700,000 GEL ($260K) | 800,000 GEL ($300K) | 900,000 GEL ($330K) | [A5] |
| Compliance and legal cost reduction | 200,000 GEL ($74K) | 300,000 GEL ($110K) | 400,000 GEL ($150K) | 450,000 GEL ($170K) | 500,000 GEL ($190K) | [A6] |
| **Total cost savings** | **1,100,000 GEL ($410K)** | **1,800,000 GEL ($670K)** | **2,400,000 GEL ($890K)** | **2,850,000 GEL ($1.1M)** | **3,200,000 GEL ($1.2M)** | |

---

## Part 3. Investment Required (Year 0)

| Cost category | Amount (GEL) | Amount (USD) | Proportion of total | Notes |
|---|---:|---:|---:|---|
| Technology platform and licensing (decision engine, outreach, model tooling) | 1,300,000 | $480,000 | 15% | Vendor software, model serving, orchestration layer |
| Implementation and integration (core banking, CRM, dialer, data warehouse) | 2,300,000 | $850,000 | 27% | Highest-risk workstream; integration complexity drives cost |
| People and change management (training, analytics product owners, SMEs) | 1,400,000 | $520,000 | 16% | Needed to convert model outputs into frontline action |
| Programme management and governance | 700,000 | $260,000 | 8% | Risk, compliance, model governance, PMO |
| Data infrastructure (feature store, streaming, monitoring, audit logs) | 1,400,000 | $520,000 | 16% | Required for real-time early-warning and model monitoring |
| Contingency (c.20% of pre-contingency build cost) | 1,400,000 | $520,000 | 16% | Buffer for delivery delays, model remediation, data issues |
| **Total investment** | **8,500,000 GEL** | **$3,150,000** | **100%** | |

**Why this is more credible than the original:** the original table's proportions did not reconcile cleanly, and it also did not make room for recurring run cost. This version keeps the upfront build in a similar range, but treats ongoing operating cost separately in Part 4. A mid-size bank AI program example cited by CostPerform includes meaningful platform, training, experimentation, and ongoing usage/compliance costs, which is directionally consistent with modeling recurring run cost rather than treating everything as one-off. [^11^]

---

## Part 4. Summary Model

**Important modeling note:** Net cash flow below is **after recurring annual run cost**. In the base case, run cost is assumed at **1.8M GEL in Year 1**, rising gradually to **2.2M GEL by Year 5** for cloud, MLOps, model monitoring, support, and governance. This was a missing item in the original draft. [^11^]

| Metric | Downside | Base Case | Upside |
|---|---:|---:|---:|
| Total investment (Year 0) | 8,500,000 GEL ($3.15M) | 8,500,000 GEL ($3.15M) | 8,500,000 GEL ($3.15M) |
| Year 1 net cash flow | 2,100,000 GEL ($780K) | 3,900,000 GEL ($1.4M) | 6,700,000 GEL ($2.5M) |
| Year 2 net cash flow | 4,600,000 GEL ($1.7M) | 8,400,000 GEL ($3.1M) | 12,800,000 GEL ($4.7M) |
| Year 3 net cash flow | 6,900,000 GEL ($2.6M) | 11,900,000 GEL ($4.4M) | 16,800,000 GEL ($6.2M) |
| Year 4 net cash flow | 8,600,000 GEL ($3.2M) | 14,450,000 GEL ($5.4M) | 19,500,000 GEL ($7.2M) |
| Year 5 net cash flow | 9,400,000 GEL ($3.5M) | 17,200,000 GEL ($6.4M) | 20,800,000 GEL ($7.7M) |
| Cumulative cash flow (Year 5, after initial investment) | 23,100,000 GEL ($8.6M) | 47,350,000 GEL ($17.6M) | 68,100,000 GEL ($25.2M) |
| **Payback period** | **27 months** | **19 months** | **14 months** |
| **NPV (10% discount rate)** | **14,100,000 GEL ($5.2M)** | **31,500,000 GEL ($11.7M)** | **47,000,000 GEL ($17.4M)** |
| **IRR** | **50%** | **85%** | **120%** |

### Scenario Assumptions: Downside / Base Case / Upside

| Assumption name | Downside | Base Case | Upside |
|---|---|---|---|
| Relative model uplift vs current scorecard (Gini improvement) | 10% | 18% | 28% |
| Reduction in annual write-offs / charge-offs on in-scope retail + MSME portfolio | 3% | 6% | 9% |
| Cure-rate uplift on early-stage delinquency (30–89 DPD equivalent) | 8% | 12% | 18% |
| Digital self-service migration from assisted collections contacts | 15% | 25% | 35% |
| Productivity gain in collections operations | 15% | 25% | 35% |
| Benefit realization ramp | 25% / 45% / 65% / 80% / 90% | 35% / 60% / 80% / 90% / 100% | 45% / 75% / 90% / 100% / 100% |
| Recurring annual run cost | 1.9M–2.3M GEL | 1.8M–2.2M GEL | 1.8M–2.2M GEL |

**Why these scenario assumptions make more sense:** the original model made scenario differentiation too dependent on one "Gini uplift" number. In practice, realized ROI also depends on adoption, workflow redesign, digital migration, and the speed of benefit ramp. The base-case **18% Gini uplift** is deliberately below the roughly **22% relative Gini uplift** implied by the retail early-warning academic paper's AUC comparison, while the upside only assumes 28%, not 35%. [^10^]

---

## Part 5. Assumptions Table

| ID | Assumption | Basis | Year 1 Impact if Assumption Changes by 20% |
|---|---|---|---|
| A1 | **6% reduction in annual write-offs / charge-offs at steady state** through earlier intervention and better prioritization | TBC reported **GEL 154.2M write-offs** in 2024. McKinsey cites **5–15%** charge-off reduction from next-gen value-at-risk assessment and an **8% reduction in charge-off losses** at a North American lender. Base case uses the lower half of that range. [^1^] [^2^] | Year 1 benefit decreases by **~560K GEL** if only **4.8%** is achieved |
| A2 | **12% cure-rate improvement** on early-stage delinquency via digital-first contact, propensity-to-pay scoring, and self-service | McKinsey finds digitally contacted digital-first customers make **12% more payments**; another bank achieved **15% more customers cured through self-service**. FICO notes early-stage accounts behave differently and many cure quickly, which is exactly where ML segmentation helps. [^3^] [^4^] [^7^] | Year 1 benefit decreases by **~240K GEL** if only **9.6%** is achieved |
| A3 | **Customer retention value of 300 GEL per saved relationship** | TBC generated **GEL 1.245B net profit** and had **1.701M monthly active customers**, implying profit per active customer well above this proxy; 300 GEL is conservative for preserved relationship value. McKinsey also cites **25%+ engagement uplift** in digital-first collections environments. [^1^] [^4^] | Year 1 value decreases by **~120K GEL** if retention value is only **240 GEL** |
| A4 | **25% productivity gain** across collections operations and assisted servicing | TBC's staff cost was **GEL 439.8M** across **9,149 employees**, or roughly **48K GEL per employee**. McKinsey cites **5–10% collector-capacity uplift** from better self-cure identification, while Debtrak and CR cite much larger manual-work reductions; 25% is a midpoint, not a top-end claim. [^1^] [^2^] [^8^] [^9^] | Year 1 savings decrease by **~120K GEL** if productivity gain is only **20%** |
| A5 | **25% assisted-to-digital migration** of routine collections interactions | McKinsey cites one bank moving **40% of inbound clients** to self-service and another achieving **15% lower cost to collect**. FICO notes traditional right-party-contact rates via phone rarely exceed **8–10%**, supporting a digital-first shift. [^4^] [^6^] | Year 1 savings decrease by **~60K GEL** if migration reaches only **20%** |
| A6 | **15% reduction in compliance / legal cost** through audit trails, frequency controls, and more consistent treatment | Debtrak says modern platforms can reduce complaints by **30–40%**, and McKinsey highlights lower conduct risk; base case assumes only half that order of magnitude for direct financial benefit. [^8^] [^4^] | Year 1 savings decrease by **~40K GEL** if only **12%** reduction is achieved |

---

## Notation and Terminology Guide

### Currency and Financial Terms

| Term | Definition | Context |
|---|---|---|
| **GEL** | Georgian Lari (national currency) | Primary currency for TBC Bank operations |
| **M** | Million | e.g., 4.6M GEL = 4,600,000 GEL |
| **K** | Thousand | e.g., 220K = 220,000 |
| **NPV** | Net Present Value | Sum of discounted future cash flows minus initial investment |
| **IRR** | Internal Rate of Return | Discount rate that makes NPV equal zero |
| **Payback Period** | Time to recover initial investment | Base case revised to 19 months |

### Banking and Credit Terms

| Term | Definition | Context |
|---|---|---|
| **NPL** | Non-Performing Loan | Loan generally 90+ days past due |
| **DPD** | Days Past Due | Number of missed days since due date |
| **Roll-rate** | Migration between delinquency buckets | Example: 30 DPD to 60/90 DPD |
| **Cure Rate** | Share of delinquent accounts brought current | Core value driver in early collections |
| **Cost of Risk** | Credit impairment expense relative to loans | TBC reported 0.5% in 2024 |
| **Provision** | Reserve for expected credit losses | Regulatory / accounting loss recognition |

### AI/ML Terms

| Term | Definition | Context |
|---|---|---|
| **Gini Coefficient** | Measure of model discrimination | Higher Gini = better ability to separate higher-risk from lower-risk borrowers |
| **Early Warning** | Detection of financial stress before hard delinquency | Uses transaction, behavioral, and servicing signals |
| **Propensity-to-Pay** | Probability a customer will pay if contacted now | Used for sequencing and treatment selection |
| **Agent Workflow** | Automated decision and action chain | Determines who to contact, when, and how |
| **Digital-first collections** | Outreach through app, SMS, email, portal before heavy agent effort | Important for cost-to-collect reduction |

### Operational Terms

| Term | Definition | Context |
|---|---|---|
| **FTE** | Full-Time Equivalent | One full-time employee |
| **CLV** | Customer Lifetime Value | Proxy for retained-relationship economics |
| **Cost-to-Collect** | Collection cost / amount recovered | Reduced through self-service and better prioritization |
| **Right-Party Contact (RPC)** | Reaching the actual debtor | Traditional phone RPC is often only 8–10% |
| **First-Party Collections** | Bank's internal collections activity | Main scope of this model |
| **Third-Party Collections** | External debt collectors / agencies | Usually later-stage accounts |

### Scenario Planning Terms

| Term | Definition | Context |
|---|---|---|
| **Base Case** | Most likely scenario | Moderate uplift, normal ramp, recurring run cost included |
| **Downside** | Conservative scenario | Lower model lift, weaker adoption, slower ramp |
| **Upside** | Optimistic but still credible scenario | Stronger model lift and adoption, faster ramp |
| **Sensitivity Analysis** | Testing the outcome if assumptions move | Shows robustness of the case |

---

## Business Case Mechanism

### How Value is Created

**Step 1: Prediction** identifies at-risk retail and MSME borrowers before they migrate deeper into delinquency. This is supported by both bank-industry practice and academic evidence that machine-learning early-warning models outperform simpler regression approaches. [^10^] [^5^]

**Step 2: Automated workflows** use those predictions to choose the right treatment, sequence, and channel. McKinsey shows that digitally contacted digital-first customers make **12% more payments**, and FICO highlights the weakness of legacy phone-only outreach where right-party-contact rates often stay around **8–10%**. [^3^] [^6^]

**Step 3: Earlier and more targeted intervention** reduces charge-offs, improves cures, shifts low-complexity work into self-service, and lowers cost-to-collect. McKinsey cites **5–15% charge-off reduction**, **15%+ lower cost of collections**, and **20–25% NPL reduction** at leading institutions that redesigned collections end-to-end; this model uses materially more conservative values because TBC already starts from relatively strong asset quality. [^2^] [^4^] [^1^]

### Order of Magnitude

For TBC Bank's in-scope **retail + MSME** book of approximately **14.65B GEL**, the more relevant anchors are not generic "20% NPL reduction" marketing claims, but TBC's actual **GEL 154.2M write-offs**, **GEL 56.8M recoveries**, **2.2% NPL ratio**, and **0.5% cost of risk**. On that base, a **6% write-off / charge-off improvement** implies about **9M GEL** of mature annual value, which is directionally sensible. [^1^]

Adding cure-rate improvement and operating savings brings the **Year 5 gross annual benefit to 19.4M GEL**, against **8.5M GEL upfront investment** plus recurring run costs of roughly **1.8M–2.2M GEL per year**. That is why the revised base case still works financially, but with a more credible **19-month payback** rather than 10 months. [^4^] [^5^] [^11^]

---

## References

[^1^]: **[TBC Bank 2024 Management Report and Financial Statements](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf)**  
Gross loans, retail/MSME exposures, NPL ratio, cost of risk, staff cost, employees, write-offs, recoveries.

[^2^]: **[McKinsey – The analytics-enabled collections model](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-analytics-enabled-collections-model)**  
Savings, charge-off reduction, collector-capacity uplift, automation examples.

[^3^]: **[McKinsey – Going digital in collections to improve resilience against credit losses](https://www.mckinsey.com/~/media/McKinsey/Business%20Functions/Risk/Our%20Insights/Going%20digital%20in%20collections%20to%20improve%20resilience%20against%20credit%20losses/Going-digital-in-collections-to-improve-resilience-against-credit-losses.ashx)**  
12% payment uplift for digital-first customers, stronger full-payment rates via digital channels.

[^4^]: **[McKinsey – Holistic customer assistance through digital-first collections](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)**  
20–25% NPL reduction at leading institutions, 15%+ lower cost of collections, 20% cash-collections uplift, self-service cures.

[^5^]: **[EY – AI-enabled early warning signals framework](https://www.ey.com/content/dam/ey-unified-site/ey-com/en-ca/services/ai/documents/ey-ai-enabled-early-warning-signal.pdf)**  
First-year benefit ranges and potential annual loss reduction for AI-enabled early warning.

[^6^]: **[FICO – Using AI to Improve Debt Collection Strategies](https://www.fico.com/blogs/using-ai-improve-debt-collection-strategies)**  
Traditional RPC rates, omnichannel rationale, role of AI in digital collections.

[^7^]: **[FICO – Debt Collection Predictive Analytics: Benefits, Types and Uses](https://www.fico.com/blogs/debt-collection-predictive-analytics-benefits-types-and-uses)**  
Early cure behavior and the value of predictive segmentation.

[^8^]: **[Debtrak – Top Challenges in Debt Collection Today and How Technology Can Solve Them](https://debtrak.com/blog/top-challenges-debt-collection-technology)**  
15–25% better recoveries, 30–40% complaint reduction, manual-work reduction.

[^9^]: **[C&R Software – How does AI improve debt collection efficiency?](https://blog.crsoftware.com/how-does-ai-improve-debt-collection-efficiency)**  
Operational automation and time-saving benchmarks.

[^10^]: **[ScienceDirect – Predicting retail customers' distress in the finance industry: An early warning system](https://www.sciencedirect.com/science/article/pii/S0969698924003977)**  
AUC benchmark for ML-based retail early-warning systems versus simpler regression models.

[^11^]: **[CostPerform – Uncover the Hidden Costs of AI: A Bank's Journey](https://www.costperform.com/uncover-the-hidden-costs-of-ai-a-banks-journey/)**  
Useful for recurring AI run-cost logic: cloud, experimentation, compliance, and monitoring costs.

---
