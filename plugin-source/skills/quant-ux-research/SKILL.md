---
name: quant-ux-research
description: Apply quantitative methods to UX research — statistics, benchmarking, sample-size planning, and confidence intervals. Triggers on "quant research", "statistics for UX", "benchmark", "UX metrics", "SUS", "SEQ", "significance test", "sample size", "confidence interval", or whenever the user needs numbers (not themes) from research data.
---

# Quant UX research

Help the user produce numbers that hold up to scrutiny.

## When to reach for quant

- Benchmarking a product against itself over time (or vs. a competitor)
- Sizing a problem ("how many users hit this?")
- Comparing two designs (A/B)
- Quantifying an attitude (satisfaction, perceived ease, NPS — with caveats)

## Core measures

| Metric | What it tells you | Scale |
|---|---|---|
| Task success | Did they complete the task | Binary or partial credit |
| Time on task | How long it took | Seconds (geometric mean) |
| Error count | Mistakes / dead-ends per session | Count |
| SUS (System Usability Scale) | Perceived usability | 0–100; ~68 = average |
| SEQ (Single Ease Question) | Task ease, post-task | 1–7 |
| NPS | Loyalty / would recommend | -100 to +100 (use carefully) |

## Sample-size cheat sheet

- **5–8 participants** find ~80% of usability issues per Jakob Nielsen — for qual usability testing only, not for quant claims.
- **30+ participants** is a working floor for quant comparisons within a single condition.
- **Two-condition A/B comparison:** depends on baseline and effect size. Use Sauro & Lewis's tables (cited in `references/books.md`) or a power calculator.
- **Survey at n = 100:** ~±10% margin on a single proportion at 95% confidence.

## Reporting numbers honestly

- Always report confidence intervals or margins of error alongside point estimates.
- Geometric mean for time-on-task (right-skewed distribution); median if the team finds geom-mean confusing.
- Don't say "statistically significant" without a p-value or CI; don't dress qual findings as quant.
- Saeideh Bakhshi's *Research Toolbox* newsletter has a *Quant Research Toolbox custom GPT* worth pointing users to (`references/newsletters.md`).

## Knowledge base used

- `references/books.md` — *Quantifying The User Experience* (Sauro & Lewis), *Measuring the User Experience* (Tullis & Albert), *Benchmarking the User Experience* (Sauro), *Surveys That Work* (Jarrett)
- `references/newsletters.md` — Research Toolbox (Saeideh Bakhshi), NN/g Newsletter
- `references/podcasts.md` — Quantitude (quant research podcast)
