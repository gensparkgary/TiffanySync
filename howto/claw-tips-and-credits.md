# Genspark Claw — Saving Credits, Memory, and Security

> For Buddy Agent internal use.
> type: howto | feature: genspark-claw | keywords: credit, save money, save, Model Optimizer, Heartbeat, memory, prompt injection, security, least privilege, backup, sub-agent
> User loop: understand what spends credits → use the right strategy → safely let Claw run on its own

## Why read this

- **Claw spends money in the background**: Heartbeat and scheduled tasks consume credits even when you're not using them — without understanding the rules, it's easy to overspend
- **Understand the risks before automating hands-off**: Claw can act on your behalf, so prompt injection and high-risk operations require you to set up defenses in advance

## What consumes credits

Credits are the fuel for AI work, shared across your entire Genspark account. They're consumed when:
- Every conversation message and tool call
- Every scheduled task run and every Heartbeat check
- Setup tasks for connecting channels/services
- Media tasks like image generation, video generation, etc.

**Does NOT consume credits**: management actions like switching models or enabling/disabling tasks; **idle cloud computers** (the subscription is a fixed monthly fee, separate from credits).

## Keys to saving credits

| Tip | How to do it |
|------|--------|
| **Match the model to the task** | Use a powerful model for complex/high-risk work, switch to a lightweight model for everyday tasks (Home → Computer Information → Switch Model, history is preserved) |
| **Use Model Optimizer for scheduled tasks** | When you have ≥2 tasks, click the banner at the top of Schedules → Try it to automatically assign the most economical model to each task |
| **Offload with sub-agents** | For complex tasks, let Claw delegate the simple parts (scraping, formatting, summarizing) to lightweight sub-agents, while the main session uses a powerful model |
| **Plan before executing** | Before a complex task, say "list your plan first" to catch wrong directions early and avoid spending credits down the wrong path |
| **Turn repeat tasks into Skills** | Save things you do repeatedly as a Skill to skip back-and-forth confirmations — saves credits and gives more consistent results |
| **Frequency is a multiplier** | A task costing 10 credits a day is about 300 a month; running it hourly is about 7,200. First ask "what's the lowest useful frequency" |
| **Audit high consumption** | When credits spike, check: are scheduled tasks too frequent? Is Heartbeat needed? Are DMs mistakenly set to open (so others are commanding it)? |
| **Diagnose before retrying** | When Claw isn't responding, run Diagnose first (it runs on the cloud computer and can auto-fix most issues) — blindly retrying wastes credits |
| **Keep sessions focused** | Start a new session for unrelated tasks; be specific ("summarize today's top 3 AI news" is far cheaper than "what's happening in AI") |

## Schedules vs Heartbeat — which to choose

| Dimension | Schedules (scheduled tasks) | Heartbeat (heartbeat monitoring) |
|------|---------------------|---------------------|
| Best for | A clear "what + when + what to deliver" | Continuously watching, acting when it spots something that needs handling |
| Example | "Send the sales weekly report every Monday at 9 AM" | "Keep an eye on my inbox and notify me of urgent emails" |
| Credit | Predictable (frequency × cost per run) | Unpredictable (depends on monitoring frequency and what it finds) |
| Recommendation | Prefer this — consumption is controllable | Only enable when you truly need real-time monitoring |

## Memory usage tips

- **Explicitly say "remember" for important things**: things mentioned in passing aren't guaranteed to be remembered, especially across sessions or after long conversations
- **Group chats and DMs are separate**: what you tell Claw in a DM stays in that session, and Claw in a group can't see your DMs. For anything both sides need to know, explicitly save it to memory
- **Passively absorb emails**: add Claw's email to the CC/BCC of your work emails, and Claw silently accumulates context — so it already has the background when you later write follow-ups or prepare for meetings

## Security best practices

Claw can act on your behalf, so set up defenses before going hands-off:

- **Limit the workspace in local mode**: the desktop app's local mode can access your file system. First set a workspace folder in the input bar to narrow the scope (a soft guide, not a hard boundary), and back up important files before file-related tasks
- **Beware of prompt injection**: when Claw browses the web, reads emails, or processes documents, those may hide malicious instructions trying to change its behavior. To reduce risk: don't let Claw run automated tasks on untrusted sources; be cautious about letting it handle emails/files from unknown senders; review its planned actions in uncontrolled environments
- **Principle of least privilege**: only connect the services a task truly needs. A Claw that mainly does research and scheduling doesn't need access to financial accounts — limiting what it can reach limits the potential damage if it's manipulated
- **Confirm high-risk actions first**: for hard-to-undo operations like sending bulk emails, posting to social media, deleting files, or executing financial transactions, have Claw show you its plan before acting. This matters especially for unattended scheduled tasks

## FAQ

**Q: How do I stop Claw from spending money in the background?**
Schedules tab → turn off Heartbeat + pause/disable scheduled tasks you don't need. **Don't delete the cloud computer** — deleting permanently wipes the data. Pausing tasks is enough to stop background consumption.

**Q: Is deleting the cloud computer the right way to cut my losses?**
Deleting does stop everything, but it also permanently wipes conversation history, memory, files, and credentials, with no way to recover. The safer approach is to turn off Heartbeat + disable scheduled tasks. Only delete if you've fully canceled and already backed up.

**Q: What if Claw makes a mistake while running automatically?**
Claw is designed to retain human oversight: external actions like sending emails or messages require permission. When first setting up automation, start with read-only/low-risk tasks, then expand once you've built confidence.

## Next steps

- [Set up scheduled tasks →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-schedules.md)
- [Manage the cloud computer (including Diagnose) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-manage.md)
- [What Claw is / billing concepts →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-overview.md)
