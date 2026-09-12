# Alex Quistberg

Injury epidemiologist. Department Chair, Environmental & Occupational Health, Drexel University Dornsife School of Public Health. I work on pedestrian and road safety, the built environment, and how public health agencies can use AI without lowering their evidentiary standards.

I am not a software engineer. On the projects here I set the question, the study design and the validation plan; Claude Code drafts most of the code; I read, test and revise it before it ships. Commits carry `Co-Authored-By` trailers so the division of labor is on the record.

## What is here

**[walksafe-ai-dashboard](https://github.com/aquistbe/walksafe-ai-dashboard)** — Public pedestrian-safety dashboard ([live](https://walksafe-ai-dashboard.daq26.workers.dev/)). Empirical Bayes crash-risk estimates for 16,984 Philadelphia intersections and 840 Bogotá zones, with documented methods. The imagery-validation study found no association between street-imagery scores and crash risk after exposure adjustment; that null result stays in the README because it is the kind of finding a health department needs before it buys a model.

**[road-casualty-agent](https://github.com/aquistbe/road-casualty-agent)** - An ADK agent that brings road crash data files onto one documented schema, with a human reviewing every mapping before it is applied. It does schema work and provenance, never analysis: it reports column names, code changes, row counts, file hashes, and whether a check passed. It does not compute or characterize crash counts.

**[transport-lit](https://github.com/aquistbe/transport-lit)** — MCP server that gives AI assistants keyword and semantic search over roughly 690,000 transportation research records from nine sources (U.S. DOT ROSA-P, PubMed transport subset, VTI, BASt, CEPAL and others), with full-text retrieval and citation export. Built because transport grey literature is invisible to PubMed. `uv tool install transport-lit`.

**[AI-for-Urban-Health-2026](https://github.com/aquistbe/AI-for-Urban-Health-2026)** — Materials for my annual Summer Institute course on AI for public health research and practice (2024–2026, 90 participants, most of them Philadelphia Department of Public Health staff).

**[DSPH-Faculty-and-Staff-AI-Training](https://github.com/aquistbe/DSPH-Faculty-and-Staff-AI-Training)** — Workshop series for Dornsife faculty and staff, summer and fall 2026 ([site](https://aquistbe.github.io/DSPH-Faculty-and-Staff-AI-Training/)).

**[BEPIDL](https://github.com/aquistbe/BEPIDL)** — Data and code from the NIH Fogarty K01 study of the built environment and pedestrian injury in Bogotá, the project the dashboard grew out of. Model development was led by Pablo Arbeláez's lab at Universidad de los Andes ([STRIDE](https://github.com/BCV-Uniandes/STRIDE)).

## Elsewhere

[Drexel profile](https://drexel.edu/uhc/about/team/alex-quistberg/) · [LinkedIn](https://www.linkedin.com/in/aquistbe/) · [Publications](https://www.ncbi.nlm.nih.gov/myncbi/d.%20alex.quistberg.1/bibliography/public/)
