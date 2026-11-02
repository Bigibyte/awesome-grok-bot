<a id="top"></a>
# Prompt library (by role)

> [!TIP]
> If this guide helps you, please give it a [star](https://github.com/bigibyte/awesome-grok-bot) so more people can find it.

Copy, tweak, send. Every example ends with a stop rule.

## Quick pick

| Role | Jump |
|------|------|
| Anyone | [Universal](#universal-five-part) |
| Sales | [Sales](#sales) |
| Recruiting | [Recruiting](#recruiting) |
| Marketing | [Marketing](#marketing) |
| Ops / finance | [Ops](#ops--finance) |
| Eng / product | [Eng](#eng--product) |
| Founder / CoS | [Founder](#founder--chief-of-staff) |
| Skills / memory | [Meta](#skills--memory) |

### Universal five-part

```
Outcome: ...
Sources: ...
Constraints: never send / post / buy / delete without approval
Deliverable: Page | file | draft
Stop: ask before anything external
```

### Sales

<details open>
<summary><strong>Account brief</strong></summary>

<br>

```
Build an account brief for <company>.
Include: what they sell, recent news, pain hypotheses for <offer>, public stakeholder titles.
Deliverable: Page + optional email draft.
Stop: do not contact anyone.
```

</details>

### Recruiting

<details>
<summary><strong>Shortlist</strong></summary>

<br>

```
From this role brief and attached list, rank candidates.
Deliverable: table + outreach drafts.
Stop: do not message candidates.
```

</details>

### Marketing

<details>
<summary><strong>Spend review</strong></summary>

<br>

```
Summarize campaign numbers from <sheet or export>.
Draft a Slack update.
Stop: do not change budgets.
```

</details>

### Ops / finance

<details>
<summary><strong>Expense digest</strong></summary>

<br>

```
Summarize expenses for <range>. Flag missing receipts and duplicates.
Deliverable: table + note for finance.
Stop: do not submit or approve.
```

</details>

### Eng / product

<details>
<summary><strong>Bug repro pack</strong></summary>

<br>

```
From this bug report: <paste>.
Deliverable: steps, expected vs actual, severity suggestion, notes/screenshots.
Stop: do not change production.
```

</details>

### Founder / chief of staff

<details>
<summary><strong>Daily digest</strong></summary>

<br>

```
Build today's digest for priorities: <3 items>.
Sources: calendar if connected, named Slack channels, open tasks file.
Deliverable: Page with must-do, waiting-on, risks.
Stop: do not message anyone for me.
```

</details>

<details>
<summary><strong>Inbox triage</strong></summary>

<br>

```
Classify new mail into DECISION, FACT, AWARE, GONE.
Draft only for FACT. Never send.
Digest DECISION first.
```

</details>

### Skills / memory

<details>
<summary><strong>Teach into a skill</strong></summary>

<br>

```
Watch me do this browser task once (Teach a task).
Turn it into skill <name>. Confirm steps before saving.
Never include passwords in the skill text.
```

</details>

<details>
<summary><strong>Fix memory</strong></summary>

<br>

```
Forget the old rule about <X>.
Remember instead: <new rule>.
Repeat the full job in 5 bullets.
```

</details>

---

| | | |
|:---|:---:|---:|
| ← [Keyboard shortcuts](keyboard-shortcuts.md) | [README](../README.md) · [Back to top](#top) | [Prompting tips](prompting-tips.md) → |

> [!TIP]
> If this guide helps you, please give it a [star](https://github.com/bigibyte/awesome-grok-bot) so more people can find it.

<p align="center"><a href="https://github.com/bigibyte">https://github.com/bigibyte</a></p>

<p align="center"><em>If this saved you time, a star helps others find it.</em></p>
