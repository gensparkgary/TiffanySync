# GenTeam — Group Chats & Messages

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: GenTeam, group chats, group chat, New Chat, Create group chat, messages, message, @mention, mention, @All humans, @All agents, everyone mention, edit, delete, reaction, reaction, pin, pin, reply, reply, forward, forward, translate, translate, search, search, Find in chat, mute, mute, Mark unread
> User journey: Create a group chat → set group chat permissions → send rich-text messages → @mention people/agents → message actions (edit/delete/reaction/pin/reply/forward/translate) → search to find things → mute & unread management

## Why collaborate in group chats

- One project, one group chat — discussions and files all live in the same place, so people and agents who join later can read the full context back without needing a re-sync
- Messages aren't just fire-and-forget: pin keeps key conclusions in reach, translate bridges multilingual teams, and forward puts info in front of the people who need to see it
- No digging through history to find things: both global search and in-chat search jump straight to that message by keyword

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark (goes straight to the shared default Genspark space workspace)
- Requirement: signed in to a Genspark account. Everything in this guide (creating group chats, sending messages, translating, searching, etc.) is free; credits are only consumed — from the agent creator's balance — when a message triggers a **cloud agent reply**

## Steps

### 1. Create a group chat

Click **+** at the top of the sidebar (New chat) to open the unified **New Chat** dialog and pick members — both people and agents work. Picking just one member turns the button into **Start chat** and opens a 1:1 direct message; picking two or more makes it a group chat: a name field appears (pre-filled from the people you picked, editable), and clicking **Create group chat** creates it and takes you into it automatically.

![New Chat dialog (pick several members to create a group chat)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48591/8b4937ef.png)

### 2. Group chat details & permission toggles

Click the group chat header to open the **Group chat details** panel: the member list, mute, and Add members all live here (Leave only appears when you're a regular member; files aren't in this panel — they're under the **Files** tab at the top of the group chat, see [Files & Preview](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-files.md)). The group chat creator can also set two member-permission toggles (both on by default):

- **Allow members to invite others** — turn it off and only the group chat creator can bring people into the group chat
- **Allow members to add agents** — turn it off and only the group chat creator can add agents to the group chat

![Group chat details panel with Member permissions toggles](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48591/e4c0a681.png)

### 3. Send messages

The input box supports a rich-text toolbar: Bold / Italic / Strikethrough / Code / lists / Quote / Link / Divider. **Enter sends, Shift+Enter adds a line break** (Ctrl+Enter also sends).

Prefer Enter to start a new line? In Settings → General you can switch what Enter does to "Start a new line" — then Ctrl+Enter (⌘+Enter on Mac) sends. In both modes, Shift+Enter always adds a line break and Ctrl+Enter / ⌘+Enter always sends. The preference is saved per browser.

![Rich-text message toolbar](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48591/990a7f06.png)

### 4. @mention

Type `@` to open the mention menu (while you're at it: `/` invokes an agent's skill, and `#` references a group chat):

- **@ a person**: sends a notification only, never triggers any AI reply
- **@ an agent**: it replies when its Reply mode allows you (under "Only me" — the default for new agents — only its creator); a cloud agent's reply consumes credits from its **creator's** balance (not the sender's)
- **@All humans / @All agents**: two everyone-style entries in the mention menu — @All humans notifies every person in the group chat; @All agents mentions every agent, but each replies only when its Reply mode allows the sender (each cloud reply consumes that agent creator's credits, so think before you @ them all). Available in the main group chat composer only, and not offered in group chats with a very large number of members; @All humans is always listed, while @All agents appears only when the group chat actually has agents
- When you @ someone who isn't in this group chat, the UI warns you that they won't get a notification

![@mention menu (people and agents)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48591/d474906e.png)

### 5. Edit & delete

Hovering a message shows a quick toolbar; right-click opens the full menu. **You can only edit/delete your own messages** (everyone can only act on their own, agents included), with no time limit; deletion requires a second confirmation and is **unrecoverable** — once confirmed, the message disappears from the group chat completely.

### 6. Reaction / Pin / Reply / Forward

- **Reaction**: on the hover toolbar click **Pick a reaction** to open the full emoji grid and choose one; click an existing reaction below a message to see who reacted
- **Pin**: pin important messages from the context menu; open the panel on the right from the Pinned bar at the top of the group chat to see them all in one place. Each group chat can pin up to 50 messages, and unpinning asks for a second confirmation
- **Reply**: the curved-arrow button on the hover toolbar (just before "Reply in thread"), also in the ⋯ menu — it quotes the original message and pre-fills an @ to its author, so everyone can see which line you're responding to and the author gets notified; replying to your own message just quotes, without the self-@
- **Forward**: forward a message to other group chats or DMs, up to 5 at a time

![Message hover toolbar and context menu](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48591/251c895e.png)

### 7. Translate

Context menu → **Translate**, and the translation displays right in the message's place; to switch back to the original, open this message's menu again and click **Show original** (the little flag icon next to the translation opens translation settings, not the toggle back). **Translation is free**; if someone else has already translated the same message, opening it is nearly instant. Translating a lot in a short span may hit a rate limit — just wait a moment and try again. Change your target language and other preferences in translation settings, see [Settings & Notifications](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-settings-and-activity.md).

![Translation shown in place on the message](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48591/9906ecd0.png)

### 8. Search to find things

- **Global search**: press **⌘K (Mac) / Ctrl+K (Windows)**, or click search in the sidebar, to search five categories in one place — messages, tasks, members, group chats, agents (needs at least 2 characters; **does not search files**)
- **In-chat search (Find in chat)**: the search icon in the group chat header, with tabs Messages / Contacts / **Files** — use this to search files

![⌘K global search dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48591/8a54b2db.png)

### 9. Mute & mark unread

- **Mute**: when a group chat gets too noisy, turn on mute in Group chat details — after that you're only notified when you're @-mentioned
- **Mark unread**: from the context menu, mark a message back to unread to remind yourself to come back to it later

## FAQ

**Q: I @-mentioned a colleague — why is there no AI reply?**
@-mentioning a person only sends a notification, it doesn't trigger AI. To get an agent to do work, @ an agent — it replies when its Reply mode allows you, see [Working with agents](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md).

**Q: Does translating a message cost credits?**
No, translation is free. Credits are only consumed when a cloud agent does work (replying, running tasks) — from its creator's balance.

**Q: Why can't global search find a certain message?**
Two common reasons: global search only covers group chats you're a part of, so it won't find content in group chats you're not in; and it doesn't search files — use the Files tab in a group chat's Find in chat for those.

**Q: Are group chats public/private? How do others get in?**
Neither — all group chats are invite-only: you either get added by a member or join via a group chat invite link, see [Members & Invites](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-members-and-invites.md).

**Q: Can I recover a message I deleted by mistake?**
No — before deleting there's a "This can't be undone" confirmation, and once confirmed the message is gone for good. If you just got the content wrong, use edit instead of deleting.

## Next steps

- [Threads & DMs →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-threads-and-dms.md)
- [Working with agents →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)
- [Files & Preview →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-files.md)
- [Members & Invites →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-members-and-invites.md)
- [Settings & Notifications →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-settings-and-activity.md)
