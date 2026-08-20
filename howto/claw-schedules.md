# Genspark Claw — Schedules & Automation

> For Buddy Agent internal use.
> type: howto | feature: genspark-claw | keywords: Schedules, Scheduled Tasks, Add Task, Smart Setup, Manual Setup, Templates, Template, Model Optimizer, Heartbeat, Skill, Automation
> User loop: Schedules tab → Add Task (Smart/Manual) or install a template → save → Claw runs automatically on schedule → one-click diagnosis on failure

## Why Use Schedules

- **Turn "asking every day" into "delivered to you automatically"**: For repetitive work like morning briefs, weekly reports, and monitoring, set it up once and Claw runs it on schedule and sends you the results
- **Output even when you're away**: Scheduled tasks run in the cloud on time, even when you're offline
- **Self-healing on failure**: When a task fails, one click lets Claw diagnose it and suggest a fix

## Prerequisites

- Entry: Claw workspace → **Schedules** tab
- Cloud Computer enabled
- If the task involves external data (email, CRM, etc.), connect it first under [Services](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-services.md)

## Creating a Scheduled Task

### 1. Click Add Task

In the Schedules tab, click **Add Task** to bring up "Create Scheduled Task — Choose your preferred task setup method" and pick a setup method:
![Schedules → Add Task dialog: Smart Setup + Manual Setup](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35661/2140517f.png)

- **Smart Setup** (recommended): Claw asks you in natural language what you want done, when it should run, and where to send the results, then builds the task automatically
- **Manual Setup** (full control): You fill in the task name, time (e.g. "every day at 9 AM" or a cron expression), time zone, and the specific prompt yourself

### 2. Save

Once saved, Claw runs automatically at the specified time, even when you're offline.

> **Credit note**: Each scheduled task run consumes credits. Frequency is a multiplier—a task that costs 10 credits per day is about 300 a month; switch it to hourly and that's about 7,200. Before setting it up, ask yourself: "What's the lowest frequency that's still useful?"

## Using Preset Templates

The **Recommended Templates** section in Schedules offers a set of **preset templates** you can install with one click, organized into 6 categories: General, Marketing, Sales, Finance, Developer, and Researcher. Examples:

- **Morning News Brief** — Daily news digest delivered to chat or email
- **Brand Monitor** — Daily analysis of brand sentiment across App Store/Reddit/G2/Trustpilot/X and more
- **Competitor Alert** — Daily roundup of competitor product moves
- **GitHub Issues Digest** — Daily summary of new issues and PRs across your repos
- **Dev Standup Brief** — Morning brief covering yesterday's commits, pending PRs, and today's meetings
- **Weekly Pipeline Report** — Auto-generated sales pipeline overview from your CRM
- **Stock Analysis** — Daily brief on your stock/crypto portfolio

(The number and list of templates is whatever your interface shows.)

> **Tip**: Whether the template library and the Model Optimizer banner appear depends on your interface (Model Optimizer only shows once you have 2 or more tasks).

## Managing Tasks

When you don't have any tasks yet, the list shows the empty-state copy "No scheduled tasks yet. Click \"Add Task\" to create one." with a **Recommended Templates** section below. Once you create tasks, each task row shows the name, run frequency, and enabled/disabled status. You can perform these actions on a task:

| Action | Description |
|------|------|
| **Run Now** | Run it manually once right now |
| **Enable / Disable** | Enable / pause |
| **⋯ → Edit / Delete** | Edit / delete |
| **Last Run Failed** | Appears when a task fails; click it and Claw automatically diagnoses the error and suggests a fix |

> The exact actions within a task row are whatever your interface shows (the verification account had no tasks at the time, so only the empty-state copy and the Add Task entry were confirmed).

## Model Optimizer (Save Credits)

When you have **2 or more** scheduled tasks, a **Model Optimizer** banner appears at the top of Schedules. Click **Try it** to install this Skill—it analyzes each task and assigns the most cost-effective model to each one individually to help you save credits.
> ⚠️ **Banner not verified live**: The verification account had no tasks at the time (didn't meet the ≥2 task trigger condition), so the Model Optimizer banner itself couldn't be seen; this entry is based on the code logic, and the actual trigger condition is whatever your interface shows.

## Heartbeat (Proactive Monitoring)

Find the **Heartbeat** toggle at the top of the Schedules tab (Off by default, labeled "Periodic checks disabled"):

- **On**: Claw periodically checks your inbox, calendar, and connected services automatically, and **acts proactively** on anything that needs handling—even when you haven't sent a message
- **Off**: Claw only works when you actively send it a message
- **Note**: Heartbeat continuously consumes credits in the background, so turn it off when you don't need proactive monitoring

For how to choose between Schedules and Heartbeat, see [claw-tips-and-credits](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md).

## Skills (Make Repetitive Work Faster and More Reliable)

A Skill is a saved set of task instructions that lets Claw handle a specific type of work in a set way—faster and more consistently.
- **Install a preset Skill**: Install directly from the template banner or a task card in the Schedules tab
- **Create a custom Skill**: Tell Claw "save this workflow as a Skill" and Claw will write, test, and install it; the next time you do a similar task, it just runs the Skill
- **When to create one**: When you notice you're giving Claw the same multi-step instructions over and over. The more specific your description (inputs, steps, output format), the more reliable the execution

## FAQ

**Q: What's the difference between scheduled tasks and Heartbeat?**
Schedules is best for tasks with a clear "what + when + what to deliver" (e.g. "every Monday at 9 AM, pull last week's sales data and email it to me"); Heartbeat is best for "keep an eye on things" (Claw periodically checks your connected services and acts on anything that needs handling, without you having to pre-define specific tasks). Both consume credits in the background.

**Q: What do I do when a scheduled task fails?**
Click the **Last Run Failed** button in the task row, and Claw will automatically diagnose the error and suggest a fix.

**Q: Why are credits being consumed so fast?**
The most common causes are scheduled tasks running too frequently or Heartbeat being left on. Go to the Schedules tab to lower frequencies, disable tasks you don't need, and turn off Heartbeat.

## Next Steps

- [Saving credits and security best practices →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md)
- [Connecting external services (the data source for tasks) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-services.md)
- [Managing the cloud computer →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-manage.md)
