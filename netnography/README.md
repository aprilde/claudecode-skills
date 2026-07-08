# Netnographer

A Claude skill that runs a structured **netnographic study** the ethnographic study of online communities and digital culture, following Robert Kozinets's five-phase framework.

Claude acts as your **research collaborator, not an autonomous researcher.** You're the principal investigator; Claude does the legwork (finding communities, reading threads, coding data, drafting the report) but stops at every phase boundary and waits for your explicit go-ahead before continuing.

## What it does

Walks a research question from a vague topic to a finished, evidence-grounded findings report across five phases:

| Phase | Name | What happens |
|-------|------|--------------|
| 0 | **Setup & calibration** | Establishes your topic, research experience, and purpose; adapts how much it explains |
| 1 | **Entrée** | Sharpens the research question and shortlists real, public field sites |
| 2 | **Data collection** | Reads real posts/threads and builds a traceable data log |
| 3 | **Analysis & interpretation** | Codes the data into themes with cultural lenses |
| 4 | **Ethical standards audit** | A dedicated pass on privacy, consent, anonymization, and harm |
| 5 | **Representation** | Produces a structured markdown findings report |

## Design principles

- **Human-in-the-loop.** No phase advances without your sign-off. Revise, redo, skip, or reorder any phase, it's your study.
- **Expertise-adaptive.** Tell it whether you're an experienced qualitative researcher or new to formal research, and it calibrates its terminology and scaffolding accordingly.
- **Evidence-grounded, no fabricated data.** Every claim in the final report traces to a real post or thread Claude actually read, logged with a source and excerpt. If it can't access live data, it says so rather than inventing example posts.
- **Ethics woven throughout.** Public vs. private spaces, disclosure, consent, anonymization, and minimizing harm are flagged as they arise, not just at the end, plus a dedicated audit before write-up.

## Requirements

- Web search / fetch tools enabled (needed to collect real data in Phase 2).

## Usage

Invoke with a topic to start:

```
/netnography 
```

Or with no argument, and Claude will ask what you want to research.

## Example research questions this fits

- How do a game's players talk about a controversial update, and what does it reveal about what they value?
- What cultural meanings does a hobbyist community attach to "doing it the hard way" vs. shortcuts?
- How does a product's subreddit narrate the brand, as advocates, critics, or something more complicated?

## A note on scope

This skill is built for **publicly readable** online spaces. It will not join closed groups under false pretenses, access gated content, or study vulnerable-population spaces without flagging the need for extra care (and, for academic work, likely IRB review). If you're doing formal academic research, treat its ethics audit as a starting point, not a substitute for your institution's review process.
