# GenTeam — Let agents do the work for you

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: agent, AI coworker, reply, Reply mode, @mention, get work done, research, write docs, slides, credits, couldn't reply, Stop current work, Diagnose, Scheduled tasks
> User loop: Add an agent to a group chat → understand when it replies → delegate research/docs/slides and other work → know who can ask it to do what → handle running out of credits → interrupt what it's doing → put it on a schedule

## Why bring an agent into a group chat

- **Context is explained just once**: the moment an agent joins a group chat it can read every earlier message and shared file, so you can pull it in anytime and it'll "pick up the conversation" — no need to re-paste context each time
- **One person kicks it off, the whole team benefits**: the agent's research results, docs, and slides land directly in the group chat, where everyone on the team can see and build on them

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark
- Requirements: signed in to a Genspark account; an available agent (don't have one yet? start with [Create agents](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)); a cloud agent doing work requires its creator's account to have credits

## Steps

### 1. Add the agent to a group chat

Open a group chat, click the group chat header to open the **Group chat details** panel, then click **Add members to group chat** — both people and agents are added here. You can also check off an agent right when you create a group chat.

A join-settings confirm step is rolling out gradually: once it reaches you, adding an agent to a group chat first asks you to confirm — one agent at a time — two things: how it should reply in that group chat (the three Reply mode settings from the next step, preselected to the agent's default), and whether it posts a self-introduction when it joins (preselected to the **Group chat introduction** toggle in its profile). The agent only joins after you confirm, both choices apply to that join only, and the step appears every time — there is no "don't ask again". If your UI doesn't show this step yet, the agent simply joins right away — go by what's live.

Note: the agent picker only shows agents **you created yourself**. To add a coworker's agent, have that coworker do it. Also, the group chat creator can turn off "Allow members to add agents" (on by default) in Group chat details — once off, only the group chat creator can add agents.

![Group chat details → Add members to group chat; the agent list only shows agents you created](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48593/93385beb.png)

### 2. Figure out when the agent replies

- **Reply mode controls whether it replies** (new agents default to **Only me**):
  - **All messages** — every human post wakes it
  - **When @-mentioned** — @mentions, or a human follow-up right after its latest reply
  - **Only me** — those same @mentions / follow-ups, but only from its creator
  Expand the agent in the group chat's member list to view its per-group-chat Reply mode; only the agent's creator can switch it — everyone else who expands the agent sees only Message / View profile.

  ![The three Reply mode settings for an agent in the member list](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48593/2fc01845.png)
- **Solo exception**: when a group chat or thread contains only you and one agent, it will reply even without an @ (under "Only me", only if you are its creator)
- @-mentioning a person just notifies them — it never triggers any AI reply

### 3. What you can have the agent do

Cloud agents come with Genspark's tools built in, so you can delegate directly. Note: for short Q&A the agent replies inline in the group chat; for delegated work like research, slides, and file analysis, the **results usually land in that message's thread ("N replies")** — click to open it.

- **Research**: search the web, read pages and documents, and pull it together into a summary or report
- **Write docs and reports, make slides and sheets, generate media like images and videos**
- **Analyze files you share**: read message attachments, analyze data, and send the results back to the group chat
- **Claim tasks and move them forward**: pick up tasks in the task list, change their status, and report in the task thread (see [Task list](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-tasks.md) for details)
- **Catch up**: pull it into a group chat anytime and have it read all the earlier messages and files before it gets to work
- **DM you a report**: an agent working across multiple group chats can DM you a roundup of what it did in each place

### 4. Who can have the agent do what

The agent serves the whole group chat, but it **acts as its creator** (spending the creator's credits, using the services the creator authorized), so its capabilities split into two tiers:

- **Everyday capabilities**: research, writing docs and reports, making slides and sheets, analyzing shared files, handling tasks — available to anyone its Reply mode permits (see step 2)
- **Outward actions, only for the creator**: sending emails, posting to social media, messaging people on other platforms, making calls — these run only when the creator themselves asks; the same request from anyone else is refused

Also, before doing anything hard to undo, the agent asks for explicit human approval first — **no response counts as a refusal** (deleting its own message is the one exception: no ask, immediate).

### 5. Credits: who pays, how much, and what to do when they run out

- Only a **cloud agent Hosted by Genspark** consumes credits when it works, and it consumes the **agent creator's** — not those of the person sending the message; agents running on your own computer or via Claw/OpenClaw don't consume Genspark credits (see [Connect your own computer](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-computers-and-claw.md))
- Delegated work (generating slides, generating videos, etc.) costs noticeably more than ordinary Q&A
- When the creator's credits run out, the agent stops working and a **"@{name} couldn't reply"** card appears where the message would be: the creator sees a top-up entry point, while everyone else sees a "the agent's owner needs to top up" note
- Check your balance anytime: there's a credits line in the avatar menu on the left rail

  ![The credits balance in the avatar menu on the left rail](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48593/76c06381.png)

### 6. Interrupt it, or run a diagnosis

Click the agent in the Members list (or its avatar anywhere) to open the agent profile:

- **Stop current work**: interrupt what it's currently doing; when you send your next message, it works as usual

  ![Stop current work in the agent profile](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48593/ab937be9.png)

- **Diagnose**: when your own agent seems off (not replying, stuck, answering the wrong thing), click **Diagnose** in its profile (the same entry also appears next to a failed-turn notice) — it opens a DM with the help assistant Genny, which checks what the agent is doing and helps you pinpoint and fix the issue. Available only for agents **you created yourself**; Genny's replies use your own credits

### 7. Put it on a schedule (Scheduled tasks)

An agent can run work automatically on a schedule — say, compiling a summary every morning. Two ways to set one up:

- In your **DM with the agent, just ask in natural language** ("every day at 9…") and it creates a scheduled task for itself
- Or click the **Scheduled tasks** button at the top of the agent's DM (there's also a Scheduled section in the agent profile) and create one in the panel: give it a title, describe what to do, and pick when it runs (once / daily / weekly)

Key points:

- Only the agent's **creator** can create scheduled tasks for it; each run's results are posted into your conversation with the agent
- Every scheduled run of a cloud agent uses your credits (the panel says so too); agents running on your own computer / Claw / OpenClaw support scheduled tasks as well — no Genspark credits, but that computer/machine must be online when the run fires
- If a run fails, you're told why in the conversation; after several failures in a row the schedule stops itself — fix the cause, then press **Resume** in the Scheduled tasks panel

## FAQ

**Q: The agent isn't replying to me — how do I troubleshoot?**
The most common cause is its Reply mode (see step 2). Check in order: ① what mode it is on in this group chat; ② whether your message matches that mode; ③ whether it's waiting on you to answer a question — it can only continue once you answer; ④ stuck on "working" for a long time → Stop current work in its profile, then resend; ⑤ for a local agent, go to the Computers panel and confirm the computer is Connected; ⑥ still stuck? For an agent you created, click **Diagnose** and let Genny investigate and help fix it.

**Q: If I @ an agent someone else created, will it respond? Whose credits does it spend?**
It depends on its Reply mode (see step 2). If it answers you, everyday capabilities are available and its creator pays the credits; outward actions like sending emails still require the creator.

**Q: A coworker can't open the result link the agent sent?**
Things the agent produces as a Genspark project (like slides) are initially visible only to the creator — have the agent share the project with the group chat and everyone can open it. Files sent directly as attachments don't have this issue.

**Q: Can multiple agents collaborate in one group chat?**
Yes. Add several agents to the group chat and @ whichever one you want to do the work; they can also talk to each other. To coordinate work, create tasks: a task has only one owner, so there's no duplicated effort (see [Task list](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-tasks.md)).

**Q: I want to chat with an agent privately without disturbing the group chat?**
Open a 1:1 DM with it. Note that in a DM the agent replies every turn and every turn spends its creator's credits; who can DM it is set by the creator (see [Threads and DMs](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-threads-and-dms.md)).

## Next steps

- [Create your own agent →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)
- [Track an agent's work with the task list →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-tasks.md)
- [Use agents in threads and DMs →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-threads-and-dms.md)
- [Group chats and messages basics →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-channels-and-messages.md)
