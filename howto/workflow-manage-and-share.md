# Workflow — Manage & Share

> For Buddy Agent internal use.
> type: howto | feature: workflow | keywords: manage, My Workflows, View All, Active, Stopped, enable, disable, disable from chat, three-dot menu, Configure, Test Run, Delete, share, Share
> User loop: My Workflows → enable/disable, Configure, Test Run, Delete, Share

## Why You Need to Manage

- **Centralized management**: All your Workflows live in My Workflows for unified viewing and operation
- **Temporary pause**: When you don't want to delete a Workflow but want to stop running it for now, just disable it (Stopped)
- **Reuse and collaboration**: Share a finished Workflow with others

## Prerequisites

- Entry: `/workflows` → **View All** to open My Workflows
- At least one existing Workflow

## Steps

### 1. Open My Workflows

Go to `/workflows` and click **View All** to see your full list of Workflows.
![My Workflows list](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/41656a57.png)

### 2. Enable / Disable (Active / Stopped)

Use the toggle to control whether a Workflow is enabled: enabled is **Active**, disabled is **Stopped**. Once disabled, it no longer runs automatically, but its configuration is retained and you can re-enable it anytime.

Besides the toggle, you can also **ask in a conversation to disable it** — in the Workflow editor's chat box, or in a Super Agent conversation, just say "turn off this Workflow". For safety, conversations can only disable, never re-enable; to resume runs, go back to the UI and flip the toggle on manually.

### 3. Edit (⋯ → Configure)

Click a Workflow's **three-dot menu ⋯** and select **Configure** to reopen the editor for changes (see [Edit Workflow](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-edit.md)).

### 4. Test Run (⋯ → Test Run)

Three-dot menu ⋯ → **Test Run** validates the Workflow with mock data without triggering real actions (see [Run & History](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-run-and-history.md)).

### 5. Delete (⋯ → Delete)

Three-dot menu ⋯ → **Delete** permanently removes a Workflow. Deletion warns that the Workflow and its automation will be permanently removed, so proceed with caution.

> Deletion can't be undone — before deleting, consider disabling (Stopped) instead.

### 6. Share

In the editor, click **Share** to open the share dialog: it shows **People with access** (including the Owner), with **General Access** defaulting to **Restricted** ("Only people with access can open with the link"). Click **Copy link** to copy the link, or **Done** to close.
![Share dialog (People with access / General Access: Restricted / Copy link)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/83bc0047.png)

> Management actions (enable/disable, Configure, delete, share) are free; **Test Run consumes credits** (it actually runs the AI steps); real runs also consume credits based on task complexity.

## FAQ

**Q: What's the difference between disabling and deleting?**
Disabling (Stopped) only pauses automatic runs; the configuration is retained and can be restored to Active anytime. Deleting permanently removes the Workflow and its automation and can't be undone. When in doubt, disable first.

**Q: Can I ask in a conversation to stop a Workflow?**
Yes. In that Workflow editor's chat box, or in a Super Agent conversation, say "disable this Workflow" to turn it off; but re-enabling can only be done manually with the toggle in the UI.

**Q: Where can I see all my Workflows?**
Click View All on `/workflows` to open My Workflows.

**Q: Where do I edit, Test Run, or delete?**
All in the Workflow's three-dot menu ⋯ — the ⋯ menu has **only these three items**: Configure (edit), Test Run, and Delete (there's no Rename; the name is auto-derived from the description).

**Q: Do management actions consume credits?**
Enable/disable, Configure, delete, and share are free; but **both Test Run and real runs consume credits based on task complexity**.

## Next Steps

- [Create Workflow](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-create.md) — Create a new Workflow
- [Schedule & Triggers](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-schedule-and-triggers.md) — Set up automatic runs
- [Run & History](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-run-and-history.md) — Run and view results
- Back to [Workflow Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-overview.md)
