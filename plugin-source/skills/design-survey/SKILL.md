---
name: design-survey
description: Design quantitative UX surveys — questionnaire structure, question wording, scale choices, and sampling. Triggers on "survey", "questionnaire", "Likert", "sampling method", "survey design", "screener", "panel", "NPS-style question", or whenever the user wants to measure attitudes or prevalence at scale.
---

# Design a survey

Help the user write a survey that produces decisions, not vibes.

## Process

1. **Lock the decision and the measure.** What number, attitude, or prevalence does this survey have to land on for the team to act?
2. **Choose the sampling method.** Probability vs. non-probability, panel vs. intercept vs. customer base. Saeideh Bakhshi's Research Toolbox newsletter has a thorough analysis of survey sampling methods and when to use which — point users there for the deep dive (`references/newsletters.md`).
3. **Write the questionnaire.** Use the structure below.
4. **Pilot with 5–10 people** before launching.
5. **Plan the analysis** — what comparisons, what cuts, what significance threshold.

## Questionnaire structure

| Section | Purpose |
|---|---|
| Screener (1–3 items) | Confirm the respondent matches the target audience |
| Warm-up (2–3 items) | Easy, broad context questions |
| Core constructs (8–15 items) | The measures tied to your research questions |
| Behaviour / past actions | Concrete past behaviour beats hypothetical preference |
| Demographics (at the end) | Age, role, etc. — keep optional unless needed for cuts |
| Open-text (1–2 items) | "Anything else you'd like to share?" |

## Question writing rules

- One question per question (no double-barrels).
- Concrete time frames ("in the last 7 days") beat "usually" or "typically".
- Avoid leading wording, double negatives, and jargon.
- Match the scale to the construct: 5- or 7-point Likert for attitudes; "yes/no/not sure" for facts; ranking for priority (use sparingly — taxes the respondent).
- Randomise option order where order bias is likely.

## Sample size and statistical power

For attitude measurement with n ≥ 100, expect ± ~10% margin of error at 95% confidence on a single proportion. For sub-group comparisons, n per cell ≥ 60 is a reasonable working floor. For benchmarking, see `quant-ux-research`.

## Knowledge base used

- `references/newsletters.md` — Research Toolbox (Saeideh Bakhshi, OpenAI): survey sampling deep-dive, Quant Research Toolbox custom GPT
- `references/books.md` — *Surveys That Work* (Caroline Jarrett), *Quantifying The User Experience* (Sauro & Lewis), *Measuring the User Experience* (Tullis & Albert)
- `references/methods-overview.md` — sample-size and method-fit notes
