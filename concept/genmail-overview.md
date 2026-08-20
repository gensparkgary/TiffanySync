# GenMail Overview: Your Inbox Now Has a Brain

> For Buddy Agent internal use.
> type: concept | feature: genmail | keywords: GenMail, desktop email client, Super Agent, Email Brain, Mail, Calendar, AI writing, multi-account, your inbox now has a brain
> Entry point: A desktop client you download and install, not a web address. Download & install → launch → sign in with your Genspark account → connect Gmail/Outlook → land in the Super Agent view.
> User loop: Understand what GenMail is, what each of the four workspaces does, how it relates to the web version, and know which article to read next.

## What Is GenMail

GenMail is a **desktop email client you download and install on your computer** (not a website, no URL to visit). It plugs in your Gmail / Outlook inbox and adds a layer of AI on top—reading, writing, organizing, and checking your schedule all happen in the same app, and whenever something needs thinking or doing, you can hand it straight to the AI.

The biggest difference from "opening webmail in a browser": GenMail is a standalone program installed on your computer. It launches fast, supports system notifications and offline viewing of downloaded email, and makes "AI handling your email" a built-in capability—you don't have to copy an email into some other chat tool and paste the result back.

Your first time using it requires two separate authorization steps, which many people confuse. Remember the distinction up front:

- **Sign in with your Genspark account**: tells GenMail "who you are" and what your membership profile is (done through your system browser).
- **Connect your mailbox**: tells GenMail "which emails it can read and write"—connect your Gmail or Outlook.

Only after both steps are done do you reach the normal working interface. See [Install & Sign In](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md) for detailed setup and login steps.

## Four Workspaces, Each With Its Own Job

GenMail has a navigation rail on the left for switching between four workspaces (nav labels are fixed English, with the Chinese in parentheses):

| Workspace | What it's responsible for | What you do here |
|--------|-----------|---------------|
| **Super Agent** | Uses your whole inbox as context and runs multi-step tasks for you | "Compile all this week's invoices into a table," "Set up a meeting with Zhang San next week" |
| **Mail** | Everyday reading, writing, replying, and organizing | Browse the list, read threads, archive, Flag, compose and reply |
| **Calendar** | View your schedule, join meetings, respond to invites | Week/month views, join Meet/Teams/Zoom, RSVP |
| **Email Brain** | Shows what the AI has learned from your email correspondence | Review, correct, or make it forget a fact it remembered |

> **Super Agent and Email Brain are rolling out gradually** and only appear once they're enabled for your account, so go by what your interface actually shows. Even if you can't see these two workspaces yet, Mail and Calendar are fully usable, and you can use AI right inside composing and scheduling (see below).

All four workspaces share the account scope selector at the top: you can have the interface show a combined view of all connected mailboxes, or view just one account.

## How It Relates to the Web Version

GenMail's AI capabilities (writing email, organizing, running tasks, learning your preferences) run on the **same brain** as the Genspark web version—the agent capabilities you use in web Buddy take an "inbox-centric" form inside GenMail. Both sign into the same Genspark account, and your membership profile and Credits are shared; there's no "GenMail-only wallet."

In short: the web version is a general-purpose AI workspace, while GenMail brings that same AI onto your computer as a desktop client built specifically around your inbox. If you want desktop notifications, offline viewing, and a native email experience, use GenMail; if you just need AI occasionally, the web version is enough.

## Quick Guide to Each Article

| What you want to do | Read this |
|-----------|--------|
| Download, sign in, and connect your mailbox for the first time | [Install & Sign In](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md) |
| Browse the list, read threads, and organize with archive/flag/delete | [Read & Manage Email](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-read-and-manage.md) |
| Compose, reply, forward, add attachments, signatures, scheduled send | [Compose, Reply & Forward](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md) |
| Have AI draft or reply to email for you | [AI Write & AI Reply](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md) |
| Search email and find contacts | [Search Email & Contacts](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-search.md) |
| Have the agent run tasks using your email as context | [Super Agent](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-super-agent.md) |
| View your schedule, join meetings, respond to invites, AI scheduling | [Calendar](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-calendar.md) |
| Understand what the AI has learned from your inbox | [Email Brain](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-email-brain.md) |
| Manage accounts, signatures, AI preferences, and shortcuts | [Settings & Account Management](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-settings-and-accounts.md) |
| Keyboard shortcuts and the command palette | [Shortcuts & Command Palette](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-shortcuts-and-command-palette.md) |

## Free vs. Credit-Consuming

GenMail has one simple dividing line: **pure email operations and local actions are free; the moment you have the AI actually think (generate text, run tasks), it consumes Credits**. Credits are shared across your entire Genspark account—the web version and GenMail draw from the same pool.

- **Free**: reading email, searching, syncing, connecting accounts, marking read/unread, Flag, starring, archiving, deleting, moving to folders, bulk actions, managing signatures, and viewing your "On Your Radar" to-dos.
- **Consumes Credits**: AI Write drafts and replies, AI reply suggestions, running your AI shortcuts, "Manage with AI" thread-assistant conversations, email translation, auto-summarizing long emails, and **Super Agent running tasks** (multi-step tasks are usually the heaviest).
- **Voice dictation** follows its own separate rules: usage is measured by the **number of words** you speak, and it has its own independent free allowance pool, which doesn't compete with the text AI above.

Membership and pricing aren't covered here; see [Membership Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-overview.md) and [Credits Explained](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-credits.md).

## What Models Power the AI

When the AI writes email or runs tasks for you, it's powered by Genspark's large models behind the scenes. **GenMail currently has no model-tier switch for regular users**—you don't pick one manually; the AI automatically uses the right model. **Which model is actually used is whatever the interface shows** (models update over time, so we don't hardcode names here).

## FAQ

**Q: Is GenMail a website? What URL do I open in my browser?**
No. GenMail is a desktop program you download and install on your computer, with no URL to visit. Install it, launch it, then sign in with your Genspark account and connect your Gmail/Outlook.

**Q: I signed into my Genspark account—why can't I see my email yet?**
Signing into your account only solves "who you are." You still need to separately **connect your mailbox** to read and write email—that's the second step. Just add and authorize your Gmail/Outlook account in the Mail workspace or in Settings.

**Q: Why can't I see Super Agent or Email Brain?**
These two workspaces are rolling out gradually and only appear after they're enabled for your account, so go by what your interface shows. Until they appear, Mail and Calendar work fine, and you can still use AI in composing and scheduling.

**Q: Are GenMail's Credits separate from the web version's?**
No. GenMail and web Genspark share the same account, the same membership profile, and the same Credits—there's no GenMail-only balance.

**Q: Does using AI always cost Credits?**
Not always. Pure email operations like reading, searching, archiving, and flagging are all free; only having the AI actually generate content or run tasks (like AI Write or Super Agent tasks) consumes Credits. Voice dictation has its own separate time-based allowance and is counted separately.

## Next Steps

- [Install & Sign In: download, sign into your account, connect your mailbox →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md)
- [Read & Manage Email →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-read-and-manage.md)
- [AI Write & AI Reply →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md)
- [Super Agent →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-super-agent.md)
- [Email Brain: what the AI has learned from your inbox →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-email-brain.md)
