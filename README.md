# Wildfire Fire Refuge Radar

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827)](#)
[![Research Radar](https://img.shields.io/badge/Research-Frontier%20Radar-2563eb)](#)
[![Wildfire](https://img.shields.io/badge/Domain-Wildfire%20Research-b45309)](#)
[![Fire Refuge](https://img.shields.io/badge/Focus-Fire%20Refuge%20%26%20Refugia-059669)](#)

**Language:** English | [中文](README.zh-CN.md)

A Codex skill for learning, tracking, screening, and synthesizing knowledge and research frontiers in **wildfire**, **fire refuge**, **fire refugia**, **wildfire risk**, **evacuation**, **remote sensing**, and **AI/GIS for fire-related studies**.

This project supports learners at different stages: beginners building core vocabulary, students preparing coursework, early researchers reading papers, graduate students developing proposals, and advanced users tracking fast-moving research frontiers.

It connects scientific literature, datasets, open-source projects, policy guidance, and research trends across wildfire science, emergency management, ecology, remote sensing, geospatial AI, and community resilience.

> The skill distinguishes **fire refuge** as a human safety and emergency-management concept from **fire refugia** as an ecological persistence and resilience concept.

## Why This Skill

Wildfire research crosses many communities: fire ecology, disaster risk reduction, emergency management, remote sensing, GIScience, climate science, computer vision, public health, and land-use planning. Important ideas often appear in different vocabularies, making it difficult for learners to build a coherent map of the field.

This skill is designed to bridge that gap:

| Need | What the skill does |
| --- | --- |
| Learn the basics | Explains key terms such as wildfire, fire refuge, fire refugia, WUI, burn severity, evacuation, and shelter-in-place |
| Build a reading path | Turns a broad topic into staged reading queues for beginners, students, and researchers |
| Track new papers | Searches recent papers, datasets, GitHub projects, policy sources, conference pages, and benchmark pages |
| Connect disciplines | Links ecology, human safety, remote sensing, AI/GIS, planning, and governance perspectives |
| Avoid concept confusion | Separates human fire refuge from ecological fire refugia unless an integrated analysis is requested |
| Prepare assignments or proposals | Produces structured outlines, related work tables, research gaps, and project ideas |
| Generate research ideas | Converts frontier trends into feasible study designs and publishable directions |

## Core Capabilities

- Beginner-friendly concept explanation
- Learning roadmap generation
- Daily or weekly wildfire research radar reports
- Paper, dataset, policy, and GitHub project screening
- Fire refuge and fire refugia comparison
- Wildfire remote sensing and AI/GIS frontier tracking
- Related work table generation
- Deep paper reading notes
- Research gap and project idea generation
- Methods, dataset, baseline, and metric planning

## Learning Stage Support

| Stage | Typical Questions | Output |
| --- | --- | --- |
| Beginner | What is fire refugia? How is it different from fire refuge? | Plain-language explanation, glossary, first reading list |
| Coursework | Help me understand wildfire risk and WUI evacuation | Topic summary, concept map, assignment outline |
| Literature entry | What should I read first on fire micro-refugia? | Ranked reading queue and key debates |
| Research training | What methods and datasets are used in wildfire remote sensing? | Dataset/method table and reproducibility plan |
| Proposal development | What gaps can become a research project? | Research questions, hypotheses, methods, risks |
| Frontier tracking | What changed this week in wildfire AI or fire refugia research? | Radar report with ranked candidates |

## Research Scope

### Wildfire, Risk, and Fire Refuge

| Area | Example Topics |
| --- | --- |
| Wildfire hazard and risk | Fire likelihood, exposure, vulnerability, WUI risk, compound drought-heat-fire risk |
| Fire behavior and spread | Fuel, wind, topography, spotting, fireline intensity, spread simulation, uncertainty |
| Fire weather and fuels | Fuel moisture, drought indices, heatwaves, lightning, fire danger rating |
| Human fire refuge | Community refuge, evacuation shelter, shelter-in-place, last-resort refuge, safer places |
| Evacuation and emergency management | Warnings, traffic networks, vulnerable populations, decision support, governance |
| Planning and adaptation | Defensible space, fuel treatment, prescribed fire, cultural burning, land-use planning |

### Fire Refugia, Ecology, and Recovery

| Area | Example Topics |
| --- | --- |
| Ecological fire refugia | Unburned patches, low-severity islands, moist gullies, riparian refugia |
| Biodiversity persistence | Habitat continuity, recolonization, species refuges, functional groups |
| Landscape resilience | Fire severity mosaics, patch configuration, repeated fire, climate refugia |
| Post-fire recovery | Vegetation recovery, erosion, hydrology, carbon, invasive species |
| Remote sensing of recovery | Burn severity, time-series monitoring, recovery trajectories |

### Remote Sensing and AI/GIS

| Direction | Wildfire Transfer Path |
| --- | --- |
| Satellite and aerial imagery | Detect active fire, burned area, burn severity, fuels, smoke, and recovery |
| Foundation models | Adapt geospatial representations to wildfire mapping and monitoring |
| Time-series modeling | Track fire risk, fuel condition, burn severity, and post-fire recovery |
| Graph and network models | Support evacuation, road vulnerability, infrastructure exposure, and landscape connectivity |
| Physics-informed AI | Combine ML with fire behavior, weather, hydrology, or evacuation models |
| Uncertainty and robustness | Improve cross-region, cross-season, cross-sensor, and operational reliability |

## Scoring Rubric

Candidate papers, datasets, policies, and projects are ranked by:

| Criterion | Meaning |
| --- | --- |
| Relevance | Direct fit to wildfire, fire refuge, fire refugia, or the user's learning goal |
| Clarity | Helps explain concepts, methods, evidence, or field structure |
| Novelty | New problem, method, dataset, benchmark, theory, or policy framing |
| Evidence | Strong data, validation, case design, uncertainty handling, and limitations |
| Reproducibility | Code, data, protocol, transparent methods, or reusable workflow |
| Operational value | Usefulness for planning, evacuation, refuge siting, risk reduction, or recovery |
| Interdisciplinary value | Bridges ecology, human safety, remote sensing, AI/GIS, policy, or community resilience |
| User fit | Matches the user's stage: learning, coursework, literature review, proposal, or frontier tracking |

## Installation

Install the skill from this repository:

```powershell
python C:\Users\shuo\.codex\skills\.system\skill-installer\scripts\install-skill-from-github.py --repo limi124/wildfire-fire-refuge-radar --path skills/wildfire-fire-refuge-radar
```

Restart Codex after installation so the skill can be discovered.

## Recommended Repository Structure

```text
wildfire-fire-refuge-radar/
├─ README.md
├─ README.zh-CN.md
└─ skills/
   └─ wildfire-fire-refuge-radar/
      ├─ SKILL.md
      ├─ agents/
      │  └─ openai.yaml
      └─ references/
         └─ frontier-radar.md
```

## Example Prompts

```text
Use wildfire-fire-refuge-radar to explain the difference between fire refuge and fire refugia for a beginner.
```

```text
Build a learning roadmap for wildfire, WUI risk, evacuation, and fire refugia from beginner to research level.
```

```text
Find recent papers and datasets on fire refugia, burn severity, and post-fire recovery. Rank them by usefulness for a literature review.
```

```text
Track this week's wildfire remote sensing and AI/GIS frontier, including papers, datasets, GitHub projects, and policy sources.
```

```text
Based on wildfire, fire refuge, and fire refugia literature, propose five feasible research project ideas with data, methods, and first experiments.
```

## Typical Output

```text
Learning or radar takeaways
- Key point 1
- Key point 2
- Key point 3

Ranked candidates
| Rank | Title/Source | Date | Topic | Scale/Geography | Data/Method | Code/Data | Score | Why it matters |

Concept map
- Fire refuge:
- Fire refugia:
- WUI risk:
- Evacuation:
- Remote sensing link:

Top 3 deep dives
1. Title
   - Core problem:
   - Method:
   - Evidence:
   - Limitations:
   - Extension:

Research or learning ideas
1. Idea name
   - Problem:
   - Hypothesis or learning goal:
   - Method:
   - Datasets/Metrics:
   - Baselines or key readings:
   - First step:
```

## Notes

- Fresh research reports should use web search because papers, datasets, GitHub projects, and policy pages change frequently.
- English paper titles and technical terms should be preserved even in Chinese reports.
- Active wildfire or life-safety questions should defer to local emergency services and official fire authority guidance.
- Fire refuge and fire refugia should be defined explicitly before being used in academic or policy writing.
