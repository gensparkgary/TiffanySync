# GenTeam — Personal Settings, Notifications & Activity

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: Settings, Settings, Interface Language, Display name, Avatar, Notifications, Desktop Notifications, Translation, Translation Settings, Saved, Saved, Activity, Activity, unread, unread
> User journey: rail avatar → Settings(General/Notifications/Translation) → save messages to Saved → check Activity → understand unread indicators

## Why spend two minutes on settings

- **Seamless collaboration across languages**: set your target translation language and you can one-click-understand whatever language a teammate writes in
- **No more scrolling back through chat for important messages**: save to Saved, activity lands in Activity — these two panels turn "finding that one message again" into a single click

Everything in this guide is free and consumes no credits.

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark (your workspace)
- Requirement: signed in to your Genspark account

## Steps

### 1. Open Settings

Click **your avatar** at the bottom of the left rail (the icon bar on the far left) → **Settings**. The Settings dialog has tabs like General / Notifications / Translation.

![Settings dialog and tabs](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/b4ccefc1.png)

### 2. General: language, display name, avatar, send key

- **Interface Language**: the display language for the entire Genspark site — it's the same setting as Display language in the main-site settings, not GenTeam-only
- **Display name & Avatar**: ⚠️ **changing these here changes the name and avatar for your whole Genspark account** — they change everywhere (across all Genspark products), not just in GenTeam
- **Message send key**: in the Messages group, choose whether pressing Enter **sends the message** (default) or **starts a new line**; either way, Shift+Enter always starts a new line and Ctrl+Enter (⌘+Enter) always sends. Saved per browser

### 3. Notifications: desktop notifications

Turn on desktop notifications in the **Notifications** tab. Note four things:

- **All new messages notify by default** — unmuted group chats and DMs notify; Notification scope can switch to DMs and @mentions only; group-chat thread replies require an @mention (DM threads are unaffected)
- **@mentions still break through in muted group chats**: muting blocks group chat noise, but you're still notified when someone calls on you by name
- **Close the GenTeam tab and notifications stop**: keep the tab open to keep receiving them (install the GenTeam app on your phone for push notifications)
- **Set per browser**: switch computers or browsers and you'll need to turn it on again

When the switch is off, the tab shows only a single hint ("Turning this on asks the browser for permission…"); helper items like the Notification scope dropdown and sending a test notification only appear **after you enable desktop notifications**.

![Notifications settings: desktop notification toggle](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/90d2f3e1.png)

### 4. Translation: translation preferences

Configure in the **Translation** tab:

- **Target language**: which language messages get translated into — pick a specific language or follow the interface language
- **never-translate list**: messages in these languages won't be translated (e.g. languages you already understand), up to 10

Once set, clicking **Translate** in any message's menu translates it per this preference. If someone else already translated the same message, it appears instantly when you open it.

![Translation settings: target language and never-translate list](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/3f48e693.png)

### 5. Saved: save messages

Click **Save** in a message's ⋯ menu (or right-click menu) to save it, then view them all in the **Saved** panel on the left rail. It holds up to 1,000 saved messages.

You can also let your own agent manage saves for you — the toggle is in that agent's profile.

![Saved panel: saved messages](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/2e60680b.png)

### 6. Activity: all your activity on one page

Click **Activity** in the left rail. Four filters: **Unread / Mentions / Reactions / Tasks** — who @mentioned you, who reacted to your message, task status updates — it's all here. Mark items read/unread individually, or click **Mark all as read** to clear everything at once. Records are kept for **30 days** before being cleaned up automatically.

A filter button in the panel header to scope by **who triggered it** (All / Humans / Agents — see only people-driven or only agent-driven activity, with the unread counts following the filter too) is rolling out gradually; if your panel doesn't show it yet, go by what's live.

### 7. Understanding unread indicators

- New messages in a group chat / DM: an unread badge shows in the sidebar
- **Muted group chats**: only a subtle hint, no count-based bombardment
- **Browser tab icon**: a red dot appears when there are unreads, so you know there's something new even when you've switched away

## FAQ

**Q: Not getting desktop notifications?**
Check in order: ① is the GenTeam tab open (closed means no notifications); ② whether Notification scope is set to "DMs and @mentions only" — on the default setting, regular messages in unmuted group chats also notify; ③ with the switch on, use the in-page test/troubleshooting hints to verify browser and system notification permissions; ④ if you switched browsers, set it up again.

**Q: I can't find an @mention from a month ago in Activity?**
For messages you want to keep long-term, use Save to put them into Saved, or use search to find the original message.

**Q: Does translation cost credits?**
No. In GenTeam, only cloud agents doing work consume credits (charged to the creator).

## Next steps

- [Message translation and group chat message actions →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md)
- [Muting and group chat management →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md)
- [Let an agent manage your saves (profile toggle) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)
- [Invite links are in Settings too →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-members-and-invites.md)
