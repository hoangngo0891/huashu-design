# Strategic Balance Sheet Dashboard · v1

## Purpose

Show progress toward year-end strategic balance-sheet objectives in a way that lets ALCO see which items are on track, which are lagging, and where corrective action may be needed.

## Required business objects

Typical monitored items include:
- Total assets
- Customer loans, including business-unit decomposition when required
- Accrued interest / interest receivables when relevant
- Customer deposits, including business-unit decomposition when required
- Deposits and borrowings from other credit institutions
- Equity / capital

Use the actual scope provided by the architect; do not invent missing categories.

## Core principle

This is a **progress dashboard**, not a balance-sheet dump.

When the user asks for progress to plan, prioritize:
- actual growth vs required growth;
- actual level vs target level;
- remaining amount / remaining growth needed;
- current run-rate vs required run-rate;
- risk status.

Do not merely repeat balances already shown on a previous slide.

## Preferred visual patterns

### Pattern A — Horizontal progress bars
Best default for 5–10 indicators.

Each row should contain:
- indicator name;
- current progress;
- target marker;
- variance / remaining gap;
- compact status signal.

Prefer this when exact comparison across many items matters.

### Pattern B — Progress rings + supporting table
Use only for a small number of headline indicators (typically 3–5). Rings show % completion; a compact table below or beside them shows actual, target, and remaining requirement.

Do not use rings for every sub-segment.

### Pattern C — Required-run-rate dashboard
Use when the key question is feasibility of meeting year-end plan.

Show:
- YTD achieved;
- remaining target;
- months remaining;
- required monthly growth/run-rate;
- current recent run-rate;
- on-track / watch / off-track status.

## Status logic

Status must be based on explicit thresholds or the architect's judgement. If thresholds are not defined, avoid fabricated traffic-light precision. Use neutral wording such as `On track`, `Needs acceleration`, `Watch`, or `Above plan` only when supported.

## Executive message examples

Good headline structure:
- `Credit is broadly on track, while customer funding requires faster Q4 growth to preserve target balance-sheet structure.`
- `Total assets are ahead of plan, but the mix is creating higher reliance on wholesale funding.`

These are examples only; use actual validated data.

## Design rules

- Keep all indicators on one comparable scale when using bars.
- Use target markers consistently.
- If some items should decline rather than increase, reverse the achievement logic explicitly.
- Separate level metrics from growth metrics visually.
- Highlight only 1–3 management-relevant exceptions.
- Keep target and actual definitions aligned to the same consolidation basis and date.

## Avoid

- donut/ring overload;
- showing balances without progress logic;
- inconsistent target denominators;
- treating a higher value as automatically better;
- color-coding status without an auditable rule;
- duplicating the full detailed balance-sheet table on the same slide.
