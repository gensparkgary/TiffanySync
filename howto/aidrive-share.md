# AI Drive — Sharing Files

> For Buddy Agent internal use.
> type: howto | feature: aidrive | keywords: drive, share, share link, invite, permissions, Can view, Can edit, General access, Anyone with the link, Restricted, Shared with me, collaborate, Remove, Stop sharing
> User loop: Select file/folder → Share opens the access panel → invite by email (view/edit) or set General access → Copy link and send it → recipient opens it from "Shared with me" (browse/download/edit) → remove access or set back to Restricted in the same panel to stop sharing

## Why use AI Drive sharing

- **Send one link**: No need to download then attach the file — every file/folder has a copyable link.
- **Precise control over who can access and what they can do**: Invite specific people by email (view-only or editable), or open it up to anyone with the link; inside an organization you can open it to all members in one step.
- **Folders support collaboration**: Share a folder with "Can edit" access and the other person can add and organize files right inside the shared folder — no more sending files back and forth.

## Prerequisites

- You must be logged in
- You already have a file or folder to share (entry point: `https://www.genspark.ai/aidrive/files`)

## Steps

### 1. Select a file and open Share

Select a file or folder and click **"Share"** (top action bar). The share panel that opens (subtitle: "Share and collaborate with others on Genspark.") is the single place to manage all access to that item: invite specific people, set the overall access scope (General access), and copy the link.
![Share panel: email invite + People with access + General access + Copy link](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51181/cc459acb.png)

> Note: opening the share dialog does **not** automatically create a public share — the default is Restricted (only you and the people you invite can open it). To open up access, you change General access yourself.

### 2. Invite by email (view or edit)

At the top of the dialog, enter the person's email ("Add by email"), pick a permission next to it — **Can view** or **Can edit** (the permission dropdown defaults to **Can edit**) — and click **Share**.

- The person is notified, and the shared item appears in the **"Shared with me"** tab of their own Drive.
- If they don't have a Genspark account yet, the entry is marked pending ("pending sign-in") — access starts at their first sign-in.

### 3. View and manage "People with access"

The **People with access** section lists the owner and everyone with access, along with their permission (Can view / Can edit). Click **Remove** on a row to take that person's access away. Rows granted through a group or organization are managed by an admin and can't be removed here individually.

### 4. Set General access (overall scope)

**General access** controls whether people outside the list can open the item:
- **Restricted** (default): only the people listed above can open it (hint: "Only people added here can open it.").
- **Anyone in your organization**: every active member of your organization can open it, with view or edit permission. It takes effect only if your account belongs to an organization — accounts without an organization still see this option in the dropdown, but selecting it has no practical effect.
- **Anyone with the link**: anyone signed in to a Genspark account who has the link can view it (link access is view-only, never edit).

### 5. Copy the link and send it

Click **"Copy link"** to copy the item's link. The link itself carries no access — when someone opens it, the server decides based on who they are: with access they land on the content, without it they see "You can't open this" and need to ask you to share.

### 6. Download toggle for single files

When sharing a **single file**, the bottom of the panel has a **"Let viewers download the file"** toggle controlling whether viewers can download it; when turned off, people opening the link are told the owner turned off downloads.

### 7. How the recipient opens it

- **Folder**: it appears in the **"Shared with me"** tab of their Drive, where they can browse and download the files inside; people with **Can edit** can also upload files, create folders, and delete files in it.
- **Single file (via link)**: opening the link gets them the file directly, if the download toggle allows it.
![Recipient view: shared content opened from the "Shared with me" tab](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51181/94a639f1.png)

### 8. Stop sharing

- **Remove one person**: click **Remove** on their row in People with access.
- **Take back link/organization access**: set General access back to **Restricted** — this is the authoritative way to revoke a link share (once set back, the link stops granting access).
- **Legacy link shares only**: the share management page (`/aidrive/shares`, "Shared" in the Drive "⋯" menu) holds only share records from the older sharing model, with **Copy link** / **Revoke**. Link shares created in the current share panel do **not** appear on that page — manage them in the share panel instead.
![Legacy share management page (/aidrive/shares): legacy link-share records only](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51181/f3ee9eb8.png)

## Notes

- Sharing **does not consume credits** — it's free.
- Link access requires the visitor to **sign in to a Genspark account** — it's not fully anonymous access.
- **Shared folder contents still live in your Drive**: they count against your storage space, and anything an editor deletes lands in your Trash, where you can restore it.
- Team/enterprise organizations may restrict public sharing (allowing sharing only with members within the organization) — if you run into a restriction, invite organization members by email instead.
- The **"Anyone in your organization"** option is shown in the General access dropdown even for accounts that don't belong to any organization — selecting it there has no practical effect.

## FAQ

**Q: Can I stop a share after creating it?**
Yes. In the share dialog, Remove the invited people or set General access back to **Restricted** — that's the authoritative way to revoke a link share. Only legacy link shares from the older sharing model can be **Revoked** on `/aidrive/shares`; link shares created in the current panel don't appear on that page.

**Q: What can someone with "Can edit" do?**
Upload files, create folders, and delete files inside the shared folder — changes are visible to both sides. They cannot touch anything in your Drive outside the shared scope.

**Q: Can recipients still see the content after access is removed or revoked?**
No. After you remove their access, set General access back to Restricted, or Revoke a link, opening it again shows an access error (such as "You can't open this" or "Share Not Found").

**Q: What if the recipient doesn't have a Genspark account?**
You can invite them by email anyway — access starts automatically at their first sign-in after registering; link access likewise requires them to sign in to a Genspark account.

## Next steps

- [Upload and organize files](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-get-started.md)
- [Download content from a URL into your Drive](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-download-and-organize.md)
- [AI Drive overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-overview.md)

---

## Screenshot checklist

| # | Screenshot ID | Capture location | What must be visible in the screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `share-dialog` | Share dialog | Email invite box (Can view/Can edit), People with access, General access (Restricted/org/link), Copy link | Show share settings (existing screenshot shows the pre-redesign UI — needs re-capture) |
| 2 | `share-recipient` | Recipient's Shared with me | Shared folder under the "Shared with me" tab + browse/download (upload with edit access) | Show the recipient view (needs re-capture) |
| 3 | `share-manage` | `/aidrive/shares` | Legacy link-share records, Copy link / Revoke (link shares created in the current panel do not appear here) | Show legacy share management (needs re-capture) |
