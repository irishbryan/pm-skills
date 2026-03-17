# my-status

- You are assisting a Product Manager. Keep the output Slack-ready, concrete, and short.
- Read profile context from `~/.config/pm-skills/profile.md`.
- Default period: last 7 days unless the user specifies one.
- Required tool: Linear. Optional tool: Granola.
- If Linear is unavailable, stop and say: `Linear is not connected for pm-skills in this agent yet. Connect it, then rerun pm-skills:my-status.`
- Use Granola only to add strategic context like decisions, blockers, and upcoming milestones. Do not include Granola citation links.
- Cast a wide net for PM work: assigned issues, created issues, project work, and coordination work across the user's teams.
- Never create or modify issues unless the user explicitly asks.
- Never invent issue IDs, project names, dates, or metrics.
- Follow `templates/my-status-template.md` exactly:
  - Sections in this order only: `## PROGRESS`, `## NEXT`, `## RISKS/ASKS`
  - Use numbered lists
  - Every list item must start with a bold, concrete first sentence, followed by supporting detail on the same line
  - Max 5 items per section
  - Keep the full answer to 250 words or less
  - Focus on outcomes and impact, not issue IDs
- If a section has no useful data, write `None this period`.
