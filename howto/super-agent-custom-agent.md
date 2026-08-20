# Super Agent — Custom Agent: Create / Invoke / Share

> For Buddy Agent internal use.
> type: howto | feature: super-agent | keywords: Custom Agent, custom Agent, @mention, create, share, Store, favorite
> User loop: Create a Custom Agent in one sentence → test and adjust → @invoke it in a Super Agent conversation → share or publish to the Store

## Why use a Custom Agent

If you have a task you do over and over (writing a weekly industry report, analyzing stocks against a fixed template), instead of re-explaining it every time, **turn it into a dedicated Agent**: describe the role and requirements once, then invoke it with `@` in one click — and you can even share it with colleagues or publish it to the community. No coding required.

## What is a Custom Agent

Custom Agent lets you create your own AI agent in a single sentence. Once created, you can invoke it with `@` in a Super Agent conversation, favorite other people's Agents, or publish it to the **Custom Agent Store** for the community to use.

## Where to find it

| Entry point | Action |
|------|------|
| Sidebar | **Custom Agent** at the top of the left sidebar's **"+ New"** menu (the "Custom" tile) takes you to the Store |
| In a conversation | Type **`@`** in the Super Agent input box to invoke an existing Agent; the list also includes a **"+ Browse Agent Store"** shortcut |

## Create a Custom Agent

1. Click **"Create New"** in the top-right corner of the **Custom Agent Store** page
2. Describe it using a structured template: [role definition] + [core functions] + [output standards]
   > Example: "Create an AI industry analyst that generates weekly reports on funding trends, technology advances, and policy interpretation, for use in investment decisions"
3. Test it in the **Preview** window, adjust the instructions based on the results, and click **"Create"** to save (to edit later, click **"Update"**). After saving, you can reopen it in **My Super Agents** to confirm your edits were retained.

> In the dialog box on the creation page, describe your needs in natural language and the system will automatically update the Instructions. Test in Preview after each change and iterate until you're satisfied.

![Custom Agent Builder: Configure + Preview](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/3c3e1382.png)

## Invoke with @ in Super Agent

1. Type **`@`** in the Super Agent input box
2. A list pops up showing the Custom Agents you've created and favorited
3. Select an Agent, enter your task, and send
4. Super Agent hands the task off to that Custom Agent to handle

> You can invoke multiple Custom Agents in sequence within a single task to collaborate — for example, first @ a financial analysis Agent, then @ an industry research Agent, and finally have Super Agent synthesize everything into a complete report.

![Custom Agents list that pops up when you type @ (includes Browse Agent Store)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35639/86337733.png)

## Manage and share

### Custom Agent Store

- **Trending**: popular Agents
- **By Genspark**: officially published Agents
- **All Agents**: all Agents, with category filters below (All / Writing / Productivity / Research & Analysis / Education / Lifestyle / Others) and a search box
- The Agents you create and favorite go into **My Super Agents** (tabs: My Own / Favorites; also visible when invoking with `@`)

![Custom Agent Store (Create New / Search / Trending)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35639/f15bbcab.png)

### Management actions (Agents you created yourself)

> Management actions (the three-dot menu / Configure) only appear for Agents **you created yourself**; Agents you favorited from the community won't show these options — you can only use them.

- **Edit / Configure**: modify settings via conversation or manually, then click Update to save
- **Delete**: delete and confirm (**permanent deletion, cannot be recovered**)
- **Share**: click Share on the Configure page. The dialog shows **People with access** (you as Owner) and a **General Access** dropdown with two scopes:
  - **Restricted** (only you)
  - **Anyone with the link** (anyone who has the link; click Copy link to get the share link)
  - Publishing to the community Store is **not** a Share scope — use the separate **Publish** button (next item).
- **Publish (as a chat-platform bot)**: click **Publish** on the create/edit page (the Builder) to open the "Publish Agent" panel — besides publishing to the Custom Agent Store, you can connect your Agent to external chat platforms and run it as a bot on **Slack / Discord / Telegram / LINE**, following each platform's setup guide (available platforms are as shown in the UI). Channels you've published to can be filtered by platform back on the **My Super Agents** page.

![Custom Agent Share dialog: General Access (Restricted / Anyone with the link) + Copy link](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51098/34a1342b.png)

> After you favorite someone else's Agent, it's added to your My Super Agents (Favorites tab) and can be invoked with `@`.

## FAQ

**How do I use an Agent I made myself?**
Type `@` in the Super Agent input box → select your Custom Agent → enter your task.

**Can a deleted Agent be recovered?**
No, deletion is permanent. We recommend exporting the conversation history from when you created it before deleting.

**Can I edit an Agent I favorited from the Store?**
No. A favorited Agent can only be used — you can't see or change its instructions.

**If I use an Agent someone shared with me, will my conversation history leak?**
No. Each user's conversation history is fully isolated, and the creator cannot see other users' conversations. Sharing only includes basic information like the name and description.

**Can I run my Agent inside chat tools like Slack or LINE?**
Yes. Click **Publish** on the Builder page, pick the platform, and follow the setup guide to connect it (available platforms are as shown in the UI).

## Next steps

- [Get started](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-get-started.md)
- [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-overview.md)
