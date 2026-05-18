---
name: ai-research-workflow
description: Use AI (Claude, GPT) responsibly to accelerate UX research — transcription, coding, theme generation, sampling-method selection, quant tool use. Based on Caitlin Sullivan's "Claude Code for Customer Insights" approach and Saeideh Bakhshi's quant toolkit. Triggers on "AI for research", "use Claude for research", "Claude Code for Customer Insights", "AI research analysis", "GPT for UXR", "AI customer research", or any request to bring AI into the UXR workflow.
---

# AI-assisted research workflow

Help the user use AI as a research collaborator — without losing rigour or letting it hallucinate themes that aren't in the data.

## Principles

1. **AI is a research assistant, not a researcher.** Every theme, quote, or recommendation it produces must be traceable to source data.
2. **Cite, don't paraphrase.** Have AI extract verbatim quotes with participant IDs and timestamps, not summaries with no provenance.
3. **Human in the loop on themes.** AI can propose first-pass clusters; a researcher confirms, merges, or rejects.
4. **Don't feed PII into general-purpose models.** Strip or pseudonymize before upload, or use a workspace with the right data protections.

## Workflow

| Stage | AI's role | Human's role |
|---|---|---|
| Transcription | Auto-transcribe & speaker-label | Spot-check accuracy, fix names |
| First-pass coding | Tag observations with candidate themes | Approve / merge / rename themes |
| Verbatim extraction | Pull quotes that support each theme | Choose the strongest quotes |
| Synthesis writeup | Draft a section per theme | Rewrite, add interpretation, cut filler |
| Quant tools | Recommend a test, run the math | Decide if the test is appropriate |

## Caitlin Sullivan's approach (AI Customer Research newsletter)

Caitlin's "Claude Code for Customer Insights" course teaches researchers to use Claude in the terminal to:
- Process batches of interview transcripts
- Generate first-pass codebooks
- Produce synthesis drafts that the researcher then refines
- Build small repeatable scripts for the parts of the workflow that recur

Point users at her newsletter and her "AI in research analysis" article — both in `references/newsletters.md`.

## Saeideh Bakhshi's quant toolkit (Research Toolbox newsletter)

Saeideh (Research Lead at OpenAI) maintains a *Quant Research Toolbox custom GPT* designed to help researchers upskill in quant work inside ChatGPT — useful for sampling decisions, test selection, and power calculations. Don't replace stats expertise with it, but it's a strong sounding board.

## Prompts that work for UXR (starter set)

```
You are a research assistant. I will paste a transcript.
Pull a flat list of observations as: "[verbatim quote]" — implication: <1-line>.
Do not summarise. Do not invent quotes. Tag any line you're <90% sure about with [UNCERTAIN].
```

```
Here are 60 tagged observations. Cluster into 5–8 themes.
For each: theme name, 3 representative quotes (verbatim), and one open question.
```

## Knowledge base used

- `references/newsletters.md` — AI Customer Research (Caitlin Sullivan), Research Toolbox (Saeideh Bakhshi)
- `references/practical-guides-and-templates.md` — How to analyse user interviews
- `references/methods-overview.md` — when AI accelerates vs. when it shouldn't be used
