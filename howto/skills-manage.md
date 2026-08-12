# Skills — Managing Skills

> For Buddy Agent internal use.
> type: howto | feature: skills | keywords: manage, Uninstall, Delete, Manage Skills, uninstall
> User loop: Manage Skills → view installed list (Installed/Received/Sent) → Uninstall/Delete → return to home page to confirm it took effect

## Why manage Skills

- **Control what's installed**: Uninstall Skills you don't need to keep the selection panel tidy
- **Edit and improve**: If a Skill's instructions aren't quite right after creation, edit and refine it
- **Clean up unused ones**: Delete Skills you no longer need to keep your workspace clean

## Prerequisites

- At least one installed Skill
- Entry point: the **"Manage Skills"** button at the top of the `/skills` page

## Steps

### 1. Open the management dialog

Click the **"Manage Skills"** button at the top of the Skills home page to open the Skills management dialog (titled **"Skills"**).

![Location of the Manage Skills button (top navigation bar)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34214/1b5edd3b.png)

The dialog is divided into three tabs by sharing status:
- **Installed** — all Skills you've installed (Community, your own, and team Skills)
- **Received** — Skill invitations others have shared with you via email
- **Sent** — Skills you've shared with others via email

There's a search box at the top of the dialog so you can search Skills by name.

![Management dialog: Installed/Received/Sent tabs and the list of installed Skills](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34214/c225de7e.png)

### 2. Uninstall

Hover over a Skill card and the button label changes from **"Added"** to **"Uninstall"**. Click it to uninstall. Once uninstalled, the Skill is removed from the SkillBar's selectable list.

![Hovering over a Skill card shows the Uninstall button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34214/eb519c2e.png)

Community / Team Skills can be reinstalled at any time after being uninstalled.

### 3. Modify a Skill you created

Installed Skills (including ones you created) **currently do not support online editing**.

To modify a Skill you created:
1. Edit the Skill files locally (the instructions, trigger words, output format, etc. in SKILL.md)
2. **Delete** the old version (see Delete below)
3. Re-upload the modified files via **+ New Skill → Upload**

Community or team-installed Skills likewise can't be edited.

### 4. Delete (My Own Skills only)

For Skills you created, click **"Delete"** to remove them. Deletion cannot be undone.

## Notes

- For a Team Skill, if the author publishes a new version, you'll see an **"Update available"** prompt
- After editing your own Skill, if it has already been Team Published, team members need to manually Update to get the changes

![Tabs based on sharing status in the management dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34214/0d6ccf34.png)

---

## Screenshot checklist

| # | Screenshot ID | Capture location | Must be visible in the screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `manage-list` | Manage Skills dialog | Installed/Received/Sent tabs, Skill list, search box | Show the full management interface |
| 3 | `manage-update` | Team Skill update prompt | "Update available" badge | Show the version update prompt |
