# Paper Pattern Mining

Use this file when the user wants to learn from strong papers in wildfire, fire
refuge, fire refugia, remote sensing, AI/GIS, ecology, evacuation, or policy.

The goal is to extract reusable research communication patterns, not to imitate
or copy text.

## Intake

Identify:

- paper type: review, empirical ecology, remote sensing/GIS, ML/modeling,
  evacuation/planning, policy, methods, dataset, or perspective
- user goal: understand, reproduce, write, design figures, build related work,
  plan a proposal, or improve expression
- target pattern: article architecture, figure logic, table design, caption
  style, results wording, discussion framing, title/abstract, or methods
- source access: full paper, abstract only, figures only, user notes, DOI, PDF,
  or pasted text

## Pattern Extraction Workflow

1. Build a claim-evidence map:
   - central question
   - main claim
   - evidence types
   - figures/tables that carry the argument
   - limitations or boundary statements
2. Classify each figure/table by job:
   - field context or study area
   - data source and workflow
   - discovery pattern
   - mechanism or driver
   - validation or benchmark
   - comparison or ablation
   - uncertainty or sensitivity
   - decision-support implication
3. Extract the section move:
   - why this matters
   - what remains unknown
   - what this study tests or maps
   - what evidence was collected
   - what the evidence shows
   - what it means and where it may fail
4. Convert to a reusable lesson for the user's topic.
5. State what requires the user's own data or cannot be borrowed.

## Output Template

```text
Paper pattern card
- Paper/source:
- Paper type:
- Central question:
- Main claim:
- Evidence chain:
- Strongest figure/table:
- Why it works:
- Reusable pattern:
- Adaptation to wildfire/fire refuge:
- Caution:

Figure/table map
| Item | Role | Data | Visual form | Claim supported | Reusable lesson |

Expression moves
- Abstract move:
- Introduction gap move:
- Results claim sentence:
- Caption move:
- Discussion boundary:
```

## Good-Paper Features

Strong papers usually:

- define the scale and decision context early
- keep the central claim close to the supporting evidence
- use figures to carry the argument, not merely display outputs
- make uncertainty visible
- distinguish mapping, prediction, explanation, and decision support
- avoid claiming operational safety from weak or retrospective evidence
- use captions that state setting, data, method, and main reading instruction
- end with boundaries, not inflated promises

## Adaptation Rules

When adapting a pattern:

- keep the structural move, not the wording
- replace the original data, geography, and evidence with the user's context
- do not reuse original images, layouts, or captions unless allowed and cited
- preserve technical precision and uncertainty language
- cite the original paper if the idea, structure, or comparison is distinctive

## Pattern Library Seeds

Look for these useful patterns in wildfire papers:

- study-area map + fire history + data coverage
- fire severity mosaic + refugia patch statistics
- workflow schematic + validation table
- time-series recovery curves + spatial examples
- evacuation network map + travel-time/capacity table
- model prediction map + uncertainty map + error analysis
- policy typology table + jurisdiction comparison
- conceptual framework linking hazard, exposure, vulnerability, and refuge
