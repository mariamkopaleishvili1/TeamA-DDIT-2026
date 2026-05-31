# Platform Strategy

## Project

Team A: Georgian Prediction-Market Platform  
Industry: Fintech  
Market: Republic of Georgia  
Client assumption: TBC-backed launch model  
Recommended strategic option: TBC-owned, GEL-settled prediction-market platform under an NBG special-designation or sandbox-first route

---

## Purpose

This document updates the Week 2 platform strategy for final submission.

The earlier platform strategy treated the prediction-market product mainly as a two-sided marketplace between users and liquidity providers. That logic is still correct, but it is incomplete for the final strategy.

The updated platform strategy adds the main strategic change from the final presentation:

> The platform should not be a standalone prediction-market app. It should be a TBC-controlled wallet-to-market platform integrated into or adjacent to the mobile banking ecosystem.

This matters because the strategic prize is not only trading-fee revenue. The strategic prize is ownership of the wallet, customer relationship, GEL settlement flow, KYC layer, responsible-use controls, official-source resolution, and regulator-facing governance model.

---

## 1. Platform Definition

The proposed platform is a regulated event-contract marketplace.

Users take positions on clearly defined public outcomes, such as inflation releases, GEL exchange-rate ranges, NBG policy decisions, election turnout, or other official-source public-data outcomes.

The platform has three connected layers:

1. **User layer**  
   Retail users access simple Yes/No event contracts through a TBC-linked mobile banking or wallet environment.

2. **Marketplace layer**  
   The platform lists approved event contracts, supports pricing, matches order flow, monitors spreads, manages liquidity, and resolves outcomes.

3. **Control layer**  
   TBC controls wallet funding, KYC, AML, responsible-use limits, market surveillance, source verification, dispute handling, settlement, and reporting.

The product should look simple to the user. It should not operate simply underneath. Underneath the interface, it must function like a supervised marketplace.

---

## 2. Platform Participants

### 2.1 Demand side

The demand side consists of users who want simple, short-term exposure to public outcomes.

Potential demand-side segments include:

- mobile banking users interested in financial events;
- risk-active users currently using betting, crypto, or brokerage products;
- entry-level investors who find traditional securities investing too complex;
- news-driven users who follow inflation, exchange rates, elections, and public events;
- information seekers who want market-implied probabilities, even if they trade lightly.

The demand side should not include gambling-excluded users, vulnerable users, or users targeted through sports-betting-style positioning.

### 2.2 Supply side

The supply side consists of participants who make markets usable.

This includes:

- market makers;
- liquidity providers;
- information-rich traders;
- high-conviction users who take the opposite side of trades;
- potentially institutional or semi-professional liquidity providers after sandbox validation.

The supply side matters because prediction markets fail when spreads are too wide, order books are empty, or users cannot enter and exit positions at reasonable prices.

### 2.3 Platform owner

The platform owner should be TBC or a TBC-backed entity.

This is a strategic choice. If TBC only partners with a foreign platform, it may lose control over the wallet, user behavior data, product experience, and regulator-facing governance model.

The preferred model is therefore:

> TBC owns the Georgian wallet layer, customer relationship, KYC layer, GEL settlement model, and regulator-facing governance. External partners may support technology, liquidity, or know-how, but they should not own the local platform.

### 2.4 Regulators and gatekeepers

The main gatekeepers are:

- NBG;
- payment partners;
- bank risk and compliance functions;
- official data sources such as NBG, Geostat, and CEC;
- liquidity providers;
- internal governance committees;
- customer protection and responsible-use owners.

These actors are not side stakeholders. They are part of the platform system because the platform cannot scale without their acceptance.

---

## 3. Core Platform Problem

The core platform problem is the marketplace cold start.

Prediction markets need both:

- enough users to create volume;
- enough liquidity to make prices usable.

If users arrive first but markets are empty, they will not trust the platform. If liquidity providers arrive first but user activity is weak, liquidity provision is unattractive.

The platform also has a second cold-start problem: trust.

Users must believe that:

- the event is clearly defined;
- the official source is credible;
- the price is fair enough to trade;
- the platform will settle correctly;
- funds are safe;
- disputes can be reviewed;
- user restrictions are explainable;
- the product is not a disguised betting app.

This is why TBC matters. TBC can reduce the trust cold start through brand, mobile app access, KYC infrastructure, GEL payment rails, and existing customer relationships.

---

## 4. Platform Flywheel

The proposed flywheel is:

1. TBC gives users a trusted wallet entry point.
2. Users enter approved event markets.
3. More activity attracts or justifies liquidity support.
4. Better liquidity creates tighter spreads and more reliable prices.
5. More reliable prices increase user trust.
6. Higher trust increases repeat trading.
7. Repeat trading increases platform turnover and market data.
8. Stronger market data supports better event selection, risk controls, and reporting.
9. Better controls strengthen regulatory comfort.
10. Regulatory comfort allows controlled expansion of markets and users.

The flywheel depends on TBC owning the wallet layer. If funding, settlement, and customer identity sit outside TBC, the flywheel weakens because TBC loses visibility and control over the most important platform interactions.

---

## 5. MVP Platform Architecture

The MVP should not be designed as a full public platform. It should prove the wallet-to-market loop under controlled conditions.

### 5.1 User-facing journey

The sandbox user journey should be:

1. User sees prediction-market access inside or adjacent to the TBC mobile banking app.
2. User passes eligibility, KYC, and product-understanding checks.
3. User funds a TBC-linked GEL wallet or platform balance.
4. User views approved event markets.
5. User opens a market page with the event question, official source, resolution rule, risk warning, and maximum loss.
6. User places a Yes or No position.
7. User monitors open positions.
8. Outcome is resolved through the official source.
9. Settlement returns to the TBC-linked wallet.
10. User can access dispute or support flow if needed.

### 5.2 Marketplace workflow

The market workflow should be:

1. Market Operations drafts the event contract.
2. Official source is matched from the source registry.
3. Compliance checks the market category and risk disclosure.
4. Governance approves listing.
5. Market opens with liquidity support.
6. Market quality is monitored through spread, depth, and volume.
7. Surveillance flags suspicious behavior.
8. Outcome is resolved using the official source.
9. Payouts are approved and settled.
10. Disputes, if any, are logged and reviewed.

### 5.3 Control workflow

The control workflow should capture:

- user KYC status;
- wallet funding and withdrawal records;
- exposure limits;
- daily loss limits;
- deposit alerts;
- responsible-use triggers;
- market surveillance alerts;
- liquidity-quality breaches;
- official-source evidence;
- human overrides;
- support tickets;
- dispute outcomes;
- regulator-ready reporting logs.

The MVP is successful only if all three workflows operate together. A working trading screen is not enough.

---

## 6. Mobile Banking Integration Strategy

### 6.1 Why mobile banking integration matters

Mobile banking integration is central to the final strategy.

If the platform is separate from the mobile banking ecosystem, it loses much of the TBC advantage. A separate app would require separate user acquisition, separate trust-building, separate funding behavior, and separate support routines.

The recommended model uses the mobile banking app or a closely linked wallet environment as the access point.

This creates four strategic advantages:

1. **Trust**  
   Users see the product inside a familiar bank environment.

2. **Lower CAC**  
   TBC can use existing digital distribution instead of buying every user through paid acquisition.

3. **Wallet control**  
   Funding, settlement, withdrawal, and responsible-use triggers remain inside the TBC ecosystem.

4. **Governance**  
   TBC can control onboarding, risk warnings, eligibility, limits, disputes, and reporting from the first interaction.

### 6.2 What should appear inside the app

The app should not simply advertise prediction markets as a new trading feature.

The app journey should include:

- product education screen;
- sandbox eligibility check;
- KYC and AML confirmation;
- short risk quiz or acknowledgement;
- TBC-linked wallet balance;
- deposit and withdrawal controls;
- approved market list;
- official-source label on each market;
- maximum loss shown before trade;
- daily exposure and loss limits;
- cooling-off and responsible-use messages;
- position dashboard;
- settlement status;
- dispute and support entry point.

### 6.3 What should not appear inside the app

The app should avoid:

- sports-betting-style language;
- promotional urgency;
- “easy money” framing;
- leaderboards during sandbox;
- push notifications that encourage impulsive trading;
- hidden risk warnings;
- default access for all users before eligibility rules are tested;
- unclear distinction from deposits, loans, and traditional investments.

### 6.4 Strategic implication

The mobile banking app is not only a distribution channel. It is the platform’s trust and control environment.

This means the app integration must be governed as part of platform strategy, not treated as a design detail.

---

## 7. Network Effects

Prediction-market network effects are weaker than social networks but stronger than ordinary financial apps.

The main network effects are:

### 7.1 Liquidity network effect

More users create more order flow. More order flow attracts liquidity providers. More liquidity tightens spreads. Tighter spreads make markets more attractive to users.

This is the most important network effect.

### 7.2 Data network effect

More trading creates more information about which event categories users care about, how quickly markets react, where disputes arise, and where liquidity is weak.

This improves event selection, risk warnings, reporting, and market quality.

### 7.3 Trust network effect

If users repeatedly see correct settlement, reliable payouts, clear official sources, and fair dispute handling, trust increases. Trust increases repeat use and reduces perceived product risk.

### 7.4 Governance network effect

As the platform builds market approval files, source records, incident reports, human override logs, and responsible-use evidence, it becomes easier to show regulators and payment partners that the model is controllable.

### Strategic implication

The strongest network effect is not viral sharing. It is repeated trust in the wallet-to-market loop.

---

## 8. Platform Governance

The platform requires governance before scale.

Key governance mechanisms include:

- Prediction Market Governance and AI Risk Committee;
- approved event taxonomy;
- prohibited event categories;
- official source registry;
- market approval memo;
- contract wording checklist;
- liquidity-quality dashboard;
- market surveillance rules;
- responsible-use thresholds;
- payment and wallet review workflow;
- outcome-resolution memo;
- dispute handling process;
- app-release governance checklist;
- regulator and payment-partner reporting pack.

### Strategic implication

The governance system is part of the platform. It is not a back-office support function. Without governance, the platform cannot credibly separate itself from betting-style speculation.

---

## 9. Platform Threat Assessment

### 9.1 Greatest structural threat

The greatest structural threat is not another simple prediction-market interface.

The greatest structural threat is:

> A foreign or crypto-native platform captures the wallet and customer relationship while TBC becomes only a payment rail.

This could happen through:

- a Polymarket-style crypto-native product;
- a Kalshi-style foreign regulated platform seeking local access;
- a crypto exchange adding event markets;
- a betting operator reframing event contracts as entertainment;
- another Georgian bank moving first through NBG engagement.

### 9.2 Threat by platform type

| Platform type | Example actors | What they could capture | Why it matters for TBC |
|---|---|---|---|
| Foreign prediction-market platform | Polymarket, Kalshi, Manifold-style entrants | Product experience, user data, market design, liquidity | TBC loses the category and may only process payments |
| Crypto or VASP platform | Binance, Bybit, CityPay-style actors | Wallet balances, speculative users, liquidity, crypto settlement | TBC loses risk-active wallet behavior outside the bank |
| Betting operator | Adjarabet-style actors | Risk-active attention, event behavior, entertainment framing | Category may be seen as gambling before bank model is established |
| Bank or brokerage competitor | Bank of Georgia, Galt & Taggart, Pave Bank | Trust, regulation, app distribution, existing users | TBC loses first-mover advantage in regulated event contracts |
| PSP or infrastructure provider | Payze, AzRy, CityPay | Funding flow, merchant integration, wallet-adjacent role | TBC may depend on external rails and lose margin |

### 9.3 Why not simply partner with Polymarket or Kalshi

Polymarket and Kalshi are useful benchmarks. They show that the category can work through different models.

However, a simple partnership is not enough for TBC.

A partnership may bring product knowledge or liquidity support, but it may also weaken TBC’s control over:

- wallet funding;
- GEL settlement;
- customer relationship;
- app journey;
- KYC and AML data;
- responsible-use controls;
- local event taxonomy;
- regulator-facing governance;
- platform economics.

The correct partnership logic is:

> Partner for know-how, infrastructure, or liquidity support only if TBC keeps ownership of the Georgian wallet, user relationship, GEL settlement flow, and regulatory operating model.

---

## 10. Platform Positioning

The platform should be positioned as:

> A TBC-controlled, GEL-settled, regulator-facing event-contract marketplace inside a trusted mobile banking and wallet environment.

It should not be positioned as:

- a gambling alternative;
- a sports-betting product;
- a crypto-native app;
- a standalone speculative game;
- a foreign platform white-label;
- a brokerage replacement.

### Positioning statement

For digitally active Georgian users who want simple exposure to public events, the TBC-backed prediction-market platform provides controlled Yes/No event contracts inside a trusted GEL wallet environment.

Unlike betting platforms, it uses official sources, transparent rules, responsible-use controls, and regulator-ready reporting.

Unlike crypto platforms, it is GEL-settled and bank-backed.

Unlike traditional brokerage, it does not require company analysis or long-term portfolio thinking.

---

## 11. Platform Success Metrics

The platform should not be evaluated only on registered users or trading volume.

The key success metrics are:

### User and wallet metrics

- monthly active traders;
- funded TBC-linked wallets;
- wallet funding volume;
- average balance retained in platform wallet;
- withdrawal rate after settlement;
- repeat trading rate;
- completed product-understanding checks.

### Market quality metrics

- bid-ask spread;
- order-book depth;
- market-maker quote uptime;
- volume by approved event category;
- number of active markets;
- market closure and settlement accuracy.

### Trust and control metrics

- payout dispute rate;
- payment hold false-positive rate;
- responsible-use interventions;
- cooling-off events;
- user complaint rate;
- percentage of markets with complete official-source records;
- percentage of high-risk alerts reviewed within SLA.

### Financial metrics

- monthly platform turnover;
- gross revenue;
- payment cost as percentage of funding flow;
- liquidity subsidy;
- CAC;
- contribution margin;
- breakeven active users;
- payback period.

### Governance metrics

- percentage of markets approved through complete workflow;
- number of human overrides;
- unresolved governance exceptions;
- regulator-facing reports delivered on time;
- app-release controls completed before sandbox.

---

## 12. Platform Roadmap Connection

The platform strategy connects directly to the 18-month roadmap.

### H1: Months 1 to 6

The platform foundation should include:

- governance committee;
- NBG engagement package;
- official event source registry;
- approved market taxonomy;
- contract templates;
- TBC-linked GEL wallet design;
- mobile banking app journey design;
- KYC and AML integration;
- responsible-use rules;
- MVP trading and admin workflow.

### H2: Months 7 to 18

The sandbox should test:

- wallet funding and withdrawal behavior;
- user understanding of event contracts;
- liquidity quality;
- spread stability;
- market-maker performance;
- responsible-use interventions;
- payout accuracy;
- dispute handling;
- support routing;
- contribution margin;
- regulator and payment-partner reporting.

### H3: Post-18 months

Public launch should be an option, not an automatic continuation.

The launch decision should depend on whether the platform proves:

- regulatory comfort;
- mobile banking integration readiness;
- wallet control;
- user adoption;
- turnover velocity;
- liquidity quality;
- responsible-use performance;
- dispute control;
- payment reliability;
- economics close to the base case.

---

## 13. Board-Level Conclusion

The platform strategy is not to build a prediction-market app.

The platform strategy is to build a controlled wallet-to-market system where TBC owns the customer entry point, funding flow, KYC layer, GEL settlement, market governance, official-source resolution, and reporting model.

This is the reason TBC should not wait and should not simply outsource the category to Polymarket, Kalshi, a crypto exchange, or a betting operator.

The defensible position is:

> TBC owns the wallet and mobile banking access. The platform owns the event marketplace. Governance owns the risk. Liquidity makes markets usable. Official sources make outcomes trusted. Together, these create the first regulated Georgian prediction-market category.

---

