# Genspark Claw — Managing Your Cloud Computer (Files / Terminal / Settings / Memory / Diagnose)

> For Buddy Agent internal use.
> type: howto | feature: genspark-claw | keywords: Files, Files, Monaco, Terminal, Terminal, Settings, Diagnose, Diagnose, Force Restart, Delete VM, Memory, Memory, Switch Model, Switch Model, Plan Management
> User loop: Right-side control panel → Files/Terminal/Settings and other tabs → Complete management action

## Why read this

- **Self-rescue first when something breaks**: When Claw isn't responding, run Diagnose before retrying — blindly retrying wastes credits without solving the problem
- **Don't delete data by mistake**: Delete VM is permanent and unrecoverable; to cut costs you should pause tasks, not delete the machine
- **Make Claw remember key info**: Things mentioned in passing aren't guaranteed to be remembered — explicitly say "remember this" for what matters

## Prerequisites

- Entry: The right-side control panel in the Claw workspace
- Cloud Computer enabled (these are cloud computer management features)

## Home: Computer Information and Switching Models

Click to expand **Computer Information** on the Home tab to view/configure:
![Home → Computer Information expanded: Claw Email / Domain / Model + Switch model / Remote Desktop Password / Heartbeat](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35661/fe5e6feb.png)

- **Claw Email**: A dedicated email address you can edit and use to manage Allowed Senders (see [claw-channels](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-channels.md))
- **Domain**: Click **Start Building** to set a custom domain; Claw can also host websites under this domain
- **AI Model** (conversation model) + a separate **Image Model**: each has its own **Switch model** button and can be switched independently. Switching the conversation model **does not clear conversation history** (verified: history fully preserved after switching)
  > Switching models reconfigures the cloud computer, which **takes about 1 minute** (the dialog shows "Applying Model… / Waiting for gateway" progress) — it's not instant, so be patient after clicking Apply and let the progress finish. Switching itself **does not consume credits** (it's a settings action).
- **Remote Desktop Password**: View (Show) / Copy / Reset the cloud computer password; click **Open Remote Desktop** to open the cloud computer's browser view

> Available models depend on what the interface shows. Switching everyday tasks to a lighter model saves credits — see [claw-tips-and-credits](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md).

The same expanded section also has two read-only infrastructure blocks (for checking status, not for configuring):
- **VM Information**: The cloud computer's Name / FQDN (domain) / Size (specs) / Region / OS / SSH User / Status (running state)
- **System**: Real-time Uptime / Memory / Disk / CPUs usage
- **Email Channel**: Claw's email address + Enabled toggle (also manageable from the Channels tab)

## Files: Browser File Manager

The **Files** tab is the cloud computer's file manager: browse, upload, download, and manage files.
![Files tab: directory tree + file list + Monaco edit/preview area](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35661/55e69554.png)

- Directory tree on the left (breadcrumb navigation, e.g. `/ home / work / .openclaw / workspace`) + **Monaco editor** on the right (Source / Preview toggle + Download, with line numbers)
- Supports previewing PDF, DOCX, XLSX, PPTX, CSV, Markdown, and images/video/audio
- When you select text in the editor, the **right-click menu** currently offers **Copy / Edit** — view and modify files directly in the editor. When you've made changes and want Claw to handle them, just go back to the chat panel on the left and describe what to do
  > Note: The editor's right-click menu currently does **not** include "Send to Chat" (live testing shows only Copy / Edit). To hand file contents to Claw, describe it in the chat panel on the left, or have Claw read the file path directly.

## Terminal: Browser Command Line

![Terminal tab: a live, connected interactive shell (Ubuntu 24.04 prompt)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35661/40272146.png)
The **Terminal** tab gives you a direct command line into your cloud computer — when the VM is running, it's a live, connected interactive terminal (Ubuntu 24.04 shell; a cursor appears after you click to focus). Run scripts, view files, install packages, and debug right in the browser without leaving the Claw panel.

## Settings: Cloud Computer Management

The buttons in the **Settings** tab refer to your cloud computer as "VM" (virtual machine) — they mean the same machine.
![Settings tab: Refresh Status / Update configuration / Diagnose / Force Restart / Delete VM](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35661/f665213f.png)

| Button | What it does | When to use |
|------|--------|--------|
| **Refresh Status** | Reloads the cloud computer status | When status info isn't updating |
| **Update configuration** | Pushes the latest Claw config to the cloud computer (a dot appears beside it when there's an update) | When you see an update prompt |
| **Diagnose** | AI health check: checks system status, inspects running services, restarts components if needed, and guides you through fixes | When Claw isn't responding or behaving abnormally |
| **Force Restart** | Forcibly restarts the cloud computer | When Diagnose can't fix it |
| **Delete VM** | Permanently deletes the cloud computer and all its data | When you're sure you're done for good and have backed up. **Unrecoverable** |

Clicking **Delete VM** brings up a confirmation dialog ("This action is irreversible / All data on this VM will be permanently deleted… files, configurations, installed software, chat history, and credentials") and requires a second confirmation before it actually deletes — if you clicked by mistake, just hit Cancel.

The bottom of the Settings tab also has a **Plan Management** section: it shows your current Cloud Computer plan (e.g. Lite Cloud Computer · Active · Annual) and the next billing date, including **Cancel Claw** (cancel subscription) and **Edit Billing** (manage billing). Before canceling, go to Files and download any files you want to keep.

## Diagnose: Troubleshooting

- When Claw isn't responding, a **Diagnose** shortcut button automatically appears at the top of the chat area; you can also reach it from Settings → Diagnose
- Diagnose runs a comprehensive health check on the cloud computer and attempts automatic fixes
- Still not resolved → Settings → **Force Restart**

## Memory: Making Claw Remember

Claw's memory persists across sessions and across channels:
- **Explicitly say "remember this"** to guarantee it's saved to long-term memory; mentioning something in passing isn't guaranteed to be remembered
- Long-term memory is **shared across all channels**; conversation history is **kept separately per channel**
- When a conversation gets too long, Claw automatically compresses older content — explicitly save important decisions/preferences to memory so they survive compression

## FAQ

**Q: What do I do when Claw stops responding?**
Find the **Diagnose** shortcut button at the top of the chat area (it appears automatically when there's no response), or go to Settings → Diagnose. Diagnose runs a comprehensive health check and can restart components, which resolves most connectivity issues. If that still doesn't work → Settings → **Force Restart**.

**Q: Can I recover my cloud computer after deleting it?**
No. Deleting permanently wipes conversation history, memory, files, and login credentials, and it's unrecoverable. To cut costs you should **turn off Heartbeat + disable scheduled tasks you don't need**, which keeps your data. Only delete if you're completely done and have backed up.

**Q: What happens to my data after I cancel the subscription?**
After the current billing cycle ends, the cloud computer is reclaimed and all data on it is permanently deleted. Before canceling, go to the **Files** tab and download any files you want to keep.

**Q: Will switching models lose my conversation?**
No. Conversation history is preserved after switching via Home → Computer Information → Switch Model.

## Next steps

- [Saving credits and staying secure →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md)
- [Scheduled tasks (key to cutting costs) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-schedules.md)
- [What is Claw →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-overview.md)
