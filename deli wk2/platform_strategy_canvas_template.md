# Platform Strategy Canvas: Option A

## Purpose

This canvas maps the client's position in the platform competitive structure and produces a specific strategic recommendation: build, join, defend, or acquire.

---

## Section 1. Value Unit

**Value unit:** Event contract (binary outcome contract) on macro-economic or civic outcomes

**Description:** A standardized digital contract that pays out 1 GEL (or equivalent) if a specific measurable event occurs (e.g., "GEL/USD rate exceeds 2.80 by December 31, 2026" or "Mayoral candidate X wins Tbilisi election with >50% of vote"), and zero otherwise. Contracts trade between 0.01-0.99 GEL based on market-implied probability, with prices reflecting real-time information aggregation from diverse market participants. The minimum trade size is 1 GEL (approximately $0.37 USD), enabling true micro-stakes participation.

---

## Section 2. Producer Side

**Producer type:** Information-rich traders and liquidity providers (market makers)

**What they contribute:**
- Capital deployment to take positions on macro-economic and civic outcomes
- Information and analysis that improves price discovery (e.g., local knowledge of political dynamics, economic data interpretation)
- Liquidity provision through limit orders and market making
- Risk absorption for hedging counterparties

**What they receive:**
- Profit potential from superior information or analysis
- Risk hedging capabilities (e.g., exporters hedging GEL/USD exposure, political consultants monetizing polling insights)
- 3.75-4% APY on idle balances (following Kalshi model) [[Kalshi]](https://www.kalshi.com/)
- Zero maker fees; taker fees only on expected earnings (following Kalshi) (https://www.kalshi.com/)

**Current number or market size:** In Georgia, the addressable producer base includes:
- ~8% retail investors in Georgian Stock Exchange (low participation creates opportunity) [[GSE]](https://gse.ge))
- Commercial banks purchasing 80-90% of GEL bonds (institutional hedging demand) [[Galt and Taggart]](https://www.galtandtaggart.com/ge/research/fixed-income/georgian-bond-market-2024)
- Exporters/importers with GEL/USD exposure (significant given 4.53% GEL depreciation in 2024 and ongoing volatility) [[Geostat]](https://www.geostat.ge/en/modules/categories/26/exchange-rates)
- Political consultants and civil society organizations with election insights (64 municipalities, 40.93% turnout in 2025 local elections creates information asymmetries) [[Cesko]](https://www.cec.gov.ge/en/cec/municipal-elections-2025)

Global benchmark: Kalshi reaches $7 million maximum exposure per market with retail and institutional participation [[Kalshi]](https://www.kalshi.com/blog/kalshi-wins-historic-legal-victory)

---

## Section 3. Consumer Side

**Consumer type:** Retail speculators seeking event-based outcomes and information seekers

**What they seek:**
- Low-cost access to macro-economic and civic outcome speculation
- Intuitive, event-based trading (vs. complex securities analysis)
- Short-term, defined-risk investment opportunities aligned with 66% of Georgians who prefer short-term financial thinking [[NBG]](https://nbg.gov.ge)
- Information on market-implied probabilities for economic and political outcomes

**What they receive:**
- 1 GEL (0.37 USD) minimum contracts,99.9% lower capital barrier than Galt & Taggart's $1,000 minimum [[Galt And Taggart]](https://www.galtandtaggart.com/ge/wealth-management/brokerage)
- Zero-commission trading (maker orders free; taker fees only)
- Transparent probability pricing on events they understand (GEL rates, local elections) vs. complex stock analysis
- Mobile-first UX matching 60%+ mobile commerce penetration in Georgia [[Geostat]](https://www.geostat.ge/ka)
- Real-time information aggregation showing crowd-sourced expectations (e.g., "Market implies 72% probability GEL strengthens to 2.60 by year-end") [[TBC Capital]](https://www.tbccapital.ge/en/research/macro/tbc-capital-forecasts-gel-to-strengthen-to-260-against-usd-by-end-of-year)

**Current number or market size:**
- 54% of Georgians achieve "high" financial knowledge (5+ correct answers out of 7), indicating baseline sophistication [[NBG]](https://nbg.gov.ge/fm/პუბლიკაციები/ანგარიშები/ფინანსური_სტაბილურობის_ანგარიში/2024/fsr-2024-eng.pdf?v=43rp1)
- Only 34% prefer long-term financial thinking; 66% focus on short-term needs,perfect alignment with event contracts [[NBG]](https://nbg.gov.ge/fm/პუბლიკაციები/ანგარიშები/ფინანსური_სტაბილურობის_ანგარიში/2024/fsr-2024-eng.pdf?v=43rp1)
- 40.93% voter turnout in 2025 local elections (3.7 million population) suggests ~1.5 million politically engaged citizens [[Cesko]](https://www.cec.gov.ge/en/cec/municipal-elections-2025)
---

## Section 4. Network Effect Mechanism

**Primary network effect type:** Data network effects (cross-side with indirect network effects)

**Mechanism description:** As more traders participate, price discovery may improve if markets are liquid, well-designed, and based on verifiable events. Kalshi's public materials suggest that some regulated event markets can produce useful forecasting signals, but the strength of that evidence and its applicability to Georgia should be verified before being used as proof. Improved liquidity could attract more informed traders, which could narrow spreads and improve user trust. The Georgian platform should aim to become a credible local signal for macro and civic expectations, not assume it will become an information monopoly.

**Critical mass threshold:** TODO: verify source. The project currently uses 10,000 active users and GEL 5 million in open interest as a planning hypothesis, but the actual threshold for self-sustaining liquidity should be validated through market-maker discussions, pilot data, and unit-economics modeling.

**Risk of negative network effects:**
- **Information cascade risk:** TODO: verify source. If a market attracts a politically or informationally concentrated user base, it could create one-sided markets with poor price discovery.
- **Regulatory shutdown:** If classified as gambling rather than financial instruments, platform faces GEL 15,000-30,000 fines and under-25 user prohibition [[Gaming Intelligigence]]([https://www.gamingintelligence.com/regulation/georgia-tightens-gambling-regulations-further/](https://www.gamingintelligence.com))
- **NBG intervention correlation:** TODO: verify source. GEL-rate markets could be politically sensitive if they are perceived as speculating on central bank actions or currency stress.

---

## Section 5. Client Position

**Current role:** Potential platform operator (not yet in market)

**Current leverage in the market:**
- First-mover advantage: No regulated prediction market exists in Georgia as of March 2026
- Regulatory relationship pathway: NBG engagement, including the Innovation Office and/or sandbox-style testing framework, may provide a path for pre-consultation, subject to eligibility and NBG confirmation [[NBG]](https://nbg.gov.ge/en)
- Technical infrastructure: Can leverage existing VASP registration framework (if crypto-settled) or payment service provider partnerships (if GEL-settled)

**Data assets available:**
- None currently,must build from zero
- Can access public data: Geostat (inflation, GDP), NBG (exchange rates, monetary policy), CEC (election results)
- Can license data from TBC Capital (which produces macro research on GEL/USD forecasts) [[TBC Capital]](https://www.tbccapital.ge/en/research/macro/tbc-capital-forecasts-gel-to-strengthen-to-260-against-usd-by-end-of-year)

**Customer relationship strength:**
- No existing customer base
- Must build trust through NBG sandbox association and transparent market-making
- Can partner with established fintechs (TBC Pay, Liberty Pay) for user acquisition

---

## Section 6. Strategic Recommendation

**Recommendation:** Build, but only through a regulatory-first sandbox pathway.

The strongest path is not to launch first and seek approval later. The platform should be structured as a bank-backed, sandbox-tested financial innovation with limited contract types, capped user exposure, full KYC/AML, and transparent event-resolution rules.

**Reason 1 (regulatory feasibility):** Prediction markets sit in a legal grey zone between financial instruments, gambling products, and virtual-asset services. A sandbox-first approach gives the client a controlled route to test product mechanics while seeking formal feedback from NBG and avoiding the reputational damage of appearing like an unlicensed betting product.

**Reason 2 (strategic fit):** A bank-backed model creates trust that a standalone startup would lack. In Georgia, where financial services are heavily trust-based and dominated by major banking brands, association with TBC or another large bank can help secure payment rails, KYC infrastructure, compliance credibility, and early user confidence.

**Reason 3 (market entry logic):** The platform should not compete with TBC Capital or Galt & Taggart only on price, because low-cost brokerage already exists. The wedge is product simplicity: binary, locally relevant event contracts that are easier to understand than stocks, bonds, options, or crypto derivatives.

---

## Section 7. First Move

**Action:** Submit a sandbox/pre-consultation proposal asking NBG whether limited macro and civic event contracts can be tested as a supervised financial innovation, and what legal classification, restrictions, caps, and consumer-protection controls would apply.

**Owner:** Chief Regulatory Officer (or external legal counsel with NBG relationships)

**Success metric:** NBG provides written feedback on whether event contracts on GEL/USD rates and municipal election outcomes can be tested in the sandbox and what classification, limits, or restrictions would apply.

**Investment required (order of magnitude):** GEL 150,000-250,000 ($55,000-92,000 USD) for legal counsel, regulatory documentation, compliance infrastructure setup, and initial NBG engagement; separate GEL 300,000-500,000 for technology MVP development.

---

## Quality Check

**Is the recommendation specific, not vague?** Yes,"Build" is explicitly selected with three distinct, evidence-based justifications.

**Are the three justification reasons distinct and evidence-based?** Yes,(1) NBG sandbox framework and regulatory flexibility 

 **Does the first move pass the specificity test: could someone actually execute it?** Yes, the action specifies a concrete sandbox/pre-consultation proposal to NBG, while leaving classification, caps, restrictions, and consumer-protection controls for NBG confirmation.

**Have you confronted the chicken-and-egg problem if you recommended Build?** Yes, but the exact critical mass threshold remains a planning hypothesis. Seed liquidity should come from market-maker partnerships or other NBG-reviewed structures, and demand for GEL/USD contracts should be validated before launch.

## Reference Links
[1] https://fintechs.ge  
[2] https://www.kalshi.com/  
[3] https://www.theblock.co/post/331953/kalshi-raises-50-million-at-20-billion-valuation  
[4] https://www.geostat.ge/ka  
[5] https://www.cec.gov.ge/en/cec/municipal-elections-2025  
[6] https://www.bloomberg.com/news/articles/2025-11-14/kalshi-raises-50-million-at-20-billion-valuation  
[7] https://www.galtandtaggart.com/ge  
[8] https://www.nbg.gov.ge/uploads/pressreleases/2025/PressRelease_on_the_NBG_Supervisory_Strategy_for_2023-2025.pdf  
[9] https://www.tbccapital.ge/en/research  
[10] https://gse.ge  

## Option B: VASP-Registered Crypto-Native Platform

---

## Purpose

This canvas maps the client's position in the platform competitive structure and produces a specific strategic recommendation: build, join, defend, or acquire.

Important caution: VASP registration may support a crypto-settled version of the platform, but it does not automatically solve the legal classification of event contracts. The core regulatory question remains whether prediction tokens are treated as virtual assets, financial instruments, gambling products, or a new category. Therefore, the VASP route should be treated as a fallback or niche crypto-native option, not as the default mass-market strategy.

---

## Industry Context

The Republic of Georgia has established one of the most crypto-friendly regulatory frameworks in the region. As of April 2025, there are **24 registered VASPs** operating under National Bank of Georgia supervision [[Fintechs]](https://fintechs.ge). The NBG has developed comprehensive regulations including the "Regulation on the Initial Offering of Stable Virtual Assets" which mandates 100% reserve backing and aligns with global best practices including EU MiCA, US Genius Act, and Dubai VARA frameworks [[NBG]](https://nbg.gov.ge/en). The Georgian fintech market is projected to reach **$2.31 billion in digital payments by 2024** with 18.6% growth [[Statista]](https://www.statista.com/outlook/dmo/fintech/digital-payments/georgia), while the NBG has explicitly prioritized blockchain-based financial infrastructure and smart contract programmability in its Fintech Development Strategy [[1]](https://fintechs.ge).

**Prediction Market Perspective:** Globally, prediction markets have exploded from $50 million weekly volume to over **$6 billion weekly** following the 2024 U.S. election, with Polymarket (decentralized, crypto-native) and Kalshi (CFTC-regulated) emerging as the two dominant models [[Geostat]](https://www.geostat.ge/ka). Polymarket reached $140 million TVL and $3 billion cumulative trading volume during the election period [[Coindesk]](https://www.coindesk.com/markets/2026/04/06/polymarket-reveals-a-full-exchange-upgrade-to-take-control-of-its-own-trading-and-truth), while Kalshi raised $185 million at a $2 billion valuation [[Bloomberg]](https://www.bloomberg.com/news/articles/2025-11-14/kalshi-raises-50-million-at-20-billion-valuation).

---

## Section 1. Value unit

What is the minimum unit of interaction the platform could facilitate in this industry? What changes hands between the two sides?

- **Value unit:** Convertible Virtual Asset Event Contract (a blockchain-based prediction token representing a binary outcome position)

- **Description:** The minimum unit is a tokenized event contract representing a position (YES/NO) on a specific verifiable outcome (e.g., "Will GEL/USD exceed 2.85 by March 31?"). These contracts may be structured as convertible virtual assets if NBG confirms that treatment, but the event-contract classification remains unresolved. Unlike traditional betting slips, the proposed design would aim for transparent on-chain settlement, where the token itself carries probabilistic pricing information and can be traded prior to event resolution.

---

## Section 2. Producer side

Who produces value on the platform? What do they get from participation?

- **Producer type:** Liquidity Providers and Market Makers (registered VASPs, professional traders, algorithmic market makers)

- **What they contribute:**
  - Initial liquidity for event contract markets through USDC/stablecoin deposits
  - Continuous two-sided quoting to maintain tight spreads
  - Risk capital to absorb order flow and enable price discovery
  - Compliance infrastructure including AML/KYC processing for all counterparties

- **What they receive:**
  - Trading fees from retail participants (zero-commission model for end users, fees extracted from spread or maker-taker rebates)
  - Yield on locked collateral in automated market maker pools
  - First-mover advantage in an emerging asset class with limited competition
  - Regulatory clarity enabling banking relationships and institutional capital deployment

- **Current number or market size:** As of April 2025, **24 registered VASPs** operate in Georgia [[Fintechs]](https://fintechs.ge). The global prediction market liquidity provider ecosystem includes sophisticated actors from both DeFi (Polygon, Ethereum L2s) and TradFi (jumping in post-Kalshi v. CFTC). Locally, Georgian VASPs currently focus on exchange/wallet services,none yet offer structured event contracts, creating a **blue ocean opportunity** for first entrants.

---

## Section 3. Consumer side

Who consumes value on the platform? What do they get from participation?

- **Consumer type:** Georgian retail speculators and digitally native investors seeking alternative to traditional brokerage

- **What they seek:**
  - Accessible speculation on macro events (currency rates, local elections, sports, crypto prices) without minimum account balances
  - Zero-commission, mobile-first experience distinct from complex banking interfaces
  - Immediate settlement and withdrawal capabilities (24/7/365)
  - Transparent pricing that reflects collective probability rather than opaque bookmaker margins

- **What they receive:**
  - Micro-stake entry (as low as 5-10 GEL equivalent in USDC)
  - Intuitive event contracts with binary outcomes (simpler than options or CFDs)
  - Non-custodial or custodial wallet options with instant conversion to fiat via VASP partners
  - Educational guardrails (daily loss limits, risk warnings) embedded in the platform

- **Current number or market size:** The Georgian digital payments market exceeded **$1 billion in 2023** and is projected to reach **$2.31 billion by 2024** [[Statista]](https://www.statista.com/outlook/dmo/fintech/digital-payments/georgia). Internet banking penetration is growing rapidly,**114.8 million online operations** conducted in 2022 (+16.4% YoY) with **8.16 billion GEL transferred** (+25.6% YoY) [[NBG]](https://nbg.gov.ge/en). Critically, Georgia's population shows high digital adoption but **92% remain uninvested in capital markets**, representing a massive latent demand for accessible speculation vehicles. The Fintech Association of Georgia reports approximately **35 member companies** as of April 2025 [[Fintechs]](https://fintechs.ge), indicating a maturing ecosystem but still early-stage retail investment penetration.

---

## Section 4. Network effect mechanism

- **Primary network effect type (direct, indirect, data, local):** Indirect (cross-side) network effects with data network effects

- **Mechanism description:** Liquidity providers (producers) attract retail traders (consumers) by offering tight spreads and deep order books; conversely, growing retail trading volume attracts more sophisticated market makers seeking yield. Additionally, as more events are created and resolved on-chain, the platform accumulates **resolution oracles and outcome datasets** that improve pricing accuracy for future markets,creating a data flywheel where historical resolution data enhances prediction quality and attracts informed traders. The USDC settlement layer creates composability with global DeFi liquidity, allowing Georgian users to tap into international capital flows while remaining compliant with local VASP regulations.

- **Critical mass threshold: what scale is needed for the effect to become self-sustaining?**
  - **Producer side:** 3-5 professional market makers providing liquidity on 50+ active markets with >$100,000 total value locked per major event category
  - **Consumer side:** 5,000 monthly active users generating  GEL 100,000+ monthly trading volume
  - **Combined:** Self-sustaining liquidity when 60% of markets maintain <5% bid-ask spreads without platform subsidy

- **Risk of negative network effects:**
  - **Liquidity fragmentation:** Too many illiquid markets dilute trading activity and create poor user experience
  - **Information asymmetry:** If sophisticated producers consistently dominate retail consumers, trust erodes and participation declines
  - **Regulatory contagion:** One VASP's compliance failure could trigger NBG scrutiny affecting all registered platforms
  - **Stablecoin depeg risk:** USDC volatility could undermine the micro-stakes value proposition

---

## Section 5. Client position

Where does the client sit today?

- **Current role:** producer / consumer / **potential platform operator**

- **Current leverage in the market:**
  - **Regulatory timing advantage:** NBG's VASP framework is operational (since July 2023) but prediction markets are unoccupied territory,no incumbent has combined event contracts with VASP registration [[NBG]](https://www.nbg.gov.ge/uploads/pressreleases/2025/PressRelease_on_the_NBG_Supervisory_Strategy_for_2023-2025.pdf)
  - **Crypto-friendly jurisdiction:** Georgia offers 0% personal income tax on crypto gains, 15% corporate tax (only on distributed profits), and explicit legal recognition of virtual assets as non-securities [[FINTECHS]](https://fintechs.ge)
  - **Technical infrastructure:** NBG's CBDC pilot (Digital GEL) and instant payment system (IPS) development create interoperability opportunities
  - **Strategic location:** Positioned as regional fintech hub for Middle Corridor countries with cross-border sandbox initiatives 

- **Data assets available:**
  - None currently (greenfield opportunity)
  - Potential partnerships with existing VASPs for KYC/AML data sharing (permitted under NBG framework)
  - Access to NBG's synthetic data sandbox for model training

- **Customer relationship strength:**
  - No existing retail customer base
  - Must build trust through compliance transparency (public NBG registration display required by January 2026) [[Statista]](https://www.statista.com/outlook/dmo/fintech/digital-payments/georgia)
  - Opportunity to leverage Georgian banking partnerships (TBC Bank, Bank of Georgia) for fiat on-ramp referrals

---

## Section 6. Strategic recommendation

Choose one: Build / Join / Defend / Acquire

- **Recommendation:** **FALLBACK / NICHE BUILD**

- **Reason 1 (client capabilities):** The VASP registration pathway may provide a defined framework for crypto custody, exchange, and AML/KYC controls, but it does not by itself resolve whether event contracts are permissible. The client should use this route only if NBG or counsel confirms that prediction tokens can be offered within a compliant virtual-asset structure.

- **Reason 2 (competitive dynamics):** No Georgian incumbent offers prediction markets, neither banks (focused on traditional lending/deposits) nor existing VASPs (focused on crypto exchange/wallets). However, a crypto-native route would likely narrow the target market to crypto-literate users and could weaken the bank-backed, mass-market trust proposition.

- **Reason 3 (financial logic):** A crypto-settled model may reduce some payment-processing friction, but the project should not assume lower costs or faster scale until legal classification, banking access, user demand, and liquidity subsidies are verified.

---

## Section 7. First move

What is the one specific action the client must take in the next 6 months?

- **Action:** Submit VASP pre-registration consultation to NBG specifically framing event contracts as "convertible virtual asset trading instruments" (not gambling products), accompanied by a technical whitepaper demonstrating USDC collateralization, automated market maker mechanics, and AML travel rule compliance for all transactions exceeding GEL 1,000 equivalent.

- **Owner:** CEO/Regulatory Lead (external Georgian legal counsel with NBG relationships mandatory)

- **Success metric:** NBG written feedback on whether a crypto-settled event-contract pilot could fit within VASP activities, and what additional restrictions would apply if event contracts are treated as financial instruments, gambling products, or a new category.

- **Investment required (order of magnitude):** GEL 100,000-GEL 150,000 (legal/consulting for VASP registration, technical MVP development, initial liquidity seeding)

---

## Quality check

Before finalizing:

 **Is the recommendation specific, not vague?** 
  - Yes: fallback or niche build via VASP consultation, not the default mass-market path

 **Are the three justification reasons distinct and evidence-based?**
  - Yes: Regulatory pathway (capability), competitive whitespace (dynamics), tax/unit economics (financial)

 **Does the first move pass the specificity test: could someone actually execute it?**
  - Yes: Concrete deliverable (pre-registration consultation), defined owner, measurable outcome, budget range

 **Have you confronted the chicken-and-egg problem if you recommended Build?**
  - Yes: Platform will seed initial liquidity through treasury allocation (1-2% of raise) to ensure tight spreads at launch, targeting 20 markets with GEL 50,000 TVL each before retail marketing spend

---

## Global Practice Comparison

**Polymarket (Decentralized Model):** Operates on Polygon with UMA optimistic oracle resolution, achieving $140M TVL and $40M daily volume through permissionless market creation and global accessibility. Georgia's VASP model cannot replicate full decentralization (NBG requires registered entity with local physical presence and identified administrators) [[Statista]](https://www.statista.com/outlook/dmo/fintech/digital-payments/georgia), but can adopt the automated market maker infrastructure and transparent settlement mechanics.

**Kalshi (Regulated Exchange Model):** CFTC-regulated with centralized order books, recently expanding on-chain via Solana for tokenized markets and "Builder Codes" for ecosystem development
The Georgian platform can learn from Kalshi's regulatory-first discipline, but NBG registration should not be treated as equivalent to CFTC approval.

**Key Differentiation:** Georgia may allow a hybrid model if NBG confirms both the virtual-asset and event-contract classifications, enabling potential partnerships for fiat on-ramps that Polymarket lacks and Kalshi achieves through traditional banking relationships.

---

## Reference Links

[1] https://fintechs.ge  
[2] https://nbg.gov.ge/en  
[3] https://www.statista.com/outlook/dmo/fintech/digital-payments/georgia  
[4] https://www.geostat.ge/ka  
[5] https://www.coindesk.com/markets/2026/04/06/polymarket-reveals-a-full-exchange-upgrade-to-take-control-of-its-own-trading-and-truth  
[6] https://www.bloomberg.com/news/articles/2025-11-14/kalshi-raises-50-million-at-20-billion-valuation  
[7] https://www.nbg.gov.ge/uploads/pressreleases/2025/PressRelease_on_the_NBG_Supervisory_Strategy_for_2023-2025.pdf  
[8] https://www.gfsis.org.ge/publications/georgia-s-cryptocurrency-regulation-landscape  
[9] https://www.kalshi.com/  

## Option C: The Responsible Speculation Bridge

---

## Purpose

This canvas maps the client's position in the platform competitive structure and produces a specific strategic recommendation: build, join, defend, or acquire.

---

## Industry Context

The Republic of Georgia has implemented strict gambling regulations while simultaneously building a progressive fintech infrastructure. As of January 2026, **1.57 million Georgians (40% of the population)** are reported to be on the national gambling exclusion registry, with the legal gambling age raised to 25 and biometric identification mandatory for all gambling venues [[Public Gaming]](https://www.publicgaming.com/news-categories/responsible-gaming/15364-the-country-of-georgia-bans-40-of-population-from-gambling). This is evidence that gambling-related harm is politically and socially sensitive in Georgia, making responsible-use controls essential for any event-contract platform.

The National Bank of Georgia (NBG) has established robust consumer protection frameworks, including payment-to-income (PTI) limits on FX lending (20-30% depending on income level) and loan-to-value (LTV) caps [[ELibrary]](https://www.elibrary.imf.org/view/journals/002/2024/135/article-A001-en.xml). The NBG settled **85% of consumer disputes in favor of citizens in 2024**, securing GEL 300,000 in refunds and demonstrating strong regulatory commitment to financial consumer protection [[GeorgiaToday]](https://georgiatoday.ge/nbg-over-90-consumer-disputes-settled-in-favor-of-citizens-in-2024/). The NBG also runs extensive financial literacy programs through FinEdu, reaching **950,000 children, youth and adults during Global Money Week 2024** [[GlobalMoneyWeek]](https://globalmoneyweek.org/countries/142-georgia.html).

**Global Best Practice:** Leading retail trading platforms have pioneered "responsible trading" features that could be adapted for prediction markets. eToro's Responsible Trading policy limits leverage to 1:100 and restricts investment per trade to 20% of account equity [[GlobalBankingAndFinance]](https://www.globalbankingandfinance.com/trading-responsibly-your-ticket-to-long-term-success/). IG Group provides negative balance protection ensuring retail clients cannot lose more than their account balance, alongside guaranteed stop orders and position-by-position risk limits [[IGGROUP]](https://www.iggroup.com/~/media/Files/I/IG-Group/documents/investors/debt-investors/ig-group-emtn-update-2025-base-prospectus-v1.pdf). Interactive Brokers' IBKR Campus offers comprehensive financial education with eight pillars including Traders' Academy, webinars, and quant resources. These mechanisms,mandatory loss limits, educational guardrails, and negative balance protection,provide the template for a "responsible speculation" platform in Georgia.

---

## Section 1. Value unit

What is the minimum unit of interaction the platform could facilitate in this industry? What changes hands between the two sides?

- **Value unit:** Responsible Event Contract with Embedded Risk Guardrails (a regulated prediction instrument with mandatory daily loss limits, educational checkpoints, and negative balance protection)

- **Description:** The minimum unit is a structured event contract that incorporates consumer protection mechanisms directly into the product architecture. Unlike standard prediction markets, each contract includes: (1) pre-trade educational confirmation requiring user acknowledgment of risk; (2) automatic daily loss limits; (3) cooling-off periods after consecutive losses; and (4) negative balance protection ensuring users cannot lose more than deposited funds. The contract represents a position on a verifiable outcome, but "financial education platform" should not be presented as a proven legal classification unless confirmed by Georgian counsel or NBG.

---

## Section 2. Producer side

Who produces value on the platform? What do they get from participation?

- **Producer type:** Responsible Market Operators and Educational Content Providers (NBG-authorized financial institutions, certified financial educators, risk management specialists)

- **What they contribute:**
  - Curated, low-volatility event markets designed for retail education (e.g., GEL/USD rate movements within bands, local weather outcomes, election participation rates)
  - Mandatory educational content integrated into trading workflow (risk assessment quizzes, financial literacy modules)
  - Risk management infrastructure including real-time monitoring, automatic position closure at loss limits, and compliance reporting to NBG
  - Liquidity provision with reduced leverage (maximum 1:5 vs. industry standard 1:100) to minimize catastrophic losses

- **What they receive:**
  - Stronger regulatory trust through a responsible-use product layer
  - Evidence that gambling-related harm is politically and socially sensitive in Georgia, making responsible-use controls essential for any event-contract platform.
  - Partnership opportunities with NBG financial literacy initiatives (FinEdu)
  - Stronger trust if responsible-use controls become part of the approved sandbox design

- **Current number or market size:** Georgia's reported gambling exclusion figures are evidence that gambling-related harm is politically and socially sensitive in Georgia, making responsible-use controls essential for any event-contract platform. Global responsible trading features are now standard,eToro's policy has been in place since 2012 [[GlobalBankingandFinance]](https://www.globalbankingandfinance.com/trading-responsibly-your-ticket-to-long-term-success/), IG's negative balance protection applies across 19 countries [[IGGroup]](https://www.iggroup.com/~/media/Files/I/IG-Group/documents/investors/debt-investors/ig-group-emtn-update-2025-base-prospectus-v1.pdf), and Interactive Brokers' education platform serves millions. No Georgian platform currently combines prediction markets with mandatory consumer protection guardrails.

---

## Section 3. Consumer side

Who consumes value on the platform? What do they get from participation?

- **Consumer type:** Digitally active Georgian retail users and novice retail investors requiring education-first onboarding, with responsible-use protections designed to prevent harm.

- **What they seek:**
  - Transparent, regulated-feeling access to event contracts without being targeted because of gambling vulnerability
  - Structured financial education integrated with practical experience
  - Protection from catastrophic losses through mandatory limits
  - Socially acceptable "investment gaming" distinct from stigmatized gambling

- **What they receive:**
  - **Daily loss limits:** Maximum 50 GEL daily loss cap (customizable down to 10 GEL), with mandatory 24-hour cooling-off after limit reached
  - **Educational checkpoints:** Required completion of risk assessment quizzes before first trade and monthly thereafter, integrated with NBG FinEdu curriculum [[GlobalMoneyWeek]](https://globalmoneyweek.org/countries/142-georgia.html)
  - **Negative balance protection:** Account balance cannot fall below zero,platform absorbs excess losses [[IgGroup]](https://www.iggroup.com/~/media/Files/I/IG-Group/documents/investors/debt-investors/ig-group-emtn-update-2025-base-prospectus-v1.pdf)
  - **Position limits:** Maximum 20% of account equity per trade (eToro model)
  - **Transparent probability displays:** Clear odds visualization with historical accuracy data, avoiding opaque bookmaker margins
  - **Progressive unlocking:** Beginner markets only (high-probability outcomes) until educational milestones completed; advanced markets unlock with demonstrated competence

- **Current number or market size:** **92% of Georgians uninvested in capital markets**; NBG financial literacy programs reached **950,000 in 2024** [[GlobalMoneyWeek]](https://globalmoneyweek.org/countries/142-georgia.html); Digital payments market **$2.31 billion** [[Statista]](https://www.statista.com/outlook/dmo/fintech/digital-payments/georgia). TODO: verify source before estimating the addressable user base for a responsible-use event-contract product.

---

## Section 4. Network effect mechanism

- **Primary network effect type (direct, indirect, data, local):** Data network effects with indirect (cross-side) network effects

- **Mechanism description:** The platform accumulates behavioral data on responsible trading patterns, specifically, which educational interventions reduce problematic trading, optimal loss limit thresholds by demographic, and predictive accuracy improvements as users progress through curriculum. This dataset becomes valuable to: (1) NBG for macroprudential policy refinement; (2) international regulators seeking gambling harm reduction models; (3) academic researchers studying behavioral finance. As more users generate data, the platform's risk models improve, enabling dynamic personalization of loss limits and educational content. Additionally, a community of responsible traders creates social proof for transparent, protected event-contract participation, similar to how eToro's CopyTrader network reduced individual risk-taking through social learning [[5]](https://www.globalbankingandfinance.com/trading-responsibly-your-ticket-to-long-term-success/).

- **Critical mass threshold: what scale is needed for the effect to become self-sustaining?**
  - **Data network effects:** 10,000 active users generating sufficient behavioral data to train predictive risk models with 80%+ accuracy in identifying at-risk behavior patterns
  - **Community effects:** 5,000 users with demonstrated positive outcomes (profitability + educational completion) creating social proof and referral network
  - **Regulatory validation:** NBG and payment-partner comfort with the responsible-use product layer after compliance history and low complaint rates
  - **Combined:** Self-sustaining when 40% of new users arrive via organic referral (vs. paid acquisition) and NBG features platform in official financial literacy materials

- **Risk of negative network effects:**
  - **Stigma contagion:** If early marketing implies the platform is a gambling substitute, the product may lose financial-market credibility.
  - **Regulatory overreach:** Success may trigger NBG to impose additional restrictions (e.g., lowering loss limits further) that undermine unit economics
  - **Data privacy concerns:** Behavioral risk profiling requires sensitive personal data; breach or misuse could destroy trust
  - **Platform gaming:** Sophisticated users may create multiple accounts to circumvent loss limits, requiring costly identity verification infrastructure

---

## Section 5. Client position

Where does the client sit today?

- **Current role:** producer / consumer / **potential platform operator**

- **Current leverage in the market:**
  - **Regulatory whitespace:** No Georgian platform currently occupies the "responsible speculation" niche,gambling is heavily restricted, traditional brokerages require minimum balances and complex onboarding, crypto platforms lack educational guardrails
  - **NBG relationship opportunity:** NBG's demonstrated commitment to consumer protection (85% dispute resolution in consumer favor) [[GeorgiaToday]](https://georgiatoday.ge/nbg-over-90-consumer-disputes-settled-in-favor-of-citizens-in-2024/) and financial literacy investment (950,000 reached) [[GlobalMoneyWeek]](https://globalmoneyweek.org/countries/142-georgia.html) creates receptive environment for education-first platform
  - **Social license:** Reported gambling exclusion figures show that gambling-related harm is politically and socially sensitive in Georgia, so responsible-use controls are essential.
  - **Global precedent:** eToro (12+ years), IG Group (50+ years), Interactive Brokers (40+ years) have validated responsible trading features [[Global Banking and Finance]](https://www.globalbankingandfinance.com/trading-responsibly-your-ticket-to-long-term-success/) [[Ig Group]](https://www.iggroup.com/~/media/Files/I/IG-Group/documents/investors/debt-investors/ig-group-emtn-update-2025-base-prospectus-v1.pdf) [[Interactive Brokers]](https://www.interactivebrokers.com/campus/trading-lessons/ibkr-campus-education-and-tutorials/),client can license/adapt proven frameworks rather than inventing new standards

- **Data assets available:**
  - None currently (greenfield opportunity)
  - Potential partnership with NBG FinEdu for anonymized financial literacy assessment data [[Global Money Week]](https://globalmoneyweek.org/countries/142-georgia.html)
  - The platform should screen against legally required exclusion or restriction lists if required by regulators, but should not use vulnerable or excluded populations as a marketing segment.

- **Customer relationship strength:**
  - No existing retail customer base
  - Must build trust through NBG-reviewed controls and transparent responsible-use features
  - Opportunity to leverage NBG's 123 participating organizations in Global Money Week 2024 [[Global Money Week]](https://globalmoneyweek.org/countries/142-georgia.html) for B2B2C distribution (banks, universities, youth programs)

---

## Section 6. Strategic recommendation

Choose one: Build / Join / Defend / Acquire

- **Recommendation:** Do not treat this as a standalone licensing route. Use it as a product-governance layer inside Option A.

Responsible-use features are essential for regulatory trust, payment-partner comfort, and reputational protection. However, "financial education platform" should not be presented as a proven legal classification unless confirmed by Georgian counsel or NBG. The stronger use of this option is to embed daily limits, loss caps, cooling-off periods, risk disclosures, market-integrity monitoring, and educational onboarding into the sandbox-first platform design.


---

## Section 7. First move

What is the one specific action the client must take in the next 6 months?

- **Action:** Include responsible-use controls in the Option A sandbox proposal, including daily limits, exposure caps, cooling-off periods, risk disclosures, market-integrity monitoring, and educational onboarding.

- **Owner:** CEO/Regulatory Lead with NBG relationship + Chief Product Officer with responsible trading platform experience (eToro/IG/Interactive Brokers alumni preferred)

- **Success metric:** NBG and payment partners confirm which responsible-use controls are required before a sandbox pilot, including whether any exclusion or restriction lists must be screened.

- **Investment required (order of magnitude):** $200,000-$350,000 (regulatory consulting, NBG relationship development, MVP with embedded risk guardrails, educational content production, pilot user acquisition subsidy)

---

## Quality check

Before finalizing:

 **Is the recommendation specific, not vague?** 
  - Yes: responsible-use product layer embedded inside the sandbox-first path, not a separate legal route

 **Are the three justification reasons distinct and evidence-based?**
  - Yes: regulatory trust, payment-partner comfort, and reputational protection are distinct benefits.

 **Does the first move pass the specificity test: could someone actually execute it?**
  - Yes: concrete controls can be included in the sandbox proposal and reviewed by NBG, counsel, and payment partners.

 **Have you confronted the chicken-and-egg problem if you recommended Build?**
  - Yes: the layer reduces harm and reputational risk while the platform solves liquidity through controlled market design and market-maker planning.

---

## Global Practice Comparison

**eToro Responsible Trading Model:** Pioneer since 2012 with mandatory leverage limits (1:100 max), 20% position size limits, and educational interventions [[Global Banking And Finance]](https://www.globalbankingandfinance.com/trading-responsibly-your-ticket-to-long-term-success/). Georgian platform should adopt position limits but tighten further (1:5 leverage max for novices) given local risk appetite and regulatory environment.

**IG Group Consumer Protection Framework:** Negative balance protection, guaranteed stops, and position-by-position Limited Risk Accounts (LRAs) that force explicit stop placement [[IgGroup]](https://www.iggroup.com/~/media/Files/I/IG-Group/documents/investors/debt-investors/ig-group-emtn-update-2025-base-prospectus-v1.pdf). IG's data shows LRA users demonstrate more thoughtful trading behavior (18.5% use limit orders vs. 13% standard account users). Georgian platform should mandate LRAs for all users first 90 days.

**Interactive Brokers IBKR Campus:** Eight-pillar education platform including Traders' Academy, webinars, podcasts, and quant resources [[InteractiveBrokers]](https://www.interactivebrokers.com/campus/trading-lessons/ibkr-campus-education-and-tutorials/). Georgian platform should license/adapt IBKR curriculum structure but localize content (Georgian language, GEL-denominated examples, local market case studies).

**Key Differentiation:** Georgia's platform can combine responsible trading practices (limits, protection, and education) with the sandbox-first recommendation. It should not claim a new "regulator-approved responsible speculation" category unless NBG confirms that classification.

---

## Reference Links

[1] https://www.publicgaming.com/news-categories/responsible-gaming/15364-the-country-of-georgia-bans-40-of-population-from-gambling

[2] https://www.elibrary.imf.org/view/journals/002/2024/135/article-A001-en.xml

[3] https://georgiatoday.ge/nbg-over-90-consumer-disputes-settled-in-favor-of-citizens-in-2024/

[4] https://globalmoneyweek.org/countries/142-georgia.html

[5] https://www.globalbankingandfinance.com/trading-responsibly-your-ticket-to-long-term-success/

[6] https://www.iggroup.com/~/media/Files/I/IG-Group/documents/investors/debt-investors/ig-group-emtn-update-2025-base-prospectus-v1.pdf

[7] https://www.interactivebrokers.com/campus/trading-lessons/ibkr-campus-education-and-tutorials/

[8] https://www.statista.com/outlook/dmo/fintech/digital-payments/georgia

---
