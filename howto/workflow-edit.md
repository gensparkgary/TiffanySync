# Workflow — Editing a Workflow

> For Buddy Agent internal use.
> type: howto | feature: workflow | keywords: edit, Configure, three-dot menu, node, Node, canvas, Canvas, step, Add step, save
> User loop: My Workflows → ⋯ → Configure to open the editor → change steps → re-run to confirm it works

## Why edit

- **Fine-tune steps**: An AI-generated flow won't always be perfect on the first try — you can add, remove, or edit steps and adjust the specific instructions for each one
- **Keep refining via chat**: You can keep describing what you need in the chat box and let the AI adjust the flow for you
- **Add new steps**: Use **Add step** in the editor to insert new actions into the flow

## Prerequisites

- Entry: `/workflows`
- At least one existing Workflow

## Steps

### 1. Open the editor (Configure)

In the **My Workflows** list, find the Workflow you want to change, click its **three-dot menu ⋯**, and select **Configure** to reopen the editor for that Workflow.
![Three-dot menu ⋯ → Configure to open the editor](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/6d968e2f.png)

### 2. Edit the steps

View and modify each step of the flow in the editor. You can:
- Keep describing what you want in natural language in the chat box on the left and let the AI adjust the flow
- Directly edit the content of a step node
- Use **Add step** to add new action steps to the flow
![Steps in the Workflow editor (STARTER / ACTIONS / Add step)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35763/caa59c82.png)

### 3. About the Workflow name

A Workflow **has no separate rename control** — the ⋯ menu only has Configure / Test run / Delete, and there's no editable name field in the editor either. The name shown in the list is **automatically taken from your original task description text**. If you want a different name, write a clear description when you create it; for existing Workflows, the name follows the original description.

### 4. Verify after editing

After editing, we recommend using **Test Run** to re-run with simulated data and confirm the changes work as expected (see [Run & History](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-run-and-history.md)).

> Editing steps and saving are free; **Test Run consumes credits** (it actually runs the AI steps); a live run also consumes credits based on task complexity.

## FAQ

**Q: Where do I open the editor?**
In the My Workflows list, click the Workflow's three-dot menu ⋯ and select Configure to reopen the editor.

**Q: Does editing steps cost credits?**
Editing steps and setting triggers are free; **both Test Run and live runs consume credits based on task complexity**.

**Q: Can I rename a Workflow?**
There's currently no separate rename control. The name is automatically taken from your original task description text, and the ⋯ menu only has Configure / Test run / Delete.

**Q: How do I confirm I didn't break anything after editing?**
Use Test Run to re-run the logic with a simulated trigger (**this consumes credits**), and once it checks out, let it run for real.

## Next steps

- [Schedules & Triggers](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-schedule-and-triggers.md) — set up automatic runs
- [Run & History](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-run-and-history.md) — full runs and viewing results
- [Manage & Share](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-manage-and-share.md) — enable/disable, delete, share
- Back to [Workflow Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/workflow-overview.md)
