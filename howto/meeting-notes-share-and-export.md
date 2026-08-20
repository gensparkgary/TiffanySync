# AI Meeting Notes — Sharing & Exporting

> For Buddy Agent internal use.
> type: howto | feature: meeting-notes | keywords: share, export, Share, Export, participants, share link, Anyone with the link, DOCX, Markdown, SRT, Save as PDF, Save to Notion, Copy, email
> User loop: Open meeting details → Share with participants (email) / Generate share link / Export download / Save as PDF / Save to Notion / Copy

## Why use Sharing & Exporting

- **Send it out in one click after the meeting**: Email the notes directly to all participants — no need to clean them up and forward manually.
- **Share with exactly who you want**: Set the share link to public or invite-only for flexible control over who can view.
- **Archive your way**: Export the notes and transcript directly as Word / text / subtitle files, export a PDF, or save to Notion in one click to feed your knowledge base.

## Prerequisites

- Login required
- Entry point: Open any meeting notes detail view (click an entry in the list at `https://www.genspark.ai/meetingnotes/home`; it opens in a new tab)
- Sharing with participants, generating a share link, Export direct downloads, Save to Notion, and Copy are all **free**; **Save as PDF consumes credits** (it's a one-time AI-generated PDF — see step 4 below)

## Steps

### 1. Share with participants (email)

After the meeting ends, expand the **Participants** section on the detail page and click **Share with X participants**. The system will automatically email the notes to all participants. Note that the Participants section appears **only when the meeting has participant data** (typically meetings recorded by the Meeting Bot) — notes from imported files or local recordings without participants don't show it.

You can also type "send email to someone@example.com" in the chat box, and the Genspark team email will send the notes on your behalf.

> **You get a copy too**: once meeting notes are generated, the AI summary is delivered to your login email by default. If you don't want this email, turn off the **Send AI summary** toggle under **Settings → AI Meeting Notes → Email Me The Summary**.

### 2. Generate a share link

Open the share settings and set **General Access** to:
- **Anyone with the link**: The link is publicly viewable
- **Only people invited**: Only people you invite by email can view it

Once set, click **Copy & Share Link** to copy the link and share it (you'll see "Link Copied!" on success).

You can also **invite specific members** by email (invitees show as "View only"), while you remain the Owner.

### 3. Export Word / text / subtitles (Export — free direct download)

With a note open, there's an **Export** button at the top of the page (next to the share entry). Click it to choose what to export:
- **Notes**: TXT / Markdown / DOCX
- **Transcript**: TXT / SRT / DOCX, with a **Timestamps** toggle (SRT always includes timecodes)

Pick a format and click **Export** — the file downloads directly to your device, **free, no credits consumed**.

> For meeting notes, the Export menu only offers Notes and Transcript text exports — **the raw audio is not downloadable**.

### 4. Export as PDF

Click **Save as PDF** to format the notes into a PDF, ideal for printing or archiving. This step is a one-time **AI generation** ("Generate PDF"): once complete, the PDF is saved to AI Drive (e.g. /meeting_pdfs/…) with preview / download available. **Save as PDF consumes credits** (refer to what the UI shows) — it's not an ordinary local export.

### 5. Save to Notion

If you've connected Notion, click **Save to Notion** to save the notes there in one click.

### 6. Copy

Click **Copy** to copy the notes content to the clipboard and paste it anywhere.

## FAQ

**Can I export to Word (DOCX) or TXT?**
Yes. Use the **Export** button at the top of the page: notes can be exported as TXT / Markdown / DOCX, and the transcript as TXT / SRT / DOCX — direct download, free.

**Does Save as PDF cost anything?**
Yes. Save as PDF is a one-time AI generation (formatting the notes into a PDF and saving it to AI Drive), which consumes credits; Export direct downloads, Save to Notion, and Copy are free. The exact cost is shown in the UI.

**Can I download the raw audio recording?**
No. To protect privacy, only the transcript and notes text are retained — the raw audio is not available for download (there is no audio option in the Export menu either).

**I've sent out a share link — how do I revoke it?**
Change General Access back to "Only people invited," and anyone who was relying on the link will no longer be able to view it.

**Who does Share with participants send to?**
It sends to the email addresses of all participants listed in this meeting's Participants section. With Auto-share enabled, it sends automatically when the meeting ends — see [Meeting Bot & Calendar](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-bot-and-calendar.md).

**Why does my own inbox keep getting the notes summary? Can I turn it off?**
Once notes are generated, the AI summary is sent to your login email by default. You can turn it off: go to **Settings → AI Meeting Notes → Email Me The Summary** and switch off the **Send AI summary** toggle.

## Next steps

- Adjust speakers and ask follow-up questions about meeting details → [Review & Edit](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-review-and-edit.md)
- Record another meeting → [Record & Import](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-record-and-import.md)
