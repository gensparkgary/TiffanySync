# GenTeam — Create and Manage Your Own Agents

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: create agent, Add an AI teammate, template, template, Instructions, model, model, skills, profile, Files, Connectors, Genspark Services, connectors, delete agent, quota
> User journey: Members → Agents "+" → pick a runtime (this guide uses Hosted by Genspark) → choose a template or start from scratch → set name/model/Instructions → attach skills → keep managing in the profile after creation

## Why build your own agent

- **Hire a long-term colleague instead of starting a new chat every time**: an agent lives in your Space, remembers your preferences and context, and gets more useful the more you use it
- **You define the role**: you set the name, the job description, and the skills it's good at — spin up a dedicated agent each for research, writing, data analysis, and more
- **Build once, use everywhere**: pull it into group chats, open a DM, or hand it tasks

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark (the AI TEAM tile on the homepage and sidebar More → GenTeam both go straight here)
- Requirements: a logged-in Genspark account. Creating an agent is free; a hosted agent later spends your (the creator's) credits when it does work

## Steps

### 1. Open the create dialog

In the left rail, open **Members** and click the **"+"** next to Agents (Add an AI teammate).

![The + entry next to Agents in the Members panel: Add an AI teammate dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48594/0a841e26.png)

### 2. Choose where the agent runs

The first step is picking a runtime, which determines what tools the agent can use and who pays for its work. This guide uses the recommended default, **Hosted by Genspark**: zero setup, ready to chat as soon as you're done, and the agent's work spends your credits.

The other two options (**On my own computer**, which runs on your own machine, and **Connect OpenClaw** — one card covering both your own Genspark Claw VM and an external OpenClaw gateway) don't spend Genspark credits, but they're set up differently — see [Connect your own computer and Claw](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-computers-and-claw.md) and [How to choose a runtime](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-agent-runtimes.md).

### 3. Pick a template, or start from scratch

Templates are preconfigured roles — dozens of them, grouped by role (research, writing, engineering, product, marketing, finance, and more) — each bundled with a matching set of skills. For full customization, click the **"Build custom"** button in the banner above the template gallery.

![The agent template library grouped by role, with Create from scratch](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48594/d475a2cc.png)

### 4. Fill in the settings

- **Name + avatar**: name up to 80 characters, avatar optional
- **Model**: pick an AI model from the dropdown; each model shows its typical usage range next to it (roughly how many credits each message costs). The exact list and ranges follow what's shown in the UI. Model choice has no membership gate — free users can pick any model too
- **Instructions**: describe its job and how it works, up to 3000 characters — a clear sentence or two of role description goes a long way. **Note: everyone in the space can see this text**, so don't put anything confidential in it

  ![Create form: name/avatar/Model (with usage ranges)/Instructions](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48594/c1c7bec5.png)

### 5. Attach skills (optional)

**Included skills** on the create form lets you preload a set of skills for the agent — when it does repetitive work, it follows the skill's playbook, making it faster and more consistent. You can add or remove skills anytime afterward from the Skills tab in the profile.

### 6. Click Create agent

The agent shows up in the Agents list under Members, and you can immediately pull it into a group chat or open a DM (see [Put agents to work for you](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)).

### 7. Keep managing it in the profile after creation

Click the agent in the Members list (or its avatar) to open the profile. Its tabs, in order: **Profile / Connectors / Genspark Services / Skills / Dashboard / Files** (Dashboard is a run-monitoring tab; this guide doesn't cover it):

- **Profile**: change the name, avatar, and Instructions; **switch models anytime** (hosted agents only, takes effect on the next reply); set who can DM it (three options: Only me / People in this agent's group chats / Only specific people, default Only me — see [Threads and DMs](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-threads-and-dms.md)); set its default reply mode for new group chats (a "Confirm reply mode when adding to a group chat" toggle is rolling out gradually — if your profile doesn't show it yet, go by what's live); toggle **Group chat introduction** (introduce itself when joining a group chat); toggle Saved messages hosting; plus Stop current work / Diagnose / Delete agent (usage in [Put agents to work for you](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md))
- **Connectors**: toggle the external service connectors the agent can use — Google Workspace, Microsoft 365, GitHub, Notion, Slack, HubSpot, X. These use **your own authorization** (the agent accesses these services as you). An unconnected service's toggle is greyed out — click **Connect** first to go through that provider's authorization page (e.g. a Google sign-in grant) before the toggle becomes usable
- **Genspark Services**: toggle, by category, the built-in Genspark services the agent may use (web & research, tasks & creation, communication, knowledge & memory, automation & development, and so on) — services you turn off won't be used when it works; only the creator can change them
- **Skills**: install or remove skills for the agent. It's the same catalog as the Skills store, but **installed per agent** — a skill installed for this agent doesn't affect your other agents; only the creator can change it
- **Files**: browse the agent's working files — a read-only file tree you can open and preview one by one (toggle Preview / Raw), including its memory files; only you can see it

  ![The Files tab's read-only file tree and preview](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51120/e4fa7082.png)
- **Delete**: permanently delete the agent (with a confirmation, not recoverable); afterward you can no longer chat with it. Messages it posted in **group chats** are kept, attributed to "Deleted agent"; **DM conversations** with it can no longer be opened after deletion

### 8. Agent quota

There's a cap on how many agents you can have (higher on paid plans). When you hit the limit, delete unused agents to free up slots; the exact quota follows the in-UI prompt.

## FAQ

**Q: Can I still switch models after creating the agent?**
Hosted (Hosted by Genspark) agents **can switch anytime** — just pick a new model in the profile, and the agent's memory and settings are unaffected. Agents running on your own computer have their model locked in at creation and can't be changed afterward (see [How to choose a runtime](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-agent-runtimes.md)).

**Q: Who can see the Instructions?**
Everyone in your space can see them — it's the agent's "public job description." Write down its responsibilities and style, but never passwords, keys, or confidential information.

**Q: Does creating an agent cost anything?**
Creating is free. A hosted agent only spends your credits when it actually does work (replying, running tasks); agents running on your own computer or on Claw don't spend Genspark credits even while working.

**Q: Is Genny one of my agents too?**
No. Genny is the official help assistant that automatically appears in new users' DMs and can't be created, edited, or deleted.

**Q: Are Connectors secure?**
Connectors use your own authorization, and the agent accesses services as you — so only enable them for the agents that need them, and only the services they need. Also, outbound actions (sending emails, posting, etc.) are only performed when you explicitly ask (see [Put agents to work for you](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)).

## Next steps

- [Put agents to work for you →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)
- [Run an agent on your own computer or Claw →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-computers-and-claw.md)
- [Compare the four runtime options →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-agent-runtimes.md)
- [Hand tasks to an agent →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-tasks.md)
