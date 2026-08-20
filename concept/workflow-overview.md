# Workflow — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: workflow | keywords: Workflow, Workflows, automation, schedule, trigger, flow, orchestration
> Entry point: `/workflows`, "Workflows" in the main navigation / Tools panel.

## Why Use Workflows

There are plenty of tasks you need to do over and over, on a schedule: summarizing industry news into your inbox every morning, turning new data in a spreadsheet into a weekly report, or automatically archiving a specific incoming email and notifying your team. Doing these by hand is time-consuming and easy to miss.

Workflows let you **set up these multi-step tasks once and have them run automatically over the long term**—just describe what you want in a single sentence, and the AI will chain together steps like research, organizing, generating, and sending into one flow. From there, it can run automatically on a schedule you set, or trigger automatically when a specific event happens, delivering the results straight to you.

## What Is a Workflow

A Workflow is a **reusable, auto-runnable** multi-step automation flow. Unlike a one-off conversation, once a Workflow is created it's saved, so you can run it repeatedly, run it on a schedule, or trigger it from an external event.

A Workflow typically includes:
- **Trigger**: when it runs—currently three options: on a schedule (On a schedule: daily/weekly/monthly/custom every N days), by email (When I get an email: when a new email arrives, supports Gmail/Outlook), or by meeting notes (Meeting notes generated: when notes for one of your meetings finish generating). Each Workflow has only one trigger slot, so only one trigger is supported.
- **Steps**: the things it does in order—research, scraping web pages, sending and receiving emails, reading and writing spreadsheets and docs, sending chat messages, managing the calendar, generating content, and more.
- **Output**: the results produced each time it runs, viewable in the run history.

## Workflow vs. a Regular One-Off Conversation

| Dimension | Regular Conversation | Workflow |
|------|---------|----------|
| Saved and reusable | One-off | Saved, can run repeatedly |
| Runs automatically | No | Can run automatically on a schedule / email / meeting-notes trigger |
| Best for | Ad hoc, single-time tasks | Repetitive, recurring, automation-worthy tasks |
| Not sure which to pick | Doing it once → just chat; doing it repeatedly or on a schedule → use a Workflow | |

## What You Can Do (Typical Scenarios)

- **Scheduled briefings**: automatically research a topic daily/weekly, generate a summary, and send it to your inbox
- **Email automation**: when a specific email arrives, automatically extract information, reply, archive, or log it into a spreadsheet
- **Post-meeting automation**: the moment meeting notes finish generating, automatically turn them into action items, send follow-up emails, or archive them
- **Data organizing**: regularly turn content in spreadsheets/docs into reports
- **Bulk content production**: generate text-and-image or media content in batches on a schedule

A Workflow's steps can call many kinds of integration tools—search, sending and receiving email, reading and writing spreadsheets and docs, sending chat messages, managing the calendar, and connecting to third-party business systems (the specific tools available are whatever the UI shows).

## Quick Guide by Stage

| What you want to do | See this |
|-----------|--------|
| Create your first Workflow from a single sentence | [Create a Workflow](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-create.md) |
| Edit the steps of an existing Workflow | [Edit a Workflow](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-edit.md) |
| Set up a schedule / email / meeting-notes trigger to run automatically | [Schedules and Triggers](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-schedule-and-triggers.md) |
| Run, test, and view result history | [Running and History](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-run-and-history.md) |
| Manage, enable/disable, delete, share | [Manage and Share](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-manage-and-share.md) |

## FAQ

**Q: What's the difference between a Workflow and a regular conversation?**
A regular conversation ends once it's done; a Workflow is saved and can be run repeatedly, run on a schedule, or triggered automatically when an email arrives or your meeting notes finish generating—ideal for repetitive, recurring tasks.

**Q: Does running a Workflow consume credits?**
Yes. Creating one (AI generates the flow), **Test Run (simulates the trigger but actually runs the AI steps)**, and every regular run all consume credits based on task complexity, just like any other AI task. Editing steps, setting triggers, and viewing run history are free.

**Q: What happens if I run out of credits for a scheduled Workflow?**
The scheduled task automatically defers until your credits are next replenished, then runs—it won't keep running and erroring out.

**Q: Can free users use Workflows?**
Yes. The main Workflow features are open to regular users, and running them consumes your daily credit budget.

**Q: Can Workflows connect to my Gmail, spreadsheets, and so on?**
Yes. A Workflow's steps can call many kinds of integration tools like email, spreadsheets, docs, chat, and calendar; triggers support schedules, email (Gmail/Outlook), and meeting notes generation. The exact options depend on what the UI shows.

**Q: Can one Workflow have multiple triggers?**
Currently each one supports only a single trigger. When you need multiple trigger scenarios, create a separate Workflow for each.
