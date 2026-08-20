# Super Agent: Run Tasks With Your Email as Context

> For Buddy Agent internal use.
> type: howto | feature: genmail-super-agent | keywords: Super Agent, Super Agent, to know, Everything else, On Your Radar, Skills, Skills, GenMail Agent, embedded agent, draft card, run tasks, Recents
> User loop: Open Super Agent → type a task / tap a skill / pick a to-do → watch the AI work step by step → confirm permissions or answer clarifications → review the draft card or file → send / adopt the result

> **Rolling out gradually**: Super Agent is being rolled out in stages and has to be enabled for your account before you can use it. If your GenMail doesn't have this entry point yet, or if opening it tells you the feature isn't enabled for your account yet, that's normal—go by what the interface actually shows. Not seeing it doesn't mean the feature is missing, it just hasn't reached your account yet; other features (reading, writing, search, calendar) are unaffected.

## Why use Super Agent

- **Collapse "read a pile of emails + do the work" into a single sentence**: Replying to one email used to mean digging through the related thread, checking attachments, lining up your schedule, then typing it out word by word—Super Agent takes your inbox as context directly, figures out the full picture, and runs the whole thing end to end, so you only make the final call.
- **Someone watches your inbox even when you're away**: It proactively surfaces things worth your attention on the home page, so items waiting for a reply, decisions to make, or time-sensitive matters won't get buried in the list anymore—the interface presents them in two groups: **to know** and **Everything else**.
- **The process is visible, and sending is your call**: The AI thinks and works at the same time, showing you which capabilities it's using step by step; a finished reply is presented to you as a draft card for review first, and it's only sent when you tap send—effortless without losing control.

## Prerequisites

- Entry: Open the **GenMail desktop client** with everything installed and signed in, then click **Super Agent** at the top of the left navigation bar (this is also GenMail's default landing view after opening). If you haven't set it up yet, see [Install and Sign In](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md) first.
- Requirements: Signed in with a Genspark account and connected to at least one mailbox (Gmail / Outlook).
- Super Agent must be enabled for your account (rolling out gradually; go by what the interface actually shows).
- **Credit**: Viewing "On Your Radar" to-dos, browsing Skills, and opening the home page are all **free**; once you have it **run a task** (start a conversation, use a skill, handle a to-do), it will **consume credits**, and this is one of the relatively heavier types of consumption in GenMail.

## Steps

### 1. Open the Super Agent home page

Click **Super Agent** in the left navigation bar. From top to bottom, the home page typically includes: a greeting, a task input box, **Skills**, things worth your attention (shown in the interface as two groups: **to know** and **Everything else**), and **Recents** (recently run tasks).

![Super Agent home page: ① task input box · ② things worth your attention (interface splits into "to know / Everything else") · ③ skill shortcuts (Morning brief / Catch me up …)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/39200/d5cf3972.png)

If it tells you here that the feature isn't enabled for your account yet, it just hasn't reached you—use other features like Mail for now.

### 2. Give a task in one sentence

Write what you want done in the input box just like you'd explain it to a person, for example:

> "Turn that invoice email Finance sent yesterday into a bullet list of key points, and draft a reply confirming receipt."

Press Enter to send. Super Agent will use your inbox as context to understand the matter, then start working.

> A task consumes credits once it's launched, and the more complex the work, the more it consumes.

### 3. Watch the AI work step by step

After sending, you enter the chat view. Super Agent shows its **thinking and the capabilities it's using** step by step (such as "Finding relevant emails," "Reading attachments," "Drafting a reply"). The right side usually mirrors a preview of **the emails it's referencing or the file it's generating**, so you can check at any time whether it has misunderstood anything.

### 4. Confirm permissions and answer clarifications

Two kinds of interruptions may come up while a task runs, and both need your response:

- **Permission confirmation**: When it's about to do something with real consequences (like sending an email or changing your schedule), it stops first and asks you to confirm—it only continues after you approve.
- **Clarifying question**: When your request is ambiguous (like "reply to him"—who, and with what?), it asks a follow-up, and picks the task back up after you answer.

These two steps exist so it **won't do anything you haven't approved**—the AI won't send an email out without your knowledge.

### 5. Review the draft card, then send after confirming

When a task involves "write an email," Super Agent won't send it for you directly—instead it gives you a **draft card** in the chat: recipient, subject, and body are all laid out for review. You can edit right on the card, and it's only sent when you're satisfied and click the send button; if you're not happy, you can have it rewrite.

> The email is only sent when you actually click send on the draft card; if you only review the draft and don't send, no email leaves your account.

### 6. Grab the output file

If a task produces a file (like an organized list, a summary table, or a report), it gives you a **downloadable / openable file** in the chat or the right-hand panel. Click to view it and download to save as needed.

### 7. Use Skills to run common tasks in one click

The **Skills** on the home page are a set of preset common tasks (like "organize today's emails awaiting reply" or "summarize recent exchanges with a sender"). Clicking a skill is like filling in a structured task for you and handing it straight to Super Agent to run—no need to compose the wording yourself.

> Tapping a skill = launching a task, which consumes credits too.

### 8. Handle things worth your attention

Things worth your attention are placed prominently on the home page—the interface splits them into two groups, **to know** and **Everything else**, listing items waiting for your reply, decisions you need to make, and things nearing a deadline. **Browsing these items is free.** When you see one you want to handle, click it, and Super Agent launches a task for it (like drafting a reply or adding it to the calendar)—this step **consumes credits**.

### 9. Use the embedded GenMail Agent next to Mail / Calendar

Don't want to leave the email or event you're looking at? Click **GenMail Agent** in the top bar of Mail or Calendar to bring up the embedded agent side panel from the right (input prompt reads "Ask GenMail Agent…"), and ask questions or give instructions about this exact email / event directly (like "draft a polite decline for me" or "move this meeting to next Tuesday") without switching back to the Super Agent home page. It uses the same set of capabilities as Super Agent—it just moves the entry point right next to what you're working on.

> Chatting with the AI in the side panel consumes credits too.

### 10. Pick back up from Recents

The **Recents** on the home page lists tasks you've recently run. Click any one to revisit its process and output at the time, or add further requests on top of it.

## FAQ

**Q: Why don't I see Super Agent when I open GenMail, or why does it say it's not enabled when I click in?**
Super Agent is rolling out gradually and has to be enabled for your account. If it hasn't reached you, not seeing the entry point or seeing a "not enabled yet" message is normal—go by what the interface actually shows; other features (reading, writing, search, calendar) are unaffected.

**Q: Will it send an email without my consent?**
No. For actions with real consequences like sending emails or changing your schedule, it stops first and asks you to confirm; a finished reply is only presented to you as a draft card for review, and **it's only sent when you click send**.

**Q: Which actions are free, and which cost credits?**
Opening the home page, browsing Skills, and viewing things worth your attention (the "to know" and "Everything else" in the interface) are all free. Once you start a conversation, tap a skill, have it handle an item, or give instructions in the embedded GenMail Agent side panel—that is, actually put the AI to work—it consumes credits, and having Super Agent run a full task is one of the relatively heavier types of consumption in GenMail.

**Q: Is it the same as the "AI Write" I use inside an email?**
No. AI Write polishes / continues a passage while you write an email yourself; Super Agent takes over an entire matter—checking context, making decisions, producing drafts or files. If you just want help writing a passage, use [AI Write and AI Reply](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md); if you want it to run the whole thing end to end, use Super Agent.

**Q: What happens if I close the app while a task is running?**
Closing the desktop client may interrupt the task. We recommend waiting until the task completes and confirming the draft or file output before leaving; you can also revisit completed tasks in Recents afterward.

## Next steps

- [AI Write and AI Reply →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md)
- [Calendar: View schedules, join meetings, RSVP, and AI scheduling →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-calendar.md)
- [Email Brain: What the AI has learned from your inbox →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-email-brain.md)
- [GenMail Overview: Your inbox now has a brain →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-overview.md)
