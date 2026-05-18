# Frontier Radar Reference

## Default Topic Taxonomy

Prioritize these wildfire and fire refuge directions:

1. Wildfire hazard and risk: fire likelihood, severity, exposure, vulnerability, WUI risk, cascading hazards, compound drought-heat-fire risk, and climate-fire interactions.
2. Fire behavior and spread modeling: fuel structure, wind, topography, spotting, ember transport, rate of spread, fireline intensity, simulation, uncertainty, and operational forecasting.
3. Fire weather and fuels: drought indices, fuel moisture, vegetation condition, heatwaves, lightning, Santa Ana or foehn winds, fire danger rating, and seasonal outlooks.
4. Remote sensing of wildfire: active fire detection, burned area mapping, burn severity, smoke plumes, fuel mapping, recovery monitoring, multi-sensor fusion, UAV data, and satellite time series.
5. Geospatial AI and modeling: machine learning, deep learning, foundation models, graph models, physics-informed learning, data assimilation, uncertainty quantification, explainable AI, and large-scale GIS pipelines.
6. Human fire refuge and evacuation: community refuges, evacuation shelters, neighbourhood safer places, shelter-in-place, last-resort refuge, evacuation modeling, traffic constraints, warning systems, and vulnerable populations.
7. Ecological fire refugia: unburned patches, low-severity islands, biodiversity persistence, habitat continuity, recolonization, landscape resilience, microclimate, riparian refugia, and post-fire succession.
8. Post-fire impacts and recovery: debris flows, erosion, hydrology, water quality, carbon emissions, vegetation recovery, invasive species, infrastructure loss, smoke exposure, and public health.
9. Planning, governance, and adaptation: prescribed fire, cultural burning, fuel treatments, defensible space, land-use planning, insurance, risk communication, Indigenous knowledge, and community resilience.
10. Datasets, benchmarks, and tools: open fire perimeters, active fire products, burned area products, weather reanalysis, land cover, fuels, WUI layers, evacuation networks, code repositories, and benchmark tasks.

## Fire Refuge Concept Guardrails

Use these distinctions:

- Fire refuge: human safety place or procedure. Examples include community refuge, evacuation shelter, temporary refuge area, neighbourhood safer place, shelter-in-place location, and last-resort refuge. Treat as jurisdiction-specific and safety-critical.
- Fire refugia: ecological persistence area. Examples include unburned patches inside a fire perimeter, low-severity burn islands, moist gullies, riparian strips, rocky outcrops, old-growth patches, and species refugia.
- Defensible space: property or landscape management around structures to reduce ignition risk. It is not automatically a refuge.
- Evacuation shelter: destination after evacuation. It may not be designed to withstand fire-front exposure.
- Shelter-in-place: a strategy that may be considered only under official local guidance. Do not recommend it as personal emergency advice.

When a user says "fire refuge", ask or infer whether they mean human refuge, ecological refugia, or both. In academic writing, explicitly define the term before using it.

## Transferable AI and Remote Sensing Topics

Track AI, CV, geospatial, and forecasting work when it can plausibly transfer to wildfire:

1. Foundation models and representation learning: satellite foundation models, masked modeling, contrastive learning, multimodal encoders, geospatial embeddings, and time-series pretraining.
2. Segmentation and detection: burned area mapping, active fire detection, fuel/vegetation mapping, smoke plume segmentation, structure detection, road network extraction, and damage assessment.
3. Temporal forecasting: video models, sequence models, transformers, neural operators, state-space models, data assimilation, and probabilistic forecasting.
4. Physics-informed and hybrid modeling: coupling ML with fire behavior models, weather models, hydrology models, or agent-based evacuation models.
5. Graph and network methods: evacuation route modeling, infrastructure vulnerability, road closures, powerline ignition risk, social vulnerability, and landscape connectivity.
6. Robustness and uncertainty: OOD detection, calibration, domain adaptation, transfer across regions/seasons/sensors, uncertainty-aware mapping, and decision-focused evaluation.
7. Data-efficient learning: weak supervision, active learning, semi-supervised learning, synthetic data, label noise handling, and human-in-the-loop annotation.
8. Decision support and human factors: warning systems, explainable AI, risk communication, emergency response, community behavior, equity, and trust.

For each transferable candidate, write a wildfire transfer note:

- Transferable component: model, loss, benchmark, data pipeline, evaluation protocol, or decision-support pattern.
- Required adaptation: geography, sensor, spatial scale, temporal resolution, weather/fuel variables, imbalanced labels, uncertainty, or operational constraints.
- Candidate wildfire task: active fire detection, spread forecasting, fire risk mapping, evacuation modeling, fire refuge siting, fire refugia detection, burn severity, smoke exposure, or recovery monitoring.
- First validation: smallest public dataset and metric that can test the transfer.
- Risk: data mismatch, label uncertainty, spatiotemporal leakage, compute cost, safety overclaim, poor interpretability, or weak novelty.

## Exclusion and Downranking

Exclude or downrank by default:

- Pure structural fire, indoor fire safety, combustion chemistry, or materials flammability papers unless the user asks for them or they directly support wildfire refuge design.
- General climate papers without a clear wildfire, fuel, drought, smoke, or fire-regime link.
- Sensational news without primary data, official reporting, or research value.
- Operational claims without date, jurisdiction, uncertainty, or evidence.
- Firefighting equipment or tactical incident reports unless needed for refuge, evacuation, or operational decision-support research.
- Papers that use black-box prediction without validation, uncertainty analysis, or plausible decision use.

Include borderline items only if they fill a specific gap. Mark scope risk explicitly.

## Query Expansion

Core wildfire search phrases:

- wildfire research frontier
- wildland fire risk assessment
- wildfire hazard exposure vulnerability
- WUI wildfire risk
- wildfire spread modeling machine learning
- fire behavior modeling uncertainty
- wildfire fire weather fuel moisture remote sensing
- wildfire evacuation modeling
- wildfire shelter in place
- wildfire community refuge
- fire refuge wildfire
- bushfire refuge
- neighbourhood safer place bushfire
- last resort refuge wildfire
- evacuation shelter wildfire
- fire refugia ecology
- wildfire refugia unburned patches
- ecological fire refugia biodiversity
- burn severity refugia
- post-fire recovery remote sensing
- smoke exposure wildfire health

Remote sensing and AI phrases:

- active fire detection satellite deep learning
- burned area mapping foundation model
- wildfire burn severity Sentinel Landsat
- VIIRS MODIS wildfire detection
- fuel moisture remote sensing machine learning
- wildfire smoke plume segmentation
- wildfire spread forecasting graph neural network
- physics informed wildfire modeling
- wildfire data assimilation machine learning
- foundation model wildfire remote sensing
- geospatial AI wildfire risk
- wildfire evacuation network optimization
- fire refugia mapping remote sensing
- post-fire vegetation recovery time series
- uncertainty quantification wildfire prediction
- domain adaptation wildfire remote sensing

Source-specific examples:

- arXiv: `wildfire spread forecasting machine learning site:arxiv.org`
- EarthArXiv: `wildfire risk remote sensing site:eartharxiv.org`
- GitHub: `wildfire spread modeling GitHub`
- Google Scholar: `fire refugia unburned patches biodiversity`
- Dataset: `wildfire perimeter dataset burned area MODIS VIIRS Landsat`
- Policy: `wildfire community refuge official guidance`
- Conference: `wildfire remote sensing AI conference 2026`

Use geography-specific synonyms:

- United States: wildfire, wildland fire, WUI, community wildfire protection plan.
- Australia: bushfire, neighbourhood safer place, community fire refuge, defendable space.
- New Zealand: wildfire, rural fire, Fire and Emergency New Zealand, evacuation.
- Mediterranean Europe: forest fire, wildland-urban interface, civil protection.
- Canada: wildland fire, evacuation order, community protection, boreal fire.

## Candidate Sources

Use these as source categories, not as a fixed list:

- Literature indexes: Google Scholar, Semantic Scholar, OpenAlex, Web of Science or Scopus if available.
- Preprints: arXiv, EarthArXiv, bioRxiv or medRxiv for ecology/health when appropriate.
- Journals: International Journal of Wildland Fire, Fire Ecology, Fire Safety Journal, Natural Hazards and Earth System Sciences, Remote Sensing of Environment, ISPRS journals, Landscape Ecology, Ecological Applications, Global Change Biology, Environmental Research Letters, Safety Science, Risk Analysis, and disaster-management journals.
- Conferences and workshops: AGU, EGU, ESA/NASA remote sensing meetings, CVPR/EarthVision, NeurIPS/ICML/ICLR geospatial or climate workshops, ACM SIGSPATIAL, ISPRS, IEEE IGARSS, and wildfire-specific symposia.
- Data/products: NASA FIRMS, MODIS and VIIRS active fire, MCD64A1 burned area, Landsat/Sentinel imagery, MTBS, LANDFIRE, FireCCI, GFED, Copernicus/GWIS, NOAA weather products, ERA5, national fire perimeters, WUI datasets, road networks, census/social vulnerability layers.
- Official guidance: national and local fire authorities, emergency management agencies, meteorological agencies, land-management agencies, standards bodies, and inquiry/royal commission reports.

When the task is jurisdiction-specific, prefer local official sources over generic international summaries.

## Scoring Rubric

Score each item from 0-10:

- Relevance: direct fit to wildfire, fire refuge, fire refugia, or the user's stated subtopic.
- Novelty: new problem, dataset, method, case comparison, theory, benchmark, or policy framing.
- Evidence strength: credible data, design, validation, case selection, uncertainty handling, and limitations.
- Spatial-temporal fit: appropriate scale, geography, temporal resolution, and transferability.
- Reproducibility: code, data, model weights, transparent methods, or clear protocol.
- Operational or policy relevance: usefulness for planning, evacuation, refuge siting, risk reduction, recovery, or governance.
- Safety and ethics: avoids overclaiming, handles uncertainty, accounts for vulnerable groups, and respects local authority guidance.
- Research potential: clear path to a publishable question, thesis chapter, or fundable project.
- User fit: matches the user's geography, discipline, methods, and target output.

Interpretation:

- 9-10: read immediately; possible anchor paper, dataset, or thesis direction.
- 7-8: strong candidate; compare with nearby work.
- 5-6: useful background, method, or baseline.
- below 5: mention only if it fills a named gap.

## Research Idea Template

For each proposed idea, include:

- Idea name.
- Problem: unresolved gap and why it matters.
- Hypothesis: testable claim or design proposition.
- Scope: geography, fire type, population/ecosystem, and time window.
- Data: likely public datasets, official records, remote-sensing products, field data, surveys, or policy documents.
- Method: model, spatial analysis, qualitative design, mixed methods, or decision-support framework.
- Baselines: scientific, operational, policy, or modeling baselines.
- Metrics: predictive, spatial, ecological, evacuation, equity, uncertainty, or decision-quality metrics.
- Expected contribution: why the work could be publishable.
- Risk: data access, label quality, ethics, safety claims, compute, causality, transferability, or policy validity.
- First experiment: smallest study that can support or falsify the idea.

## Fire Refuge Analysis Template

Use this when the task involves fire refuge or fire refugia:

```text
Concept definition
- User meaning:
- Human refuge / ecological refugia / integrated:
- Jurisdiction or ecosystem:

Evidence map
| Theme | Key source | Geography | Method | Finding | Limitation | Relevance |

Human refuge dimensions
- Evacuation feasibility:
- Shelter/refuge design:
- Warning and communication:
- Vulnerable populations:
- Governance and liability:
- Evidence gaps:

Ecological refugia dimensions
- Fire severity and patch pattern:
- Microclimate/topography/fuels:
- Species or habitat function:
- Persistence across repeated fire:
- Remote-sensing detectability:
- Evidence gaps:

Research opportunity
- Gap:
- Hypothesis:
- Data/method:
- First study:
```

## Output Template

Use this structure for a weekly radar:

```text
Weekly takeaways
- Trend 1
- Trend 2
- Trend 3

Ranked candidates
| Rank | Title/Project | Source/Date | Topic | Scale/Geography | Data/Method | Code/Data | Score | Why it matters |

Top 3 deep dives
1. Title
   - Core problem:
   - Method:
   - Evidence:
   - Limitations:
   - Extension:

Fire refuge / refugia notes
- Item:
- Concept:
- Evidence:
- Planning/ecological implication:
- Risk or limitation:

AI or remote-sensing transfer notes
- Paper/project:
- Transferable component:
- Required adaptation:
- Candidate wildfire datasets:
- First experiment:
- Risk:

Publishable research ideas
1. Idea name
   - Problem:
   - Hypothesis:
   - Method:
   - Datasets/Metrics:
   - Baselines:
   - First experiment:

Next reading queue
- Paper/project/source 1
- Paper/project/source 2
```

For related work, group by problem families such as risk mapping, spread forecasting, remote sensing, evacuation/refuge planning, ecological refugia, and governance unless the user asks for historical development.
