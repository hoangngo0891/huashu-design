# Tool Routing · v2.1

## Purpose

Route work to the right specialist while keeping the architect in control of business reasoning, data integrity, storyline, and final judgement.

The architect decides **what the deliverable must communicate**. Specialist tools decide **how to execute a bounded part of that deliverable**.

## Core routing hierarchy

1. **Architect / analyst**
   - defines the business question, audience, decision objective, message, evidence, and constraints;
   - validates factual claims and determines whether a comparison is meaningful;
   - decides what should be shown, omitted, emphasized, or escalated.

2. **Data / calculation layer**
   - use spreadsheet, Python, SQL, or another data tool when aggregation, joins, filters, pivots, derived fields, time-bucketing, reconciliation, or QA are required;
   - never ask Flint or a visual design engine to infer missing calculations from presentation data;
   - output a clean, analysis-ready table with explicit units and comparison bases.

3. **Flint Chart Author**
   - preferred specialist for quantitative charts when a semantic chart specification can express the analytical intent;
   - use after the data are prepared and sanity-checked;
   - appropriate for time series, ranking/comparison, target-vs-actual, distribution, relationship, composition, waterfall, heatmap, small multiples, and other supported chart forms;
   - Flint owns chart grammar and chart-level layout, not business interpretation.

4. **Huashu Design**
   - preferred specialist for page/slide composition, visual hierarchy, high-fidelity layout, information graphics, flow diagrams, and overall visual refinement;
   - use after the architect has fixed the message and after Flint has produced any quantitative charts needed;
   - Huashu must not alter validated numbers or invent analytical conclusions.

5. **SHB Executive Design**
   - governs brand discipline, executive readability, chart/table consistency, language quality, integration of all components, and final QA;
   - acts as the final visual governance layer for SHB-facing or SHB-internal deliverables.

## Routing rules

### Quantitative charting

If the task contains quantitative data and a chart would improve comprehension:

1. inspect the actual values, not only column names;
2. confirm units, timing basis, totals/subtotals, missing values, and comparison basis;
3. transform the data upstream if required;
4. decide the analytical question and appropriate chart family;
5. use `Flint Chart Author` when Flint supports the intended chart cleanly;
6. integrate the output into the SHB visual system;
7. apply final SHB QA.

Do not use Flint merely because data are present. A table may be better when exact values or many definitions matter more than shape.

### Data transformation before Flint

Transform upstream when the chart requires:
- aggregation or grouped totals;
- filters or exclusions;
- joins across sources;
- pivots / long-wide reshaping beyond Flint's built-in capabilities;
- derived ratios, spreads, gaps, indexation, or normalization;
- YoY, MoM, QoQ, YTD, vs-plan, or other calculated comparisons;
- removal of embedded totals/subtotals;
- unit conversion or reconciliation.

The prepared table passed to Flint should contain only fields that are actually used or required for interpretation.

### When not to use Flint

Prefer another method when:
- the key output is a table rather than a chart;
- the visual is primarily a conceptual flow/process map rather than quantitative encoding;
- highly bespoke annotations/layouts would require fighting the chart grammar;
- the requested output must follow an existing native chart object that Flint cannot preserve;
- the chart type is unsupported or another available tool is materially better.

### Slide/report composition

If a chart is one component of a larger slide or report page:
- architect defines the headline and role of the chart;
- data layer prepares the table;
- Flint authors/renders the chart when suitable;
- Huashu or another design engine composes the page;
- SHB Executive Design governs the final result.

### Existing SHB document

When revising an existing SHB deck/report, source-document visual grammar has precedence. Flint may generate a replacement chart, but the final chart must be adapted to the established document system rather than pasted in as an unrelated graphic.

## Flint handoff contract

When handing a charting task to Flint, provide:
- analytical question;
- validated prepared data or exact field names;
- comparison basis and units;
- intended message/headline;
- chart role (primary evidence, supporting evidence, appendix, KPI tile, etc.);
- target dimensions/output when relevant.

Do not ask Flint to discover the business conclusion from unvalidated raw data when the architect can determine it first.

## Decision rule in one line

**Reason first → prepare data → Flint for quantitative chart grammar → Huashu for composition → SHB Executive Design for final governance.**
