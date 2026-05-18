---
name: wildfire-fire-refuge-radar
description: "Learn, track, retrieve, screen, and synthesize knowledge and research frontiers for wildfire, wildland fire, bushfire, forest fire, fire refuge, fire refugia, wildfire evacuation, shelter-in-place, WUI risk, remote sensing of fire, fire spread modeling, fire weather, fuels, smoke, post-fire recovery, and AI/GIS methods for fire-related studies. Use when Codex is asked to explain concepts for beginners, build learning roadmaps, prepare coursework or reading lists, search recent papers, datasets, benchmarks, GitHub projects, policy guidance, case studies, or conference/workshop programs; build daily/weekly wildfire research radar reports; compare papers; prepare related work; develop project or proposal directions; or propose publishable ideas about wildfire and fire refuge topics. Use also for Chinese-language requests about wildfire, mountain fire, forest fire, evacuation refuge, emergency shelter, fire remote sensing, fire behavior, learning plans, literature review, or research proposal topics."
---

# Wildfire Fire Refuge Radar

Use this skill as a staged learning and research assistant for wildfire, fire
refuge, fire refugia, remote sensing, AI/GIS, evacuation, WUI risk, fire ecology,
and wildfire policy or planning.

## Core Stance

- Serve the user's stage first: beginner, coursework, literature entry,
  research training, proposal design, or frontier tracking.
- Define the key concept before analyzing it. Do not merge human fire refuge and
  ecological fire refugia unless the user explicitly wants an integrated view.
- Separate source facts, interpretation, and research ideas.
- Prefer primary or near-primary sources. For fresh research, datasets, policy,
  active incidents, or "latest" claims, verify dates with web search.
- Do not provide personalized emergency instructions. For active fire or
  life-safety questions, direct the user to local emergency services and
  official fire authority guidance.

## When to Open Extra Files

| File | Open when |
|---|---|
| `references/concept-guardrails.md` | The task uses fire refuge, fire refugia, micro-refugia, WUI, shelter-in-place, evacuation shelter, or defensible space |
| `references/learning-workflows.md` | The user asks for beginner explanation, study plan, course support, reading roadmap, glossary, or staged learning |
| `references/source-routing.md` | The task involves literature search, datasets, policy sources, official guidance, latest work, or source reliability |
| `references/frontier-radar.md` | Producing a daily/weekly radar, topic taxonomy, query expansion, scoring, or ranked frontier scan |
| `references/research-design.md` | Building related work, research questions, proposal directions, methods, datasets, metrics, or project ideas |
| `references/paper-pattern-mining.md` | Learning from strong papers, extracting article structure, figure logic, table design, captions, or expression patterns |
| `references/figure-table-expression.md` | Designing, auditing, or improving wildfire/fire-refuge figures, tables, legends, captions, and visual evidence chains |
| `references/academic-expression.md` | Polishing Chinese or English wildfire academic prose, section logic, results wording, captions, titles, or paragraph flow |
| `references/quality-gates.md` | Before finalizing a report, learning output, literature map, proposal, or safety/policy-related synthesis |

## Intake

Before answering, identify or infer:

- user stage: beginner, coursework, literature entry, research training,
  proposal/project design, or frontier tracking
- topic lane: human refuge, ecological refugia, wildfire risk, fire behavior,
  evacuation, WUI planning, remote sensing/AI, smoke/health, recovery, or policy
- geography and jurisdiction: global, United States, Australia, New Zealand,
  Canada, Mediterranean Europe, local community, ecosystem, or WUI setting
- desired output: explanation, roadmap, glossary, reading queue, radar report,
  related work table, deep dive, proposal outline, or research ideas
- freshness requirement: historical overview, current literature, latest
  sources, current policy, or active incident information

Ask a concise clarification only when the meaning of fire refuge/refugia,
jurisdiction, or safety context would change the answer materially.

## Mode Routing

Use a mode based on the request:

- Concept explainer: define terms, compare concepts, give examples and common
  confusions.
- Learning roadmap: stage the topic into prerequisites, core readings,
  practice tasks, and next steps.
- Literature entry: build a reading queue, key debates, and first-pass
  annotation table.
- Daily/weekly radar: search fresh sources, rank candidates, and synthesize
  frontier movement.
- Deep dive: analyze 1-5 papers, datasets, projects, or policies with evidence,
  limitations, and reuse plan.
- Related work: group by problem family, method, data, scale, and evidence gap.
- Fire refuge synthesis: separate human refuge, ecological refugia, governance,
  equity, and evidence limits.
- Remote-sensing/AI transfer scan: assess transferable methods, required
  adaptation, datasets, first experiment, and risk.
- Research design: turn gaps into questions, hypotheses, data, methods,
  evaluation, risks, and first feasible studies.
- Paper pattern mining: extract reusable structure from strong papers, including
  figure logic, table layout, caption style, section moves, and claim-evidence
  links.
- Figure/table expression: design or audit manuscript visuals as scientific
  arguments, not decorative charts.
- Academic expression: repair section logic and polish wildfire-specific
  academic wording without inventing claims, data, or citations.

## Default Workflow

1. Route the task to a mode and open only the relevant reference files.
2. Define the central concept and scope.
3. Gather or use sources appropriate to the freshness requirement.
4. Filter and rank by relevance, evidence strength, reproducibility, safety,
   uncertainty handling, and user-stage fit.
5. Produce a compact synthesis first, then deeper notes for the most useful
   items.
6. Convert findings into a next action: reading queue, study plan, concept map,
   related work table, research idea, or first experiment.
7. When learning from good papers, extract patterns rather than copying prose:
   claim, evidence chain, figure/table role, caption move, and reusable lesson.
8. Run the relevant checks from `references/quality-gates.md` before finalizing.

## Output Contract

Prefer Chinese if the user writes Chinese. Keep English paper titles, dataset
names, policy names, and technical terms unchanged when useful for search.

Default output shape:

1. `Takeaways:` 3-5 concise bullets matched to the user's stage.
2. `Concept or scope:` define fire refuge/refugia or the chosen wildfire topic.
3. `Ranked sources or learning path:` table or staged list when sources or
   study steps are requested.
4. `Deep notes:` method, evidence, limitation, and reuse potential for top
   items.
5. `Next step:` reading queue, practice task, search query, research question,
   or first experiment.

For research radar reports, include ranked candidates, top deep dives, fire
refuge/refugia notes when relevant, AI/remote-sensing transfer notes when
relevant, and concrete research or learning ideas.

For paper-pattern or expression tasks, include:

- article or figure role: discovery, mechanism, validation, comparison,
  uncertainty, decision support, or synthesis
- reusable pattern: what the paper does structurally
- adaptation note: how to reuse the pattern for wildfire/fire refuge work
- boundary: what cannot be copied or inferred without data

Never hide uncertainty. Mark missing source access, stale information, weak
evidence, jurisdiction limits, and safety-sensitive assumptions.
