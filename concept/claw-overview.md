# Genspark Claw — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: genspark-claw | keywords: Claw, AI employee, Cloud Computer, Desktop App, 24/7, automation, Super Agent
> Entry point: `/claw`, the "Genspark Claw" tile in the Agents grid.

## What is Genspark Claw

Genspark Claw is **your first AI employee** — not a chatbot you have to brief from scratch every time, but an always-on assistant that remembers you and can act on your behalf. It connects to your email, calendar, and messaging apps, remembers your preferences and work context, and keeps getting things done for you even when you're away.

The key difference: a regular chat AI stops the moment you close the page, and a new conversation starts from zero. Claw runs continuously in the background as your "employee," remembers you across sessions and channels, and proactively handles repetitive work like email, monitoring, and reporting on your behalf.

## Core Value (What You Get)

- **Turn "explaining over and over" into "explaining once"**: Connect your email/calendar/messaging app once, and Claw can then send, organize, and report on your behalf — no need to issue the same instructions every day
- **Output even when you're not around**: The Cloud Computer runs 24/7 — while you sleep, travel, or have your computer off, scheduled briefings and monitoring alerts still get done, ready for you when you're back
- **Gets to know you the more you use it**: Long-term memory across sessions and channels — a preference you told it to remember in Slack automatically applies in WhatsApp too, no need to repeat yourself
- **Works inside the tools you already use**: Send it instructions directly in WhatsApp, Slack, Teams, and more — no need to switch back to the Genspark website

## Two Ways to Use It (You Can Use Both on the Same Account)

| Dimension | Cloud Computer | Desktop App (local) |
|------|----------------------|------------------------|
| **Where it runs** | A dedicated cloud computer Genspark provisions for you | On your own computer |
| **Subscription needed** | Requires a Cloud Computer subscription | No — just a Genspark account + credits |
| **24/7 operation** | Yes, keeps running even with the browser closed or the machine off | No, pauses when your computer is off or the app is quit |
| **Features** | Everything: Channels, Services, Schedules, Heartbeat, Terminal, Files, and more | Chat, Channels, Skills, Memory (features keep expanding) |
| **File access** | Files live in an isolated cloud environment | Can access your local file system; we recommend setting a workspace directory to limit scope |
| **Best for** | Needing 24/7 automation, cross-platform messaging, scheduled tasks | Trying it out / occasional use / not wanting to pay for a subscription |

**Recommendation**: Not sure → start with the **Desktop App** (free, just needs credits) to get a feel for what it can do. Certain you want it to "work for you while you're away" or "continuously monitor email/Slack" → go with the **Cloud Computer**. Both share the same account's memory and Skills, and you can use them at the same time.

## Claw vs Super Agent

| Dimension | Super Agent | Genspark Claw |
|------|-------------|---------------|
| **Work mode** | You message it, it replies; closing the page stops it | Runs continuously as your "employee," working even when you're away |
| **Memory** | Within a single session; new sessions start from scratch | Persistent across sessions and channels |
| **External app connections** | None | Connects to email/calendar/Slack/WhatsApp and more |
| **Scheduled tasks** | Not supported | Supported — can run automatically daily/weekly |
| **Cost** | Just credits | Cloud Computer needs a subscription + credits; Desktop App just needs credits |
| **Best for** | One-off tasks, research, content creation | Ongoing work, automation, cross-platform collaboration |

**Buddy's selection rule**: User just wants to "chat with AI to complete a one-off task" → Super Agent; user wants "AI to keep working in the background for me" or "to connect my email/Slack" → Claw. When unsure, ask: "Do you need the AI to keep working for you even when you're away?"

## 30+ Pre-installed Skills

Claw comes with 30+ built-in Skills — research, email, calendar, slides, docs, code, image generation, video generation, outbound calls, and more, all ready out of the box. You can also have Claw **save processes you do repeatedly as custom Skills**: next time you do a similar task, it executes the Skill directly, skipping the back-and-forth confirmations to be faster and more consistent. See [howto/claw-schedules](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-schedules.md) for details.

## Memory System

Claw's memory persists across sessions and channels:
- Only by **explicitly saying "remember this"** is something guaranteed to be saved to long-term memory; things mentioned in passing aren't guaranteed to be remembered
- **Long-term memory is shared across all channels** — what's remembered in Slack is usable in WhatsApp too
- **Conversation history is separate per channel** — your Slack chats won't appear in WhatsApp
- When a conversation gets too long, Claw will **automatically compress** older content — explicitly tell it to save important information to memory

## Billing: Subscription and Credits Are Two Different Things

- The **Cloud Computer subscription** is a **fixed monthly fee** for your dedicated cloud machine (CPU, memory, storage, fixed IP) — think of it as your "office." **An idle Cloud Computer consumes no credits**
- **Credits** are the "fuel" for AI work — think of them as "office supplies." Claw consumes them each time it generates text, calls a tool, runs a scheduled task, or performs a Heartbeat check. Credits are **shared across your entire Genspark account**; there's no separate Claw wallet
- The **Desktop App doesn't require an extra subscription** — just a Genspark account + credits, but Claw only works while your computer is on and the app is running
- Need more credits: subscribe to Plus/Pro or upgrade to a higher tier (higher tiers come with a larger monthly credit allowance)

The specific tiers (Lite / Standard / Powerful) and prices are as shown in the interface. See [howto/claw-tips-and-credits](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md) for tips on saving credits.

## Quick Guide by Scenario

| What you want to do | Read this |
|-----------|--------|
| Set up the Cloud Computer / install the Desktop App for the first time | [howto/claw-get-started](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-get-started.md) |
| Use Claw in WhatsApp/Slack and more | [howto/claw-channels](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-channels.md) |
| Have Claw connect to email/calendar/GitHub, etc. | [howto/claw-services](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-services.md) |
| Set up scheduled tasks / automation / Skills | [howto/claw-schedules](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-schedules.md) |
| Manage the Cloud Computer (files/terminal/settings/memory/diagnostics) | [howto/claw-manage](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-manage.md) |
| Save credits / memory tips / security | [howto/claw-tips-and-credits](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md) |

## FAQ

**Q: Which should I choose, Claw or Super Agent?**
One-off tasks, research, content creation → Super Agent. Need continuous operation, external app connections, scheduled automation → Claw.

**Q: Does Claw keep working when I'm offline?**
The Cloud Computer does (24/7 in the cloud, keeps running even with your computer off); the Desktop App doesn't (it pauses when your computer is off or you quit the app).

**Q: Is my data safe?**
Each user has their own isolated Cloud Computer, not shared between users. Your service login sessions are stored in your private cloud browser; email uses an Allowed Senders whitelist, so only approved people can email Claw.

**Q: Why does the Cloud Computer need a separate subscription instead of being covered by Plus/Pro?**
The Cloud Computer dedicates a real machine to you alone (your own CPU/memory/storage/IP), and running 24/7 has real costs, so it's a separate monthly fee. The Desktop App uses your own machine, so no extra subscription is needed. Credits for both are shared across your whole account.
