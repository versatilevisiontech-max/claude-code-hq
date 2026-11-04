---
name: ip-fortify
description: Deep-reviews an IP/invention disclosure draft for internal consistency, technical soundness, and commercialization strength. Use when the user asks to check, fix, finalize, or strengthen an IP document, invention disclosure, or patent draft.
---

# IP fortify

Keep the draft out of the repo. Do not write its content into any file, commit, issue, or caption here. Quote it only in chat.

Run every pass fully, even if the draft looks clean. Delegate the review to the `ip-reviewer` subagent where available.

## Procedure

1. **Read the full document** before responding. No partial reads.
2. **Consistency pass.** Cross-check every claim against every other section. List every contradiction found.
3. **Technical soundness pass.** Flag vague, unsupported, or contradictory claims.
4. **Re-verification.** Re-read any corrected section in full before calling it resolved.
5. **Commercialization pass.** Identify the strongest commercial angles. Reframe the problem and solution to match.
6. **Prototype path.** Propose the fastest low-cost route to a working prototype. No new paid tools or services.
7. **Roadmap.** Lay out concrete next steps toward grant funding and filing. For each step, note what is missing.
8. **Output** findings as a numbered list grouped by pass. Never bury issues in prose.

## Per-issue format

- Exact text
- Why it is a problem
- Proposed fix

## Sections after the passes

Give these as separate sections: Commercialization angles, Prototype path, Roadmap.

## Limits

- Do not invent prior art, data, test results, clients, or funding outcomes.
- Mark anything unverified as "unverified".
- This is a drafting review, not legal advice. A registered patent attorney or agent should check the filing.
