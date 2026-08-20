# GenMail — Keyboard Shortcuts & Command Palette

> For Buddy Agent internal use.
> type: howto | feature: genmail | keywords: shortcuts, Command Palette, Cmd+K, search, quick actions, navigation, key customization, keyboard operation
> User loop: Open the Command Palette / memorize common keys → search, navigate, compose, and organize without leaving the keyboard → remap keys to whatever feels natural in Settings

## Why go keyboard-first

- **One keystroke and you're there**: find a message, jump to a folder, start a new email, reply, archive, delete — no need to move the mouse hunting for buttons. A single key or one Cmd+K makes it happen, turning inbox cleanup from a minutes-long chore into seconds.
- **Read your entire inbox without touching the mouse**: move between messages with J / K, hit Enter to expand a conversation, and flip through today's mail like turning pages — no more bouncing back and forth between the list and the body.
- **Make it yours**: if the default keys are hard to remember or clash with your other apps, remap them in Settings so your most-used actions land on the gestures you already know.

## Prerequisites

- Entry: GenMail is a desktop client you download and install. Download and install → launch → sign in with your Genspark account (this opens your system browser to finish) → (first time) connect your Gmail / Outlook account → once you reach the main app screen, all shortcuts and the Command Palette are available. For install and sign-in, see [Install & Sign In](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md).
- No extra activation needed — keyboard operation works for all accounts and is entirely free (no credits consumed).
- Only shortcuts that trigger AI (such as invoking AI Write in the compose box) consume credits; keyboard operation itself is free.

## Steps

### 1. Open the Command Palette

From anywhere in the app, press **Cmd+K** (**Ctrl+K** on Windows). The Command Palette pops up in the center of the screen — an overlay with a search box that serves as the app's "universal entry point."

![Command Palette (Cmd+K / Ctrl+K): ① search box — type > to enter command mode · ② quick actions (New Mail) · ③ one-click folder jump](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/39207/b6c419ea.png)

Press **Esc** to close the palette and return to where you were.

### 2. Search email from the Command Palette

Type a keyword (sender, subject, or content snippet) right into the search box and the palette instantly lists matching emails — hit Enter or click to open. This is the fastest way to dig up an old message without breaking your current flow.

> For more complex filtering (with attachments, unread, or a specific account only), use the dedicated search panel — see [Search Email & Contacts](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-search.md).

### 3. Type "&gt;" to switch to command mode

Type **>** at the start of the search box and the palette switches from "search email" to "find commands," listing actions you can run — new email, jump to a folder, and so on. Keep typing to filter by command name, then press Enter to run.

The Command Palette generally holds four kinds of content:

| Category | What it does |
|------|------|
| Search email | The default mode — type a keyword to find a message |
| Quick actions (type >) | Common actions like new, reply, archive, delete |
| Navigation | Jump to Inbox / Drafts / Sent / Trash and other folders (Email Brain is rolling out gradually and must be enabled for your account — go by what the UI actually shows) |
| Recent email | With nothing typed, lists the emails you opened recently for a one-click jump back |

### 4. View the shortcuts help dialog

When you can't recall a key, open the **shortcuts help dialog** — it lists every available shortcut by group (Global, Email, Navigation, Conversation, Compose). The common entry point is pressing **?** (the question-mark key), or searching "shortcuts" in the Command Palette.

### 5. Handle daily tasks with common keys

Here's the set of keys you'll use most day to day. The exact keys **follow whatever the shortcuts help dialog shows** (they may differ by platform or after customization):

| What you want to do | Common key |
|------------|----------|
| New email (compose) | C |
| Reply | R |
| Reply all | Enter (Enter / ↵) |
| Forward | F |
| Archive the current email | E |
| Delete the current email | # |
| Move down / up in the list | J / K |
| Expand / collapse the current conversation | O (expand / collapse all: ⇧O) |
| Jump to a folder | G then the folder key |
| Send (in the compose window) | Cmd+Enter (Windows: Ctrl+Enter) |

> In the compose window you can also invoke **AI Write** from the keyboard to draft for you — this step consumes credits. See [AI Write & AI Reply](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md).

### 6. Customize keys in Settings

If the default keys don't feel right or clash with another app, change them: **Settings** at the bottom → the shortcut customization entry, find the action you want to change in the list, and press your desired new key combo to bind it.

## FAQ

**Q: Cmd+K isn't doing anything?**
First make sure focus is inside the GenMail app window (click anywhere in the app), then press Cmd+K (Ctrl+K on Windows). If you're typing in a text field, press Esc to exit it first, then try again.

**Q: What's the difference between Command Palette search and the search on the left?**
The Command Palette (Cmd+K) is best for "quickly digging up a message" or "running an action" — lightweight and non-disruptive. When you need complex filters like attachments, unread, or by account source, use the dedicated search panel — see [Search Email & Contacts](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-search.md).

**Q: Does keyboard operation consume credits?**
No. Search, navigation, archive, delete, and move are all free local operations. Only keyboard-triggered AI actions (like AI Write or Manage with AI) consume credits.

**Q: J / K won't move / expand doesn't work?**
Make sure focus is on the email list (click the list area first). If you've remapped keys, go by what you set in Settings; if you forgot what you changed them to, open the shortcuts help dialog to check.

**Q: What if my custom key clashes with a system shortcut?**
Go back to shortcut customization in Settings and rebind that action to a non-conflicting combo. If you can't find your original setting, most lists let you reset each item back to default.

## Next steps

- [Install & Sign In →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md)
- [Read & Manage Email →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-read-and-manage.md)
- [Search Email & Contacts →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-search.md)
- [Compose, Reply & Forward →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md)
- [Settings & Account Management →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-settings-and-accounts.md)
- [Super Agent: run tasks using email as context →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-super-agent.md)
