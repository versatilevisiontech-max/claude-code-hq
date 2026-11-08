---
name: ip-reverse-engineering
description: Use when the owner is stuck on a software part of their IP and wants to reverse engineer a tool, app, or binary (for example with REA). Sets legal and confidentiality guardrails. Contains no IP.
---

# IP reverse engineering

Scope: software only. Physical, materials, and façade IP cannot be reverse engineered with REA. For those, say so and suggest literature, supplier datasheets, or lab testing instead.

Run `public-safety` first. This skill adds to it.

## Before any analysis

1. Target check. Proceed only if the target is one of:
   - the owner's own code
   - open source, with its licence read
   - software the owner is licensed to inspect, where the EULA allows it
2. If the target is a competitor's product, stop. Say it needs the patent attorney's approval first. Do not proceed on the owner's say-so alone.
3. Goal check. State the one question being answered, for example "how does X handle Y". No broad "copy this feature" runs.

## Clean-room method

1. Analysis session: study the target and write a plain-language behavior description. No code, no copied structures, no identifiers.
2. Build session: a fresh session works from the description alone and never sees the target.
3. Keep both records so independent creation can be shown later.

## Confidentiality

- Unfiled inventions, designs, and formulas never go into prompts, repos, issues, commits, or captions. Describe the problem generically instead.
- Keep REA output and notes in a private local folder, never in this repo.
- REA runs locally, but the agent driving it is a cloud model. Treat anything typed to the agent as disclosed.
- Do not install REA or any tool from a session without the owner's explicit yes.

## Reply format

Short. Give: target allowed or not, the one question, and the next step. Add "not legal advice; confirm with your patent attorney" when a competitor product is involved.
