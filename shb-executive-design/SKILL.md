---
name: shb-executive-design
description: Adaptive SHB executive design skill for management presentations, reports, dashboards, analytical visuals, executive summaries, research notes, financial communications, and other professional deliverables. Preserve SHB visual identity and institutional discipline while adapting layout, information architecture, charting, and visual language to the content, audience, decision objective, and source material. The architect owns reasoning, structure, data integrity, and message; this skill governs specialist routing, design execution, and quality.
---

# SHB Executive Design · v2.1

## Mission
Create professional SHB-facing or SHB-internal visual deliverables that are accurate, executive-readable, visually disciplined, and adaptable to the problem at hand.

This is a **general design system and orchestration layer**, not a collection of fixed templates.

The skill may design or redesign:
- management presentations and committee decks;
- ALCO and treasury materials;
- research notes and analytical reports;
- dashboards and management summaries;
- financial tables and charts;
- strategic planning and balance-sheet materials;
- market, macro, peer, FTP, liquidity, capital, risk, and performance visuals;
- process maps, flow diagrams, frameworks, and infographics;
- other professional SHB deliverables where structured visual communication is useful.

Existing pattern files are examples and accelerators. They must **never limit the scope of the skill**.

## Operating model
1. **Architect / analyst** — owns business reasoning, data validation, insight, storyline, structure, decision framing, and final judgement.
2. **Data / calculation layer** — prepares, transforms, reconciles, and sanity-checks quantitative data before charting when required.
3. **Specialist execution layer** — routes bounded tasks to Flint Chart Author for quantitative chart grammar, Huashu for visual composition, or another appropriate tool.
4. **SHB Executive Design** — integrates all components, applies SHB visual discipline, and governs final QA.

The design layer must not invent business conclusions, unsupported causality, numbers, sources, or management recommendations.

## Priority order
When rules conflict, use this order:
1. Factual and numerical accuracy
2. Architect-approved message and decision objective
3. Source-document constraints and established SHB visual identity
4. Executive readability and information hierarchy
5. Fit-for-purpose analytical and visual design
6. Reusability and editability
7. Aesthetics and novelty

## Core idea: SHB identity is a guardrail, not a template prison
Preserve recognisable SHB institutional DNA, but allow the layout and visual language to change when the content demands it.

A macro dashboard, funding-flow map, management report, peer analysis, FTP proposal, strategy deck, and research note do **not** need to look identical. They should feel related through disciplined use of brand, typography, spacing, hierarchy, tables, charts, and tone.

## Adaptive routing
Before designing, determine:
1. **Deliverable** — slide, deck, dashboard, report page, infographic, chart, table, framework, or other format.
2. **Audience** — executive management, ALCO, specialist team, broad internal audience, external stakeholder, etc.
3. **Decision objective** — inform, compare, diagnose, recommend, monitor, approve, or explain.
4. **Primary message** — what the audience should understand first.
5. **Evidence** — numbers, trends, drivers, comparisons, or qualitative facts that support the message.
6. **Source visual system** — existing SHB deck/report, supplied template, or no existing system.
7. **Best visual form** — chosen from the content, not from a fixed template catalogue.
8. **Best specialist** — route quantitative charting, data preparation, and visual composition according to `core/tool-routing.md`.

If a suitable pattern exists, reuse and adapt it. If none fits, create a new structure using the core design rules.

## Three-direction rule override
Huashu's generic three-direction gate is **not mandatory** for SHB work.

- Existing SHB document/deck → preserve and improve the visual grammar directly.
- New page/slide inside an established system → use that system directly.
- New deliverable with SHB reference/template → use the reference directly.
- Only when there is genuinely no established visual direction and exploration would materially improve the outcome → offer up to three directions.

Do not create concept-selection friction when the design direction is already implied by context.

## Core references
Always use the core files as guardrails:
- `core/design-principles.md`
- `core/shb-brand-system.md`
- `core/visual-language.md`
- `core/charts-tables.md`
- `core/executive-storytelling.md`
- `core/quality-review.md`
- `core/tool-routing.md`

## Specialist routing

### Data / calculation tools
Use spreadsheet, Python, SQL, or another suitable data tool first when the request requires aggregation, joins, filters, pivots, reconciliations, derived metrics, or comparison calculations such as YoY, MoM, QoQ, YTD, spreads, gaps, or vs-plan.

### Flint Chart Author
Prefer Flint when:
- the task is quantitative charting;
- the analytical question is clear;
- the data are already prepared and validated;
- Flint supports the intended chart cleanly.

Flint is a specialist for chart semantics and chart grammar. It does **not** own business insight, data transformation, or final SHB presentation design.

### Huashu Design
Prefer Huashu when:
- the task requires page/slide composition;
- a dashboard, information graphic, flow map, framework, or high-fidelity visual needs layout refinement;
- multiple components need to be combined into one executive visual.

Huashu does **not** own validated data or business conclusions.

### Final integration
For SHB deliverables, specialist outputs must be adapted into the SHB visual system and reviewed through `core/quality-review.md` before delivery.

## Pattern library
Patterns are optional accelerators, not mandatory routes:
- `patterns/macro-dashboard.md`
- `patterns/funding-flow.md`
- `patterns/balance-sheet-dashboard.md`

When a task does not match a pattern, design from first principles using the core files.

## Existing-document adaptation
When editing an existing SHB deck/report:
- inspect representative pages before redesigning;
- preserve page size, logo logic, title system, footer, typography rhythm, and visual motifs unless redesign is explicitly requested;
- prefer local improvement over wholesale reset;
- reuse established chart/table styles where they still serve the message;
- preserve editability whenever practical.

## Data-led design
For analytical and financial work:
- data values should be visible where exactness matters;
- comparison periods must be explicit (`YoY`, `YTD`, `vs plan`, `MoM`, `QoQ`, etc.);
- arrows and signals must refer to a defined comparison basis;
- distinguish stock, flow, period-end, average, YTD growth, annualized values, and estimates;
- never use decorative trend symbols as substitutes for actual comparison information;
- never fabricate unavailable values or implied causal relationships.

If charting is required, follow `core/tool-routing.md`: **reason first → prepare data → Flint when suitable → compose → SHB final governance**.

## Language
Executive copy should sound like an internal professional report, not generic AI prose.

Prefer:
- short statements;
- direct verbs;
- quantified comparisons;
- specific management implications;
- natural Vietnamese institutional wording.

Avoid:
- filler phrases;
- vague adjectives without evidence;
- over-explaining obvious chart content;
- generic consultant-style wording that could apply to any bank.

## Flint handoff contract
When Flint is used:
- the architect defines the analytical question and intended message;
- the data layer provides validated prepared data or exact field names;
- units and comparison basis are explicit;
- Flint selects/implements chart grammar through its semantic specification;
- Flint must not invent missing calculations, fields, labels, or business conclusions;
- the resulting chart is adapted to the SHB visual system before final delivery.

## Huashu handoff contract
When Huashu is used as the downstream execution engine:
- the architect brief is authoritative;
- SHB core references override generic Huashu style exploration;
- Huashu may improve composition, spacing, hierarchy, and visual craft;
- Huashu may not invent business meaning, data, labels, sources, or recommendations;
- HTML/CSS is an implementation medium, not a reason to make slides look like websites;
- editable PowerPoint elements are preferred over flattened screenshots when feasible;
- Huashu critique may improve design craft but must not override business or brand constraints.

## Default workflow
1. Architect validates content and defines the decision objective.
2. Determine deliverable, audience, and primary message.
3. Inspect source material and existing SHB visual system if available.
4. Read the core references, including `core/tool-routing.md`.
5. If quantitative charting is needed, prepare/transform data first and route to Flint when suitable.
6. Check whether a pattern is useful; adapt if yes, create freely if no.
7. Build the information architecture and visual specification.
8. Execute composition using Huashu or another appropriate rendering tool when needed.
9. Review against `core/quality-review.md`.
10. Revise failed dimensions only.
11. Deliver in the requested format.

## Scope boundary
Use this skill for professional SHB communication and analytical design. For consumer marketing campaigns, entertainment visuals, cinematic launch films, or unrelated product UI work, use a more appropriate general design skill unless the user specifically asks to apply SHB Executive Design.
