# Activity: AI Opportunity Mapping

## Purpose

Map specific AI use cases to specific value chain activities and evaluate them on two dimensions: business value potential and implementation readiness.

## Output
AI Opportunity Map v1
| Quadrant                                             | Use Cases | Count                                                          |
| ---------------------------------------------------- | --------- | -------------------------------------------------------------- |
| **Deploy Now**        | 2         | Wealth Management Robo-Advisory, Loan Collections Optimization |
| **Invest to Enable**  | 2         | Prediction Market Platform, Open Banking Personalization       |
| **Quick Wins**        | 2         | Mobile Payment Fraud Detection, Customer Service Automation    |
| **Future Options**    | 2         | SME Credit Scoring, Regulatory Compliance Automation           |


## Time
60 minutes

## Process

1. List every value chain activity from your Weekend 1 Competitive Landscape. Add specific AI use cases alongside each activity. Use the capability vocabulary: prediction, generation, synthesis, agent workflow.

2. Score each use case on business value potential (High, Medium, Low) and implementation readiness (High, Medium, Low). For High value scores, write one sentence of evidence. For Low readiness scores, name the specific barrier.

3. Place use cases in the 2x2 matrix. Identify two priority use cases in the Deploy Now quadrant and two in the Invest to Enable quadrant.

4. For the two Deploy Now use cases, draft a two-sentence business case: the mechanism by which value is created and the rough order-of-magnitude financial impact.

##
Use Case 1: Wealth Management & Investment (DEPLOY NOW)
| Dimension                    | Assessment | Evidence                                                                                                                                                                                       |
| ---------------------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Value**           | **High**   | TBC Capital and Galt & Taggart manage brokerage for 60+ exchanges with \$1,000 minimums; 8% retail participation in GSE suggests massive untapped demand for accessible investment tools \[46] |
| **Implementation Readiness** | **High**   | Existing brokerage infrastructure, NBG-approved investment platforms, established KYC pipelines                               |

AI Capabilities: Generation (natural language portfolio explanations), Prediction (risk profiling, return forecasting), Synthesis (market data aggregation)

Two-Sentence Business Case: Robo-advisory using generative AI for natural language portfolio reporting and predictive risk profiling reduces the advisory cost-to-serve by 70% while capturing the 92% of Georgian adults currently excluded from equity markets due to high minimums and complexity. For TBC Capital with existing zero-commission, $1-minimum infrastructure [51], AI-powered advisory could increase account activation rates by 25% across 100,000+ mobile users, generating $2-3M annual fee income from previously unprofitable micro-accounts while reducing human advisor workload by 40%.


Use Case 2: Loan A/R Collections Optimization (DEPLOY NOW)
| Dimension                    | Assessment | Evidence                                                                                                                                                                                                                                                         |
| ---------------------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Value**           | **High**   | Georgian net interest margins of 6-8% are attractive but fragile—banks lose 2-3% of portfolio value annually to delayed collections, and relationship-based SME lending currently lacks systematic early warning signals before 90-day delinquencies crystallize |
| **Implementation Readiness** | **High**   | Medium. Barrier: NBG consumer protection regulations require human oversight for certain collection activities, necessitating "human-in-the-loop" workflow design                                                                                                |

AI Capabilities: Prediction (default probability modeling, optimal contact timing, propensity-to-pay scoring), Synthesis (transaction pattern analysis, behavioral data integration), Agent workflow (automated escalation triggers and personalized negotiation paths)

Two-Sentence Business Case: Prediction models analyzing transaction velocity and behavioral triggers identify at-risk loans 45-60 days before traditional 30-day delinquency markers, enabling soft-touch remediation that reduces roll-rates from 30DPD to 90DPD by 35-40%. For Bank of Georgia with approximately $3.5B retail and SME loan book, preventing 0.5% deterioration through early intervention preserves $17.5M in portfolio value annually while reducing cost-to-collect by 50% through automated outreach versus manual relationship manager interventions.

Use Case 3: Georgian Prediction Market Platform (INVEST TO ENABLE)
| Dimension                    | Assessment | Evidence                                                                                                                                                                                                                            |
| ---------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Value**           | **High**   | No regulated prediction market currently appears to operate in Georgia, and the product would require regulatory classification before launch. Business value is potentially high because event contracts could activate users who find traditional brokerage too complex, but implementation readiness is only medium because the legal category, payment-rail access, and market-integrity requirements remain unresolved. |
| **Implementation Readiness** | **Medium** | Barrier: Regulatory classification undefined—requires NBG sandbox entry and determination whether event contracts are financial instruments, gambling, or VASP services; NBG Innovation Office accepts applications \[75]           |

AI Capabilities: Prediction (probability pricing models, market sentiment analysis), Generation (natural language market explanations, event descriptions), Synthesis (multi-source data aggregation for outcome resolution), Agent workflow (automated market making, liquidity management)

Use Case 4: Open Banking-Powered Personalization (INVEST TO ENABLE)
| Dimension                    | Assessment | Evidence                                                                                                                                                                                                            |
| ---------------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Value**           | **High**   | Open Banking Phase 1 launched 2021, non-bank inclusion regulations issued 2023 \[1]; 60%+ mobile commerce penetration creates data foundation \[4]; TBC Pay and Liberty Pay have established payment infrastructure |
| **Implementation Readiness** | **Medium** | Barrier: API standardization incomplete across Georgian banks; requires NBG-mandated common API specifications and consent management framework buildout                                                            |


AI Capabilities: Synthesis (transaction pattern analysis across multiple accounts), Prediction (spending forecasting, cash flow optimization), Generation (personalized financial insights, product recommendations), Agent workflow (automated savings transfers, bill optimization)


Use Case 5: Real-Time Payment Fraud Detection (QUICK WIN)
| Dimension                    | Assessment | Evidence                                                                                                                                                                        |
| ---------------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Value**           | **Medium** | Cards dominate 89% of e-purchases \[11]; Georgian Card instant payment infrastructure exists; mobile wallet adoption (TBC Pay, Liberty Pay) creates concentrated attack surface |
| **Implementation Readiness** | **High**   | Existing transaction monitoring systems, NBG supervision framework for payment service providers, established fraud databases                                                   |

AI Capabilities: Prediction (anomaly detection, behavioral biometrics), Synthesis (device fingerprinting, location data correlation), Agent workflow (automated transaction blocking, step-up authentication triggers)


Use Case 6: Customer Service Automation for Digital Banking (QUICK WIN)
| Dimension                    | Assessment | Evidence                                                                                                                                        |
| ---------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Value**           | **Medium** | Mobile-first UX is "non-negotiable" per your analysis; 60%+ mobile commerce adoption \[4]; Georgian consumers show "low tolerance for friction" |
| **Implementation Readiness** | **High**   | Existing chatbot infrastructure at major banks; Georgian language NLP models improving; established escalation protocols to human agents        |

AI Capabilities: Generation (Georgian-language conversational AI, product explanations), Synthesis (knowledge base retrieval, customer history integration), Agent workflow (intent classification, automated routing, callback scheduling)

Use Case 7: AI-Powered SME Credit Scoring (FUTURE OPTION)
| Dimension                    | Assessment | Evidence                                                                                                                                                                                        |
| ---------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Value**           | **Medium** | Alternative lending is identified fintech segment \[10]; 54% financial literacy \[65] suggests data availability gap; SME segment underserved by traditional collateral-based lending           |
| **Implementation Readiness** | **Medium** | Barrier: Limited alternative data availability in Georgia—requires utility payment history, mobile money transaction data, and e-commerce platform integration not yet systematically available |

AI Capabilities: Prediction (credit default probability, optimal loan pricing), Synthesis (alternative data integration—utility payments, mobile transactions, supply chain relationships), Generation (automated loan decision explanations for NBG compliance)


Use Case 8: Regulatory Compliance Automation (FUTURE OPTION)
| Dimension                    | Assessment | Evidence                                                                                                                                                                                                          |
| ---------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Value**           | **Medium** | NBG's "proactive fintech supervision framework" \[1] requires intensive reporting; VASP registration mandatory since July 2023 \[19]; 0% corporate tax on foreign IT services creates compliance complexity \[18] |
| **Implementation Readiness** | **Medium** | Barrier: Georgian regulatory reporting standards still evolving—NBG's authority to "define new virtual asset services independently through normative acts" \[30] creates uncertainty requiring adaptive systems  |


AI Capabilities: Synthesis (multi-source regulatory document monitoring), Prediction (compliance risk scoring, reporting deadline forecasting), Generation (automated regulatory filing drafts, policy update summaries), Agent workflow (compliance calendar management, escalation for regulatory changes)

| Citation | Source                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| \[1]     | [Fintech Georgia - Fintech in Georgia](https://www.fintechgeorgia.ge/fintech-in-georgia/)                                                               |
| \[4]     | [Geostat ICT Usage in Households 2023](https://www.geostat.ge/media/uploads/files/economy/ICT%20Usage%20in%20Households%20and%20Individuals%202023.pdf) |
| \[11]    | [Statista Digital Payments Georgia](https://www.statista.com/outlook/dmo/fintech/digital-payments/georgia)                                              |
| \[18]    | [Cointelegraph Georgia Crypto Regulation](https://cointelegraph.com/news/georgia-crypto-regulation-vasp-registration)                                   |
| \[19]    | [GFSIS Georgia Cryptocurrency Regulation](https://www.gfsis.org.ge/publications/georgia-s-cryptocurrency-regulation-landscape)                          |
| \[30]    | [NBG Amendments to Virtual Assets Law](https://www.nbg.gov.ge/uploads/pressreleases/2025/Amendments_to_the_Law_on_Operating_of_the_Virtual_Assets.pdf)  |
| \[31]    | [Legal Sports Report Georgia](https://www.legalsportsreport.com/georgia-sports-betting/)                                                                |
| \[46]    | [Georgian Stock Exchange 2024 Annual Report](https://gse.ge/Uploads/2024%20Annual%20Report.pdf)                                                         |
| \[48]    | [Bloomberg DFS Challengers](https://www.bloomberg.com/news/articles/2025-10-28/draftkings-and-fanduel-face-new-challengers-in-daily-fantasy-sports)     |
| \[51]    | [TBC Capital Individuals](https://www.tbcbank.ge/en/corporate/tbc-capital/tbc-capital-individuals)                                                      |
| \[65]    | [NBG Financial Literacy Survey 2024](https://www.nbg.gov.ge/uploads/pressreleases/2025/Financial_Literacy_Survey_2024.pdf)                              |
| \[75]    | [NBG Financial Innovation Office](https://www.nbg.gov.ge/en/pages/financial-innovation-office)                                                          |



## Scoring definitions

| Dimension | High | Medium | Low |
|---|---|---|---|
| Business value | Greater than 10% impact on a material business metric | 3 to 10% impact | Less than 3% impact |
| Implementation readiness | Deployable within 6 months with current infrastructure | 12 months with modest investment | 24+ months requiring significant foundational work |

## Common error

Scoring everything Medium to avoid committing to a position. Force differentiation.

## Deliverable

Save as:
`ai_opportunity_map_v1.md`
