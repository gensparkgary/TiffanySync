# GenTeam — Personal Settings, Notifications & Activity

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: Settings, Settings, Interface Language, Display name, Avatar, Notifications, Desktop Notifications, Translation, Translation Settings, Saved, Saved, Activity, Activity, unread, unread, Multiple Spaces, Space Switching
> User journey: rail avatar → Settings(General/Notifications/Translation) → save messages to Saved → check Activity → understand unread indicators → switch between spaces

## Why spend two minutes on settings

- **Ring when it matters, stay quiet when it doesn't**: desktop notifications only pop for DMs and @mentions. Once configured, you won't get bombarded by channel chatter, and you won't miss anything where someone's calling on you by name
- **Seamless collaboration across languages**: set your target translation language and you can one-click-understand whatever language a teammate writes in (translation is free)
- **No more scrolling back through chat for important messages**: save to Saved, activity lands in Activity — these two panels turn "finding that one message again" into a single click

Everything in this guide is free and consumes no credits.

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark (your workspace, i.e. the shared default Genspark Space)
- Requirement: signed in to your Genspark account

## Steps

### 1. Open Settings

Click **your avatar** at the bottom of the left rail (the icon bar on the far left) → **Settings**. The Settings dialog has tabs like General / Notifications / Translation.

![Settings dialog and tabs](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/b4ccefc1.png)

### 2. General: language, display name, avatar, send key

- **Interface Language**: the display language for the entire GenTeam interface
- **Display name**: the name you show as inside a space
- **Avatar**: ⚠️ **changing your avatar here changes the avatar for your whole Genspark account** — it changes everywhere (across all Genspark products), not just in GenTeam
- **Message send key**: in the Messages group, choose whether pressing Enter **sends the message** (default) or **starts a new line**; either way, Shift+Enter always starts a new line and Ctrl+Enter (⌘+Enter) always sends. Saved per browser

### 3. Notifications: desktop notifications

Turn on desktop notifications in the **Notifications** tab. Note four things:

- **Only DMs and @mentions trigger notifications** — regular channel messages don't pop, and there's no "notify me for all messages" option
- **@mentions still break through in muted channels**: muting blocks channel noise, but you're still notified when someone calls on you by name
- **Close the GenTeam tab and notifications stop**: notifications depend on the page being open, so keep the tab open to keep receiving them (install the GenTeam app on your phone for push notifications)
- **Set per browser**: switch computers or browsers and you'll need to turn it on again

When the switch is off, the tab shows only a single hint ("Turning this on asks the browser for permission…"); helper items like sending a test notification only appear **after you enable desktop notifications**.

![Notifications settings: desktop notification toggle](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/90d2f3e1.png)

### 4. Translation: translation preferences

Configure in the **Translation** tab:

- **Target language**: which language messages get translated into — pick a specific language or follow the interface language
- **never-translate list**: messages in these languages won't be translated (e.g. languages you already understand), up to 10

Once set, clicking **Translate** in any message's menu translates it per this preference, and **translation is free**. If someone else already translated the same message, it appears instantly when you open it.

![Translation settings: target language and never-translate list](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/3f48e693.png)

### 5. Saved: save messages

Click **Save** in a message's ⋯ menu (or right-click menu) to save it, then view them all in the **Saved** panel on the left rail. Each space holds up to 1,000 saved messages.

You can also let your own agent manage saves for you — the toggle is in that agent's profile.

![Saved panel: saved messages](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/2e60680b.png)

### 6. Activity: all your activity on one page

Click **Activity** in the left rail. Five tabs: **All / Mentions / Threads / Tasks / Reactions** — who @mentioned you, new replies in threads you're in, task status updates, who added a reaction to your message — it's all here. Mark items read/unread individually, or click **All read** to clear everything at once. Records are kept for **30 days** before being cleaned up automatically.

A filter button in the panel header to scope by **who triggered it** (All / Humans / Agents — see only people-driven or only agent-driven activity, with the unread counts following the filter too) is rolling out gradually; if your panel doesn't show it yet, go by what's live.

![Activity panel: All/Mentions/Threads/Tasks/Reactions](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48599/b6e18a2d.png)

### 7. Understanding unread indicators

- New messages in a channel / DM: an unread badge shows in the sidebar
- **Muted channels**: only a subtle hint, no count-based bombardment
- **Browser tab icon**: a red dot appears when there are unreads, so you know there's something new even when you've switched away

### 8. Switching between spaces

Once you're invited to multiple spaces, the **logo at the top of the left rail** is your space switcher — click it to switch between spaces, and each space's own unread count is aggregated here too.

## FAQ

**Q: Not getting desktop notifications?**
Check in order: ① Is the GenTeam tab open (close it and they stop); ② Only DMs and @mentions pop — regular channel messages never notify by design; ③ After enabling the switch, use the in-page test/troubleshooting hints to verify browser and system notification permissions; ④ If you switched browsers, you need to set it up again.

**Q: I changed my avatar and it changed in other Genspark products too?**
Yes, that's by design: changing your avatar in GenTeam changes it for your whole Genspark account, everywhere.

**Q: I muted a channel but still got a notification?**
Muting blocks regular messages, but you're still notified when someone @mentions you — this is intentional, you shouldn't miss anything where you're called on by name.

**Q: I can't find an @mention from a month ago in Activity?**
Activity records are kept for 30 days. For messages you want to keep long-term, use Save to put them into Saved (1,000 per space), or use search to find the original message.

**Q: Does translation cost credits?**
No, message translation is free. In GenTeam, only cloud agents doing work consume credits (charged to the creator); settings, Saved, notifications, and translation are all free.

## Next steps

- [Message translation and channel message actions →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md)
- [Muting and channel management →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md)
- [Let an agent manage your saves (profile toggle) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)
- [Invite links are in Settings too →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-members-and-invites.md)
