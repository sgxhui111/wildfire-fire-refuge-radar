# Source Routing

Use this file for literature search, policy search, dataset search, current
research, and source reliability decisions.

## Freshness Rule

Use web search when the user asks for:

- latest, recent, this week, this month, or current work
- active fire, current alerts, evacuation, policy, regulation, or official
  guidance
- GitHub projects, datasets, benchmarks, conference programs, or leaderboards
- recommendations that depend on what exists now

If web search is unavailable, state that the output is based on local or
user-provided material.

## Source Tiers

| Need | Primary | Secondary | Use with caution |
|---|---|---|---|
| Peer-reviewed literature | Publisher pages, DOI pages, journal pages | Google Scholar, Semantic Scholar, OpenAlex | Unsourced blog summaries |
| Preprints | arXiv, EarthArXiv, bioRxiv/medRxiv when relevant | Author pages, lab pages | Reposted PDFs without metadata |
| Fire data | Official agency dataset pages | Peer-reviewed dataset papers | Unversioned mirrors |
| Active fire or alerts | Local emergency services, official fire authority, government alerts | Official incident dashboards | Social media, news-only updates |
| Policy and refuge guidance | Fire authority, emergency management, standards bodies, government reports | Inquiry reports, local plans | Generic safety blogs |
| Code and tools | Official GitHub or project page | Papers with Code, model hubs | Third-party reimplementations |
| Remote sensing products | NASA, USGS, ESA, Copernicus, NOAA, national agencies | Dataset papers | Unclear downloads |

## Search Strategy

Start broad, then narrow:

1. Concept terms: wildfire, bushfire, wildland fire, fire refuge, fire refugia.
2. Method terms: remote sensing, GIS, machine learning, evacuation model,
   burn severity, fuel moisture, graph model, uncertainty.
3. Geography: country, region, biome, WUI community, protected area, or fire
   regime.
4. Evidence type: review, dataset, benchmark, case study, policy, code.
5. Time window: recent year, last month, conference year, or historical period.

Translate Chinese questions into English search concepts. Preserve English
terms in outputs so the user can search them later.

## Screening Fields

For each candidate, capture:

- title or source name
- year/date and source type
- geography and scale
- topic lane
- data/method
- main contribution
- evidence strength
- code/data availability
- limitations
- why it matters for the user's stage

## Citation and Claim Discipline

- Do not invent DOI, author list, year, journal, dataset URL, code URL, or policy
  status.
- Mark inferred relevance as inference.
- For policy or safety claims, include jurisdiction and date.
- For active fire information, never summarize stale pages as current.
