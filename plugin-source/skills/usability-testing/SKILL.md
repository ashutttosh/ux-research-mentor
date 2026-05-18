---
name: usability-testing
description: Plan and run moderated or unmoderated usability tests — test plans, task scripts, success criteria, and severity scoring for issues found. Triggers on "usability test", "user test", "moderated test", "unmoderated test", "task script", "usability issues", "task success", or when the user wants to evaluate an existing design or prototype against real users.
---

# Run a usability test

Help the user evaluate a design with real users, then turn the findings into a clear set of fixes.

## Process

1. **Pin the design and the questions.** What flow, screen, or prototype is being tested? What 3–5 things must it do for users?
2. **Pick the format.** Moderated (5–8 users, deep insight, ~1 hr each) vs. unmoderated (15–30 users, breadth, shorter tasks). Lab vs. remote.
3. **Write the test plan.** Use the structure below.
4. **Write the task script.** Realistic scenarios, not feature lists.
5. **Run the sessions.** Observe, don't help. Capture task success, time, errors, and verbatims.
6. **Score and prioritise** issues by severity × frequency. Hand to `analyze-research` for synthesis.

## Test plan template

```
Design under test: (link / version)
Test type: moderated / unmoderated, remote / in-person
Research questions (3–5):
Tasks (3–6, each with success criteria):
Participants:
  - n:
  - Criteria:
  - Recruit source:
Metrics: task success, time on task, error count, SEQ / SUS
Risks: (e.g., prototype limitations, hardware)
Schedule: (recruit → pilot → sessions → readout)
```

## Task script — good vs. bad

| Good | Bad |
|---|---|
| "You're trying to send $500 to a friend who just paid for dinner. Show me how you'd do that." | "Use the payment feature to transfer money." |
| "It's Friday night and you want to find a romcom under 90 minutes. Find one." | "Open the filter menu." |
| Open-ended; the user infers the path. | Names the UI; tells them what to click. |

## Severity scoring (NN/g-style)

| Score | Definition |
|---|---|
| 0 | Not a usability problem |
| 1 | Cosmetic — fix if time |
| 2 | Minor — low priority |
| 3 | Major — high priority |
| 4 | Catastrophic — must fix before release |

Combine with frequency (how many of n users hit the issue) to triage.

## Knowledge base used

- `references/books.md` — *Don't Make Me Think* (Krug), *Moderator's Survival Guide* (Tedesco), *Measuring the User Experience* (Tullis & Albert), *Think Like a UX Researcher* (Travis)
- `references/practical-guides-and-templates.md` — research plan template
- `references/methods-overview.md` — usability testing method card
