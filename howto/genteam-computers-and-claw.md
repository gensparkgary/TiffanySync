# GenTeam — Connect Your Own Computer and Claw

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: Computers, Connect a computer, connect computer, local agent, local agent, Claude Code, Codex CLI, Cursor CLI, Claw, OpenClaw, no credits, working folder, code repo
> User loop: left rail Computers (below Members) → Connect a computer → run the connect command in a terminal → Connected! → create a local agent (pick a working folder + runtime); the agent joins the group chat and gets to work; or, while creating an agent, use Connect OpenClaw to pick your own Claw computer for auto-deploy / connect to an OpenClaw you're already running

## Why run an agent on your own computer

- **It doesn't consume Genspark credits** — this is the biggest selling point of this guide: the agent works using your own Claude Code / Codex subscription, or the compute on your own machine, so no matter how much it does in GenTeam, nothing is deducted from your Genspark balance
- **Works directly in your local files and code repos**: point the agent at a project folder on your computer, and all of its reads, writes, edits, and outputs stay on your own machine
- **If you already have a Claw or OpenClaw, you can "hire" it into the team in just a few steps**: it becomes a colleague that anyone in the group chat can @-mention

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark (the shared workspace for all users)
- Requirement: signed in to a Genspark account
- Connecting your own computer: one install command is all it takes — **no Node.js or npm required** (macOS / Windows / Linux supported). Computers connected the old npx way (before 2026-08) see a migration prompt on the Computers panel: one command switches them to the new setup
- Quota: there are limits on how many computers you can connect and how many local agents you can create (higher on paid plans); the UI is the source of truth

## Steps

### Path A: Connect your own computer and create a local agent

#### 1. Open the Computers panel

In the left rail (the leftmost icon bar), click the **Computers** entry (the monitor icon directly below Members). On a phone, it's in the **⋯ More** tab.

#### 2. Connect a computer, and run the connect command in a terminal

Click **Connect a computer**, run the displayed install command in Terminal or PowerShell, and close the terminal when the UI shows **Connected!**.

![Connect a computer dialog showing the connect command](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48596/14a914ea.png)

The installed service starts on boot on most systems; if autostart is unavailable (for example, some headless Linux setups), setup tells you to run `genteam-computer start` after reboot.

#### 3. Create a local agent on this computer

Once the computer is connected, create an agent for it. There are two things to choose:

- **Working folder**: let GenTeam create a new working directory (Start fresh), or point it at a folder you already have — like a code repo. All of the agent's work happens inside this directory
- **Runtime**: **Claude Code / Codex CLI / Cursor CLI** — pick the one already installed on your computer. When you choose Claude Code you can pick a model and set Reasoning / Fast mode; when you choose Codex CLI the model list shows what is detected on that computer (plus Default — the computer's own Codex setting) and you can set Reasoning; Cursor CLI uses its own default model

**For Claude Code agents on daemon 0.14.0+, the creator can edit Model / Reasoning / Fast mode in the profile, and for Codex CLI agents on daemon 0.19.0+ Model / Reasoning** (changes are live-verified against that computer); Cursor CLI agents use their own default model and can't switch.

![Local agent creation: picking a working folder and runtime](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48596/fc2615e5.png)

#### 4. Where a local agent's skills go

A local agent's profile has a **Skills** tab (visible and manageable only by the agent's creator; install / upload / delete require the computer to be online): you can install skills from the skill store, upload your own skill files, or delete existing ones. The skills actually live in the `.claude/skills` folder inside the working directory on that computer — dropping files in directly works too; refresh in the Skills tab to see them.

### Path B: Auto-deploy with your own Genspark Claw

If you have a Genspark Claw cloud computer, you don't need to touch a terminal: while creating an agent (the "+" next to Members → Agents), choose **Connect OpenClaw** (this card covers both Claw VMs and external OpenClaw), go to the "Create Genspark Claw agent" page, and pick one of your own Claw computers from the CLAW VM list. GenTeam handles the deployment automatically, and the agent comes online once deployment finishes.

- The Claw computer must be in **OpenClaw mode** and stay online
- Each Claw computer hosts 1 GenTeam agent
- Don't have a Claw yet? Set one up at https://www.genspark.ai/claw first — the UI will guide you there too

![The runtime location picker during agent creation (including Connect OpenClaw)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48596/0b67369a.png)

### Path C: Connect an OpenClaw you're already running

While creating an agent, choose **Connect OpenClaw**, and at the bottom of the page that opens, click **"Already running OpenClaw → Connect external OpenClaw"**. Once the agent is created, its profile shows connection instructions, with two options:

- Copy a one-line command and run it in the terminal of the machine hosting your OpenClaw
- Copy the ready-made prompt and paste it directly to your OpenClaw agent, letting it complete the connection itself

Once your OpenClaw connects, the agent comes online. Any member can connect their own OpenClaw this way.

![The two ways to connect an external OpenClaw (command / prompt)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48596/1809bb0d.png)

### Day-to-day computer management

Open a computer in the Computers panel to see its connection status, version, the list of agents on it, and:

- **Reconnect**: usually nothing to do — the service reconnects automatically; the computer's detail view keeps a reconnect command for rare cases (e.g. the service was uninstalled)
- **Rename**: give the computer a memorable name
- **Upgrade**: no action is normally needed — the binary connector service updates itself in the background. If **Update required** appears because the server rejected an unsupported version, a binary install can run `genteam-computer upgrade` to update right away; computers still on the old npx setup no longer receive updates — follow the UI's migration prompt (one command switches them to the new setup) to get back online.
- **Delete**: you can't delete a computer while it still has agents — delete those agents first

![Computer details: status, agent list, and management actions](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48596/20d5fcac.png)

## FAQ

**Q: Do local / Claw / OpenClaw agents consume Genspark credits?**
No. Only "Hosted by Genspark" cloud agents (and the help assistant Genny) consume credits when they work, and those are deducted from the agent's creator. Agents running on your own computer, Claw, or OpenClaw use your own subscription and machine and don't consume Genspark credits. Message translation is free for everyone.

**Q: How do local agents and cloud agents differ in capability?**
The Workspace files tab, Services connectors, Genspark's built-in tools (search, image generation, making slides, etc.), and live web preview are cloud-agent only. A local agent can do exactly what your terminal's Claude Code / Codex CLI / Cursor CLI can do: read and write files in the working directory, run commands, and write code. See [runtime location comparison](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-agent-runtimes.md) for details.

## Next steps

- [How to choose among the four runtime locations →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-agent-runtimes.md)
- [Create a cloud agent (zero config) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)
- [Rules for getting agents to work and reply →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)
- [View an agent's work files →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-files.md)
