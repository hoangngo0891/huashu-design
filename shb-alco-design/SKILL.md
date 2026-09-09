---
name: shb-alco-design
description: SHB ALCO design orchestration layer built on Huashu Design. Use for ALCO slides, funding-flow maps, strategic balance-sheet dashboards, macro dashboards, FTP/ALM visuals, and revisions to existing SHB presentations. The architect owns analytical logic, storyline, and decision framing; Huashu is the visual execution engine. Existing SHB templates and visual grammar override generic design exploration.
---

# SHB ALCO Design · v1

## Purpose

This skill is an orchestration and policy layer for SHB ALCO work. It does **not** replace analytical reasoning, ALM judgement, market interpretation, or executive storytelling. Those remain the responsibility of the architect model. Huashu Design is used as a downstream visual-design and implementation engine.

## Operating model

The hierarchy is:

1. **Architect / analyst** — understands the business question, validates data, forms insight, decides the executive message, chooses the information hierarchy, and specifies the visual objective.
2. **SHB ALCO Design wrapper** — translates the architect brief into SHB-specific design rules, decides whether to preserve or create visual grammar, and selects the appropriate ALCO pattern.
3. **Huashu Design** — executes high-fidelity layout, HTML composition, visual refinement, critique, and export mechanics.
4. **Delivery QA** — checks factual accuracy, executive readability, SHB consistency, and editability before final output.

Never allow the visual layer to invent business conclusions that were not supplied or validated by the architect.

## Priority order

When rules conflict, use this priority order:

1. Factual and numerical accuracy
2. Architect-approved message and storyline
3. Existing SHB presentation template / established visual grammar
4. Executive readability for ALCO
5. SHB-specific design patterns in this skill
6. Huashu generic design principles
7. Pure aesthetics / novelty

## Critical override: no mandatory three-direction gate

Huashu's generic rule requiring three design directions for every new visual is **overridden for SHB ALCO work**.

Use the following routing instead:

- **Editing an existing SHB/ALCO slide or deck:** preserve the existing visual grammar. Do not propose three directions. Improve hierarchy, spacing, chart selection, and readability while remaining recognizably part of the same deck.
- **Creating a new slide inside an established SHB deck:** infer the design system from surrounding slides and use it directly. Do not stop for concept selection.
- **Creating a new ALCO deck with a supplied SHB template/reference:** use the supplied template directly.
- **Only when no SHB reference, no existing deck, and no established visual system exists:** propose up to three materially different directions, then proceed after selection.

The purpose is to reduce design churn and preserve institutional consistency.

## Architect brief requirement

Before visual execution, the architect should provide or derive a concise brief with:

- **Decision question** — what ALCO/management needs to understand or decide.
- **Key message** — one sentence the slide must communicate.
- **Evidence** — data or facts that support the message.
- **Required visual form** — dashboard, flow map, bridge, timeline, chart, table, matrix, etc.
- **Hierarchy** — what must be seen first, second, and third.
- **Constraints** — SHB template, data labels, footnotes, source notes, confidentiality, language.

If the brief is incomplete but can be inferred from the working context, proceed. Do not create unnecessary clarification loops.

## Existing-slide preservation rule

When revising an existing SHB slide:

- Preserve page size, master layout, title system, footer logic, logo placement, color system, typography hierarchy, and neighboring-slide rhythm unless explicitly asked to redesign the whole deck.
- Do not replace every component simply because a different design might look more modern.
- Prefer local improvements over wholesale visual reset.
- Reuse proven visual motifs already present in the deck.
- Preserve editability wherever practical.

## ALCO executive storytelling rules

Every slide should answer at least one of these:

- What changed?
- Why did it change?
- Is it good, bad, or neutral relative to plan / risk appetite / market?
- What is the implication for the balance sheet, liquidity, NIM, funding, capital, or risk?
- What should ALCO watch or decide next?

Avoid slides that merely display data without interpretation.

### Information hierarchy

Default reading order:

1. Executive message / headline
2. Primary evidence / visual
3. Secondary drivers or decomposition
4. Implication / watchpoint
5. Source / definition / footnote

Do not let footnotes, legends, decorative labels, or secondary KPIs compete with the primary message.

## Pattern routing

Use the appropriate reference file before execution:

- Funding Flow / economy liquidity map → `references/funding-flow-patterns.md`
- Strategic Balance Sheet progress dashboard → `references/balance-sheet-dashboard.md`
- Macro / market ALCO dashboard → `references/macro-dashboard.md`
- General SHB style and slide behavior → `references/shb-slide-system.md`

## Financial-data visualization rules

- Use tables when exact values and side-by-side comparison matter more than shape.
- Use bars for progress, peer comparison, and magnitude.
- Use lines for time series and inflection.
- Use waterfall/bridge for movement decomposition.
- Use flow diagrams for source/use/liquidity transmission, but only when flows are conceptually defensible.
- Use rings/donuts sparingly: progress to target or simple composition only.
- Avoid 3D charts, excessive gradients, decorative gauges, and unnecessary iconography.
- Always state units, time basis, and whether numbers are stock, flow, YTD growth, annualized, or period-end.
- Do not fabricate unavailable data. Leave blank, mark N/A, or distinguish qualitative indicators explicitly.

## SHB-specific review gate

Before delivery, review on five dimensions:

1. **Accuracy** — numbers, units, dates, sources, definitions, and direction of change are correct.
2. **Message clarity** — the executive takeaway is visible within 3–5 seconds.
3. **Institutional consistency** — it looks like the same SHB/ALCO deck, not an unrelated agency concept.
4. **Decision usefulness** — the slide supports discussion, escalation, or monitoring.
5. **Editability** — PowerPoint elements remain editable where feasible; source data and footnotes are maintainable.

A visually attractive slide that fails any of the first four dimensions is not acceptable.

## Huashu handoff contract

When handing work to Huashu Design, the instruction should include:

- Treat the architect brief as authoritative.
- Apply SHB references before generic Huashu style exploration.
- Do not invent business insights, data, labels, or sources.
- Preserve the existing deck system when one exists.
- Use HTML/CSS as an implementation medium, not as a reason to make a slide look like a web dashboard.
- For PPT delivery, prefer editable text, shapes, charts, and tables over flattened screenshots whenever possible.
- Run Huashu critique after execution, but do not let critique override factual or SHB-specific constraints.

## Default workflow

1. Architect validates content and determines the message.
2. Identify whether this is an existing-slide revision or a new slide.
3. Read the relevant SHB reference pattern.
4. Build a visual specification.
5. Execute with Huashu.
6. Review against the SHB-specific review gate.
7. Revise only the dimensions that fail.
8. Export / deliver in the requested format.

## Scope

Primary scope:

- ALCO monthly decks
- Funding Flow / liquidity maps
- Strategic balance sheet dashboards
- Market and macro dashboards
- FTP / funding-cost visuals
- Balance sheet optimization visuals
- Management-level ALM infographics
- Revisions to existing SHB slides

Out of scope unless explicitly requested:

- consumer marketing creatives
- generic social media posts
- product UI prototypes unrelated to ALM/finance
- cinematic launch films

In those cases, use Huashu Design directly rather than this wrapper.
