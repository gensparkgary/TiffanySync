# Workflow — Running & History

> For Buddy Agent internal use.
> type: howto | feature: workflow | keywords: run, Run, Test Run, dry run, simulated data, Simulated, execution, history, run records, Details, Pending Confirmation, status, duration
> User loop: Open Workflow → Test Run dry run / live run → check status → view output → review past runs in My Workflows

## Why understand running & history

- **Dry run before going live**: Test Run lets you run the flow once with simulated data to confirm everything works before going live, avoiding accidentally triggering real actions
- **Reviewable**: Each run's status, time, and result stay in the run history for you to check anytime
- **Step in when needed**: When a step needs your confirmation (Pending Confirmation), you can handle it right in the run record

## Prerequisites

- You already have a Workflow

## Ways to run

| Method | Purpose | Consumes credits? |
|------|------|------------------|
| **Test Run** | Dry run with a simulated trigger — no real emails/actions sent, but AI steps actually execute | Yes (based on complexity) |
| **Live run / auto trigger** | After Turn On, runs for real based on the trigger | Yes (based on task complexity) |

## Steps — Test Run dry run

### 1. Start a Test Run

Click **Test Run** on the Workflow (in the editor, or via the three-dot menu ⋯ → **Test Run** in the My Workflows list). The system executes step by step with simulated data — the trigger is marked **"(Simulated)"** to indicate it's using simulated data.
![Test Run executes step by step with simulated data (trigger marked Simulated, each step has Details)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/77f5b80f.png)

### 2. Review the dry run results

During execution, each step has **Details** that you can expand to view its inputs/outputs. Confirm every step ran as expected and produced reasonable output, then Turn On to run it for real.

> Test Run uses a simulated trigger — no real emails are sent and no real data is modified, but **it does consume credits based on task complexity**. It follows the same execution path as a live run and actually runs the AI steps, making it the best way to validate your logic before going live.

## Steps — View run history

### 1. Select a Workflow in My Workflows

Go to `/workflows`, click **View All** to open My Workflows, and select a Workflow. The middle panel shows its complete run history.
![My Workflows run history (status / trigger time / duration)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/66d55249.png)

### 2. View a single run's details

Each run record shows the **run status, trigger time, and duration**. Click a record to view its complete results in the right panel. For runs fired automatically by a trigger, the record shows **which trigger actually fired this run** (schedule / email / meeting notes); only Test Run dry runs are marked "(Simulated)".

If a Workflow is live (Active) but hasn't actually been triggered yet, the details area shows the message: *"Currently no run history. This workflow is active and will trigger on future events."* — this means it's on standby, not an error.

> You don't have to keep watching the list: when there are new run results, the **Workflows** entry in the left navigation shows an unread dot; hovering over the entry pops up an **Active Workflows** card where you can preview running Workflows and Recent Runs, and click **View all** to open the full list (appears only when you have at least one active Workflow).

### 3. Handle steps awaiting confirmation (Pending Confirmation)

If a step is waiting for your input (**Pending Confirmation**), you can view the details and handle it directly in the run record.

## FAQ

**Q: What's the difference between Test Run and a live run?**
Test Run uses a simulated trigger for a dry run — no real emails are sent and no real data is modified, but **it does consume credits based on task complexity** (the AI steps actually run), making it convenient for validating logic before going live. Only after Turn On does it run automatically based on the trigger (which also consumes credits).

**Q: Does viewing run history cost credits?**
Viewing history and results is free; but **Test Run consumes credits based on task complexity** (the AI steps actually execute), and live runs consume credits too.

**Q: A run is stuck on a step and won't move?**
The step may be waiting for your confirmation (Pending Confirmation). Open the corresponding run record to view and handle it.

**Q: Why did a run stop early?**
Open that run record — it explains why the run stopped. A common reason is that an account used by the flow hasn't been authorized yet; connect the account and run again.

## Next steps

- [Schedules & Triggers](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-schedule-and-triggers.md) — set up automatic runs
- [Manage & Share](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-manage-and-share.md) — enable/disable, delete, share
- Back to [Workflow Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-overview.md)
