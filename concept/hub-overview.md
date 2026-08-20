# Hub — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: hub | keywords: Hub, workspace, persistence, shared context, cross-project, team collaboration, Custom Instructions, long-term projects
> User loop: Understand what Hub is → Know what problem it solves → Know when to use Hub vs. regular chat → Know where to find it

## Why Use Hub

Every regular chat starts from scratch: you have to re-upload your materials and re-explain the background and rules. That's fine for one-off tasks, but if you're working on a **long-term project**—the same set of materials, the same rules, a series of related tasks—that repetition keeps eating into your time.

Hub solves this once and for all: **store your materials and rules once, and every conversation and project in this space automatically carries them along—they can even reference each other's history and share the same context with your team.** Instead of re-explaining the background every time, you just keep working in a space that "remembers what you're doing."

## What Is Hub

Hub is a persistent workspace. You create a Hub for a project, drop in files, write a fixed set of instructions, and from then on every conversation you start inside that Hub automatically carries this context. Going further: projects within the same Hub **share conversation history** and can reference one another; you can also **invite teammates to join**, so everyone sees the same files and the same history, taking turns to work on any project.

How to find it: Left sidebar **More → Hub**, landing page `/hub` (the "Your Hubs" list); once you enter a Hub it's `/hub?id=<id>` (the detail view).

## What Hub Can Do for You

| Capability | What you get |
|------|-----------|
| **Shared files** | Upload materials once, and every conversation in this Hub can reference them directly—no more repeated uploads |
| **Custom Instructions** | Write your fixed rules (tone, format, domain, terminology) once, and every conversation follows them automatically |
| **Cross-project history reference** | A new conversation can directly reference conclusions from earlier projects in the same Hub and pick up where they left off |
| **Team collaboration** | Invite teammates so everyone shares the same files and history, taking turns on any project |
| **Centralized project management** | One Hub homepage gathers all of the project's tasks, so you can review or continue anytime |

> Managing the Hub itself (creating a space, uploading files, setting instructions, adding members) doesn't consume any credits; what actually consumes credits is the conversations inside the Hub—just like regular chats, the more files you have, the larger the context, and the higher the consumption.

## How to Choose: Hub vs. Regular Chat

```
What I'm trying to do……
│
├─ A one-off task, done once and forgotten → A regular chat will do
│
└─ A long-term project: the same materials, the same rules, a series of related tasks
    └─ → Create a Hub
        ├─ Just for myself → A personal Hub
        └─ Working on it with my team → Invite members, share the space
```

| Situation | Recommended | Why |
|------|------|------|
| Asking a quick question, running a one-off task | Regular chat | No need to save context |
| Repeatedly working on the same set of materials | Hub | Upload files once, all conversations share them |
| Re-explaining background/rules with every new conversation | Hub | Custom Instructions set once, in effect long-term |
| Need to reference conclusions from earlier tasks to keep going | Hub | Projects in the same Hub share conversation history |
| A team collaborating around the same project | Hub | Invite members, share files and history |

## How Hub Relates to super-agent-hub

Hub is part of Super Agent's capabilities, and can also be used as a standalone workspace: when you start a conversation in a Hub, it defaults to Super Agent (you can also use `@` to switch to specialized Agents like AI Slides, AI Sheets, AI Docs, etc.). In short—**Super Agent decides "which capability to use for this task," while Hub decides "which set of context these tasks share."**

## FAQ

**What's the biggest difference between Hub and a regular chat?**
Regular chats are each independent and don't remember one another; all conversations in a Hub share files, rules, and history. If you need to work on the same set of materials over the long term and continuously → use Hub.

**Do I have to pay extra to use Hub?**
Creating a Hub, uploading files, setting instructions, and adding members are all free. You only consume credits when you have conversations inside the Hub, just as you normally would.

**Can I use specialized Agents in a Hub?**
Yes. Conversations started in a Hub default to Super Agent, but you can also use `@` to select AI Slides / AI Sheets / AI Docs / Genspark Code / Genspark Design, etc.

## Quick Guide to Each Article

| I want to... | Go read... |
|---------|--------|
| Create a Hub, upload files, set rules | [Set Up Your Hub](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-setup.md) |
| Work in a Hub, reference history, manage projects | [Working in a Hub](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-work.md) |
| Invite teammates, collaborate as a team | [Team Collaboration](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-collaborate.md) |
