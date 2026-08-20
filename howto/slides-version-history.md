# AI Slides — Version History

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: History, Save Point, version, rollback
> User loop: Versions saved automatically while editing → open the History panel from the top of the workspace → preview a Save Point → roll back to an earlier version → keep editing

## Prerequisites

- You've made several rounds of edits in an AI Slides project

## Why version history matters

- **Experiment boldly**: With Save Points, you can let AI make sweeping changes with confidence — roll back anytime if you don't like the result
- **Save credits**: Rolling back to an earlier version is free, far cheaper than asking AI to regenerate
- **Compare and choose**: Compare different versions and keep the best one

## What is a Save Point

Each time the Agent finishes a round of edits, it automatically creates a Save Point — a restore point for the deck's state at that moment. You can roll back to any historical version at any time.

**Manual edits and AI edits share the same history**: changes you make in the built-in editor (Edit mode) also enter the History, and can be previewed and rolled back the same way.

## Steps

### 1. View the version history

Click the **"History" button at the top of the workspace** (alongside Present and Export) to open the version history panel, which lists all Save Points with the current version tagged **Current**.

### 2. Preview a historical version

Click a Save Point to preview the deck's state at that moment (previewing does not affect the current version).

### 3. Roll back to a historical version

Select the target version and perform the rollback; a confirmation dialog (**"Revert to Previous Version"**) appears — confirm to roll back. The rollback creates a new Save Point, and all existing historical versions are kept.

### 4. Keep editing

After rolling back, continue editing normally — new edits create new Save Points.

## FAQ

**Do I need to save versions manually?**
No. Save Points are created automatically after each of the Agent's editing rounds; manual changes in the built-in editor are auto-saved into the same history too.

**Will newer versions be lost after a rollback?**
No. The rollback itself creates a new Save Point, and all subsequent versions are preserved.

**What if I regret the rollback?**
Open the History panel again anytime and roll back to a different version. All versions remain — nothing disappears because of a rollback.

**Does rolling back cost credits?**
No. Rolling back to a historical version is free — far cheaper than regenerating.

**What if I just want to undo my last action?**
Inside the built-in editor (Edit mode), every action can be undone/redone directly — no need to touch version history. History is for returning to an earlier overall state.

## Next steps

- Happy with the result and ready to send it out? See [Export, Share & Reuse](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-export-and-share.md)
- Want to present the deck fullscreen right away? See [Presenting](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-present.md)
