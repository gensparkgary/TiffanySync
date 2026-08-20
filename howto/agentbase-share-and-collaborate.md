# Dashboards & CRM — Sharing & Collaboration

> For Buddy Agent internal use.
> type: howto | feature: agentbase | keywords: share, collaboration, share, invite, invite, link, Copy link, role, Viewer, Editor, Owner, team, permissions, public link, dashboard sharing
> User loop: In the workspace → open Share → copy the link or invite by email → set roles (Viewer / Editor / Owner) → teammates work together based on their permissions

## Why use it

- **Teammates work in the same system**: Share a workspace and your team sees the same live data — no more passing files back and forth or chasing versions.
- **Grant exactly the right access by role**: Let some people edit and others only view, so everyone has the right access and your data stays safer.
- **Collaboration is just a link or an invite**: Sharing a system is as simple as sharing a document.
- **Dashboards can be handed out on their own**: A finished dashboard can be shared read-only by itself — even to people without an account — without opening up the whole workspace.

## Prerequisites

- You need to be signed in and be the owner of a workspace (first [create a system](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-create-a-system.md))
- Entry point: open Share in the workspace
- Sharing, inviting, and changing roles are all **free** (no AI calls)

## Steps

### 1. Open Share

Open the **Share** dialog in your workspace.

![Share dialog: ① Copy link ② Invite by email ③ Member and role list](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/2032fa93.png)

### 2. Option A: Share by copying the link

Click **Copy link** to copy this workspace's link and send it to the people you want to collaborate with. They can open the link to access it (within the permissions you've granted).

> If a person hasn't been granted access, opening the link shows a "no access" card — you'll need to invite or authorize them first.

### 3. Option B: Invite by email and set a role

In the Share dialog, enter your teammates' emails to invite them (you can enter several at once), and choose a role for each from the role dropdown — there are three:

| Role | What they can do |
|------|---------|
| **Viewer** | View only, no changes |
| **Editor** | View + edit data and change views |
| **Owner** | Owner permissions, including managing members, changing others' roles, and deleting the workspace |

(You're the Owner by default when you create a workspace. Use Editor for teammates who collaborate on the data, Viewer for people who only read reports, and Owner only when you need another full administrator.)

![Role dropdown: Viewer / Editor / Owner roles](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/3dc83617.png)

### 4. Manage members and roles

The member list shows everyone's role. As the owner, you can **adjust someone's role** or remove a member at any time.

Beyond the overall role, you can also fine-tune a member's access **down to individual dashboards and tables** — for example, let them see only one specific dashboard, or hide certain tables from them entirely. Select the member in the Share dialog to set this per item.

### 5. Share a single dashboard (read-only link, works without an account)

A finished dashboard can be shared read-only **on its own, without opening the whole workspace**: open that dashboard's share entry and set its access level — restrict it to invited members, or set it so **anyone with the link can view it (no sign-in required)** — then send out the generated link.

People who open the link:

- can only **view** this dashboard — no data changes;
- see nothing else in the workspace — **the underlying data tables are never exposed through these links**.

To stop sharing, just change the access level back — links you've already sent out **stop working immediately**.

> If your account belongs to a team/organization space, this link-sharing capability may need to be enabled by your organization admin first; personal accounts are not affected.

### 6. The recipient's side

A workspace someone shares with you appears in the **"Shared with me"** section of your home page (this section is hidden until someone shares with you — it only appears once you receive your first share).

- If you're a **Viewer**, the interface scales back accordingly (read-only, no edit actions shown).
- If you no longer want to keep a workspace someone shared with you, you can **Leave** (with a confirmation prompt).

## FAQ

**What's the exact difference between Editor and Viewer?**
An Editor can both view and change data and views; a Viewer can only view, with no changes. Assign as needed — Editor for teammates collaborating on the data, Viewer for people who only need to read reports.

**Will sharing leak all my data?**
The recipient can only access this one workspace within the role you granted, and you can further narrow a specific member's access per dashboard and per table. A Viewer can't change anything, and you can adjust roles or remove members at any time.

**Can I show a dashboard to someone who has no Genspark account at all?**
Yes. Set that dashboard's access to "anyone with the link" and they can view it without signing in — read-only, that one dashboard only, and revocable at any time (old links stop working immediately once revoked).

**Do sharing and inviting cost credits?**
No. Sharing links, inviting, and changing roles are all free and don't call AI.

**Where do I see systems others have shared with me?**
In the "Shared with me" section of the home page. If you no longer want one, you can Leave.

**Can I give owner permissions to someone else?**
The role dropdown has an **Owner** option, so you can set a member as Owner, giving them the ability to manage members and delete the workspace too. If they just need to collaborate on the data, Editor is enough.

## Next steps

- Haven't built a system yet? First [create a system](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-create-a-system.md)
- Keep a shared system's data automatically up to date → [Automate workflows](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-automate-workflows.md)
- Want the big picture on this product → [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-overview.md)
