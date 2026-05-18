# Methods overview

The source guide names two canonical methodology references and one starter publication. Both are summarized below with the substance the agent should be able to apply.

## NN/g — When to Use Which User-Experience Research Methods
- URL: https://www.nngroup.com/articles/which-ux-research-methods/
- Author: Christian Rohrer (Nielsen Norman Group)
- The article maps ~20 UX research methods across three dimensions plus a product-development timeline. It is the field's canonical method-selection chart.
- **Dimension 1 — Attitudinal vs. Behavioral.** Attitudinal = what people say (surveys, focus groups). Behavioral = what people do (A/B tests, eye-tracking, clickstream).
- **Dimension 2 — Qualitative vs. Quantitative.** Qual gathers behaviors and attitudes by direct observation; quant gathers data indirectly through surveys or instruments.
- **Dimension 3 — Context of product use.** Natural / scripted / not using product at all / hybrid.
- **Product-phase axis.** Generative methods at strategy (deciding direction), formative methods during design (informing improvements), summative methods after development (benchmarking vs. prior versions or competitors).
- Methods covered include: usability testing (lab), remote/unmoderated usability, contextual inquiry, field studies, ethnographic study, participatory design, focus groups, interviews, concept testing, card sorting, tree testing, surveys, desirability studies, customer-feedback analysis, intercept surveys, email surveys, diary/camera studies, clickstream analysis, A/B testing, and eye tracking.
- Card sorting reveals users' mental models for information architecture; eye-tracking quantifies where attention lands (special equipment required).
- A/B testing splits live traffic between versions and picks the winner on a metric.
- Clickstream/analytics captures uncontrolled real-world behavior rather than scripted task behavior.
- Diary studies are longitudinal and limited to data participants can easily self-record.
- Usability and field studies are flexible across attitudinal and behavioral; behavioral framings are usually more reliable.
- **Headline recommendation:** triangulate. Mix methods from different quadrants. Qualitative reveals what to measure; quantitative confirms scale.

## Meta Research — Comparing UX Research Methods (John Hu et al.)
- URL: https://medium.com/meta-research/comparing-ux-research-methods-d315050b1698
- Published Dec 2021. Contributors: Donna Tedesco, Kathleen Stanko, Alex McEvoy, Kevin Smith.
- A matrix built for Facebook UX researchers summarizing strengths, weaknesses, and misconceptions per method.
- Designed for newer-to-qualitative audiences: research interns, junior researchers, quant researchers expanding into qual, and research partners (designers, content strategists, PMs, data scientists, engineers, design/research program managers).
- Frames method choice as a core researcher skill that hiring teams screen for.
- Uses the same two foundational axes as NN/g (qual vs. quant, attitudinal vs. behavioral) applied to Meta's most-used methods.
- Methods covered: in-depth interviews, surveys, diary studies, usability evaluations, concept testing, participatory design, focus groups, ethnographic/field research.
- Each method entry highlights: best-fit research questions, output type, sample-size guidance, pitfalls (e.g., treating surveys as a substitute for interviews; over-generalizing from small qual samples), and misconceptions that lead to misuse.
- Heavy emphasis on mixed-methods.
- Positions interviewing as the workhorse for "why" behind behavior; surveys as the scale instrument for prevalence; diary studies for longitudinal/contextual behavior; concept testing as formative validation before build.

## "Getting Started in User Experience and Design Research" (Medium publication)
- URL: https://medium.com/getting-started-in-user-experience-and-design
- A Medium publication (aggregation, not a single article) curated by Laith Ulaby and Grace Vorreuter.
- A starter library aggregating beginner-friendly UXR/design research essays from many practitioner contributors.
- Covers foundations, qualitative methods, getting your first role, breaking into the field, portfolio building, stakeholders, project case studies.
- Many of the practical guides cited elsewhere in this KB (note-taking, research plans, interview analysis) actually live inside this publication.

## Working method matrix

| Method | Best for | Sample size | Time | Plugin skill |
|---|---|---|---|---|
| User interviews | Needs, motivations, mental models | 5–8 | 2–4 weeks | `conduct-interviews` |
| Usability testing (moderated) | Evaluating a flow/prototype | 5–8 | 1–2 weeks | `usability-testing` |
| Usability testing (unmoderated) | Breadth on a flow | 15–30 | 1 week | `usability-testing` |
| Surveys | Quantifying attitudes / prevalence | 100+ | 1–2 weeks | `design-survey` |
| Card sorting / tree testing | Information architecture | 15–30 | 1 week | `plan-research-study` |
| Diary studies | Behaviour & context over time | 10–15 | 2–8 weeks | `diary-studies` |
| A/B testing | Comparing variants in production | Power-dependent | 1–4 weeks | `quant-ux-research` |
| Concept testing | Validating a direction | 5–8 (qual) or 100+ (quant) | 1–2 weeks | `plan-research-study` |
| Field study / ethnography | Context in situ | 5–10 | 2–6 weeks | `plan-research-study` |
| Benchmark study | Tracking UX over time | 30+ per wave | Recurring | `quant-ux-research` |
| Eye tracking | Attention measurement | 30+ for stats | 1–2 weeks | `quant-ux-research` |
| Clickstream / analytics | Real-world uncontrolled behavior | Whole population | Ongoing | `quant-ux-research` |

## Tool lists referenced in the source guide

The doc says "check out lists of tools here and here." The two canonical curated lists (best-fit matches):

### User Interviews — UX Research Tools Map
- URL: https://www.userinterviews.com/ux-research-tools-map
- Plots ~800 tools by core use case across the research lifecycle (ideation through post-launch).
- Regions: project/research-ops management, participant recruiting, moderated research, unmoderated testing, surveys, analytics, continuous data collection, research repositories, analysis/synthesis.
- Annual edition with 2026 update adding AI tools and emerging categories.
- Companion: https://www.userinterviews.com/blog/ux-research-tools-map-methodology-and-history documents curation methodology.

### TOOOLS.design — UX Research category
- URL: https://www.toools.design/best-ux-tools  (and https://www.toools.design/for/ux-designers)
- Curated by manual review; only tools actively used in real UX workflows.
- Subcategories: research repositories and synthesis, user testing and feedback, collaborative workshops/whiteboards, surveys, all-in-one research platforms.

Alternates (if the doc links elsewhere): Airtable Universe "User research tool box," UX Tools' "17 Tools That Will Streamline Your UX Research," Maze's "19 Best UX Research Tools."
