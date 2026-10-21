# Content, Copy & PR — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **content, copy and PR** skills for **Claude, Claude Code, OpenAI Codex** and any agent that
reads the [Agent Skills](https://agentskills.io/specification) format. Content strategy, brand voice, copywriting,
editing, editorial operations, newsletters, original research, thought leadership and digital PR — including
cleaning up AI-sounding writing. Each skill is a single `SKILL.md`: a senior practitioner's workflow — when to use
it, the inputs to ask for, a numbered process, decision rules, an output template and sources — loaded only when a
task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/content-copy-pr/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/content-copy-pr-skills.git
cp -r content-copy-pr-skills/content-marketing-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r content-copy-pr-skills/content-marketing-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/content-copy-pr/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`content-marketing-audit`](content-marketing-audit/SKILL.md) | Audit a content and PR programme end to end, with keep/update/combine/retire decisions. The entry point. |
| [`content-strategy`](content-strategy/SKILL.md) | Build a content strategy connecting every piece to an audience need and a business goal. |
| [`editorial-operations`](editorial-operations/SKILL.md) | Set up editorial operations that publish on schedule: workflow, briefs, calendar, AI policy. |
| [`brand-voice-guide`](brand-voice-guide/SKILL.md) | Create and maintain brand voice and style guides, with an AI instruction block. |
| [`marketing-copywriting`](marketing-copywriting/SKILL.md) | Write marketing copy across channels: briefs, frameworks, headlines, CTAs. |
| [`editing-proofreading`](editing-proofreading/SKILL.md) | Edit content in layers from structure to typos, with a fact-check log. |
| [`ai-writing-cleanup`](ai-writing-cleanup/SKILL.md) | Audit and rewrite drafts that sound machine-made, restoring a specific human voice. |
| [`newsletter-strategy`](newsletter-strategy/SKILL.md) | Plan newsletters readers look forward to: promise, format, growth, deliverability. |
| [`original-research-reports`](original-research-reports/SKILL.md) | Plan, run and publish original research that earns coverage and links. |
| [`thought-leadership`](thought-leadership/SKILL.md) | Build thought leadership that changes how audiences think, ghostwritten in the expert's voice. |
| [`digital-pr`](digital-pr/SKILL.md) | Plan and run digital PR that earns coverage and links: angles, pitches, media lists. |
| [`content-repurposing`](content-repurposing/SKILL.md) | Turn one strong piece into many: pillar assets mapped to channel-native derivatives. |
| [`content-pr-measurement`](content-pr-measurement/SKILL.md) | Measure content and PR against business goals, with honest attribution and coverage scoring. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: content marketing skills, copywriting, digital PR, SKILL.md, Agent Skills, Claude skills, Claude Code
skills, Codex skills, AI agent skills, brand voice, editorial operations, newsletter strategy, original research,
thought leadership, AI writing cleanup, content measurement.</sub>
