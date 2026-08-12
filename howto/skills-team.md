# Skills — Team Skills (Create, Review & Manage)

> For Buddy Agent internal use.
> type: howto | feature: skills | keywords: Team Skills, Teams, Review, Governance, Admin, Create Team Skill, Manage
> User loop (creator): + New Skill → Create for Team → agent guidance → submit for review → approved → available to the team
> User loop (admin): Team Skills admin page → set policy → review submissions → manage the published library

## Why use Team Skills

- **Unified team workflows**: Skills are published after admin review, ensuring consistent quality across all members
- **Knowledge capture**: Turn your top performers' working methods into Skills so new hires can get up to speed instantly
- **Access control**: Admins decide which Skills are available to the team and which require review

## Prerequisites

- Requires a **Team Plan** (without one, you'll be redirected to the upgrade page)
- Creator: any team member
- Admin: Team Owner or Admin

---

## Part 1: Create a Team Skill (member view)

### 1. Click "+ New Skill" → "Create for Team"

In the dropdown menu this appears as **"Create for Team"** (with a "Team Plan" badge; the specific team name is not shown). The system launches the skill-creator Agent and opens the conversation view. The flow is the same as creating a personal Skill (see [skills-create.md](https://page.gensparksite.com/manual/buddy-guides/v1/en/skills-create.md)).

![+ New Skill dropdown Create for Team (Team Plan badge)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34218/246f9ee7.png)

### 2. Agent-guided creation

Chat with the Agent to describe the Skill's purpose, inputs and outputs, and tool permissions. The Agent automatically generates the SKILL.md.

### 3. Submit for review

Once created, the Skill is automatically submitted to the team review queue. Its status becomes **"Pending Review"**.

You can see this Skill in the My Own Skills tab, marked as pending review.

### 4. Wait for review

After an admin approves it, the Skill appears in the **Team Skills** tab and becomes visible to all team members.

If it's rejected, you'll get a notification and can revise and resubmit.

---

## Part 2: Review & Manage (admin view)

### 1. Open the Team Skills admin page

Entry point: `/payment/team_skills` (accessible from Team settings or the Skills page).

The admin page is titled **"Skills"** (not "Team Skills") and has three tabs:
- **Review**: Skill submissions awaiting review
- **Library**: Skills that have been approved
- **Settings**: policy settings

![Team Skills admin page (Review/Library/Settings)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34218/8526e5e5.png)

### 2. Review Skill submissions

In the Review tab, view Skills submitted by members:

1. Click a pending item to open the **review detail**
2. Review the Skill content: name, description, instructions, tool permissions
3. Choose an action:
   - **Approve**: approved → the Skill is published to the Team Skills tab
   - **Reject**: rejected → the submitter is notified

### 3. Manage published Skills

In the Library tab:
- View all published Team Skills
- Unpublish Skills that are no longer needed
- View install/usage statistics

### 4. Configure publishing policy (Settings)

Admins can set:
- **Whether review is required**: when enabled, all Team Skill submissions require review; when disabled, they're published automatically

Connector management lives on a separate page, **`/payment/team_connectors`** (not inside team_skills Settings), controlling which Connectors are visible to members (member-level visibility, not per-Skill restrictions).

![Connector ACL management page](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34218/c9ef46b4.png)

---

## Part 3: Team members install and use

### 1. Browse Team Skills

On the Skills home page, switch to the **Team Skills** tab to see all admin-approved Skills.

![Team Skills tab (empty state)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34218/262c353a.png)

### 2. Install

Click the **"Add"** button to install it to your personal account.

### 3. Version updates

When the Skill author publishes an update, you'll see an **"Update available"** prompt; click it to get the latest version.

---

## Notes

- Users without a Team Plan who click "Create for Team" will open the `/team_pricing` upgrade page in a new tab

![Team Plan upgrade page](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34218/1525fb89.png)

- Team Skills and personal Skills don't affect each other—a Skill installed from the Team is a copy (copy_skill_subtree); uninstalling only removes the local record and doesn't affect the team library
- Admins control which Connectors are visible to members on the `/payment/team_connectors` page (member-level visibility control)

---

## Screenshot checklist

| # | Screenshot ID | Capture location | What must be visible in the screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `team-create-option` | + New Skill dropdown | "Create for Team" (Team Plan badge) option | Show the team creation entry point |
| 2 | `team-review` | Team Skills admin page Review tab | Pending Skill list, status markers | Show the review queue |
| 3 | `team-review-detail` | Review detail page | Skill content preview, Approve/Reject buttons | Show review actions |
| 4 | `team-library` | Library tab | Published Skill list, install statistics | Show the approved library |
| 5 | `team-settings` | Settings area | Review policy toggle, Connector allowlist | Show admin settings |
| 6 | `team-member-tab` | Regular member Team Skills tab | Team Skill cards, Add/Update buttons | Show the member view |
