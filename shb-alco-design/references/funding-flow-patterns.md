# Funding Flow Patterns · v1

## Purpose

Turn the economy/banking funding-flow framework into a management insight map, not a decorative Sankey. The visual must help ALCO answer whether system liquidity is sufficient, where pressure is accumulating, and which channels are absorbing or supplying funds.

## Core structure

Prefer a left-to-right or top-to-bottom architecture with clearly separated layers:

1. **External sources** — FDI disbursement, FII, remittances, external borrowing, FX-related SBV operations when relevant.
2. **Domestic sources** — household deposits, corporate deposits, bank-issued valuable papers, equity/capital, State Treasury deposits at banks, OMO support.
3. **Banking system / transmission layer** — TT1 and TT2 separated visually.
4. **Uses of funds** — credit to economy, government/corporate securities where relevant, liquidity reserves, interbank placement.
5. **Pressure indicators** — deposit rates, interbank ON/1W, FX, CASA, OMO/Treasury liquidity support.

## TT1 / TT2 convention

TT1 should represent customer/economy funding and use channels. TT2 should represent interbank and central-bank liquidity redistribution/support. Do not mix the two in one undifferentiated box.

## Quantification discipline

Only draw arrow thickness proportional to size when the quantities are measured on a comparable basis.

If data are not directly comparable:
- use equal-width conceptual arrows;
- put the numeric indicator next to the node;
- label as stock, flow, YTD growth, or qualitative pressure;
- never imply a conservation identity that the data cannot prove.

Do not present an unverified `funding gap` as the central truth of the system.

## Insight layer

The slide must include 2–4 insight callouts tied to measured indicators. Typical forms:

- `Credit growth is outpacing deposit growth → TT1 funding pressure remains elevated.`
- `High OMO / Treasury-deposit support is cushioning TT2 liquidity, but does not substitute for stable TT1 funding.`
- `FX pressure + elevated deposit rates indicate competition for stable funding.`
- `External inflows improve system liquidity only when transmission into banking deposits is visible; do not assume full pass-through.`

Do not use these as boilerplate; include only if supported by the data.

## Preferred visual patterns

### Pattern A — Economy-to-banking map
Use for full-system narrative. Two source columns feed a central banking-system block, then uses and pressure signals.

### Pattern B — TT1 vs TT2 pressure bridge
Use when the key story is that customer funding is tight but interbank/central-bank liquidity is cushioning short-term stress.

### Pattern C — Flow map + time-series strip
Use a simplified flow map in the upper 60–70% and a lower strip with 4–6 small multiples for credit, deposits, OMO, interbank rate, FX, and deposit rate.

## Visual hierarchy

- Main headline = system-level conclusion.
- Largest central object = banking system / TT1–TT2 relationship.
- Strongest accent = current pressure point, not the largest historical number.
- Secondary labels = channels and amounts.
- Footnote = definitions and comparability caveats.

## Avoid

- decorative pipes with fake thickness;
- too many icons;
- implying FDI/remittance amounts directly equal banking deposits;
- mixing stocks and flows without labels;
- using arrow direction to assert causality not supported by data;
- showing every available macro series on one slide.
