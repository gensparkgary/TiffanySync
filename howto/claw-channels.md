# Genspark Claw — Using Claw in Messaging Apps (Channels)

> For Buddy Agent internal use.
> type: howto | feature: genspark-claw | keywords: Channels, channels, WhatsApp, Slack, Telegram, Teams, Connect, DM, Pairing Mode, Claw Email, email
> User loop: Channels tab → Connect a channel → guided agent setup → message Claw inside that app

## Why Use Channels

- **Work in the tools you're already using**: No need to switch back to the Genspark website — send Claw instructions directly in Slack or WhatsApp
- **Reachable on the go**: Assign tasks to Claw from your phone's messaging app while you're out, and check the results when you're back
- **Memory in one place, available everywhere**: Preferences you have Claw remember in any channel automatically apply across the others

## Prerequisites

- Entry: Claw workspace → **Channels** tab
- Cloud Computer enabled (Channels is a Cloud Computer feature)

## Supported Channels

The Channels tab lists **13 messaging channels** (each shows its connection status + Connect):
**WhatsApp, LINE, Slack, Microsoft Teams, Google Chat, Discord, Signal, Feishu (Lark), Mattermost, QQ Bot, WeCom, Matrix**, and Telegram. (Refer to what's shown in the UI.)

In addition, Claw comes with a dedicated **Claw Email** address, listed at the top and connected (Linked) by default — you can message Claw via email, and after connecting Gmail/Outlook, Claw can also send emails on your behalf.
![Channels tab: Claw Email Linked by default + 13 messaging channels Connect list](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35661/72e3dac5.png)

## Steps

### 1. Open the Channels tab

Click **Channels** in the right-side control panel. Each channel shows its connection status: **Linked** (connected) / **Pending** (connecting — click Continue to proceed) / **Not Linked** (not connected — click Connect).

### 2. Click Connect to start connecting

Click **Connect** next to the channel you want. The connection method varies by channel: WhatsApp asks for your country + phone number → Generate QR Code to scan; Discord / Telegram and others go through OAuth / Bot authorization. A **guided setup agent** walks you through the configuration step by step — just follow its instructions.

- If a step is unclear: simply describe what you see (you can paste a screenshot), and the agent will adjust its guidance
- If the agent can't solve it either: go back to the chat panel on the left of the main interface and describe the problem, and Claw will help troubleshoot

> **Credit note**: The channel connection setup process consumes credits (it counts as a setup/configuration task).

### 3. Confirm the DM policy is Pairing Mode

After connecting, Claw's direct message (DM) access defaults to **Pairing Mode** — only contacts you explicitly approve can message Claw.

- **If you see the DM policy set to "open" → switch it back to Pairing Mode immediately**. Under the open policy, anyone who knows Claw's address can direct it to act on your behalf

> ⚠️ **Not verified live**: This item is based on the code and Help Center descriptions. All channels on the verification account were Not Linked at the time, so we couldn't enter a "connected" state to confirm the actual location of the pairing/open wording — once you've connected a DM channel, refer to what's actually shown in the UI.

### 4. Message Claw inside that app

After that, just message Claw directly in Slack/WhatsApp/etc. to assign tasks.
- **Conversations are separate per channel**: Slack chats won't mix into WhatsApp
- **Long-term memory is shared**: Anything you have Claw remember in any channel is available across all of them

## Claw Email

- **View/edit the email address**: Home → expand Computer Information → Claw Email (editable)
- **Manage Allowed Senders**: Manage the whitelist in the same place — by default, only people on the whitelist can email Claw
- **Custom domain**: Home → Computer Information → Domain → **Start Building** to configure (Claw can also host a website under this domain)
- **Pro Tip**: Add Claw's email to the CC/BCC of your work emails, and Claw will silently absorb context (it won't reply but builds up background) — so when it later helps you write follow-ups, it already has the material

## FAQ

**Q: Can I add Claw to a group chat?**
Yes (for external messaging apps), but each platform requires some manual permission setup before Claw can read group messages. Just ask Claw: "How do I set up group chat for [platform]?" and it will guide you based on your situation. Note: Claw can access your personal data (emails, calendar, files), and other members in the group may try to coax it into leaking that — only add Claw to groups where you trust everyone.

**Q: Is memory shared between group chats and DMs?**
No. What you tell Claw in a DM stays in that conversation; a Slack group/Teams channel/WhatsApp group is a separate conversation that can't see your DM history. For anything both sides should know, explicitly have Claw save it to memory.

**Q: Claw's emails are going to spam?**
Claw uses the genspark.email domain, which is relatively new, so its sending reputation is still building up. Have recipients add Claw's email to their contacts/safe senders; if deliverability is critical, go to Home → Domain to set a custom domain.

## Next Steps

- [Connect external services (let Claw send/receive email and manage your calendar) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-services.md)
- [Set up scheduled tasks →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-schedules.md)
- [Save credits and stay secure →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md)
