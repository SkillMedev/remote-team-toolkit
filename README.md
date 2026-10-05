# Remote Team Toolkit

**For remote managers: keep the team aligned async, without back-to-back meetings.** — built in-house by [Skill&nbsp;Me](https://skillme.dev/?utm_source=github&utm_medium=readme&utm_campaign=pack-remote-team-toolkit).

Reach for this when your remote team is drowning in status meetings and threads. It turns meetings into tracked actions, writes the async updates and stakeholder notes that replace standups, structures 1:1s, and helps you deliver feedback that lands - so alignment happens in writing, on everyone's own clock, and your calendar opens back up.

## Install

- **Claude, ChatGPT, Codex, Cursor (connector):** [install the whole pack from skillme.dev](https://skillme.dev/pack/remote-team-toolkit?utm_source=github&utm_medium=readme&utm_campaign=pack-remote-team-toolkit) — one connection, then ask for any skill by name.
- **As files for Codex, Cursor, or Claude Code:** `npx @skillme/cli add meeting-notes-to-actions weekly-review okr-builder feedback-writer stakeholder-update async-communication 1on1-agenda --target all`
- **With the skills CLI:** `npx skills add SkillMedev/remote-team-toolkit`
- **Manually:** copy any `skills/<slug>/SKILL.md` into `.agents/skills/`, `.cursor/skills/`, or `.claude/skills/`.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Skills in this pack

- **[Meeting Notes → Actions](skills/meeting-notes-to-actions/SKILL.md)** — Converts raw meeting notes or transcripts into a four-part record - a 3-5 sentence summary, the decisions actually made, an action table with owner, verb-phrased action, due date, and status, and the open questions - without inventing owners, dates, or tasks.
- **[Weekly Review](skills/weekly-review/SKILL.md)** — Runs a timeboxed weekly review - empty every inbox to a decision, audit every open commitment, and pick the 3-5 outcomes that define next week.
- **[OKR Builder](skills/okr-builder/SKILL.md)** — Drafts a quarter's OKRs - an inspiring qualitative objective with 3-5 measurable key results, each with a baseline, target, and owner - plus the weekly confidence check-in and end-of-quarter grading cadence.
- **[Feedback Writer](skills/feedback-writer/SKILL.md)** — Drafts specific, observable, kind workplace feedback using the SBI model - Situation, Behavior, Impact - for both praise and correction.
- **[Stakeholder Update](skills/stakeholder-update/SKILL.md)** — Writes project stakeholder updates readable in under 60 seconds - honest RAG status, decisions made, explicit asks with owners and dates, next milestones - tiered to the audience.
- **[Async Communication](skills/async-communication/SKILL.md)** — Converts sync meetings and vague pings into structured asynchronous messages - TL;DR up front, an explicit ask with owner and deadline, and a default-action line that keeps work moving if nobody replies - plus team response norms per channel.
- **[1:1 Agenda](skills/1on1-agenda/SKILL.md)** — Structures recurring manager-report 1:1s with a rolling shared agenda that balances check-in, blockers, two-way feedback, and career growth instead of status updates.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev/browse?utm_source=github&utm_medium=readme&utm_campaign=pack-remote-team-toolkit).
