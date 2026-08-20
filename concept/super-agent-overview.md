# Super Agent — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: super-agent | keywords: Super Agent, universal entry point, default assistant, multi-step, auto-orchestration, Deep Research, Fact Check, Custom Agent, Hub, choosing
> User loop: Understand what Super Agent is → know what it can do → understand how it auto-orchestrates specialized Agents → know when to use it vs. a specialized Agent or Claw

## Why use Super Agent

You have a task you want to get done, but you don't know which tool to use or how to break it into steps. Super Agent lets you **just describe the goal and leave the rest to it**: it decides on its own whether to research online first, whether to write code to crunch numbers, whether to call a specialized Agent to build a slide deck, and then hands you the finished result.

Core value: **Say what you want in one sentence, and the whole chain—from research, analysis, and creation to making calls and sending emails—is automatically planned and executed by AI. You don't need to know how the tools fit together; you just describe the goal and sign off on the result.**

## What is Super Agent

Super Agent is Genspark's **universal AI assistant**, and the default entry point for most users. A single prompt can complete research, writing, data analysis, image/video generation, phone calls, emails, and more. It automatically plans the steps based on the task, picks the right tools, and when needed calls specialized Agents like Slides, Sheets, Docs, Designer, and Developer to handle the corresponding parts.

Entry point: just type into the big central input box on the Genspark homepage and send (the homepage defaults to Super Agent). After sending, you'll land on the conversation page `https://www.genspark.ai/agents?id=<session id>`. You can also go directly to `https://www.genspark.ai/agents?type=super_agent` to start a new Super Agent conversation.

![Super Agent homepage input box (input box / attachment "+" / New menu entry)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35639/c8456610.png)

## What Super Agent can do

| Capability | Description |
|------|------|
| **Comprehensive research + output** | Searches and gathers material online, cross-verifies, and organizes it into reports/decks/spreadsheets |
| **Data analysis** | Upload a data file and it automatically analyzes, computes metrics, and draws charts |
| **Image / video generation** | Just describe it in the conversation to generate (consumes credits) |
| **Real-world actions** | Make calls (Call For Me), send emails (connect Gmail/Outlook), save files to AI Drive |
| **Code execution** | Built-in code runtime that can run scripts and do calculations |
| **Auto-orchestrate specialized Agents** | When a step in the task needs a specialized capability, it automatically calls the corresponding Agent |

Behind the scenes it orchestrates multiple models, hundreds of tools, and a large number of third-party integrations—none of which you need to worry about. Just describe the task.

## How it auto-orchestrates specialized Agents

When a step in a task is better suited to a specialized Agent, Super Agent automatically hands that part off to it, then brings the result back into the conversation. For example:

> "Research 2024 electric vehicle market trends, compile the key data, and turn it into a 10-page presentation"

Super Agent will, in order: research online → compile the data → call AI Slides to generate the deck—all within a single conversation, with no manual tool switching required.

> You don't need to specify which Agent to use up front—just describe the full task, and Super Agent will choose and orchestrate automatically.

## Featured capabilities

- **Deep Research**: report-grade in-depth investigation that automatically gathers large amounts of material and cross-verifies it. See [Research and Fact Check](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-research-and-verify.md) for details.
- **Fact Check**: verifies factual claims in a document/article one by one, marking each with ✅/❌ (Support / Against) for whether it holds up and providing source links.
- **Custom Agent**: create your own AI agent with a single sentence, then call it with `@` in conversations, share it with others, or publish it to the Custom Agent Store. See [Custom Agent](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-custom-agent.md) for details.
- **Hub (persistent workspace)**: upload files and set instructions, and all conversations share the same context—ideal for long-running projects. See [Hub](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-overview.md) for details.

## How to choose: Super Agent / specialized Agent / Claw

```
What do I want to do?
│
├─ The task clearly belongs to a specific specialized Agent (and you already have the content ready)
│   ├─ Only making a deck/presentation → AI Slides (dedicated editing UI is more efficient)
│   ├─ Only spreadsheets/data analysis → AI Sheets
│   ├─ Only writing a long document → AI Docs
│   ├─ Only design/posters → Genspark Design
│   └─ Complex code project → Genspark Code (dedicated code environment)
│
├─ The task needs multiple capabilities working together, or I can't pin down which tool to use
│   └─ → Super Agent (universal entry point, auto-orchestrates)
│
└─ I need "continuous automation"—connect my apps, do things automatically 24/7
    └─ → Genspark Claw (AI employee, always running)
```

| Situation | Recommended | Why |
|------|------|------|
| One-off task that requires research before producing output | Super Agent | Research + output end to end |
| A single specialized task with content already in hand | The corresponding specialized Agent | Has a dedicated UI, easier to edit |
| Not sure what to use | Super Agent | It auto-orchestrates |
| Need something always-on, connected to apps, doing things on a schedule | Genspark Claw | Super Agent only works when you actively use it |

> When in doubt, use Super Agent—it automatically calls the right specialized Agent, with no switching needed on your part.

## FAQ

**What's the difference between Super Agent and AI Slides?**
Super Agent is the universal entry point and automatically calls Slides when needed. If you only want to make a deck and the content is already prepared, using AI Slides directly is more efficient (it has a dedicated editing interface); if you need to research first and then make the deck, use Super Agent.

**What's the difference between Super Agent and Genspark Claw?**
Super Agent is a one-off task assistant that only works when you actively use it; Claw is a 24/7 always-on AI employee—it connects to your email/Slack/calendar and does things for you automatically. Need continuous automation → Claw; one-off task → Super Agent.

**Which Agent should I use?**
When in doubt, use Super Agent—it will auto-orchestrate. Only go directly to a specialized Agent when you clearly know which one you need (and the content is already prepared).

## Quick guide by scenario

| I want to... | Go see... |
|---------|--------|
| Start my first task / write a good prompt / upload files | [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-get-started.md) |
| Do deep research or fact-check | [Research and Fact Check](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-research-and-verify.md) |
| Generate images or videos | [Create Images and Videos](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-create-media.md) |
| Make a call / send an email / save a file | [Real-World Actions](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-actions.md) |
| Create/call/share my own Agent | [Custom Agent](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-custom-agent.md) |
| Keep context across conversations | [Hub Workspace](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-overview.md) |
