# Second Brain — Connecting Data Sources

> For Buddy Agent internal use.
> type: howto | feature: secondbrain | keywords: Second Brain, data sources, connectors, connect, connect, Gmail, Outlook, Notion, Slack, Google Drive, sync, sync, Import files, disconnect, disconnect, privacy, privacy
> User journey: Home Connectors bar / sidebar Connect more → data source hub → learn the two data source groups → connect (confirmation dialog + authorization window) → check status and retry failures → email auto-sync → disconnecting and what happens to data → Import files manual import

## Why use it

- Bring in your email, meeting notes, Notion, calendar, and Genspark project history so Second Brain can "remember you" — then when you ask questions here, it answers across all these sources
- Connecting, syncing, and importing are all free and don't consume credits; only asking questions (Ask/Chat) is billed by usage
- What happens to your data when you disconnect each source follows different rules — this article spells them all out one by one, so you know your exit plan before you connect

## Prerequisites

- Entry point: https://www.genspark.ai/second-brain/home (designed for desktop browsers)
- Requirements: log in to your Genspark account; when connecting a third-party service, complete authorization in the authorization window using the corresponding account

## Steps

### 1. Open the data source hub

Use any entry point to reach the data source hub:

- The **Connectors** bar below the Ask input box on the Home page (labeled "read live, only when you ask")
- **Connect more** in the sidebar
- **Connect more** in the bottom-right corner of the Memory Map page

![Full data source hub page: In your brain and Connectors groups shown together](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48744/6cbd15c0.png)

### 2. Learn the two data source groups

The data source hub is divided into two semantically distinct groups — tell them apart before you connect:

| Group | UI description (original English) | Meaning | Members |
|---|---|---|---|
| In your brain | "Imported and always searchable" | **Imported into your brain**: content is imported and searchable/askable at any time | Meeting Notes, Genspark History (your Genspark project history), Gmail, Outlook |
| Connectors | "Read live, only when you ask" | **Connected but not imported**: content isn't imported; read live when you ask | Notion, Microsoft Teams, GitHub, Google Drive, Slack, Salesforce, Google Docs, Google Sheets, HubSpot, Google Calendar, Outlook Calendar |

One line to remember: content in the first group becomes part of your memory; the second group merely authorizes it to "take a look on your behalf when you ask."

### 3. Connect a data source

1. Click the connect button for the target data source; a **confirmation dialog** appears first, explaining what you're about to connect
2. After confirming, the service's **authorization window** pops up — complete authorization with your account
3. Once authorization is done, you return to the data source hub and the source shows as connected

Exception: **HubSpot** doesn't pop an authorization window; instead, it asks you to paste an access token generated in the HubSpot admin console to complete the connection.

![Confirmation dialog before connecting (Notion as example): explains what you're about to connect and how it reads after authorization](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48744/4cd62d0c.png)

![HubSpot exception: paste an access token to complete the connection, no authorization window](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48744/0cb814c5.png)

### 4. Check status and retry failures

- The Gmail / Outlook rows provide a **View** entry point; open the drawer to check import status
- When an import fails, the row shows "**Import failed — didn't finish**"; click "**Import again**" to retry

### 5. Email auto-sync cadence

- On first connection, Gmail / Outlook import emails from the **past 6 months**, **up to 6,000 emails**
- After that, new emails sync automatically at intervals — no manual action needed
- Syncing runs in the background and doesn't consume credits

![Gmail connection dialog: import up to 6,000 recent emails, disconnect anytime](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48744/2d65c04c.png)

### 6. Disconnecting and what happens to data (important)

Every disconnect has a confirmation dialog, but the consequences differ across four categories:

1. **Disconnecting Connectors group (Notion, Slack, etc.): nothing is deleted.** This group never imported content in the first place; disconnecting just revokes the "read live when you ask" authorization
2. **Turning off Meeting Notes / Genspark History: data is retained.** After turning off, it stops being used but existing content isn't deleted; turn it back on to restore
3. **Gmail / Outlook Remove: deletes the imported copies of your emails and revokes authorization.** This is the only disconnect operation that deletes data — think it through before you do it
4. **Cascading disconnect: no data deleted.** Disconnecting one connection may cascade to disconnect other connections under the same account's authorization (e.g., disconnecting Google Docs may affect Gmail's connection status) — already-imported data is unaffected; just reconnect to keep using it

![Genspark History Remove confirmation dialog: stops reading but data is retained, add it back anytime](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48744/86020725.png)

### 7. Import files (manual import)

Want to feed files you have on hand directly in: go back to the Second Brain home page, click the **Upload** button in the **Your documents** section, and the panel that pops up is titled **Import files** (you can also send content into your brain via the paperclip attachment in the chat box or via Quick note):

- Supports ZIP, Markdown, CSV, HTML, PDF
- Limit of **500 MB (the Import files panel copy may still show an older number — the enforced limit governs)** per import 
- Imports can run in the background — no need to watch the progress
- Once done, click "**Ask about these**" to jump straight to chat and immediately ask about what you just imported

![Import files panel: supports ZIP, Markdown, CSV, HTML, PDF, 100 MB limit per import](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48744/7f679143.png)

![Import complete: 1 file added to your brain, click Ask about these to jump to chat](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48744/15cd8ea0.png)

## FAQ

**Q: Do connecting data sources and auto-sync cost credits?**
No. Connecting, syncing, importing, and disconnecting are all free; only asking questions (Ask/Chat) consumes credits by usage — see [Ask and Chat](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-ask-and-chat.md).

**Q: Does disconnecting delete my data?**
It falls into four categories: disconnecting the Connectors group deletes nothing; turning off Meeting Notes / Genspark History retains data and restores on turning it back on; only Gmail / Outlook's Remove deletes the imported email copies; cascading disconnect deletes no data. See Step 6 for details.

**Q: What do I do if an email import fails?**
The data source row shows "Import failed — didn't finish"; just click "Import again" to retry.

**Q: I want to delete some already-imported content — where's the entry point?**
There's no entry point to delete imported content item by item: emails can only be deleted as copies in bulk via Remove; Meeting Notes / Genspark History can only be turned off (data retained). Documents you create or upload yourself can be deleted in the file tree — see [Notes and file management](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-notes-and-files.md).

**Q: How long after connecting can I query this data?**
The first group (imported into your brain) needs a little time for the first import — you can check progress in the View drawer; the second group (connected but not imported) is usable as soon as it's connected, read live when you ask.

## Next steps

- [Get started →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-get-started.md)
- [Ask and Chat →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-ask-and-chat.md)
- [Telegram quick notes →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-quick-notes.md)
- [Notes and file management →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-notes-and-files.md)
- [Product overview →](https://page.gensparksite.com/manual/buddy-guides/v1/en/secondbrain-overview.md)
