# Dashboards & CRM — Automated Workflows

> For Buddy Agent internal use.
> type: howto | feature: agentbase | keywords: workflows, automation, workflow, scheduled, schedule, daily weekly monthly, timezone, Next Run At, auto-send reports, auto-sync, scheduled tasks, monitor, alert, push notification
> User loop: In a workspace → ask AI to build a scheduled workflow → the system runs it automatically on schedule (syncing data, sending reports)

## Why use it

- **Let the system run itself**: Instead of manually refreshing data and sending weekly reports every day, set it up once and let it **run automatically**—a sales report auto-sent every morning, orders auto-synced every hour.
- **Stays updated even when you're away from your computer**: Scheduled tasks run in the background, so you don't have to babysit them—they fire on time automatically.
- **Configure once, save effort long-term**: Just describe "when and what" in chat, and AI builds the automation for you. After that, it keeps running on your behalf.

## Prerequisites

- You need to be signed in and have a workspace (first [create a system](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-create-a-system.md))
- Workflows are created through chat; **every background run consumes credits based on that run's usage** (your credit balance is checked before each run—if it's insufficient, the run is skipped/flagged)

## Steps

### 1. What workflows can do

Workflows let your system **automatically complete repetitive tasks on a schedule**—mainly two types:

- **Scheduled data sync**: e.g., sync the latest records from one of your apps every hour to keep your system's data current.
- **Scheduled report sending**: e.g., compile the current sales situation into a report each morning and auto-send it to your inbox.

![Workflow builder: a scheduled workflow that sends a sales report every morning](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/73338903.png)

### 2. Create a workflow

In chat, spell out two things—**when it triggers** and **what it does when triggered**—and AI will build the workflow for you. For example:

- "Every morning at 9, compile yesterday's new deals into a report and send it to my inbox"
- "Sync new orders from my connected app every hour"

> **If your workflow sends email**: The send step requires you to connect Gmail or Outlook first. The workflow can still be created and show a future run time (Next Run At) even if you haven't connected one—but **the email-sending step will fail when it runs** until you connect your mailbox. To make auto-sent reports actually arrive, connect the sending mailbox first.

### 3. Trigger on a schedule

Workflows are triggered by a **schedule**—running automatically at a fixed frequency. In the builder's trigger settings, you can choose:

| Setting | Options |
|--------|------|
| **Frequency** | Daily / Weekly / Monthly / Custom |
| **Time** | A specific date and time |
| **Timezone** | Set to your timezone (e.g., UTC) |

Once set, the workflow shows a **Next Run At** line so you can confirm when it will run. For example, if set to "Daily at 09:00", it will show the next run as tomorrow morning at 9.

![Scheduled trigger settings: frequency + time + timezone, with Next Run At shown](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/c9e47fc4.png)

### 4. Manage workflows

You can ask AI to modify (change the time or action) or delete a built workflow at any time, and you can also **Test run** (run it once) or **Turn off** it directly in the builder. After a workflow runs, its past runs accumulate into a run history so you can confirm the result of each automatic run.

### 5. About credits for automatic runs

Every background run of a workflow is a real AI execution (syncing, compiling, sending reports), so **each run consumes credits based on that run's usage**—billed the same as if you'd asked AI to do the same thing manually. The system checks your credit balance before each run and skips the run with a notice if your balance is insufficient.

> Setting up a workflow that runs too often (e.g., every minute) will continuously consume credits. Just set the frequency to what you actually need.

### 6. Have AI watch a metric: monitors with mobile push alerts

Beyond running tasks on a schedule, you can have the system **watch a number you care about and alert you when it crosses a line**. Tell AI in chat what to watch and what counts as "not normal", for example:

- "Alert me when stock drops below 10"
- "Tell me if pending orders go above 50"
- "Alert me if the lead count hits zero"

AI builds a **monitor** for it: the system checks that metric in the background on a regular cadence, and when the condition trips, it alerts you via a **push notification from the Genspark mobile app** (you need the app installed on your phone with notifications allowed); you can optionally get one more notification when the metric recovers.

Monitors are also managed entirely through chat (they do not appear as a sidebar section — ask the AI to list them): ask AI to list your existing monitors, change a condition or check frequency, mute one temporarily (no alerts, but it keeps checking), or delete it.

> A monitor's background checks just verify the data — they don't go through AI and **cost no extra credits**; creating and changing monitors happens in chat and is billed as a normal conversation turn.

## FAQ

**Are workflows free?**
Creating a workflow doesn't cost anything extra by itself, but it **consumes credits on every automatic run**—because each run is a real AI execution. Just set the frequency to what you actually need.

**Will scheduled tasks still run if my computer is off?**
Yes. Workflows run in the background and don't depend on your computer being on.

**What if the auto-sent report email didn't go out?**
Check whether the sending mailbox (Gmail / Outlook) is connected. A workflow can be created and show its next run time even without a connected mailbox, but the email-sending step will fail when it fires—connect your mailbox and it will deliver normally.

**What if a workflow errors out or doesn't behave as expected?**
Check its run history to confirm the result of each run; to adjust it, ask AI in chat to change the trigger time or action, or just delete it and rebuild.

**How is a monitor alert different from a workflow?**
A workflow "does a task when the time comes" (sync, send a report) and consumes credits on each run; a monitor "keeps watching one number and only alerts when it crosses the line" — its background checks don't go through AI and cost no extra credits, and alerts arrive as mobile app push notifications.

**I'm in a team/organization space — why can't I create workflows?**
Team-space admins can centrally control whether members may create and run workflows. If such an action is refused, ask your organization admin to enable it.

## Next steps

- Make auto-synced data look better → [Views and Dashboards](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-views-and-dashboards.md)
- Share your auto-updating system with colleagues → [Share and Collaborate](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-share-and-collaborate.md)
- Haven't connected a data source yet? First [import data](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-import-data.md)
