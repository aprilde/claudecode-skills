# claudecode-skills

A collection of Claude skills I've built and want to share: reusable, structured workflows that give Claude a repeatable methodology for a specific kind of task.

Each skill lives in its own folder, with a `SKILL.md` (the skill itself) and a `README.md` explaining what it does and how to use it.

## What's a skill?

A skill is a self-contained set of instructions that Claude loads when it's relevant to what you're doing. Instead of re-explaining a whole methodology every time, you package it once — the domain knowledge, the process, the guardrails and Claude follows it consistently. Think of it as the difference between giving someone ad-hoc directions each time and handing them a well-written playbook.

## Skills in this repo

| Skill | What it does |
|-------|--------------|
| [**netnography**](./netnography) | Runs a guided netnographic study of an online community, from research question to an evidence-grounded findings report, following Kozinets's five-phase framework, with a human checkpoint at every phase. |

## Using a skill

1. Open the skill's folder and read its `README.md` for what it does, requirements, and usage.
2. Add the `SKILL.md` to your Claude setup however your environment loads skills.
3. Invoke it as described in that skill's README.

## Repo structure

​```
claudecode-skills/
├── README.md              ← you are here
└── netnography/
    ├── SKILL.md           ← the skill
    └── README.md          ← writeup & usage
​```
