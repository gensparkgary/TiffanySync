# Super Agent — Getting Started

> For Buddy Agent internal use.
> type: howto | feature: super-agent | keywords: getting started, new conversation, prompt, upload files, send, results, tips
> User loop: Open Super Agent → write a clear prompt → (optional) upload files → send → review the results and keep asking follow-ups

## Why start here

The quality of what Super Agent produces depends on how you describe the task. A clear, complete prompt lets it plan the whole workflow in one pass, and providing a data file is more accurate than pasting numbers by hand. Learning how to start well saves you the time and credits you'd otherwise spend on corrections.

## Open Super Agent

The most direct way: type into the large input box in the center of the Genspark homepage and send (the homepage defaults to Super Agent). After sending, you land on the conversation page `https://www.genspark.ai/agents?id=<conversation id>`. You can also go straight to `https://www.genspark.ai/agents?type=super_agent` to start a new Super Agent conversation.

You can also find and open Super Agent in the **All Agents** list in the left sidebar.

![Super Agent homepage input box (input box / attachment "+" / New menu entry)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35639/c8456610.png)

## 1. Write a clear prompt

Describe the task you want done in natural language in the input box. Describe the task itself—you don't need to specify tools, because Super Agent picks them automatically.

**Good prompts**:
> "Research 2024 EV market trends, compile the key data, and turn it into a 10-page presentation"

> "Analyze the sales data I uploaded, make a revenue pie chart by category and a growth trend line chart by month, then give me 3 key insights"

**Bad prompts**:
> "Make me something" (too vague—the AI has no idea what you want)

| Tip | Explanation |
|------|------|
| Describe the task, not the tools | Say "make a competitive analysis deck," not "research first, then use Slides" |
| Describe the full workflow at once | Putting all the steps into one prompt is more efficient than asking step by step |
| Specify the output format | "Make a deck," "put it in a table," "write it as an email"—it'll call the right capability |
| Upload files if you have data | Don't paste numbers by hand; uploading the file directly is more accurate |

## 2. Upload files (optional)

Click the **attachment button ("+")** next to the input box to expand the upload source menu:

- **Browse Local Files**: upload from your local computer
- **Choose from AI Drive**: select from your Genspark AI Drive
- **Connectors**: select from a connected third-party cloud drive (e.g., Google Drive, SharePoint). These sources live in the Connectors submenu and only appear after you've connected the corresponding account; if nothing is connected, this is empty and shows only the connection entry point.
- **Personalization**: personalization-related options

After uploading, describe in the input box what you want the AI to do with the file, and it will read the contents and process them automatically. Common formats include PDF, Word, Excel/CSV, PPT, images, and code files.

![Upload sources expanded from the attachment "+" (Browse Local Files / Choose from AI Drive / Connectors)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35639/79488770.png)

## 3. Send and watch the work in progress

After you click send, Super Agent shows its work in progress—what it's searching, which tool or specialized agent it called, and the current status.

- If it's heading the wrong way, click **"Stop"**.
- For actions like making a phone call, sending an email, or generating an image, it usually pops up a clarification card first (with radio options + Skip / Submit), asking for details over one or more rounds before executing—it's not one-and-done, so just pick or fill in as prompted.

## 4. Review the results and keep going

Results are shown in conversation form. If a specialized agent (e.g., Slides, Sheets) was called, its output is embedded in the conversation (slide previews, tables, etc.). You can keep asking follow-ups or requesting changes right in the conversation:

> "Swap the chart on page 3 for a bar chart"
> "Add a paragraph of competitor comparison"

> If the direction is completely off, starting a new conversation is more efficient than repeatedly correcting the old one.

## FAQ

**How do I upload a file?**
Click the attachment button ("+") next to the input box → choose a source (Browse Local Files / Choose from AI Drive, and if you've connected a cloud drive you can also pick Google Drive / SharePoint, etc. in the Connectors submenu) → select the file → describe in the input box how you want it handled.

**Super Agent feels slow?**
Complex tasks (deep research, multi-agent collaboration) really do take longer. For a simple Q&A that doesn't need such a heavy workflow, just ask quickly in the homepage input box.

**What if I'm not happy with the results and want a different direction?**
Just say what changes you want right in the conversation. If the direction is completely off, starting a new conversation is more efficient.

**How do I save credits?**
Describe the task clearly and completely in one go to reduce back-and-forth corrections; don't ask for image/video generation unless you need it (those two consume more credits).

## Next steps

- [Deep research and fact checking](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-research-and-verify.md) — Deep Research / Fact Check
- [Generate images and videos](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-create-media.md)
- [Real-world actions](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-actions.md) — make a call / send an email / save a file
- [Custom Agent](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-custom-agent.md) — create and @-call your own agent
- [Hub workspace](https://page.gensparksite.com/manual/buddy-guides/v1/en/hub-overview.md) — share context across conversations
- Not sure whether Super Agent is right for your task? See the [product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-overview.md)
