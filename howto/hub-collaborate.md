# Hub — Team Collaboration

> For Buddy Agent internal use.
> type: howto | feature: hub | keywords: Hub, members, invite, collaboration, team, permissions, Leave Hub, Delete Hub
> User loop: Invite colleagues to the Hub → colleagues see shared files and history → the team works in the same space as a relay → manage members (remove/leave)

## Why Use a Hub for Collaboration

When a team works around the same project, the biggest waste is everyone maintaining their own copy of materials and repeatedly re-explaining context. Bring your team into the same Hub, and everyone sees **the same files and the same conversation history**. Anyone can pick up and continue on any project—project progress belongs to the whole team, not locked away in one person's conversation.

## Prerequisites

- Entry: `https://www.genspark.ai/hub`, then open the Hub you created
- Requirements: a logged-in account; only the **Hub creator (Owner)** can invite and remove members

## Steps

### 1. Invite Members

Open your Hub, click **Members** to bring up the "Hub Members" modal → click **Invite**, then enter the person's email address to invite them. Once the invitation is sent, you'll see "Invitation email sent…", and the invitee appears in the member list with a **Pending** status, turning into a full member once they accept.
![Invite members (Members → Invite → enter email, with permission notes)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35760/95ec14d9.png)

You can also invite directly from within a project; or move an existing project that already has members into the Hub, and those members automatically gain access to that Hub.

> Each Hub supports up to 200 members, and you can invite up to 50 emails at a time.

### 2. What Members Can Do

Once they join, members can view all files in the Hub, access the conversation history of all projects, continue working on any project, and create new projects with shared context. Members can also manage files and edit the Hub's basic info and Custom Instructions. The invite modal includes this "what members can / can't do" permission allowlist, so you can check it before inviting.

What members **cannot** do: invite or remove other members, archive or unarchive the Hub, or delete the entire Hub. These are reserved for the creator.

| | Creator (Owner) | Member |
|---|---|---|
| View files / project history | ✅ | ✅ |
| Work on projects / create new projects | ✅ | ✅ |
| Manage files / edit Hub info / edit instructions | ✅ | ✅ |
| Invite / remove members | ✅ | ❌ |
| Archive / unarchive Hub | ✅ | ❌ |
| Delete Hub | ✅ | ❌ |
| Leave Hub | ❌ (can only delete) | ✅ |

> Not sure who to give which permissions? There are currently only two roles: the creator holds member management and deletion rights, and members have all the other collaboration capabilities.

### 3. Remove Members (Creator Only)

On the Hub home page, click **Members**, then click the trash can icon next to a member → **Remove**.

### 4. Leave a Hub (Members)

Members can leave in two ways:
- **On the Your Hubs page**: hover over the Hub → **⋯ → Leave Hub**
- **Inside the Hub**: top-right **⋯ → Edit Hub → Leave Hub**

> The Hub creator cannot leave their own Hub—they can only delete it.

### 5. Delete a Hub (Creator Only)

Top-right **⋯ → Delete Hub**. A confirmation dialog pops up ("Delete this hub? … This action cannot be undone."), and once confirmed, all files and projects in this Hub are deleted along with it, with no way to undo.

> If the project has just wrapped up and you're not ready to delete, the creator can **archive** instead (⋯ → Archive hub): the Hub moves to the Archived tab with everything kept, and can be restored anytime. See [Working in a Hub](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-work.md).

## FAQ

**Who can invite and remove members?**
Only the Hub creator (Owner). Members can collaborate, but they can't manage other members or delete the Hub.

**Does inviting members or collaborating cost credits?**
Inviting, removing, and leaving are all free. Each member consumes credits based on their own conversations within the Hub.

**Can the creator leave their own Hub?**
No. The creator can only delete the Hub (which deletes all files and projects along with it, and cannot be undone).

**Can members delete my files or projects?**
Members can manage files, but they can't delete the entire Hub. Deleting a Hub is reserved for the creator.

## Next Steps

- [Set Up Your Hub](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-setup.md) — create, upload files, Custom Instructions
- [Working in a Hub](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-work.md) — Recent Tasks, referencing history across projects, project ownership
- [Hub Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-overview.md)
