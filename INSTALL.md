# Install map

These five repos are the ones that matter for Claude Code. Use them upstream. Do not fork them into this account — forks go stale and are not your work.

| Repo | Why it is here | Add it |
|------|----------------|--------|
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | The tool itself | Install from their README |
| [anthropics/skills](https://github.com/anthropics/skills) | Official skills: docs, frontend, web testing | `/plugin marketplace add anthropics/skills` then `/plugin install example-skills@anthropic-agent-skills` |
| [obra/superpowers](https://github.com/obra/superpowers) | Plan, test, and review before coding | `/plugin install superpowers@claude-plugins-official` |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | React, Next, and web quality | `npx skills add vercel-labs/agent-skills -a claude-code` |
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | Directory. Browse it. Do not install everything | Read only |

Commands were checked on 19 Oct 2026. If one fails, open that repo's README — plugin names move.

## Copy this repo onto the machine

```bash
mkdir -p ~/.claude
cp CLAUDE.md ~/.claude/CLAUDE.md
cp -R .claude/skills ~/.claude/skills
```

Review `.claude/settings.json` before copying it to `~/.claude/settings.json`.

## What not to add

Random skill packs from social posts. One bad skill can tell Claude to ignore the public-safety rule. Add a skill only if you can read its `SKILL.md` first.
