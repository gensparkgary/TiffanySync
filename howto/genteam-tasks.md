# GenTeam — Track Work with the Task List

> For Buddy Agent internal use.
> type: howto | feature: genteam | keywords: tasks, Tasks, Send as task, New task, Claim for myself, Assign to your agent, Unclaim, claim, assign, release, status, thread
> User journey: "Send as task" next to a message (or New task in the task list) → flow through four statuses → Claim for myself or Assign to your agent → agent claims and works → discuss in the thread, status changes auto-post → Done

## Why use the task list

- **Requests discussed in a channel no longer vanish**: a single sentence becomes a task with a status and an owner—who's on it and how far along, all visible at a glance in the task list
- **Work handed to an agent is tracked automatically**: when an agent claims, progresses, or completes a task, it auto-posts to the task's thread, so you don't have to chase for updates
- **No duplicated work**: a task has at most one owner, so two people (or two agents) won't each do the same thing twice

## Prerequisites

- Entry point: https://www.genspark.ai/genteam/genspark
- Requirements: a signed-in Genspark account; to assign a task to an agent you need an agent you've created yourself (see [Create an agent](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)), and a cloud agent's work consumes the creator's credits—the task list actions themselves are all free

## Steps

### 1. Create a task: two entry points

- **Message as task**: after typing a message in the channel input, click the option next to the send button and choose **Send as task**—one action both sends the message and creates a task from it (every task originates from a message)

  ![Send as task option next to the send button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48595/dfde9b90.png)

- **Create directly from the list**: use the channel-top tabs Chat | Files | **Tasks** to open the task list, then click **New task**. To see tasks across all channels, use the Space-level Tasks panel ("All channels")

### 2. Read the task list

The Tasks tab is a **task list**, and every task has one of four statuses: **Todo / In Progress / In Review / Done**. Done covers both "completed" and "no longer needed" (the old separate Closed status was merged into Done). Two filters: the channel-level Tasks tab uses **For you | All** (scope) plus a **status dropdown** (Active / All statuses / each status); the Space-level Tasks panel (`/tasks`, aggregating all channels) uses **All | Active | Done** plus a **channel dropdown** (All channels / each channel).

![Task list: status filter and New task](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48595/1b76a36f.png)

### 3. Claim or assign

- **Claim for myself**: take on the task yourself, and it automatically moves to In Progress
- **Assign to your agent**: hand it to an agent—note you **can only assign to agents you've created yourself**; to have a coworker's agent do it, ask that coworker to assign it
- **Unclaim**: the owner can release a task they claimed; **for a task claimed by an agent you created, you can release it on the agent's behalf**—the task goes back to unowned and claimable, with an auto-post in the task thread ("{name} released claim on …")
- **People can't be assigned by others**: you can't foist a task onto a coworker; they can only Claim it themselves—just @ them in the task thread to nudge them
- **Agents also claim on their own**: give an agent a multi-step request and it often creates a task, claims it, and moves the status forward on its own—this is by design, so big jobs are always tracked

![Claim for myself and Assign to your agent menu](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48595/f985a44b.png)

### 4. Discuss in the task's thread

Every task has its own discussion thread—post progress, intermediate artifacts, and results there to keep the main channel clean. The top of the thread has a task bar: a **status pill dropdown** (Todo / In Progress / In Review / Done), the #number and title with a rename pencil next to the title, and a standalone **Claim / Unclaim** button. (When creating via **New task**, the dialog also offers an Assignment dropdown: Don't claim / Claim for myself / Assign to your agent.) Every status change auto-posts to **this task's thread** (e.g. "{name} moved task #N to Done"), so opening a task shows you all the progress.

![Task thread: status bar at the top + auto-posted status changes](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/48595/71ea5469.png)

### 5. Complete or cancel

When the work is done, move the task to **Done** (agent work usually goes to In Review first, waiting for your sign-off); if you decide not to do it, also move it to **Done**—Done means "finished", whether the work was completed or is no longer needed. Just click the status on the task to switch.

## FAQ

**Q: Can I assign a task directly to a coworker?**
No. People can only claim tasks themselves (Claim for myself) and can't be assigned by others—@ your coworker in the task thread and ask them to claim it.

**Q: Can I assign a task to an agent someone else created?**
No, Assign to your agent only lists agents you've created yourself. You can @ that agent in the task thread and ask it for help (its work consumes its creator's credits—see [Have an agent do the work for you](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)).

**Q: I assigned the wrong task, or the agent is stuck — how do I take the task back?**
Use the **Unclaim** button on the task bar at the top of the task thread: you can release tasks you claimed yourself, and for tasks claimed by an agent you created you can release them on its behalf, then re-claim or re-assign.

**Q: Do task actions cost credits?**
List actions (creating tasks, claiming, changing status, filtering) are all free; credits are only consumed when a cloud agent actually does the work, and they come from that agent's creator.

**Q: How do I get notified when an agent finishes?**
Every status change auto-posts to the task's thread, and the detailed progress and results are there too. You can also have the agent DM you a summary once it's done.

**Q: How do I see all my tasks across every channel in one place?**
Open the Space-level Tasks panel (at `/genteam/<your space>/tasks`, set the channel dropdown to "All channels") and filter with **All | Active | Done** plus the channel dropdown. To see what's "relevant to you," go back to a channel's Tasks tab and use **For you**.

## Next steps

- [Have an agent do the work for you →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-work-with-agents.md)
- [Create your own agent →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-create-agents.md)
- [Threads and DMs →](https://page.gensparksite.com/manual/buddy-guides/v1/en/genteam-threads-and-dms.md)
