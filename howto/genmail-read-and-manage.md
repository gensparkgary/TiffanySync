# Reading & Managing Email: List, Conversations, Cleanup Actions

> For Buddy Agent internal use.
> type: howto | feature: genmail | keywords: inbox, list, conversation, reading, translation, attachments, archive, delete, flag, Flag, star, bulk, multi-account, folders, Load images
> User loop: Open an email in the Mail view → understand the body and attachments → clean up (read/archive/flag/move/delete) → keep the inbox tidy

## Why read this first

- **See every mailbox in one interface**: mail from multiple Gmail and Outlook accounts is gathered into a single list, grouped by conversation and by time. No more bouncing between browser tabs or trying to remember which message lives in which account.
- **Cleanup costs nothing and works offline too**: marking as read, archiving, flagging, moving, and deleting are all free. When you're offline, actions are recorded locally first and sync automatically once you're back online — so you can clear your inbox anytime, anywhere, without worrying about credits or connectivity.

## Prerequisites

- Entry: first download and install the GenMail desktop client, sign in to your Genspark account, and connect your Gmail/Outlook mailbox (see [Install & Sign In](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md)). Once the app is open, click **Mail** in the left nav rail to enter the mail view.
- Requirement: signed in to your Genspark account with at least one mailbox connected. Cleanup actions are free for all accounts.

## Steps

### 1. Get to know the columns in the Mail view

After entering **Mail**, the interface reads left to right: the left nav rail, the folders & labels panel, the email list, and the conversation body that expands once you select a message. When the window is wide enough, the body gets its own column; on a narrow screen, tap a message to expand it. Everything about reading and cleanup in this guide happens inside **Mail**.

![GenMail inbox layout: ① multi-account & folders panel · ② All / Unread filters above the list · ③ top cleanup toolbar (Delete / Archive / Move / Flag)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/39038/d4a90586.png)

> Besides **Mail**, the nav rail may also show entries like **Calendar**, Super Agent, and Email Brain. Super Agent, Email Brain, and calendar-related AI capabilities are rolling out gradually and need to be enabled for your account, so whether they appear depends on what your app actually shows — not seeing them doesn't mean the feature is missing, it just hasn't reached your account yet.

### 2. Find mail in the list by time and status

The email list groups by conversation by default (multiple messages in the same thread merge into one entry) and groups by time into **Today / Yesterday / Older**. Unread mail carries a dot marker so it's easy to scan.

Above the list are filter chips — tap one to see only the matching mail:

- **All** — every email in the list
- **Unread** — only messages you haven't read yet

The list shows only **recent** mail by default to stay snappy (the exact range is whatever the interface shows). To see older messages, **just keep scrolling down and older mail loads automatically** (a `Loading…` indicator appears at the bottom) — no button to click.

### 3. Expand a conversation and read the body

Click any message in the list to open the conversation. For back-and-forth threads, multiple messages stack together — click a single one to expand/collapse it, with the latest message expanded by default.

The body is displayed after safety processing, so links and styling render properly. To protect your privacy, **external images in email don't auto-load by default** (this prevents senders from secretly confirming you've read the message via a tracking image). Once you've confirmed the message is trustworthy, click **Load images** above the body to show them.

> If you'd like all future emails to show images automatically, turn on auto-load in Settings (see [Settings & Account Management](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-settings-and-accounts.md)).

### 4. Translate foreign-language email into your language

When you get email in a language you don't understand, use GenMail's **email translation** to translate the whole body into your language for an at-a-glance read. Translation is done by AI and **consumes credits**.

### 5. Preview and download attachments

For email with attachments, each attachment is listed below the body. Click an attachment to **preview** common types (documents, images, PDFs, etc.) right in the app without saving to your computer first; when you need to keep a copy, click **download** to save it locally. Both preview and download are free.

### 6. Clean up a single email (all free)

When you open an email or hover over it in the list, a row of cleanup actions appears. None of these cost credits:

- **Mark read / unread** — mark a message as read or unread
- **Archive** — move it out of the inbox without deleting; you can still search it back when needed
- **Delete** — move to Trash; you can permanently delete from Trash
- **Move to folder** — file the message into a chosen folder
- **Flag** — apply a **colored flag** (multiple colors available, as shown in the interface); use different colors to distinguish urgency or category

### 7. Handle multiple emails in bulk

To clear a batch of messages at once, select several in the list — a bulk-action panel appears on screen so you can archive, delete, mark read/unread, move, or flag all the selected emails in one go.

### 8. Switch between accounts and folders

The folders & labels panel on the left lists the Inbox, Sent, Drafts, and Trash for the current scope, along with the folders/labels from your mailbox. Mail from multiple accounts is aggregated together by default; use the account scope selector in the avatar area (**All Email Accounts**) to switch to viewing just one account.

### 9. Clean up as usual even offline

When you're offline, the cleanup actions you take (read, archive, flag, move, delete, etc.) are recorded locally first and **sync automatically** to your mailbox once the app reconnects — nothing gets lost. So you can clear your inbox just fine on a plane or the subway.

## FAQ

**Q: Why aren't images in my email showing up?**
To protect your privacy, external images don't auto-load by default (this prevents senders from tracking whether you've read the message via an image). Once you've confirmed the sender is trustworthy, click **Load images** above the body to show them; to fix it for good, enable auto-load images in Settings.

**Q: What's the difference between archive and delete?**
Archive just moves a message out of the inbox without deleting it, and you can still find it via search later. Delete moves it to Trash, where you can permanently delete it. If you want to clear your inbox but aren't ready to throw messages away, archive is the safest bet.

**Q: Do reading, cleanup, and translation cost credits?**
Reading mail, archiving, flagging, marking read/unread, moving, deleting, bulk operations, and syncing after being offline are all **free**. Only AI-powered capabilities like **email translation** **consume credits**.

**Q: How should I use Flag colors?**
Flags come in **multiple colors** (as shown in the interface), great for categorizing email — e.g. red = urgent, blue = to reply, green = handled. Once you've applied a colored flag, the Flag color palette makes it easy to tell priorities apart at a glance.

**Q: I have several mailboxes — won't it get messy?**
By default all accounts are aggregated into one list, arranged consistently by conversation and time. When you want to focus on a single account, just switch scope with the **All Email Accounts** selector in the avatar area.

## Next steps

- [Compose, Reply & Forward →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md)
- [AI Write & AI Reply →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md)
- [Search Email & Contacts →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-search.md)
- [Settings & Account Management →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-settings-and-accounts.md)
- [GenMail Overview: Your Inbox Now Has a Brain →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-overview.md)
