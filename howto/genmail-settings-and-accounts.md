# Settings & Account Management: Accounts, Signatures, General Preferences, Shortcuts

> For Buddy Agent internal use.
> type: howto | feature: genmail-settings | keywords: settings, Settings, mail accounts, primary account, signature, Signature, shortcuts, Shortcuts, dark mode, display language, agent language, desktop notifications, load remote images, Outlook folders, clear cache, membership, subscription
> User loop: Open the Settings dialog → adjust general preferences / accounts / signatures / shortcuts across the four tabs → changes take effect instantly

## Why manage settings

- **Get GenMail to work exactly the way you like — all in one place**: which language the interface uses, whether AI talks to you in Chinese or English, dark or light theme, whether to show desktop notifications — set it all once here and enjoy the convenience every day after.
- **Send and receive from multiple mailboxes on one desk**: bring in Gmail and Outlook, order them, and set a primary account. You decide who's the default sender when composing new mail and whose inbox shows first — no more bouncing between clients.
- **Set signatures and folder display once**: assign different signatures to different mailboxes, decide whether Gmail labels / Outlook folders stay pinned in the sidebar. Set your favorite organization preferences once and they stick.

> These management-type settings are all **free**: changing preferences, adding accounts, organizing signatures, and setting shortcuts don't consume credits. Credits are only used when AI actually helps you write emails or run tasks.

## Prerequisites

- Entry: GenMail is a **downloadable desktop client**. First download and install → launch → sign in with your Genspark account (this hands off to your system browser) → (first time) connect your Gmail / Outlook mailbox. Once you're in the main interface, click **Settings** (the gear) at the **bottom of the left navigation bar** to open the settings dialog. For installation and login, see [Install & Sign In →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md).
- Requirements: signed in to a Genspark account; at least one mailbox must be connected before you can manage mail accounts or grant per-account calendar access.

## Steps

### 1. Open the Settings dialog

Click **Settings** (the gear icon) at the very bottom of the left navigation bar in the main interface to open the settings window. Category tabs are on the left, and the corresponding options are on the right.

![Settings dialog: ① four tabs General / Mail Accounts / Signatures / Shortcuts (no AI assistant tab) · ② general settings such as appearance, display / agent language](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/39009/6d9e753c.png)

### 2. General: Appearance, Language, Notifications

Adjust your global experience under **General**:

- **Theme**: Light / Dark / Match system. Dark mode suits nighttime or low-light environments.
- **Display language**: which language the interface text (menus, buttons, etc.) uses. Note: the left-nav tabs like Super Agent / Mail / Calendar / Email Brain are fixed in English and don't change with this setting.
- **Agent language**: which language AI uses when it talks to you and drafts emails. It can differ from the display language (e.g., keep the interface in Chinese but have AI draft in English).
- **Desktop notifications**: when enabled, new emails and important items alert you in your system notification center.
- **Load remote images**: when enabled, external images in emails display automatically; disable it to protect your privacy and prevent senders from tracking whether you've opened an email.
- **Folder sidebar**: you can pin Gmail labels / Outlook custom folders to the sidebar instead of tucking them under "More" — so your frequently used folders are visible at a glance.
- **Local full-text cache + Clear cache**: GenMail stores a copy of your emails on your machine so you can search and read offline and open them faster. If it takes up too much space or you want to wipe local data, just click **Clear cache** here (this won't delete the actual emails on the server).

### 3. Accounts: Add, Order, Primary, Reconnect, Remove

Switch to the **Mail Accounts** tab to manage every mailbox connected to GenMail:

- **Add account**: click **Add account**, choose Gmail or Outlook, and complete authorization in your system browser to connect it. You can connect multiple mailboxes at once, with inboxes aggregated into a unified view.
- **Order**: drag to reorder accounts, deciding their sequence in the sidebar and the aggregated list.
- **Primary**: the **account pinned at the top of the list is your primary account** (the default sender when composing new mail), marked with a **Primary** badge. There's no separate "Set as primary" button — **just drag the mailbox you want as primary to the very top of the list**.
- **Reconnect**: when an account needs re-authorization (e.g., a changed password or expired authorization), a reconnect entry appears; click it and re-run authorization to resume sending and receiving (healthy accounts don't show this entry).
- **Remove**: disconnect a mailbox you no longer need from GenMail. Removing only disconnects it and doesn't affect that mailbox's emails in the original service (Gmail/Outlook).
- **Grant calendar access per account**: each mailbox's calendar is authorized separately. Enable calendar access for an account here so its events appear in Calendar. For the calendar feature, see [Calendar →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-calendar.md).

### 4. Signature: Manage per Account or Globally

Switch to the **Signatures** tab to set up email sign-offs:

- You can set one **global signature** or **set a separate signature for each account** — send from your work mailbox and it carries your work sign-off; send from your personal mailbox and it carries your personal one.
- Supports **importing existing signatures from Gmail / Outlook**, so you don't have to reformat from scratch.

For how signatures are used when composing, see [Compose, Reply & Forward →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md).

> **About AI preferences**: GenMail's AI behavior (draft tone, model, etc.) doesn't have a dedicated "AI assistant" settings tab — `General → Agent Language` determines which language AI uses to talk to you / write for you, and the rest of the AI behavior currently surfaces in-context during use rather than being centrally configured in Settings.

### 5. Shortcuts: Customize Key Bindings

Switch to the **Shortcuts** tab to view and customize keyboard shortcuts for common actions. Remap high-frequency actions (archive, delete, reply, compose, etc.) to keys that feel natural, for faster keyboard-driven workflows. For full shortcut and command palette usage, see [Keyboard Shortcuts & Command Palette →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-shortcuts-and-command-palette.md).

### 6. Genspark Membership / Subscription Entry

From Settings you can access **Genspark membership / subscription** management, as well as sign out. GenMail shares the same Genspark account and credits as the web version. To learn how to choose a membership, how credits are counted, and how to subscribe and manage, see:

- [Membership Overview →](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-overview.md)
- [What Credits Are and How They're Used →](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-credits.md)
- [Subscribe & Upgrade →](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-subscribe.md)
- [Manage an Existing Subscription →](https://page.gensparksite.com/manual/buddy-guides/v1/en/membership-manage.md)

## FAQ

**Q: What's the difference between display language and agent language?**
Display language changes which language the **interface text** (menus, buttons) uses; agent language changes which language **AI uses to talk to you and write for you**. The two can differ — e.g., keep the interface in Chinese but have AI draft emails in English. Note that the left-nav tabs like Super Agent / Mail / Calendar are fixed in English and aren't affected by the display language.

**Q: Does removing an account delete its emails?**
No. Removing only disconnects that mailbox from GenMail; the emails remain safely in the original Gmail / Outlook. To restore, just Add account and re-authorize.

**Q: Does clearing the cache lose emails?**
No. The cache is just a copy GenMail keeps on your machine for offline reading and faster loading. After clearing, your emails re-sync from the server once you're online, and the actual emails on the server are unaffected.

**Q: Can I adjust AI tone, model, and such in GenMail's Settings?**
Not currently — there's no centralized "AI assistant" settings page. Only `General → Agent Language` lets you set which language AI uses to talk to you / write for you; the rest of the AI behavior surfaces in-context while using AI compose or Super Agent, rather than being preset in Settings.

## Next steps

- [Install & Sign In: Download, sign in, connect mailboxes →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-get-started.md)
- [Compose, Reply & Forward: Editor, attachments, signatures, scheduled send →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-compose-and-reply.md)
- [AI Write & AI Reply: Let AI write emails for you →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-ai-write.md)
- [Keyboard Shortcuts & Command Palette →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-shortcuts-and-command-palette.md)
- [GenMail Overview: Your inbox now has a brain →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genmail-overview.md)
