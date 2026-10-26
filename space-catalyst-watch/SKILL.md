---
name: space-catalyst-watch
description: Research current, public catalysts for the tracked U.S.-listed space equities—SpaceX (SPCX), Rocket Lab (RKLB), AST SpaceMobile (ASTS), Planet Labs (PL), and Redwire (RDW). Use for a catalyst card, weekly/monthly space-stock roundup, earnings or contract review, or a concise buy/neutral/sell research signal. Prioritize primary sources, verify dates and market data, and distinguish facts from inference.
---

# Space Catalyst Watch

Create evidence-led, short-horizon research for the tracked space-equity universe. This skill produces a research signal, not an order, a target price, or personalized investment advice.

## Read first

Read [references/ticker-universe.md](references/ticker-universe.md) for the current universe, official-source map, and company-specific event drivers. Read [references/catalyst-rubric.md](references/catalyst-rubric.md) when assigning a research signal or preparing a weekly/monthly roundup.

## Workflow

1. Identify the requested horizon: intraday/event reaction, 1–4 weeks, or a weekly/monthly review. If absent, use 1–4 weeks.
2. Get current facts. Search primary sources first: SEC/EDGAR filings, company IR, earnings material, and NASA, DoD, or FCC releases. Use reputable reporting only to add context or report an attributed market reaction.
3. Get a price snapshot and state its timestamp. If the market is closed, label it as the last close; never imply that it is a live quote.
4. Establish whether the new information changes expectations. A press release is not automatically a catalyst. Compare it with the last disclosed guidance, schedule, backlog, cash position, or stated milestone.
5. Check downside explicitly: cash runway, debt, ATM/shelf/warrant activity, equity issuance, delays, regulatory approvals, customer concentration, and execution risk.
6. Write the result in the user's language. Cite every material current fact near the claim; separate source-backed facts from inference.

## Research-signal rules

Use these labels only as an informational research status:

- **BUY research signal:** a verified positive change in expectations, a near-term catalyst, and no material unaddressed dilution/liquidity or execution red flag.
- **NEUTRAL / WATCH:** evidence is mixed, the next decisive event is pending, valuation/technical evidence is incomplete, or event risk is two-sided.
- **SELL research signal:** a verified negative change in expectations, material dilution/financing pressure, a delay or failed milestone, or deterioration that invalidates the prior thesis.

Do not force a label from a single headline. Do not propose leverage, position size, stop loss, automatic execution, or personalized allocation. If evidence is insufficient, say so and use **NEUTRAL / WATCH**.

## Default catalyst card

Use this compact structure unless the user asks for a different format:

```markdown
## [Company] ([Ticker]) — Catalyst Card

**As of:** [date, timezone]
**Horizon:** [event / 1–4 weeks / weekly]
**Price snapshot:** [price, timestamp; label last close if applicable]
**Research status:** BUY / NEUTRAL / SELL

**What changed**
- [Verified event and primary source]

**Why it matters now**
- [Expectation change and near-term implication]

**Bull case / Bear case**
- Bull: [condition]
- Bear: [condition]

**Key risk check**
- [dilution, cash, schedule, regulation, or liquidity]

**Invalidation / next decisive proof**
- [specific filing, result, milestone, or disclosure]
```

For a multi-company weekly or monthly output, lead with a table containing ticker, event, research status, and next decisive date. Add individual cards only for names with genuinely material changes. Say plainly when there was no material update.

## Monitoring requests

For a recurring request, monitor only this universe unless the user changes it. Notify only when new information is plausibly price-relevant. Treat Intuitive Machines (LUNR) as an event-driven reserve name: include it only for a major NASA/CLPS, mission, contract, or financing event that is relevant to the broader sector.

Never use social posts as confirmation. Preserve URLs, publication dates, and the distinction between announcement date and event date.
