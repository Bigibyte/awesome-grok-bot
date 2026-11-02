<a id="top"></a>
# Limits and what it cannot do

> [!TIP]
> If this guide helps you, please give it a [star](https://github.com/bigibyte/awesome-grok-bot) so more people can find it.

Verified constraints only. Sources linked. No invented quotas.

## Product boundaries

| Limit | Detail | Source |
|-------|--------|--------|
| Not Grok chat | Different app and sign-in story | [FAQ](https://docs.x.ai/grok-bot/faq) |
| No model picker | You cannot choose the underlying model | [FAQ](https://docs.x.ai/grok-bot/faq) |
| Shared computer | All your Bots share one cloud PC (files, sessions, logins) | [computer and apps](https://docs.x.ai/grok-bot/computer-and-apps) |
| Sites can block automation | Captchas, expired sessions, human-only steps get handed to you | [overview FAQ](https://docs.x.ai/grok-bot/overview) |
| Voice chat limits | One voice chat at a time; not in group chats; no keybinding to start | [chat and collaboration](https://docs.x.ai/grok-bot/chat-and-collaboration) |
| Group chat limits | 2 to 6 Bots; approvals, secret, login, and email/Slack drafts do not appear in the group UI | [chat and collaboration](https://docs.x.ai/grok-bot/chat-and-collaboration) |
| Pages rollout | Desktop 0.60.0+ / phone 1.14.0+; not on Enterprise yet | [files and results](https://docs.x.ai/grok-bot/files-and-results) |
| Attachment caps | Desktop: 20 attachments/message; images 25 MB each (200 MB total); docs/audio 250 MB; video 1 GB | [files and results](https://docs.x.ai/grok-bot/files-and-results) |
| Teach a task length | Browser workflow recording up to 10 minutes (skills docs) | [skills and routines](https://docs.x.ai/grok-bot/skills-routines-and-automations) |
| @bot on X | Needs connected X account; not every region | [overview](https://docs.x.ai/grok-bot/overview) |
| Pricing / usage | Weekly usage pools and plan matrix live on official pages; this repo does not invent numbers | [overview](https://docs.x.ai/grok-bot/overview), [x.ai/bot](https://x.ai/bot) |

## What you should not expect

- Perfect isolation of secrets between your own Bots (they share a computer)
- Silent calendar writes or silent sends when drafts/approvals are on (by design)
- A guarantee that every website works under computer use
- This community list to be official product support

> [!IMPORTANT]
> Approvals do not undo work already completed. Design routines as draft-first. Source: [approvals docs](https://docs.x.ai/grok-bot/approvals-security-and-privacy).

---

| | | |
|:---|:---:|---:|
| ← [Feature examples](feature-examples.md) | [README](../README.md) · [Back to top](#top) | [Bots and teammates](bots-and-teammates.md) → |

> [!TIP]
> If this guide helps you, please give it a [star](https://github.com/bigibyte/awesome-grok-bot) so more people can find it.

<p align="center"><a href="https://github.com/bigibyte">https://github.com/bigibyte</a></p>

<p align="center"><em>If this saved you time, a star helps others find it.</em></p>
