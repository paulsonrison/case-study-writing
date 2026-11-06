# Case Study Writing

A standalone AI-agent skill and plugin for customer stories, portfolio case
studies and sales one-pagers grounded in actual project evidence.

Uses Situation, Task, Action and Result to explain the customer's problem,
the work performed and the supported outcome. Qualitative outcomes are valid:
the skill never requires invented metrics, quotations, customer names or approval.
It adapts to short drafts and respects local-only tools.

## Install in Codex

```sh
codex plugin marketplace add paulsonrison/case-study-writing
codex plugin add case-study-writing@case-study-writing-marketplace
```

Use `$case-study-writing` with your project notes.

## Install in Claude Code

```text
/plugin marketplace add paulsonrison/case-study-writing
/plugin install case-study-writing@case-study-writing-marketplace
```

Use `/case-study-writing:case-study-writing`.

## Other agents

Copy the complete `skills/case-study-writing/` folder to the host's supported
skills directory. No paid service, CLI account, API key or other plugin is required.
PDF, Word and slide files use the host's available artifact tools; no document
engine is bundled. Installation availability depends on the host.

## Example

```text
Use case-study-writing to turn these project notes into a short customer story.
Use only the facts I supplied. Ask about missing measurements and quote approval;
do not invent them. Show a review draft before any publication.
```

This is an original standalone skill, not a redistributed copy of the installed
third-party inference.sh/Belt skill. Drafting does not authorise external uploads
or publication of customer material.

## Validate

```sh
python tools/check_package.py
```

MIT licensed. This repository and its release ZIP contain only Case Study Writing.
Companion plugins are released independently:
[Notebook Forge](https://github.com/paulsonrison/notebook-forge),
[Resume Optimizer](https://github.com/paulsonrison/resume-optimizer),
[Ooh Shiny](https://github.com/paulsonrison/ooh-shiny).
