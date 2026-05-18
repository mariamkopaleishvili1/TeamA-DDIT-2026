# Project Charter Template

## Purpose

A project without a defined charter drifts. Scope grows. Teams solve different problems. Deliverables arrive late or answer the wrong question.

This charter defines the engagement for the semester. It is a living document: update it when the team's understanding of the problem evolves. The version you submit at the end of Weekend 1 is a starting point, not a final commitment.

The charter is separate from the Team Charter. The Team Charter covers how you work together. This document covers what you are working on.

---

## Team Information

- Team name: Team AAA+
- Industry context: Fintech
- Members: Mariam Kopaleishvili, Mariam Piranishvili, Ani Rusieshvili, Gega Mukhigulashvili
- Instructor: Zeshan Ahmad
- Semester: Spring 2026
- Version: 1
- Date last updated: 03/14/2026

---

## Part 1. Client Context

Describe the industry and the focal organisation or organisation type in three sentences. Be specific. A vague client context produces vague analysis.

- Industry: Fintech
- Geographic market: Georgia
- Focal organisation type (e.g., incumbent retail bank, regional hospital network, last-mile logistics operator): TBC Bank, Bank of Georgia
- Why this context has meaningful disruption underway now: The global rise of event‑based financial products (e.g., political markets, macro‑event futures, entertainment/sports forecasting) and their rapid adoption in the U.S. and EU demonstrate strong demand for “information markets.” At the same time, Georgia’s fintech environment is evolving: payment digitization is accelerating, crypto usage is widespread relative to population, and regulators are actively modernizing financial and digital‑asset frameworks. This combination of consumer readiness, regulatory fluidity, and market white space creates an opportunity for a first‑mover to introduce predictive financial instruments in a compliant way.
- Public data availability: what sources exist for this industry?
  Georgian National Bank (NBG) regulatory guidelines, fintech licensing frameworks, and digital‑asset regulations
  Ministry of Finance and Parliamentary records on gambling, futures, derivatives, and financial markets
  Polymarket, Kalshi, PredictIt, Metaculus public data and investor reports
  Academic research on prediction markets
  Global industry analyses, crypto adoption reports, and consumer‑behavior studies in Georgia
  Georgian economic and political event datasets (GEOstat, NBG, IFI reports)

---

## Part 2. Strategic Question

Write the one question your final recommendation will answer. This question must be:

- Specific: it names the client type and the disruption force
- Answerable: it can be resolved with data and analysis available within the semester
- Consequential: a wrong answer has material strategic and financial implications
- Contested: reasonable analysts could disagree on the answer

### Strong format

How should [focal organisation] respond to [specific disruption force] in order to [strategic objective] while managing [main constraint or risk]?

### Draft strategic question

Write three versions and select one:

- Version A: How should a Georgian fintech prediction-market startup design and launch a Polymarket/Kalshi-type event-trading platform while navigating Georgia's financial, gambling, and digital-asset regulations?
- Version B: How should TBC Bank or Bank of Georgia enter the prediction‑market space—or partner with a startup—to capture emerging demand for event‑based financial products while controlling regulatory and reputational risk?
- Version C: How should a new prediction‑market operator position itself in Georgia to achieve rapid user adoption and regulatory approval while maintaining financial sustainability and avoiding classification as gambling?
- Selected version and reason for selection: Selected version: How should a Georgian fintech, potentially backed by a major Georgian bank such as TBC, launch a Polymarket/Kalshi-type prediction-market product in Georgia in order to achieve regulatory approval, attract early users, and reach sustainable scale while managing legal, reputational, and platform-risk constraints?
The bank-backed assumption matters because regulatory trust, payment rails, KYC infrastructure, and reputational credibility are likely to be decisive in a market where prediction contracts may otherwise be perceived as gambling.
This phrasing is specific (focuses on a Georgian fintech potentially backed by a major bank), answerable within the semester (regulatory review + market sizing + product design), consequential (mistakes could make the product illegal or unviable), and contested (reasonable analysts disagree on where prediction markets should sit legally and operationally).

### Why this question matters

- What happens if the client gets the answer wrong: The product could be classified as illegal gambling, resulting in immediate shutdown and fines. The venture could be denied licensing by the National Bank of Georgia, preventing launch entirely. The platform could attract the wrong type of users (speculators, arbitrage bots) and fail to build trust.
- What is at stake financially: Failure to meet compliance standards could block payment‑provider integrations, eliminating the platform’s ability to earn transaction fees.
- What is at stake competitively: Georgia currently has no major prediction‑market operator, so the first compliant mover could secure dominant network‑effects and user liquidity.

---

## Part 3. Analytical Scope

Define what is explicitly in scope. Be precise. Broad scope statements lead to unfocused analysis and missed assessment criteria.

### In scope

List five to eight specific areas of analysis the project will cover.

1. Regulatory classification pathway analysis, examining NBG sandbox eligibility, the regulatory distinction between VASP, payment service, and gambling classification, and the timeline and compliance requirements required for legal operation in Georgia.
2. Market sizing and customer segmentation, quantifying TAM, SAM, and SOM for prediction markets in Georgia, specifically measuring the 66% short-term preference population and the activation potential among the 92% of Georgians not currently participating in retail brokerage.
3. Competitive positioning and dynamics, applying Porter's Five Forces to understand banking duopoly supplier power, buyer fragmentation, and threat of substitutes, while mapping the value chain and positioning competitors across the Regulatory Integration versus Digital Architecture matrix.
4. Customer jobs-to-be-done and behavior analysis, identifying functional needs such as instant payments and micro-contracts, emotional needs including financial competence and social belonging, and the specific triggers that cause users to switch from crypto platforms, betting sites, or traditional banks.
5. Product-market fit and UX strategy, evaluating contract design choices including the critical distinction between one-dollar micro-contracts and TBC Capital's existing one-dollar fractional investing, the localization of events around Georgian elections, sports, and macroeconomic indicators, and the infrastructure for oracle-based resolution mechanisms.
6. Economic model and unit economics, defining revenue models comparing spread-based versus commission structures, assessing market maker requirements and liquidity subsidies needed for network effects, and modeling customer acquisition costs across regulated versus unregulated channels.
7. Strategic options development, rigorously evaluating three distinct paths: the NBG Sandbox First-Mover approach, the Crypto-Native Trojan Horse strategy, and the Incumbent Partnership Play, establishing clear decision criteria and tradeoffs for each.
8. Risk governance and implementation, designing responsible use features including self-exclusion tools and deposit limits, building AML and KYC compliance frameworks, and constructing the phased 18-month roadmap with appropriate governance structures.
9. Evaluation of whether a TBC-backed model improves regulatory credibility, payment access, customer trust, and early distribution compared with a standalone startup.

### Scope boundaries

- Geographic scope: Georgia and neighboring countries
- Time horizon for analysis: An 18-month implementation roadmap for the Sprint 3 deliverable, which aligns with the NBG sandbox timeline of 12 to 24 months plus a 6-month post-approval launch window, alongside 3-year financial projections to validate sustainable unit economics and breakeven trajectory referencing Pave Bank's achievement of breakeven in 8 months.
- Which part of the value chain: Customer acquisition through digital onboarding, the trading platform layer including contract design and oracle resolution, and settlement infrastructure through PSP partnerships; deep primary market making infrastructure is excluded and will rely on automated market makers or third-party liquidity, and proprietary blockchain development is excluded in favor of existing rails.
- Which customer segments: Urban, digitally active Georgians aged 18 to 35 who exhibit the 66% short-term preference behavior and 54% financial literacy rates; rural unbanked populations dependent on Liberty Bank's 500-plus branch network are excluded, high-net-worth individuals served by Solo and Bank of Georgia premium segments are excluded, and corporate or institutional B2B markets are excluded as requiring a distinct business model.
- Which competitors or entrants: Direct competitors including TBC Capital through Space, Galt and Taggart through Solo and Bank of Georgia, the 24 NBG-registered VASPs including Binance, Bybit, Werty, GeCrypto, and 1tab, plus CityPay.io, Payze, AzRy, and Cryptomat; indirect competitors including traditional sports betting operators like Adjarabet, informal crypto P2P markets through Binance P2P, real estate speculation as an alternative investment, and consumption or cash hoarding behaviors; plus the global threat of Polymarket and Kalshi should they pursue international expansion; traditional corporate lending, SME banking, insurance products, remittance specialists like Wise and Western Union, and unregulated offshore gambling sites are excluded from competitive analysis.

---

## Part 4. Non-Goals

List at least three topics that look related to your strategic question but are explicitly out of scope. Non-goals prevent scope creep and focus team energy.

For each non-goal, state why it is out of scope, not just that it is.

| Non-Goal                                                  | Why Out of Scope                                                                                                                                                                                                                                                                    |
| --------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. **International expansion strategy**                   | Georgian regulatory and market dynamics are unique; adding other jurisdictions such as Armenia, Azerbaijan, or EU markets would dilute focus from the core NBG approval challenge and require separate regulatory analysis beyond the semester timeline.                            |
| 2. **Blockchain infrastructure development**              | The project assumes use of existing blockchain rails such as Ethereum or Polygon, or third-party oracle providers; building proprietary chain infrastructure is capital-intensive and not required for MVP launch.                                                                  |
| 3. **Sports betting operator acquisition or partnership** | Betting companies operate under a different legal framework requiring gambling licenses; mixing with financial instrument classification creates regulatory confusion, reputational risk, and conflicts with the strategic goal of distinguishing prediction markets from gambling. |
| 4. **Corporate or institutional B2B prediction markets**  | Enterprise risk management and supply chain forecasting represent a distinct business model with different sales cycles, contract structures, and liquidity requirements; the focus is retail consumer adoption for network effects.                                                |
| 5. **Full banking license acquisition**                   | Pave Bank's model proves this is possible but requires 250,000 GEL minimum capital and 12-18 month timeline; prediction market platforms can operate under lighter PSP or VASP frameworks without becoming full banks.                                                              |


---

## Part 5. Key Assumptions

State at least three assumptions that enable the analysis. An assumption is a condition you are treating as given for the purpose of the project. Unstated assumptions are the most common source of analytical failure.

### Required format

We assume [specific condition] for the purpose of this project because [basis or rationale]. This assumption is [low / medium / high] risk of being wrong. If it is wrong, the analysis [describe impact on the strategic question or recommendation].

**Assumption 1**

**Statement**: We assume NBG may be willing to review or test event-based prediction contracts as a virtual-asset service, innovative payment service, financial instrument, or new sandbox category rather than immediately treating them as gambling, provided the platform implements responsible-use features and avoids sports betting overlap. This assumption is based on NBG's authority to define new virtual asset services via normative acts, the existence of a sandbox framework for innovative products, and global precedent through Kalshi's regulated event-contract model.

**Risk of being wrong**: Medium-High

**Impact if wrong**: The analysis must discard the "NBG Sandbox First-Mover" strategic option entirely, force reliance on either offshore operation without GEL rails or gambling license acquisition with associated social stigma and advertising restrictions, and fundamentally invalidate the regulatory positioning moat that underpins the entire business case.

**Assumption 2**

**Statement**: We assume TBC Bank and/or Bank of Georgia will provide payment rail access to a regulated prediction market platform, or viable crypto-fiat bridge alternatives such as CityPay.io or Pave Bank integration exist for the purpose of this project because Georgian law requires PSPs to block transactions to unlicensed gambling sites implying licensed platforms can access rails, Pave Bank demonstrates digital-native licensed alternatives are possible, and CityPay.io has proven 600+ merchant partnerships for crypto-fiat bridges.

**Risk of being wrong**: Medium

**Impact if wrong**: The analysis must eliminate the "Incumbent Partnership" strategic option, force reliance solely on crypto-native rails (USDC) limiting addressable market to crypto-literate users (~5-10% of target demographic), and pivot entirely to the "Crypto-Native Trojan Horse" option with associated regulatory enforcement risks and inability to advertise broadly.

**Assumption 3**

**Statement**: We assume at least 100,000 Georgians (2.6% of population, ~10% of urban 18-35 demographic) will actively trade on a prediction market platform if offered localized events, $1 minimum contracts, and mobile-first UX for the purpose of this project because TBC Capital reached 100,000+ brokerage customers in 2025 with traditional equities demonstrating market depth, 66% short-term preference suggests latent demand unmet by existing products, and 8% retail GSE participation leaves 92% non-consumers available for activation.

**Risk of being wrong:** Medium

**Impact if wrong**: The analysis shows network effects never form, liquidity remains insufficient for market making causing spreads to widen and user churn, the platform fails to reach critical mass for sustainable unit economics, and all three strategic options become unviable regardless of regulatory or partnership success.
### Additional assumptions (add as needed)

---

## Part 6. Deliverable Map

Map the semester deliverables to the analytical scope. This confirms that the scope is sufficient to support the final exam deliverables.

| Deliverable | Assessment Component | Analytical Scope Elements Required |
|---|---|---|
| Disruption Diagnostic v1 | Foundation for midterm and final | Parts 1–2 of this charter |
| Issue Tree v1 | Foundation for midterm and final | Part 2 of this charter |
| Competitive Landscape v1 | Midterm: industry analysis | Part 3 of this charter |
| Midterm deck (25–30 slides) | Midterm exam (25 pts) | All scope elements, strategic options, ROI model |
| 18-month roadmap | Final exam (40 pts) | Full scope plus implementation logic |
| Final executive presentation | Final exam (40 pts) | All scope elements plus governance plan |

### Scope completeness check

Does the analytical scope defined in Part 3 provide sufficient material to answer the strategic question and build all six deliverables? If not, what is missing?

- Gap identified:
- How to address:

---

## Part 7. Data and Evidence Plan

Identify the primary sources you will use for each major area of analysis.

| Analysis Area | Primary Source | Access Method | Owner | Due Date |
|---|---|---|---|---|
| Industry market size and growth | | | | |
| Competitor capabilities and moves | | | | |
| Customer behaviour and expectations | | | | |
| Technology capability benchmarks | | | | |
| AI adoption data | | | | |
| Regulatory context | | | | |
| Financial benchmarks (cost, margin, CAC) | | | | |

---

## Part 8. Risks to the Project

Identify three risks that could prevent the team from producing high-quality deliverables. For each, state a mitigation.

| Risk                                                                                                     | Probability | Impact                                                                                 | Mitigation                                                                                                                                                                                                                                                                                                                                                 |
| -------------------------------------------------------------------------------------------------------- | ----------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. **Insufficient primary source evidence for hypothesis testing by March 29 deadline**                  | Medium      | Critical (weakens strategic options; forces reliance on assumptions for midterm)       | Prioritize highest-leverage sources first: NBG sandbox inquiry (Gega), TBC Capital pricing (Mariam P.), market sizing data (Mariam K.); use secondary sources (World Bank, academic papers) with clear attribution; flag evidence gaps explicitly in deliverables; schedule working session March 29 to triangulate findings and fill gaps with proxy data |
| 2. **Key hypothesis invalidated late in Sprint 1 (e.g., TBC Capital already offers equivalent product)** | Medium      | Critical (forces strategic pivot with limited time; undermines differentiation thesis) | Build early warning system: test H1 (cost advantage) and H2 (non-consumer activation) by March 22; maintain parallel option development (all three options assume different hypothesis outcomes); schedule Week 1 check-in March 22 to surface findings early; preserve Option C (Incumbent Partnership) as fallback if differentiation proves weak        |
| 3. **Cannot access primary source data (TBC Capital app features, NBG internal statistics)**             | Medium      | High (weakens hypothesis testing; reduces evidence quality for midterm)                | Build relationships with Tbilisi-based university contacts for app access; substitute with public investor presentations and annual reports; use global benchmarks (Robinhood, eToro UX) with clear assumption flags; conduct user interviews (n=10) to proxy for app behavior; assign Mariam Piranishvili as owner                                        |


---

## Submission

Save this file as: `TeamX_ProjectCharter_v1_YYYYMMDD`

Upload to your team folder in Microsoft Teams by Saturday 18:00.

Update and resubmit the version number whenever the strategic question, scope, or key assumptions change materially.
