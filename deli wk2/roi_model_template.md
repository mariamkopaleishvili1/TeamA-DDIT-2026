# ROI Model: AI-Driven Collections Transformation for TBC Bank

## Executive Summary

This document presents the financial case for implementing predictive early warning and automated collections orchestration at TBC Bank using AI/ML capabilities. The model projects a **19-month payback period** in the base case, with cumulative cash flow of **47.4M GEL ($17.6M USD)** over 5 years and an **IRR of 85%**.

The model is built on TBC Bank's actual 2024 financial metrics: **25.0B GEL gross loan book**, **14.65B GEL retail + MSME exposure**, **2.2% NPL ratio**, and **0.5% cost of risk** ([TBC Bank 2024 Management Report](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf)). Revenue projections reflect conservative ramp-up curves accounting for implementation timelines, adoption rates, and the reality that TBC already operates at relatively strong asset quality levels compared to industry benchmarks.

---

## Part 1. Revenue Impact (Annual)

**Note:** Revenue figures below represent **gross benefits before deducting recurring run costs**. Net cash flows in Part 4 account for ongoing operational expenses (cloud, MLOps, monitoring).

| Revenue driver | Year 1 | Year 2 | Year 3 | Year 4 | Year 5 | Assumption ID |
|---|---:|---:|---:|---:|---:|---|
| NPL reduction through early warning (charge-off avoidance) | 2,800,000 GEL ($1.0M) | 5,000,000 GEL ($1.9M) | 6,500,000 GEL ($2.4M) | 7,600,000 GEL ($2.8M) | 9,000,000 GEL ($3.3M) | [A1] |
| Cure rate improvement (accounts brought current) | 1,200,000 GEL ($440K) | 2,400,000 GEL ($890K) | 3,400,000 GEL ($1.3M) | 4,100,000 GEL ($1.5M) | 4,800,000 GEL ($1.8M) | [A2] |
| Customer retention value (prevented churn) | 600,000 GEL ($220K) | 1,100,000 GEL ($410K) | 1,600,000 GEL ($590K) | 2,000,000 GEL ($740K) | 2,400,000 GEL ($890K) | [A3] |
| **Total revenue impact** | **4,600,000 GEL ($1.7M)** | **8,500,000 GEL ($3.1M)** | **11,500,000 GEL ($4.3M)** | **13,700,000 GEL ($5.1M)** | **16,200,000 GEL ($6.0M)** | |

*Exchange rate: 1 USD = 2.70 GEL*

---

## Part 2. Cost Impact (Annual Savings)

| Cost driver | Year 1 | Year 2 | Year 3 | Year 4 | Year 5 | Assumption ID |
|---|---:|---:|---:|---:|---:|---|
| Collections staff efficiency (workflow automation) | 600,000 GEL ($220K) | 1,000,000 GEL ($370K) | 1,300,000 GEL ($480K) | 1,600,000 GEL ($590K) | 1,800,000 GEL ($670K) | [A4] |
| Reduced call center operations (digital migration) | 300,000 GEL ($110K) | 500,000 GEL ($190K) | 700,000 GEL ($260K) | 800,000 GEL ($300K) | 900,000 GEL ($330K) | [A5] |
| Compliance and legal cost reduction | 200,000 GEL ($74K) | 300,000 GEL ($110K) | 400,000 GEL ($150K) | 450,000 GEL ($170K) | 500,000 GEL ($190K) | [A6] |
| **Total cost savings** | **1,100,000 GEL ($410K)** | **1,800,000 GEL ($670K)** | **2,400,000 GEL ($890K)** | **2,850,000 GEL ($1.1M)** | **3,200,000 GEL ($1.2M)** | |

---

## Part 3. Investment Required (Year 0)

| Cost category | Amount (GEL) | Amount (USD) | Proportion of total | Notes |
|---|---:|---:|---:|---|
| Technology platform and licensing | 1,300,000 | $480,000 | 15% | ML/AI engines, cloud infrastructure, vendor software |
| Implementation and integration | 2,300,000 | $850,000 | 27% | Core banking integration, CRM, dialer, data warehouse |
| People and change management | 1,400,000 | $520,000 | 16% | Training, analytics product owners, SMEs |
| Programme management and governance | 700,000 | $260,000 | 8% | Risk, compliance, model governance, PMO |
| Data infrastructure | 1,400,000 | $520,000 | 16% | Feature store, streaming, monitoring, audit logs |
| Contingency (20%) | 1,400,000 | $520,000 | 16% | Buffer for delivery delays, model remediation |
| **Total investment** | **8,500,000 GEL** | **$3,150,000** | **100%** | |

---

## Part 4. Summary Model

**Important modeling note:** Net cash flow below is **after recurring annual run cost** (cloud, MLOps, monitoring, support). Base case assumes **1.8M GEL in Year 1**, rising to **2.2M GEL by Year 5** based on industry benchmarks for AI system maintenance ([CostPerform](https://www.costperform.com/uncover-the-hidden-costs-of-ai-a-banks-journey/)).

| Metric | Downside | Base Case | Upside |
|---|---:|---:|---:|
| Total investment (Year 0) | 8,500,000 GEL ($3.15M) | 8,500,000 GEL ($3.15M) | 8,500,000 GEL ($3.15M) |
| Year 1 net cash flow | 2,100,000 GEL ($780K) | 3,900,000 GEL ($1.4M) | 6,700,000 GEL ($2.5M) |
| Year 2 net cash flow | 4,600,000 GEL ($1.7M) | 8,400,000 GEL ($3.1M) | 12,800,000 GEL ($4.7M) |
| Year 3 net cash flow | 6,900,000 GEL ($2.6M) | 11,900,000 GEL ($4.4M) | 16,800,000 GEL ($6.2M) |
| Year 4 net cash flow | 8,600,000 GEL ($3.2M) | 14,450,000 GEL ($5.4M) | 19,500,000 GEL ($7.2M) |
| Year 5 net cash flow | 9,400,000 GEL ($3.5M) | 17,200,000 GEL ($6.4M) | 20,800,000 GEL ($7.7M) |
| Cumulative cash flow (Year 5) | 23,100,000 GEL ($8.6M) | 47,350,000 GEL ($17.6M) | 68,100,000 GEL ($25.2M) |
| **Payback period** | **27 months** | **19 months** | **14 months** |
| **NPV (10% discount rate)** | **14,100,000 GEL ($5.2M)** | **31,500,000 GEL ($11.7M)** | **47,000,000 GEL ($17.4M)** |
| **IRR** | **50%** | **85%** | **120%** |

---

## Part 5. Assumptions Table

| ID | Assumption | Basis | Year 1 Impact if Assumption Changes by 20% |
|---|---|---|---|
| A1 | **6% reduction in annual write-offs / charge-offs at steady state** | TBC reported **GEL 154.2M write-offs** in 2024 ([TBC Bank 2024 Management Report](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf)). McKinsey cites **5–15%** charge-off reduction from next-gen value-at-risk assessment and an **8% reduction** at a North American lender ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-analytics-enabled-collections-model)). Conservative lower-half assumption. | Year 1 benefit decreases by **~560K GEL** if only **4.8%** achieved |
| A2 | **12% cure-rate improvement** on early-stage delinquency | McKinsey finds digitally contacted customers make **12% more payments**; another bank achieved **15% more customers cured through self-service** ([McKinsey](https://www.mckinsey.com/~/media/McKinsey/Business%20Functions/Risk/Our%20Insights/Going%20digital%20in%20collections%20to%20improve%20resilience%20against%20credit%20losses/Going-digital-in-collections-to-improve-resilience-against-credit-losses.ashx)) ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)). FICO notes early-stage accounts behave differently and many cure quickly, which is exactly where ML segmentation helps ([FICO](https://www.fico.com/blogs/debt-collection-predictive-analytics-benefits-types-and-uses)). | Year 1 benefit decreases by **~240K GEL** if only **9.6%** achieved |
| A3 | **Customer retention value of 300 GEL per saved relationship** | TBC generated **GEL 1.245B net profit** and had **1.701M monthly active customers**, implying profit per active customer well above this proxy; 300 GEL is conservative for preserved relationship value ([TBC Bank 2024 Management Report](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf)). McKinsey also cites **25%+ engagement uplift** in digital-first collections environments ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)). | Year 1 value decreases by **~120K GEL** if retention value is only **240 GEL** |
| A4 | **25% productivity gain** across collections operations and assisted servicing | TBC's staff cost was **GEL 439.8M** across **9,149 employees**, or roughly **48K GEL per employee** ([TBC Bank 2024 Management Report](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf)). McKinsey cites **5–10% collector-capacity uplift** from better self-cure identification, while Debtrak and CR cite much larger manual-work reductions; 25% is a midpoint ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-analytics-enabled-collections-model)) ([Debtrak](https://debtrak.com/blog/top-challenges-debt-collection-technology)) ([C&R Software](https://blog.crsoftware.com/how-does-ai-improve-debt-collection-efficiency)). | Year 1 savings decrease by **~120K GEL** if productivity gain is only **20%** |
| A5 | **25% assisted-to-digital migration** of routine collections interactions | McKinsey cites one bank moving **40% of inbound clients** to self-service and another achieving **15% lower cost to collect** ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)). FICO notes traditional right-party-contact rates via phone rarely exceed **8–10%**, supporting a digital-first shift ([FICO](https://www.fico.com/blogs/using-ai-improve-debt-collection-strategies)). | Year 1 savings decrease by **~60K GEL** if migration reaches only **20%** |
| A6 | **15% reduction in compliance / legal cost** through audit trails, frequency controls, and more consistent treatment | Debtrak says modern platforms can reduce complaints by **30–40%**, and McKinsey highlights lower conduct risk; base case assumes only half that order of magnitude for direct financial benefit ([Debtrak](https://debtrak.com/blog/top-challenges-debt-collection-technology)) ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)). | Year 1 savings decrease by **~40K GEL** if only **12%** reduction is achieved |

---

## Detailed Revenue Calculation Methodology

### 1. NPL Reduction / Charge-Off Avoidance (Driver A1)

**Base Calculation:**
- TBC 2024 write-offs: **154.2M GEL** ([TBC Bank 2024 Management Report](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf))
- In-scope portfolio (Retail + MSME): **14.65B GEL** out of **25.0B GEL** total gross loans ([TBC Bank 2024 Management Report](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf))
- Assumption: **6% reduction** in annual write-offs at steady state
- **Steady-state annual benefit**: 154.2M GEL × 6% = **9.25M GEL**

**Why 6%?**
McKinsey research indicates **5–15% charge-off reduction** from analytics-enabled collections models, with one North American lender achieving **8% reduction** in charge-off losses ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-analytics-enabled-collections-model)). TBC's asset quality is already strong (2.2% NPL, 0.5% cost of risk), so the model assumes the lower half of the benchmark range. This is conservative compared to industry "up to 20%" marketing claims, which typically apply to banks starting from weaker baseline performance.

**Ramp-Up Curve:**
- Year 1: 25% of steady state = **2.8M GEL** (implementation phase, limited rollout)
- Year 2: 45% of steady state = **5.0M GEL** (broader deployment)
- Year 3: 65% of steady state = **6.5M GEL** (near-full coverage)
- Year 4: 80% of steady state = **7.6M GEL** (optimization phase)
- Year 5: 90% of steady state = **9.0M GEL** (mature operations)

The ramp reflects that benefits do not materialize immediately upon implementation. Months 1-6 require model training, integration, and pilot testing. Months 7-12 see initial rollout to 30-40% of portfolios. Full coverage requires 18-24 months.

### 2. Cure Rate Improvement (Driver A2)

**Base Calculation:**
- Estimated early-stage delinquency volume (30-89 DPD): **~280M GEL** (based on 14.65B GEL retail/MSME book with industry-standard roll rates)
- Average balance per early-stage delinquent account: **~3,500 GEL**
- Cure rate improvement: **12%** (percentage point increase in accounts brought current)
- **Steady-state annual benefit**: 280M GEL × 12% × implied recovery margin = **~4.8M GEL**

**Why 12%?**
McKinsey research demonstrates that digitally contacted, digital-first customers make **12% more payments** than those contacted through traditional channels ([McKinsey](https://www.mckinsey.com/~/media/McKinsey/Business%20Functions/Risk/Our%20Insights/Going%20digital%20in%20collections%20to%20improve%20resilience%20against%20credit%20losses/Going-digital-in-collections-to-improve-resilience-against-credit-losses.ashx)). A European bank achieved **15% more customers cured through self-service** when using AI-driven segmentation ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)). FICO notes that early-stage delinquencies (30-59 DPD) exhibit high natural cure rates, and ML segmentation helps identify which accounts will self-cure versus which require intervention, allowing targeted treatment ([FICO](https://www.fico.com/blogs/debt-collection-predictive-analytics-benefits-types-and-uses)).

The 12% assumes that AI-driven early warning (identifying at-risk accounts 45-60 days before traditional markers) combined with automated digital outreach increases the probability of curing accounts by 12 percentage points above baseline.

**Ramp-Up Curve:**
- Year 1: 25% effectiveness = **1.2M GEL**
- Year 2: 50% effectiveness = **2.4M GEL**
- Year 3: 71% effectiveness = **3.4M GEL**
- Year 4: 85% effectiveness = **4.1M GEL**
- Year 5: 100% effectiveness = **4.8M GEL**

### 3. Customer Retention Value (Driver A3)

**Base Calculation:**
- Estimated annual customer loss from collections-related churn: **~8,000 customers**
- Customer lifetime value (CLV): **300 GEL** (conservative proxy)
- Prevention rate: **25%** of at-risk relationships saved through better treatment
- **Steady-state annual benefit**: 8,000 × 25% × 300 GEL = **2.4M GEL**

**Why 300 GEL CLV?**
TBC generated **GEL 1.245B net profit** with **1.701M monthly active customers**, implying **731 GEL profit per active customer** ([TBC Bank 2024 Management Report](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf)). The 300 GEL assumption is conservative, reflecting that saved collections customers may be lower-value than average (higher credit risk) and that "saving" a relationship preserves only a portion of full lifetime value. McKinsey cites **25%+ engagement uplift** in digital-first collections environments, supporting the retention mechanism ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)).

**Ramp-Up Curve:**
- Year 1: 25% of target = **600K GEL**
- Year 2: 46% of target = **1.1M GEL**
- Year 3: 67% of target = **1.6M GEL**
- Year 4: 83% of target = **2.0M GEL**
- Year 5: 100% of target = **2.4M GEL**

---

## Cost Savings Calculation Methodology

### 1. Collections Staff Efficiency (Driver A4)

**Base Calculation:**
- Collections-related staff: **~150 FTEs** (estimated from TBC's 9,149 total employees)
- Average fully-loaded cost per employee: **48K GEL** (439.8M GEL staff cost / 9,149 employees) ([TBC Bank 2024 Management Report](https://assets.eu.ctfassets.net/psnuheg7hu1m/2CNySE47pbIu0GW6W0RsDk/07682ce95dd707fa80c9e7a7a85d4529/jsc-tbc-bank-management-report-and-financial-statements-2024.pdf))
- Baseline collections labor cost: **7.2M GEL**
- Productivity gain: **25%** (more accounts handled per FTE through automation/prioritization)
- **Steady-state annual savings**: 7.2M GEL × 25% = **1.8M GEL**

**Why 25%?**
McKinsey cites **5–10% collector-capacity uplift** from better self-cure identification and prioritization ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-analytics-enabled-collections-model)). Debtrak and C&R Software cite **30–40% manual work reduction** through automation ([Debtrak](https://debtrak.com/blog/top-challenges-debt-collection-technology)) ([C&R Software](https://blog.crsoftware.com/how-does-ai-improve-debt-collection-efficiency)). The 25% assumes a midpoint that accounts for Georgian operational context and the need to maintain human oversight for complex cases.

### 2. Call Center Operations Reduction (Driver A5)

**Base Calculation:**
- Baseline call center cost for collections: **~3.6M GEL** (estimated 50% of total collections labor)
- Digital migration: **25%** of calls deflected to self-service (app, SMS, IVR)
- **Steady-state annual savings**: 3.6M GEL × 25% = **900K GEL**

**Why 25%?**
FICO notes traditional right-party-contact rates via phone rarely exceed **8–10%**, while digital channels achieve **25–30%** engagement ([FICO](https://www.fico.com/blogs/using-ai-improve-debt-collection-strategies)). McKinsey cites one bank moving **40% of inbound clients** to self-service ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)). The 25% assumes an achievable target given TBC's existing Space digital platform infrastructure.

### 3. Compliance Cost Reduction (Driver A6)

**Base Calculation:**
- Baseline compliance/legal costs for collections: **~3.3M GEL** (estimated)
- Efficiency gain: **15%** through automated audit trails, consistent treatment, reduced complaints
- **Steady-state annual savings**: 3.3M GEL × 15% = **500K GEL**

**Why 15%?**
Debtrak indicates modern platforms reduce complaints by **30–40%** ([Debtrak](https://debtrak.com/blog/top-challenges-debt-collection-technology)). McKinsey highlights lower conduct risk from consistent, data-driven treatment ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)). The 15% assumes only half the potential benefit materializes as direct cost savings (remainder is risk avoidance).

---

## Scenario Differentiation Logic

The Downside/Base/Upside scenarios reflect uncertainty across **five dimensions**, not just model accuracy:

| Dimension | Downside | Base Case | Upside | Rationale |
|---|---|---|---|---|
| **Model uplift (Gini improvement)** | 10% | 18% | 28% | Base case 18% is below academic benchmark of ~22% ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0969698924003977)) |
| **Write-off reduction** | 3% | 6% | 9% | Downside assumes minimal impact; upside approaches McKinsey's 8% benchmark ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-analytics-enabled-collections-model)) |
| **Cure rate uplift** | 8% | 12% | 18% | Downside reflects poor adoption; upside matches best-practice 15% ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/holistic-customer-assistance-through-digital-first-collections)) |
| **Digital migration** | 15% | 25% | 35% | Reflects varying success in customer behavior change |
| **Benefit realization ramp** | 25/45/65/80/90% | 35/60/80/90/100% | 45/75/90/100/100% | Downside = implementation delays; Upside = faster rollout |

The **base case 19-month payback** reflects:
- Conservative benefit assumptions relative to industry benchmarks
- Realistic ramp-up acknowledging organizational adoption curves
- Explicit deduction of recurring run costs (often ignored in vendor ROI calculators) ([CostPerform](https://www.costperform.com/uncover-the-hidden-costs-of-ai-a-banks-journey/))


## The Three Scenarios: What Actually Happens in Each Case

### Downside Case: "The Implementation Struggle" (27-Month Payback, 50% IRR)

**What goes wrong:** The model gets built but the organization does not change. Data scientists deliver accurate predictions, but frontline collectors ignore the new system and continue calling the same accounts they always have. The IT integration takes 6 months longer than planned, pushing go-live into Year 2. Middle managers resist the automation, fearing job losses, and quietly throttle the rollout to protect their teams. The digital self-service portal launches but only 15% of customers use it—most still call the hotline because they do not trust the app or were never properly notified.

**The numbers:** Write-off reduction hits only 3% instead of 6% because early warnings are not acted upon. Cure rates improve just 8% because agents still use old scripts. Digital migration stalls at 15%. The project delivers 23M GEL over 5 years—still positive, but barely compelling against other uses of capital.

**Why this happens:** This is the most common outcome in bank AI projects globally. The technology works; the people do not. McKinsey's research shows 70% of digital transformations fail due to people and process issues, not technology limitations ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-analytics-enabled-collections-model)). TBC would experience this if it under-invests in change management (the model allocates 1.4M GEL—16% of budget—but this could prove insufficient if senior leadership does not actively sponsor the behavioral shift).

**Survival:** Yes, TBC survives this scenario. The investment still pays back, but the opportunity cost is significant. TBC continues losing share to nimbler competitors while the 8.5M GEL investment generates mediocre returns. The board becomes skeptical of future AI initiatives.

---

### Base Case: "The Disciplined Execution" (19-Month Payback, 85% IRR)

**What goes right:** TBC follows the plan with professional discipline. The 8.5M GEL investment is deployed as budgeted. The change management program successfully retrains 150 collections staff to trust and use the AI recommendations—productivity gains hit 25% not because people work harder, but because they work on the right accounts. The Space digital platform integration enables 25% of customers to self-serve through the app, reducing call volume. The early warning system identifies at-risk borrowers 45 days earlier, and relationship managers actually intervene—reducing write-offs by 6%.

**The numbers:** Year 1 delivers 3.9M GEL net cash flow despite implementation delays. By Year 3, the system operates at 80% effectiveness. Cumulative 47M GEL over 5 years. The 19-month payback is respectable for a bank technology investment—faster than core system replacements, slower than simple automation.

**Why this is realistic:** This assumes TBC performs at industry median levels. The 18% Gini uplift for the prediction model is below the 22% academic benchmark, acknowledging that real-world data is messier than research datasets ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0969698924003977)). The 6% write-off reduction sits at the bottom of McKinsey's 5-15% range because TBC's 2.2% NPL ratio leaves less room for improvement than a bank starting at 8% NPL ([McKinsey](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-analytics-enabled-collections-model)).

**The critical success factor:** Sustained executive attention for 18 months. Not just the CEO announcing the project, but monthly steering committee reviews where business leaders confront adoption metrics and remove blockers. Without this, the base case slips toward downside.

---

### Upside Case: "The Industry Leader" (14-Month Payback, 120% IRR)

**What goes exceptionally well:** TBC's Space platform proves more powerful than expected—the digital self-service portal achieves 35% migration because the UX team nail the customer journey. The data science team accesses external data (telco payments, utility records) that improves model accuracy to 28% Gini uplift, above academic benchmarks. A competitor bank suffers a public collections scandal, causing regulators to favor TBC's compliant, documented approach. TBC's Galt & Taggart brokerage arm leverages the same prediction infrastructure to offer differentiated products to corporate clients.

**The numbers:** Year 1 net cash flow hits 6.7M GEL as benefits materialize faster. Write-off reduction reaches 9%, approaching the top of McKinsey's range. Cumulative 68M GEL over 5 years. The 14-month payback and 120% IRR make this one of TBC's best-performing strategic initiatives.

**Why this is possible but not probable:** This requires multiple independent factors to align—technical excellence, customer behavior change, competitive dynamics, and regulatory luck. Each factor has maybe 60% probability individually; combined probability is roughly 20%. TBC should not budget for this scenario, but leadership should recognize the upside optionality if execution exceeds expectations.

**Strategic implication:** If upside materializes, TBC gains a sustainable competitive advantage. The prediction infrastructure becomes a platform for adjacent products—credit line management, fraud detection, even the prediction market platform discussed in strategic optionality analysis. The 8.5M GEL investment creates capabilities that competitors would need 24-36 months to replicate.

---

## Scenario Comparison Summary

| Dimension | Downside: "Implementation Struggle" | Base Case: "Disciplined Execution" | Upside: "Industry Leader" |
|---|---|---|---|
| **Payback** | 27 months | 19 months | 14 months |
| **5-Year Return** | 23M GEL | 47M GEL | 68M GEL |
| **IRR** | 50% | 85% | 120% |
| **Primary Risk** | People ignore the system | Adoption plateaus at 80% | None—execution exceeds plan |
| **Key Driver** | Change management fails | Professional execution | External data + competitive shock |
| **Probability** | 30% | 50% | 20% |

---

## Why the Base Case Is the Right Anchor

The 19-month payback and 85% IRR represent a "good but not heroic" outcome. This is appropriate because:

1. **TBC's starting position is strong.** A bank with 5% NPL and manual processes could target 20% write-off reduction. TBC's 2.2% NPL and existing Space platform means the ceiling is lower—6% reduction is realistic, 15% is not.

2. **Georgian market constraints.** While TBC has 38.8% market share, the 70% urban digital penetration is not 95% like Nordic markets. Some customers will never adopt self-service, limiting digital migration to 25-35% range, not 60%+.

3. **Recurring costs are real.** The model explicitly deducts 1.8-2.2M GEL annual run cost for cloud, monitoring, and compliance. Many vendor ROI calculators ignore this, showing inflated returns. TBC's finance team would catch this omission during due diligence.

4. **Ramp-up curves matter.** Benefits do not appear on Day 1. Month 1-6 is implementation. Month 7-12 is pilot with 30% coverage. Full deployment requires 18-24 months. The base case reflects this reality; the upside case assumes acceleration that rarely occurs.

---

## The Single Most Important Decision

TBC's board should approve the **base case budget of 8.5M GEL** with explicit contingency triggers:

- If change management metrics (training completion, system login rates, recommendation adherence) fall below 70% by Month 9, deploy additional 500K GEL for intensive coaching or risk slipping to downside scenario.

- If model accuracy (Gini uplift) exceeds 25% by Month 6, accelerate external data acquisition to capture upside scenario.

- If regulatory environment shifts (NBG tightens collections rules), redirect 300K GEL from efficiency savings to compliance automation to maintain competitive position.

---

## Business Case Mechanism

**Step 1: Prediction** identifies at-risk retail and MSME borrowers before they migrate deeper into delinquency. ML models analyzing transaction patterns, behavioral data, and alternative signals detect financial stress **45-60 days before** traditional 30-day delinquency markers. Academic evidence shows ML-based early-warning systems achieve significantly higher AUC (Area Under Curve) than traditional logistic regression models ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0969698924003977)).

**Step 2: Automated workflows** use these predictions to select optimal treatment channels and timing. Instead of uniform phone campaigns (with 8-10% right-party-contact rates), the system routes low-risk accounts to self-service apps, medium-risk to targeted SMS/email, and high-risk to specialized human agents. McKinsey demonstrates this digital-first approach yields **12% more payments** than traditional methods ([McKinsey](https://www.mckinsey.com/~/media/McKinsey/Business%20Functions/Risk/Our%20Insights/Going%20digital%20in%20collections%20to%20improve%20resilience%20against%20credit%20losses/Going-digital-in-collections-to-improve-resilience-against-credit-losses.ashx)).

**Step 3: Economic value** materializes through three channels:
- **Loss avoidance**: Earlier intervention prevents roll-rate migration (30 DPD → 90 DPD), reducing the **154.2M GEL** annual write-off base by 6%
- **Cure acceleration**: Faster resolution of early-stage delinquencies reduces provision requirements and preserves customer relationships
- **Operational efficiency**: Automation reduces manual effort and shifts volume to lower-cost digital channels

---

## Notation and Terminology Guide

### Currency and Financial Terms

| Term | Definition |
|---|---|
| **GEL** | Georgian Lari (national currency) |
| **M / K** | Million / Thousand |
| **NPV** | Net Present Value (discounted cash flow minus investment) |
| **IRR** | Internal Rate of Return (discount rate yielding NPV=0) |
| **Payback Period** | Months to recover initial investment |

### Banking Terms

| Term | Definition |
|---|---|
| **NPL** | Non-Performing Loan (90+ days past due) |
| **DPD** | Days Past Due |
| **Cost of Risk** | Credit impairment / average gross loans |
| **Write-off** | Loan removed from balance sheet as uncollectible |
| **Cure** | Delinquent account returning to current status |

### AI/ML Terms

| Term | Definition |
|---|---|
| **Gini Coefficient** | Model discrimination metric (higher = better risk ranking) |
| **AUC** | Area Under ROC Curve (model accuracy metric) |
| **Early Warning** | Predictive system flagging risk before delinquency |
| **Propensity-to-Pay** | ML score predicting payment likelihood |

---
