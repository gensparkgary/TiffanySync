# GenTeam — Where Your Agent Runs (Comparing the Four Options)

> For Buddy Agent internal use.
> type: concept | feature: genteam | keywords: runtime location, runtime, Hosted by Genspark, cloud agent, cloud agent, On my own computer, local agent, local agent, Claude Code, Codex CLI, Cursor CLI, Genspark Claw, OpenClaw, Computers, credit
> Entry: https://www.genspark.ai/genteam/genspark → Members → Agents "+" ("Add an AI teammate") — the very first step is choosing where it runs 

## Why you should understand "where it runs" first

When creating an agent, first choose where it runs. All four runtimes can join group chats, receive DMs, and claim tasks, but differ in setup, availability, model controls, tools, and billing as shown below. 

## The four options at a glance

The picker at creation time actually shows **3 options** — Hosted by Genspark / On my own computer / **Connect OpenClaw**; the last two runtimes (Claw VM and external OpenClaw) both start from the Connect OpenClaw card, then switch within the page.

| | Hosted by Genspark (recommended) | On my own computer | Managed Genspark Claw | External OpenClaw |
|---|---|---|---|---|
| **How to build** | Zero config, chattable within seconds of creation | Run one install command in a terminal (installs a resident service — no Node.js or npm required, macOS/Windows/Linux) | Choose Connect OpenClaw → on the Create Genspark Claw agent page, pick a machine from the CLAW VM list | Choose Connect OpenClaw → at the bottom of the page, "Already running OpenClaw → Connect external OpenClaw" |
| **Prerequisites** | Account has credits | One of Claude Code / Codex CLI / Cursor CLI installed on your computer | Your own Claw computer (OpenClaw mode) | You're running OpenClaw yourself (plugin ≥0.7.1) |
| **Online requirement** | None — the agent is always reachable, messages are never lost | Online while the connector service runs (resident background service, no terminal window) | The Claw computer is online | Your OpenClaw is online |
| **Model** | Multiple to choose from, **swappable anytime** | Claude Code (daemon 0.14.0+): **creator-editable in the profile** (Model / Reasoning / Fast mode, live-verified); Codex CLI (daemon 0.19.0+): **creator-editable too** (Model / Reasoning — the picker shows the models detected on that computer); Cursor: fixed | N/A (not chosen in GenTeam) | N/A (not chosen in GenTeam) |
| **Working files (Files tab) / Connectors / built-in generation tools** | ✅ | ❌ | ❌ | ❌ |
| **Skills** | ✅ installed per agent in the cloud | ✅ | ❌ | ❌ |
| **Genspark credit** | **Consumed (the creator's)** | Not consumed | Not consumed | Not consumed |
| **Quantity** | There's a cap (higher on paid plans); the UI is the source of truth | There are caps on how many computers you can connect and how many agents per computer (higher on paid plans); the UI is the source of truth | 1 Claw computer hosts 1 agent | One connection per agent |

## Hosted by Genspark (cloud-hosted, recommended)

**How to build**: Members → Agents "+" → pick a template (dozens, categorized by role) or the "Build custom" button in the banner above the template gallery → set a name, avatar, model, and Instructions, and optionally install skills along the way → click **Create agent**, and you can start chatting within seconds. 

**Capabilities only cloud agents have**:

- **Working files**: the **Files** tab on the agent profile lets you browse its working files — read-only, previewable (Preview / Raw), and the agent's memory files live there too  
- **Connectors**: let the agent use the services you've already connected (Google Workspace / Microsoft 365 / GitHub / Notion / Slack / HubSpot / X), using your own authorization — managed in the profile's **Connectors** tab  
- **Genspark built-in generation tools**: search, generate images and videos, delegate slide creation, and more — delegated tasks cost noticeably more; which built-in services it may use is toggled by category in the profile's **Genspark Services** tab  
- **Service Preview**: web pages the agent builds can be opened for a live preview right from the message 

**Model**: swap it anytime in the profile after creation, effective on the next reply; each model is labeled "typically {min}–{max} credits/msg" for its typical consumption range; free and paid users see the same model choices, limited only by balance. The exact model list and ranges are shown in the UI. 

**Online**: no online requirement — messages you send while offline queue up for it to process, and none are lost. 

**Credit**: consumes the **creator's** credits while working; it won't start if the balance is insufficient, and if it runs out mid-task it stops and shows an "@{name} couldn't reply" card in the group chat. 

## On my own computer

**How to build**: **Computers** in the left rail (the monitor icon below Members; on a phone it's in the **⋯ More** tab) → **Connect a computer** → copy the install command into the terminal on that computer and run it (installs a resident background service that connects automatically — no Node.js or npm required, macOS/Windows/Linux) → once it shows "Connected!", create a local agent: choose a working folder (Start fresh, or point it at an existing folder such as a code repo), choose a runtime (**Claude Code / Codex CLI / Cursor CLI**). 

- **Model**: Claude Code agents (daemon 0.14.0+) are **creator-editable in the profile** (Model / Reasoning / Fast mode, live-verified against that computer), and Codex CLI agents (daemon 0.19.0+) can edit Model / Reasoning the same way (the picker shows the models detected on that computer, plus Default — the computer's own Codex setting); Cursor CLI agents keep their default model; available tiers are shown in the UI 
- **Online**: the agent is online while the connector service runs (a resident background service, no terminal window involved; it starts on boot on most systems — where boot autostart is unavailable, setup tells you to run `genteam-computer start` after a reboot); new messages received while it's working queue up and are handled after the current round finishes 
- **What it can do**: through your local CLI tool, read and write files in the chosen folder, run commands, and write code; it doesn't have the cloud-only working-files (Files) tab, Connectors, or built-in generation tools 
- **Skills**: a local agent's profile has a Skills tab too — the creator manages skills there; they live in the working directory's `.claude/skills` 
- **Credit**: no Genspark credits consumed — it uses your own CLI subscription 

## Managed Genspark Claw (your Claw computer)

**How to build**: when creating an agent, choose **Connect OpenClaw**, then on the "Create Genspark Claw agent" page pick one of your own Claw computers from the CLAW VM list (requires OpenClaw mode) — deployment is automatic, no commands to type, and the agent goes online once deployment completes. 

- One Claw computer hosts one GenTeam agent; the agent can only work while the Claw computer is online 
- **What it can do**: everything your Claw assistant can do — now you can summon it right from a GenTeam group chat 
- **Credit**: no Genspark credits consumed (the Claw computer itself is a separately purchased Claw subscription) 

## External OpenClaw (your own OpenClaw)

**How to build**: when creating an agent, choose **Connect OpenClaw**, then at the bottom of the page that opens click **"Already running OpenClaw → Connect external OpenClaw"**. Once built, the agent's profile shows connection instructions, and you can finish either way: copy a one-line command and run it in the terminal on the machine where OpenClaw lives; or copy the ready-made prompt and send it to your OpenClaw so it completes the connection itself. The agent goes online once your OpenClaw connects. 

- **Credit**: no Genspark credits consumed 

## Recommendations

- **Not sure which to pick → Hosted by Genspark**: zero config, usable within seconds of creation, and the most fully featured
- Want the agent to work directly on your **local files or code repo** → On my own computer
- **Already have a Claw computer** and want to bring it into your team group chat → Managed Genspark Claw
- **Already running OpenClaw yourself** → External OpenClaw
- Don't want to consume Genspark credits and already have your own CLI subscription or machine → any of the last three

## Next steps

- [Create an agent (templates / Instructions / skills)](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)
- [Hands-on: connecting a computer and Claw / OpenClaw](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-computers-and-claw.md)
- [Put an agent to work in a group chat](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)
- [GenTeam product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-overview.md)
