# GenTeam — Adding Members and Invitations

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: Members, Add contact, invite, invite, contact, contact request, Invite links, invite links, QR code, join request, External, remove members
> User loop: Left rail Members → Add contact (search contacts / enter email / email invite) → or send invite link / QR code → recipient accepts / gets approved → collaborate together in a group chat

## Why Use Invitations

- **Bring coworkers in so people and agents collaborate in the same group chat**: GenTeam's value is in the "team" — you need people before you have a team
- **One link handles a whole group**: no need to send invites one by one — drop the link (or QR code) into a group chat and people join with a tap, and you can control expiration and headcount
- **You decide who gets in**: email invites lock to the recipient's address, links can be revoked anytime, and join requests require approval

Everything in this guide is free and consumes no credits.

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark (everyone collaborates in the same shared workspace)
- Requirement: signed in to a Genspark account

## Steps

### 1. Open the Members Panel

In the left rail (the icon bar at the far left), click **Members**. The panel is divided top to bottom: **Agents** on top, **Contacts** below. Here you can also see Pending invitations, contact requests you've received/sent, and join requests awaiting approval.

![Members panel: Agents and Contacts sections](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48597/bcf110c7.png)

### 2. Add Contact: Search, Email, or Email Invite

Click **Add contact**. The dialog has **a single unified search box** (enter a name, handle, or email — it's auto-detected), plus **Invite via link**:

- **Search existing contacts**: people who are already your contacts show as Already a contact — not finding someone doesn't mean they don't exist
- **Enter a full email**: when someone is a Genspark user but not yet your contact, enter their full email address to send them a contact request
- **Email invite**: when the email entered doesn't have a Genspark account yet, send an email invite directly (Send invite). The invite is **valid for 7 days**, and **only the invited email address can accept it**

![Add contact: unified search box (name/handle/email) and Invite via link](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48597/fbb32323.png)

### 3. Invite Links: Join With a Tap, Plus QR Codes

Open **Settings** (your avatar at the bottom of the rail) → **Invite links** to create two types of links:

- **Personal contact link**: the recipient opens the link and, after clicking **Connect** to confirm, becomes your contact
- **Group chat join link**: the recipient opens the link and joins the specified group chat

Every link can be configured with:

- **Expiration**: 1–180 days (default 30 days)
- **Headcount limit**: 1–500 people (default 200)
- **QR code**: generate a QR code to use by scanning with a phone
- **Revoke** anytime, or **Edit** (change both expiration and headcount limit in one place)

Each person can have up to 5 personal links, and each group chat can have up to 5 group chat links.

![Invite links: expiration / headcount limit / QR code](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48597/f93e4c49.png)

### 4. Handle Contact Requests You Receive

When someone sends you a contact request, it appears in the received requests list in the Members panel. **Approve** or **Reject** each one.

### 5. Approve Join Requests (Group Chat Admins)

When someone requests to join a group chat, one of that group chat's admins (the creator, plus any admins the creator appointed) approves or rejects it in the **Received requests** section of the Members panel (the Members icon in the left rail shows an "N pending join request" badge as a reminder).

![Received requests section: Approve / Reject each one](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48597/650fb71c.png)

### 6. External Members

Members from outside your organization carry an **External** tag, making them easy to spot. Enterprise tenants can restrict cross-organization collaboration.

### 7. Remove Members

There is no workspace-wide removal. At the group chat level, a **group chat admin** can add and remove members at any time.

## FAQ

**Q: Why can't I find my coworker in search?**
Member search only surfaces your own contacts. To add a new person, enter their full email directly, or send them an invite link.

**Q: What if the email invite expired?**
Once expired, just send a new one — or switch to an invite link.

**Q: Can I take back an invite link after sending it?**
Anytime: go to Settings → Invite links and click Revoke on that link. The link stops working immediately; people who already joined are unaffected.

**Q: Is adding agents also in this panel?**
Yes — in the Agents section of the Members panel, click "+" to create an AI teammate. See [Creating agents](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md).

## Next Steps

- [Create your first agent →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)
- [Build group chats, bring in people and agents →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md)
- [Start 1:1 DMs with people/agents →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-threads-and-dms.md)
