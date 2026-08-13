# Skills — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: skills | keywords: Skills, Skill, Skill, Reuse, Community, Team, My Own, SAS, SuperAgent Sandbox
> Entry: `/skills`, the "Skills" icon in the sidebar.

## Why Use Skills

Every conversation with AI starts from scratch describing your needs—inefficient and inconsistent results. Skills package validated working methods into reusable solutions—pick a Skill, enter your content, and get stable, high-quality output.

Core value: **No need to write your own prompts, use solutions others have validated, create once and reuse continuously**.

## What Is a Skill

A Skill is a reusable AI tool. Each Skill includes:
- **Instructions**: tell the AI how to do it (structure, style, steps)
- **Trigger words**: shortcut commands (e.g. `@pdf-helper analyze`)
- **Tool permissions**: the tools a Skill can use (search, web scraping, etc.)
- **Output format**: the expected deliverable (documents, data, charts, etc.)

Skills run in the **SuperAgent Sandbox**—an isolated execution environment that can run code, read and write files, and call external tools.

## Three Sources

| Source | Description | Scale |
|------|------|--------|
| **Community Skills** | Platform-curated, organized by publisher (Anthropic, OpenAI, Genspark, etc.) | 100+ |
| **Team Skills** | Skills published by your team, visible only to team members (requires Team Plan) | Depends on team |
| **My Own Skills** | Skills you create, upload, or customize yourself | Personal collection |

## Four Ways to Create

| Method | Use Case | Steps |
|------|---------|------|
| **Create for myself** | Start from scratch, AI guides you through describing your needs | + New Skill → Create for myself → chat with the Agent |
| **Upload** | Already have a Skill file (.zip/.skill/.md) | + New Skill → Upload → select file |
| **Start from a community skill (customize)** | An existing Skill is close to what you need and you want to build on it | + New Skill → Start from a community skill (or Customize on a Skill's detail page) → get your own copy → edit conversationally |
| **Create for Team** | Create a shared Skill for your team (requires Team Plan) | + New Skill → Create for Team |

A customized copy is saved in My Own Skills, labeled "from you" on the card; it's an independent copy and won't receive updates to the original. Any Skill you own can then keep being refined conversationally via **Edit** in its detail dialog (the card face has no Edit button).

## Three Ways to Share

| Method | Applies To | How They Get It |
|------|------|-------------|
| **Public Link** | Anyone | Open link → preview → sign in and install |
| **Team Publish** | Team members (requires Team Plan) | Automatically appears in the Team Skills tab |
| **Peer Share** | Specified email | Receive invite → Accept → install |

## Skill Execution Flow

```
Select a Skill → enter prompt → Sandbox executes → streaming output → deliver files
```

1. Select a Skill from the SkillBar on the home page (click "Select a skill first" or type `/`)
2. Enter your specific content/requirements
3. The Skill executes in the Sandbox (can search, generate files, run code)
4. See execution steps and output in real time
5. Preview and download deliverable files; the task owner can also rename or delete delivered files from the files pane

## Connectors — Let Skills Access External Data

Connectors link your external services (Gmail, Slack, Notion, etc.), allowing a Skill to read data from these services during execution.

Major supported services:
- **Google**: Google Suite (aggregated), Gmail / Calendar / Drive / Google Contacts
- **Microsoft**: Microsoft 365 (aggregated), Outlook Email / Calendar / Teams / OneDrive / SharePoint
- **CRM**: Salesforce / Pipedrive / Affinity CRM
- **Collaboration**: Slack / Notion / Jira / Confluence / GitHub
- **Others**: Box / Mailchimp / X (Twitter) / LinkedIn Lite (Beta)
- **MCP**: Reddit / Deep Wiki / Hacker News / Asana, etc. (supports adding custom MCP servers)

## Scenario Selection Guide

```
What's the user intent?
│
├─ "I want to find a ready-made tool"
│   └─ Community Skills → filter by Role/Publisher/Output → install → use
│
├─ "An existing Skill is close, but I want to tweak it"
│   └─ Customize on the Skill's detail page (or + New Skill → Start from a community skill) → get your own editable copy
│
├─ "I want to package my workflow"
│   ├─ For myself → Create for myself
│   └─ For my team → Create for Team (requires Team Plan)
│
├─ "I have a .skill file"
│   └─ Upload → appears in My Own Skills
│
├─ "I want to share a useful Skill with others"
│   ├─ Share with anyone → Public Link
│   ├─ Share with my team → Team Publish
│   └─ Share with specific people → Peer Share (email invite)
│
├─ "The Skill needs to read my email/calendar/files to run"
│   └─ Connect Connectors first → then run the Skill
│
└─ "I'm not sure which Skill to use"
    └─ Browse by Role (Sales / Marketer / Product manager / Researcher...)
```

## Core Capabilities at a Glance

| Capability | Description |
|------|------|
| Discover | Community / Team / My Own tabs + Publisher/Role/Output filters + Recently viewed recall |
| Create | AI-guided creation / file upload / customize from a community Skill / team creation |
| Edit | Your own Skills are editable conversationally (Edit in the Skill's detail dialog); community Skills can be Customized into a copy first |
| Run | SkillBar select → input → Sandbox execution → streaming output → file delivery |
| Share | Public Link / Team Publish / Peer Share |
| Manage | Install / Uninstall / Delete / Update |
| Connect | Connectors link 30+ external services |
| History | Task List to view past runs and deliverable files |

---

## Screenshot Checklist

| # | Screenshot ID | Capture Location | What Must Be Visible in the Screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `overview-landing` | `/skills` home page full view | SkillBar input area, Community/Team/My Own tabs, Skill card list, + New Skill button | Show the full product in one image |
| 2 | `overview-filters` | Filter panel expanded | Publisher filter (Anthropic/OpenAI/Genspark), Role filter (Sales/Marketer/PM...), Output filter | Show filter dimensions |
| 3 | `overview-skill-card` | Single Skill card | Card title, description, Publisher tag, Add & Use button | Show card information structure |
| 4 | `overview-skillbar` | SkillBar area | "Select a skill first" prompt, number of installed Skills, input box | Show the quick reuse entry |
| 5 | `overview-connectors` | Connectors modal | Available services list (Google/Microsoft/CRM/Collaboration) | Show external connection capability |
