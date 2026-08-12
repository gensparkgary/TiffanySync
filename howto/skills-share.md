# Skills — Share a Skill

> For Buddy Agent internal use.
> type: howto | feature: skills | keywords: Share, Share, Public Link, Team Publish, Peer Share, Invite
> User loop: Select a Skill → Share → Choose how to share (Email / Team / Public link) → Recipient receives it → Preview → Install → Use

## Why Share a Skill

- **Standardize your team**: One person builds a great Skill, and the whole team works from the same process with consistent output quality
- **Skip repetitive work**: No need for everyone to build from scratch — share once and everyone benefits
- **External collaboration**: Share via Public Link with clients and partners without requiring them to join your team

## Prerequisites

- At least one Skill in My Own Skills
- Team Publish requires the Team Plan
- Entry point: the **"Share"** button on the Skill detail page

![Share button location (My Own Skills card)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34217/a9f0fddd.png)

## Three Ways to Share

The Share dialog has three tabs, in order: **Email** (default) → **Team** → **Public link**.

![Three tabs in the Share dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34217/111a2dec.png)

### Option 1: Peer Share (Email Invite)

The default tab. Share directly with specific people via an email invite.

#### 1. Open the Share dialog

On the Skill detail page or in My Own Skills, click the **"Share"** button. The dialog opens to the **Email** tab by default.

![Email/Peer Share tab](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34217/69fe3658.png)

#### 2. Enter the recipient's email

Enter the recipient's registered Genspark email. You can include a message to explain.

#### 3. Send the invite

Click send. The recipient gets an invite notification.

#### 4. Recipient accepts

The recipient sees the invite in the **"Shared with me"** section of the Skills home page → clicks **"Accept"** → the Skill is installed to their account.

Invites are valid for 30 days. The recipient can also Decline. The recipient must be a registered Genspark user.

### Option 2: Team Publish

Publish a Skill to your team so all team members can see it automatically. Requires the Team Plan.

#### 1. Publish to your team

In the Share dialog, switch to the **"Team"** tab and click **"Publish to Team"**.

![Upgrade prompt on the Team tab](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34217/7b5d222a.png)

#### 2. Review process

If your team admin has enabled review:
- The Skill enters the review queue
- The admin reviews it on the Team Skills management page
- Once approved, the Skill appears in every member's **Team Skills** tab

If review is not enabled, the Skill is visible to the team immediately after publishing.

#### 3. Team members install it

Members see the published Skill in the Team Skills tab → click **"Add"** → it installs to their personal account → use it in the SkillBar.

#### 4. Version updates

After you update a Skill, team members see an **"Update available"** prompt and can click to update to the latest version.

### Option 3: Public Link

The simplest way to share. Generate a link that anyone can open to preview, then install after logging in.

#### 1. Switch to the Public link tab

In the Share dialog, switch to the **"Public link"** tab.

#### 2. Generate the link

Click the **"Create public link"** button. The system generates a `https://www.genspark.ai/skills/share/{token}` link and displays the install count and creation time.

Copy the link and send it to the recipient.

![Generated public link result (Copy/Regenerate/Revoke)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34217/a7aed769.png)

#### 3. Recipient receives it

When the recipient opens the link, they see the Skill preview page (titled "SHARED SKILL", viewable anonymously), including the name, description, and the collapsible SKILL.md source. They click **"Add to my skills"** → log in → the Skill installs to their account (a snapshot copy that does not sync in real time).

![Public preview page (SHARED SKILL + Add to my skills)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34217/fec195cd.png)

#### 4. Manage the link

- **Regenerate**: Generate a new link token (the old link becomes invalid immediately). There is no confirmation step, so proceed with care.
- **Revoke**: Revoke the link (a native browser confirmation dialog appears). Once revoked, the link is invalid, but users who already installed it are unaffected. The dialog does not auto-refresh after revoking — refresh the page to see the latest status.

## Notes

- For Skills shared via Public Link, the recipient installs a snapshot copy (pinned to source_commit_sha) that does not sync in real time
- Skills shared via Team Publish have a version-update mechanism (comparing installed_commit_sha vs reviewed_commit_sha), so members can get the latest version
- Peer Share requires the recipient to be a registered Genspark user (an unregistered email triggers a RecipientNotRegisteredError)

---

## Screenshot Checklist

| # | Screenshot ID | Capture location | Must be visible in the screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `share-modal` | Full Share dialog | The three tabs: Email / Team / Public link (Email by default) | Show the three sharing methods |
| 2 | `share-public-link` | Public link tab | The generated link, Copy button, Regenerate/Revoke buttons, install count | Show public link actions |
| 3 | `share-public-preview` | `/skills/share/{token}` preview page | The "SHARED SKILL" title, Skill name, description, "Add to my skills" button | Show the page the recipient sees |
| 4 | `share-team-publish` | Team tab | Publish to Team button (or published state) | Show team publishing |
| 5 | `share-peer-email` | Email tab | Email input field, message input, Send button | Show the email invite |
