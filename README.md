# UX Research Mentor

A Cowork / Claude Code plugin that turns **Tarah Srethwatanakul's** [UX Research Resource Guide](https://bit.ly/UXRguide) into a working assistant.

**11 skills · 15 knowledge-base files · ~2,000 lines of curated UXR expertise.**

> Built from Tarah's guide — a curated collection of resources for UX researchers at any stage, maintained by a Staff Researcher with 10+ years across fintech (Monzo), big tech (Meta), and independent consulting. If this plugin is useful to you, the credit belongs to her curation. Read the original at [bit.ly/UXRguide](https://bit.ly/UXRguide).

---

## What it does

Eleven skills that activate on natural language — no commands to memorize:

| Skill | What it handles |
|---|---|
| `plan-research-study` | Pick the right method, scope, plan, brief stakeholders |
| `conduct-interviews` | Interview guides, Mom Test principles, moderation |
| `design-survey` | Questionnaire structure, scales, sampling |
| `usability-testing` | Moderated/unmoderated tests, scripts, severity scoring |
| `diary-studies` | Longitudinal study design, monitoring, exit interviews |
| `analyze-research` | Thematic analysis, affinity mapping, large-scale group analysis |
| `quant-ux-research` | Stats, SUS/SEQ, benchmarking, sample-size planning |
| `ai-research-workflow` | Caitlin Sullivan's AI-augmented research approach |
| `accessibility-research` | Inclusive research, AT-aware moderation, AR/spatial |
| `research-ops` | Recruitment, repositories, templates, governance |
| `uxr-career-coach` | Transitions, jobs, mentorship, salary, negotiation |

## Knowledge base

The plugin's `references/` folder contains 15 structured KB files mirroring the source guide:

- `methods-overview.md` — NN/g + Meta Research method frameworks
- `practical-guides-and-templates.md` — 7 fetched practical guides + UXinsight briefing template
- `books.md` — 22 books with author bios, key concepts, signature contributions
- `blogs.md`, `podcasts.md`, `newsletters.md`, `videos-and-channels.md` — every content source from the guide
- `communities.md`, `mentorship.md` — Slack, FB, meetups, professional associations, mentorship programs
- `career-transitions.md`, `pathways-into-uxr.md` — transition essays + apprenticeships + certifications
- `job-search.md`, `recruiting-agencies.md` — every job board and agency from the guide
- `compensation-and-negotiation.md` — actual salary numbers (Google L4 UXR ~$263K total comp, Meta IC5 ~$276K, UK senior ~£70–110K) + negotiation frameworks
- `source-guide.md` — provenance and link to Tarah's original

## Install

### Option A — Download the .plugin file
1. Download [`ux-research-mentor.plugin`](./ux-research-mentor.plugin) (75 KB).
2. **Cowork:** Settings → Plugins → Install from file → pick the `.plugin`.
3. **Claude Code:** unzip and drop the folder into your plugins directory.
4. Restart and start chatting.

### Option B — Clone and use the unpacked source
```bash
git clone https://github.com/ashutttosh/ux-research-mentor.git
cd ux-research-mentor/plugin-source
# Then drop the contents into your plugins directory
```

## Try it

Just describe what you need:

```
"Plan a usability test for our new checkout flow"
"What's a fair UXR salary for L5 at Google?"
"Help me transition from anthropology to UXR"
"Analyze these 12 interview transcripts and give me 5 themes"
"Design a survey to measure NPS for our onboarding flow"
```

## Live site

🌐 **[uxresearch-lemon.vercel.app](https://uxresearch-lemon.vercel.app)**

Download the plugin, read the docs, see all 11 skills and the full knowledge base index.

## How this was built

1. Read Tarah's source guide via Claude in Chrome (the doc had copy/paste and download disabled).
2. Designed an 11-skill plugin structure mapping methodologies → workflows → career paths.
3. Used parallel sub-agents to fetch every public resource the guide references — articles, blogs, books, podcasts, newsletters, videos, communities, mentorship programs, job boards, recruiting agencies, salary reports, negotiation resources.
4. Integrated everything into 15 reference files structured for an agent to actually use (not just cite).
5. Packaged as a Cowork-compatible `.plugin` archive.

## Credit

This plugin is a derivative work built entirely from [**Tarah Srethwatanakul's**](https://www.linkedin.com/in/tarahsrethwatanakul/) UX Research Resource Guide. All recommended resources, framing, and structure trace back to her curation.

If you find this useful, share Tarah's original guide: [bit.ly/UXRguide](https://bit.ly/UXRguide).

## License

MIT — see [LICENSE](./LICENSE).

The plugin's structure and prose are MIT-licensed. The curated resource recommendations are derived from Tarah Srethwatanakul's UX Research Resource Guide and remain her intellectual contribution; this plugin does not claim ownership of the curation, only the agent scaffolding around it.
