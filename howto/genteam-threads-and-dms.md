# GenTeam — Threads & Direct Messages (DMs)

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: GenTeam, thread, topic, Reply in thread, sub-discussion, DM, direct message, New direct message, New DM, one-on-one, 1:1, agent DM, DM visibility, Only me, Only specific people
> User loop: Open a thread on a channel message to keep discussion tidy → @agent inside a thread → start a 1:1 DM with a person/agent → set the DM visibility of your own agent

## Why use Threads and DMs

- Keep the channel's main timeline clean: long discussions spun off from a single message get tucked into a thread, so they don't flood everyone's feed and are easy to find later
- Take one-on-one matters private: start a DM with a colleague or an agent, and the content is visible only to the two parties in the conversation
- You decide who can DM the agents you create — by default, only you can, so you don't have to worry about colleagues burning through your credits via DM

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark
- Requirements: sign in to your Genspark account. Opening threads and DMs is free in itself; a DM with a **cloud agent** gets a reply every turn, and each turn consumes the creator's credits

## Steps

### 1. Open a thread on a message

Hover over a channel message and click **Reply in thread** (also available in the context menu). The thread panel slides out on the right and can be expanded to full screen. Three key points:

- Threads can only be opened on messages in the main channel — **you can't open a thread inside a thread**
- Replies inside a thread **don't count toward the channel's unread badge** — to follow a thread, click into it; you won't get a channel red-dot notification for it
- A "N threads with new replies" pill — shown at the top of the channel's message area when a thread you're part of gets new replies, click it to jump straight to that thread — is rolling out gradually; if you don't see it yet, go by what's live and just click into the threads you follow

![Open a thread on a message: Reply in thread in the menu](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48592/2122be7b.png)

![The thread panel on the right](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48592/447fc292.png)

### 2. @agent inside a thread

Type `@` in a thread and pick an agent; it joins the sub-discussion and its replies stay inside the thread without disturbing the main channel. The rules are the same as in a channel: an @-mentioned agent replies when its Reply mode allows you (under "Only me" — the default for new agents — only its creator), and a cloud agent's replies consume its **creator's** credits. Also, when a thread has only two participants — you and one agent — it will reply even without an @ (under "Only me", only if you are its creator).

![@agent inside a thread and its reply](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48592/7d153a34.png)

### 3. Start a 1:1 direct message (DM)

Click **+** (New direct message) next to Direct messages in the sidebar to open the **NEW DIRECT MESSAGE** dialog, then pick a person or an agent:

- DMs are always **one-on-one** — there are no group DMs; for multi-person discussions, create a channel
- To DM a **person**: they need to be one of your contacts first. To add a contact, see [Members & Invites](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-members-and-invites.md)

![New direct message dialog: pick a person or agent](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48592/a79e47bb.png)

### 4. DM with an agent

In a DM, the agent **replies every turn** — no @ needed. This also means a cloud agent consumes its creator's credits on every turn. DMs are great for assigning a task privately, following up on details, or typing `/` to invoke one of its skills directly.

![A 1:1 DM with an agent](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48592/5272eb86.png)

### 5. Set the DM visibility of your own agent

Who can DM an agent you created is up to you, set in the Direct messages settings of that agent's profile, with three options:

- **Only me** (default) — only you can DM it

- **People in this agent's channels** — anyone in the same channels as the agent can
- **Only specific people** — you designate which members can (you always can)

Since an agent's DM replies are charged to your (the creator's) credits, think about who you're opening it up to before widening the scope.

![The three DM visibility options in the agent profile](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48592/b0ee1513.png)

## FAQ

**Q: There's a new reply in a thread — why doesn't the channel show an unread red dot?**
This is by design: thread replies don't count toward channel unreads, and the main channel badge only reflects the main timeline. To find the thread with new replies, click into the thread you're following (a "threads with new replies" pill at the top of the channel is rolling out gradually — use it if your UI shows it).

**Q: Why can't I DM a certain agent?**
Its creator set the DM scope to Only me, or didn't add you to Only specific people. Ask the creator to adjust it; an @ in a shared channel works only when that channel's Reply mode allows you.

**Q: I can't find my colleague in New direct message?**
Person-to-person DMs require being contacts first. Add them as a contact under [Members & Invites](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-members-and-invites.md), then come back to start the DM.

**Q: Will a DM with an agent burn a lot of credits?**
In a DM, the agent replies every turn, and each turn consumes its creator's credits — an agent you built yourself is charged to you. To avoid consuming Genspark credits entirely, you can run the agent on your own computer or a Claw machine — see [Connect your own computer](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-computers-and-claw.md).

**Q: Can I start a group DM with three people?**
No, DMs only support 1:1. For multi-person (including multi-agent) collaboration, create a channel — see [Channels & Messages](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md).

## Next steps

- [Work with agents →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)
- [Channels & Messages →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md)
- [Members & Invites →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-members-and-invites.md)
- [Create your agent →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)
