# Figure and Table Expression

Use this file when designing, auditing, or improving figures, tables, captions,
legends, or visual evidence chains for wildfire and fire refuge work.

## First Move: Figure Contract

Before suggesting a figure or table, define:

- core conclusion: one sentence the visual must defend
- audience: beginner, coursework, supervisor, manuscript reviewer, policy reader,
  or community stakeholder
- evidence chain: what data supports the conclusion
- visual job: context, method, result, comparison, uncertainty, synthesis, or
  decision support
- scale: site, patch, landscape, region, national, or global
- risk: possible misreading, overclaim, missing uncertainty, or safety-sensitive
  interpretation

If there is no core conclusion, produce a figure plan rather than pretending a
plot is ready.

## Wildfire Figure Archetypes

| Archetype | Use for | Typical panels |
|---|---|---|
| Study-system map | Introduce geography, fire perimeter, WUI, roads, sampling, or sensor coverage | Locator map, fire history, data layers |
| Severity-refugia composite | Show where low-severity or unburned patches occur and why they matter | Burn severity map, patch metrics, example imagery |
| Time-series recovery figure | Show vegetation, fuel, smoke, or recovery trajectories | Satellite index curves, event markers, uncertainty bands |
| Workflow schematic | Explain data fusion, modeling pipeline, or screening protocol | Input data, processing steps, model, outputs, validation |
| Model evaluation grid | Compare methods or products | Metrics table, spatial error examples, calibration/uncertainty |
| Evacuation/refuge decision figure | Explain accessibility, capacity, warning time, or route vulnerability | Network map, travel-time surface, capacity table |
| Conceptual framework | Integrate ecology, risk, planning, and governance | Boxes/arrows, evidence streams, decision points |

## Panel Logic

Use the sequence:

1. Context: where, when, and what system.
2. Data/method: how the evidence was produced.
3. Main result: what changed, persisted, failed, or was detected.
4. Validation or uncertainty: how much to trust it.
5. Implication: what the result means for ecology, risk, planning, or learning.

Not every figure needs all five, but missing validation or uncertainty should be
deliberate, not accidental.

## Table Patterns

Use tables when comparison matters more than visual trend:

- concept comparison: fire refuge vs fire refugia vs shelter vs defensible space
- dataset inventory: product, sensor, resolution, temporal coverage, access,
  strengths, limitations
- literature matrix: theme, source, geography, method, finding, limitation
- method comparison: model, inputs, scale, metric, baseline, reproducibility
- policy comparison: jurisdiction, refuge term, authority, criteria, limitations
- research design matrix: question, data, method, metric, risk, first experiment

Table rules:

- one table, one message
- put units and metric direction in headers
- keep precision consistent
- group rows by concept or method family
- include limitation or evidence strength when ranking sources
- avoid mixing facts, interpretation, and recommendations in one column

## Caption Pattern

Good wildfire captions usually include:

1. what the figure shows
2. where and when
3. data or method
4. how to read key colors/symbols/metrics
5. main takeaway
6. uncertainty, limitation, or boundary if relevant

Template:

```text
Figure X. [Main message]. The figure shows [data/object] for [place/time].
[Colors/symbols] indicate [meaning]. [Panel letters] show [panel jobs].
The result highlights [claim], with [uncertainty/limitation] noted by [visual cue].
```

For tables:

```text
Table X. [Comparison purpose]. Rows group [items] by [logic]. Columns report
[variables/metrics]. Higher/lower values indicate [metric direction]. The table
is intended to support [claim or decision].
```

## Visual Risk Checks

Before finalizing a figure/table, ask:

- Does the figure prove one clear claim?
- Can a reader understand the scale, date, and geography?
- Are uncertainty and data limitations visible?
- Are colors interpretable for severity, hazard, or categories?
- Could the visual be mistaken for real-time safety guidance?
- Are vulnerable populations or access issues hidden by aggregation?
- Are maps using appropriate projection, legend, north/scale cues, and source
  notes when needed?
- Are captions strong enough to read independently?

## Adaptation Examples

- Fire refugia paper: map burn severity, identify candidate refugia, quantify
  patch persistence, then relate patches to topography, moisture, or habitat.
- Fire refuge planning: map WUI exposure, roads, evacuation time, and candidate
  refuge accessibility, then add capacity and governance constraints.
- Remote sensing/AI: show model workflow, spatial predictions, uncertainty, and
  failure cases, then include a reproducibility table.
