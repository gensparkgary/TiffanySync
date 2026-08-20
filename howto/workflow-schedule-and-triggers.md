# Workflow — Schedules & Triggers

> For Buddy Agent internal use.
> type: howto | feature: workflow | keywords: schedule, Schedule, trigger, Trigger, On a schedule, When I get an email, Meeting notes generated, meeting trigger, Daily, Weekly, Monthly, Custom, End date, timezone, Email, Gmail, Outlook, auto-run, Turn On
> User loop: Edit Workflow → Set up an On a schedule / When I get an email / Meeting notes generated trigger → Turn On → Confirm it runs automatically

## Why Set a Trigger

- **True automation**: Once a trigger is set, the Workflow runs on its own without you clicking anything—this is what sets Workflows apart from one-off conversations
- **Run on a schedule**: Execute automatically every day, week, month, or at a custom interval (e.g., a morning briefing every day)
- **Run on email**: Trigger automatically when a new email arrives and process its contents
- **Run on meetings**: Trigger automatically the moment your meeting notes finish generating, for post-meeting automation (e.g., turn notes into action items, send follow-up emails)

## Prerequisites

- An existing Workflow (to create one, see [Create a Workflow](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-create.md))
- To use the Email trigger, you must first authorize the corresponding email account (Gmail or Outlook)
- To use the meeting notes trigger, you need to be using [AI Meeting Notes](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-record-and-import.md) (notes from any source count — live recording, upload, or Meeting Bot)

## Three Types of Triggers

The Workflow trigger panel currently has **only three** trigger types (you'll also see a *"More triggers are on the way"* note—more trigger options are rolling out over time):

| Type | UI Label | Description | Best for |
|------|---------|------|------|
| **Schedule** | **On a schedule** | Runs automatically at a set time or interval | Recurring tasks: daily briefings, weekly reports |
| **Email** | **When I get an email** | Runs automatically when a new email arrives, using the email content as input; supports Gmail and Outlook, account authorization required first | Reactive tasks: auto-extract/reply/archive when an email comes in |
| **Meeting notes** | **Meeting notes generated** | Runs automatically when notes for one of your meetings or recordings finish generating, using the notes content as input | Post-meeting automation: notes to action items, follow-up emails, logging to a sheet |

Not sure which to pick: "do it on a schedule" → On a schedule; "do it when an email arrives" → When I get an email; "do it as soon as a meeting wraps up" → Meeting notes generated.

> **Trigger ≠ Step**: The Sheets / Notion / Slack / Calendar options you see in the UI are **action steps (ACTIONS)**, not triggers. There are currently only the three trigger types above.
>
> Each Workflow has only **one trigger slot (STARTER)**, so you can set only one trigger. When you need to handle multiple trigger scenarios, create a separate Workflow for each.

## Steps — Schedule Trigger (On a schedule)

### 1. Choose the On a schedule trigger

In your Workflow's trigger settings, select **On a schedule**.
![Configuring the On a schedule trigger](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/e552cef9.png)

### 2. Set the repeat rule

Set the date and time, then choose a repeat rule:
- **No repeat** — Runs only once, no repeat
- **Daily** — Every day
- **Weekly** — Every week
- **Monthly** — Every month
- **Custom** — Custom: runs once every N days, with an optional **End date** (Never / a specific end date)

You can also set the **Timezone**. After changing the repeat rule, the step label updates dynamically (e.g., "Every day at 09:00").

A schedule with an **End date** automatically stops triggering once the end date passes and won't keep running — handy for event-style tasks with a clear cutoff (e.g., "post a daily update during the campaign").
![Custom repeat rule (every N days + End date)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/810439eb.png)

### 3. Turn On to go live

Once everything checks out, click **Turn On** to activate the Workflow, after which it will run automatically at the time you set.

> Every automatic run consumes credits. If you run out of credits, the scheduled task is automatically deferred until your credits are replenished, rather than continually erroring out.

## Steps — Email Trigger (When I get an email)

### 1. Choose the When I get an email trigger and authorize an account

Select the **When I get an email** trigger, choose the email service to listen to from the Provider dropdown (**Gmail** or **Outlook**), then click **Configure** to complete account authorization (when not connected, you'll see "No Gmail account connected").
![Email trigger configuration (Provider: Gmail / Outlook + Configure authorization)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/b47e527c.png)

### 2. Turn On to go live

Save and **Turn On**. From then on, when a qualifying new email arrives, the Workflow runs automatically with the email content as input.

## Steps — Meeting Notes Trigger (Meeting notes generated)

### 1. Choose the Meeting notes generated trigger

Select the **Meeting notes generated** trigger (the UI describes it as "Runs when notes for one of your meetings or recordings finish generating"). No extra authorization is needed, but it only fires if you're producing notes with [AI Meeting Notes](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-record-and-import.md) (live recording, uploaded audio, or Meeting Bot recordings all count).

### 2. Turn On to go live

Save and **Turn On**. From then on, every time notes for one of your meetings or recordings finish generating, this Workflow runs automatically with those notes as input for the following steps.

## About Integration Tools

Beyond triggers, the **steps** in a Workflow can call various integration tools to perform specific actions—such as searching, sending/receiving email, reading/writing sheets and docs, posting chat messages, managing calendars, and connecting to third-party business systems. The exact tools available are as shown in the UI.

## FAQ

**Q: Can one Workflow have multiple triggers?**
Currently each Workflow supports only one trigger. When you need multiple trigger scenarios, create a separate Workflow for each.

**Q: Does setting a trigger cost credits?**
Configuring a trigger is free; credits are only consumed when the Workflow actually runs after being triggered.

**Q: What happens if a scheduled time arrives but I don't have enough credits?**
That run is automatically deferred until your credits are next replenished—it won't keep running empty or erroring out.

**Q: What happens when a schedule with an End date expires?**
Once the end date passes, the Workflow automatically stops triggering — it no longer runs and no longer consumes credits.

**Q: What if a step in my flow uses an account I haven't connected yet?**
When you Turn On, if the flow uses accounts that aren't authorized yet, a prompt appears suggesting you connect them first (it doesn't hard-block). If a required account is still unauthorized when the Workflow runs, that run stops early and the run record explains why. Connect the account and run again.

**Q: Do I need to connect an account first for the Email trigger?**
Yes. Before using the Email trigger, you must first authorize a Gmail or Outlook account.

**Q: When does the meeting notes trigger fire?**
It fires when **notes finish generating** for one of your meetings or recordings in AI Meeting Notes — whether the notes came from a live recording, an uploaded audio file, or a Meeting Bot recording. No extra account authorization is required.

## Next Steps

- [Running & History](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-run-and-history.md) — Manual runs, Test Run previews, viewing history
- [Manage & Share](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-manage-and-share.md) — Enable/disable, delete, share
- Back to [Workflow Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-overview.md)
