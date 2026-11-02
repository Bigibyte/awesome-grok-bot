<a id="top"></a>
# Routines

> [!TIP]
> If this guide helps you, please give it a [star](https://github.com/bigibyte/awesome-grok-bot) so more people can find it.

<p align="center">
  <img src="https://pub-84e44a6cb4244c4c83fe8c430a1dae49.r2.dev/awesome-grok-bot-v3-sec-routines.png" alt="Routines" width="100%">
</p>

Routines run skills (or instructions) on a **schedule** or when an **event** fires. Source: [skills and routines](https://docs.x.ai/grok-bot/skills-routines-and-automations).

```mermaid
flowchart TD
  T[Trigger: schedule or event] --> R[Routine]
  R --> S[Skill / instructions]
  S --> D[Draft deliverable]
  D --> A{Approval?}
  A -->|Yes| You[You review]
  A -->|Safe draft path| Save[Page / file]
  You --> Save
```

## Common trigger types

Official and community docs mention schedules plus events such as Slack messages, GitHub activity, email, and webhooks. Always confirm the exact list in your app, since trigger catalogs can grow.

## Safe routine checklist

- [ ] Start with **draft only** outputs
- [ ] Keep approvals on for send / post / buy / delete
- [ ] Name routines after the outcome
- [ ] Test once manually before you trust the schedule

<details>
<summary><strong>Example: Monday research digest</strong></summary>

<br>

- Trigger: every Monday 09:00 your local time
- Skill: competitor brief
- Deliverable: Page + Slack draft
- Stop: do not post the Slack message until approved

</details>

<details>
<summary><strong>Example: Inbox triage</strong></summary>

<br>

- Trigger: new email (if available) or hourly check
- Skill: triage labels + draft replies
- Stop: never send

</details>

More recipes: [use-case-recipes.md](use-case-recipes.md).

---

| | | |
|:---|:---:|---:|
| ← [Skills](skills.md) | [README](../README.md) · [Back to top](#top) | [Workflows](workflows.md) → |

> [!TIP]
> If this guide helps you, please give it a [star](https://github.com/bigibyte/awesome-grok-bot) so more people can find it.

<p align="center"><a href="https://github.com/bigibyte">https://github.com/bigibyte</a></p>

<p align="center"><em>If this saved you time, a star helps others find it.</em></p>
